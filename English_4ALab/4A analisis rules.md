
## A. Error Labels（正解ラベル：何が誤りか）
- **CONTENT_REVERSE**  
  極性反転。例：slower↔faster, out of↔under。
- **CONTENT_DRIFT**  
  反対ではない意味ずれ・論理矛盾。例：主語役割の逆転。
- **LEXICAL_NUANCE**  
  文法可だが不自然コロケ。例：defined impact→definite impact。

- **REL_PRONOUN**  
  関係詞・先行詞・格の誤り。例：by which↔on which。
- **VERB_VALENCY**  
  自他/補語枠の誤り。例：adapt to, agree on/with/to。
- **PREP_COLLOC**  
  固定前置詞の誤り。例：impact on, include in, reach for。
- **SVA_AGREEMENT**  
  主語‐動詞一致・代名詞単複。
- **PARALLEL_COMPAR**  
  並列/比較の崩れ。either–or, as … as, than。
- **VOICE_PASSIVE**  
  受動/能動の誤り・be欠落・前置詞残置。
- **TENSE_ASPECT**  
  時制・完了/進行の基準時点ずれ。
- **ADV_ADJ_FORM**  
  副詞/形容詞・分詞形の誤り（-ly, -ed/-ing）。
- **CONNECTIVE_SYNTAX**  
  接続の型・句読点。例：Just as …, so … / コロン誤用。
- **WORD_ORDER**  
  語順・位置。例：make available **to people**。
- **ARTICLE_DET**  
  冠詞・指示語。a/the/∅, this/those。
- **QUANT_NEG**  
  量・否定の射程。Not all / any / no の範囲。
- **DANGLING_MOD**  
  ぶら下がり修飾（分詞・不定詞の主語不一致）。
- **IDIOM_FAKE（イディオム誤用）**
  定義：定型句・句動詞・慣用コロケの**形 or 意味**を誤らせる／“それっぽい偽イディオム”で誘導。

## B. Lure Labels（ダミー誘導：どう騙すか）
Error と同名タグをそのまま使用可（原因別分析に一致）。加えて下記1点を使用。

- **ANXIETY_CUE**  
  不安誘導。難語・法務表現・固有名連打・ハイフン複合・長同格など“見た目の圧”。文法上は正。

### よく使う個別ルアー（任意補助）
- **ADD_THAN**：含意比較に than を足したくなる。  
- **DROP_ARTICLE**：a/the を落とす。  
- **SWAP_PREP**：on↔to, in↔at など“それっぽい”置換。  
- **MISS_BE**：受動の be 抜け。  
- **AS_TIME**：“as＋時点”を誤用（→ by/in/at）。  
- **MOVE_ADV**：副詞位置いじり。  
- **SELF_REF**：内容整合を狙い him→himself など。

## 優先度（主タグ選定の順）
1) 形式破綻：REL_PRONOUN / VOICE_PASSIVE / SVA_AGREEMENT / PREP_COLLOC / PARALLEL_COMPAR / TENSE_ASPECT  
2) 構文語法：VERB_VALENCY / ADV_ADJ_FORM / WORD_ORDER / CONNECTIVE_SYNTAX / ARTICLE_DET  
3) 内容：CONTENT_REVERSE / CONTENT_DRIFT  
4) 語感：LEXICAL_NUANCE

## DBブロック雛形
```db
set: <ID>
question: <21-25>
correct: <a-e>
label: <主タグ, 上から選ぶ> 
sublabels: [<補助>]
explanation: <一行>
text:
  a: <…>  b: <…>  c: <…>  d: <…>  e: <…>
ja: 
  a: <translate, 該当部分付近> b:  c: d: e:
lures:
  - opt: a  tags: [<…>]  expl: <短く, 生徒が間違えそうなところを予測>
  - opt: b  tags: [<…>]  expl: <短く>
  - opt: c  tags: [<…>]  expl: <短く>
  - opt: d  tags: [<…>]  expl: <短く>
  - opt: e  tags: [<…>]  expl: <短く>
```