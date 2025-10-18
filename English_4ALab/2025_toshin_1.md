```
4 (A) 以下の英文の段落(21)~(25)にはそれぞれ文法上または内容上の誤りがある。修正が必要な下線部を各段落から一つずつ選び、マークシートの(21)~(25)にその記号をマークせよ。

(21) For half a century, the Sernesi family lived (a) in a storied villa overlooking (a) Florence where the Renaissance artist Michelangelo was raised and (b) he later owned. (b) The property (c) came with (c) several buildings, an orchard and a drawing of a muscular male nude etched on the wall of a former kitchen. (d) Tradition has it that (d) the work was drawn by a young Michelangelo, though scholars are (e) not as sure. (e)

(22) Last year, the Sernesi family sold the villa. Now they want to sell the mural drawing, (a) which was detached from (a) its original location in 1979 (b) so that it could (b) undergo a much-needed restoration. Art historians have identified the figure, (c) and having etched with (c) charcoal or black chalk on plaster and (d) measuring about (d) 40 by 50 inches, as a "triton," a god of the sea, or a "satyr," (e) part man part beast. (e)

(23) Over the decades, the drawing (a) has been loaned (a) as (b) a Michelangelo work to exhibitions (b) in Japan, Canada, China and, most recently, the United States, (c) where it was included (c) to the Metropolitan Museum's blockbuster 2017 show "Michelangelo: Divine Draftsman and Designer" . (d) The catalog entry for that exhibition, (d) by Carmen C. Bambach, the Met's curator of drawings and prints, (e) describes it as (e) "the only surviving manifestation of Michelangelo's skill as a draftsman in large scale." 

(24) News that the drawing (a) is going on the market (a) (b) is likely to expand  (b) (c) what has until now been (c) (d) a rather low-key, academic debate over (d) the authorship of a work that has remained in private hands, and mostly (e) under the public eye,(e) for the past five centuries. "It's very interesting, and now it's surely necessary to carry out further investigations," said Cecilie Hollberg, the director of the Accademia Gallery in Florence. She had already been to take a look at the drawing, at the request of the Sernesi family, she said.

(25) Years ago, (a) culture ministry officials have declared (a) (b) the work of national importance, (b) (c) meaning that it cannot leave Italy (c) (d) except on loan. (d) (e) In the case of a sale, (e) the culture ministry has the right of first refusal to match the sale price and buy the piece for the Italian state. 

注
storied 歴史に名高い
villa 邸宅
orchard 果樹園
etch ~をエッチングで描く
draftsman 製図家
the right of first refusal 第1先買権
```

# Michelangelo Mural Dispute
set: 2025_toshin_1
title: Michelangelo Mural Dispute
answers: 21-b / 22-c / 23-c / 24-e / 25-a

---

### (2025_toshin_1 Q21)
```db
set: 2025_toshin_1
question: 21
correct: b
label: VERB_VALENCY
sublabels: [REL_PRONOUN, WORD_ORDER]
explanation: **own** は他動詞。*he later owned* は目的語欠落で×。意味上は「（その**別荘**を）後に所有した」→ “**which he later owned**” などが必要（下線外の where の位置も誤解誘発）。
text:
  a: in a storied villa overlooking **Florence where** the Renaissance artist Michelangelo was raised and
  b: **he later owned**
  c: came with
  d: Tradition has it that
  e: not as sure
ja:
  a: 「（フィレンツェを見下ろす）歴史ある別荘に…」「where の係り先が曖昧」
  b: 「彼が**後に所有した**」（目的語欠落で×）
  c: 「…が**付属していた**」
  d: 「言い伝えでは…」
  e: 「それほど**確信していない**」（比較参照先なしでやや不自然だが文法×ではない）
lures:
  - opt: a
    tags: [REL_PRONOUN]
    expl: where の先行詞が **Florence** に見える配置で混乱狙い。
  - opt: c
    tags: [LEXICAL_NUANCE]
    expl: come with＝可。
  - opt: d
    tags: [IDIOM_REAL]
    expl: Tradition has it that …＝定型。
  - opt: e
    tags: [LEXICAL_NUANCE, ANXIETY_CUE]
    expl: not so sure が自然だが not as sure でも用例あり。
```

---

### (2025_toshin_1 Q22)
```db
set: 2025_toshin_1
question: 22
correct: c
label: VOICE_PASSIVE
sublabels: [PARTICIPLE, PREP_COLLOC]
explanation: 分詞句は **having been etched with** / **etched with** が正。× *and having etched with …*（能動で主語不一致）。
text:
  a: which was detached from
  b: so that it could
  c: and **having etched with**
  d: measuring about
  e: part man part beast
ja:
  a: 「…から**切り離された**」
  b: 「…できるように」
  c: 「**（〜で）刻まれており**」にする必要（受動）
  d: 「約 40×50 インチの**大きさ**」
  e: 「**半分人間半分獣**」
lures:
  - opt: a
    tags: [VOICE_PASSIVE]
    expl: was detached from＝可。
  - opt: b
    tags: [CONNECTIVE_SYNTAX]
    expl: so that … could＝目的を表す定型。
  - opt: d
    tags: [PARTICIPLE]
    expl: measuring … の付帯状況は可。
  - opt: e
    tags: [NOUN_PHRASE]
    expl: apposition（同格）として自然。
```

---

### (2025_toshin_1 Q23)
```db
set: 2025_toshin_1
question: 23
correct: c
label: PREP_COLLOC
sublabels: []
explanation: include の前置詞は **in**。× *included **to** the Metropolitan Museum’s …* → “included **in** …”
text:
  a: has been loaned
  b: as a Michelangelo work to exhibitions
  c: where it was included **to** the Metropolitan Museum’s …
  d: The catalog entry for that exhibition,
  e: describes it as “the only surviving …”
ja:
  a: 「長年**貸し出されてきた**」
  b: 「ミケランジェロ作として各展覧会に」
  c: 「メトの 2017 年展に**含まれた**（**in** が要る）」
  d: 「その展覧会の図録項目は」
  e: 「それを…と**記述している**」
lures:
  - opt: a
    tags: [TENSE_ASPECT]
    expl: 現在完了受動＝可。
  - opt: b
    tags: [LEXICAL_NUANCE]
    expl: as a Michelangelo work＝許容。
  - opt: d
    tags: [APPOSITIVE]
    expl: 挿入句の読点は自然。
  - opt: e
    tags: [VERB_VALENCY]
    expl: describe A as B＝定型。
```

---

### (2025_toshin_1 Q24)
```db
set: 2025_toshin_1
question: 24
correct: e
label: CONTENT_REVERSE
sublabels: [PREP_COLLOC]
explanation: 慣用は **in the public eye**。× *under the public eye*。
text:
  a: is going on the market
  b: is likely to expand
  c: what has until now been
  d: a rather low-key, academic debate over
  e: **under** the public eye
ja:
  a: 「市場に**出る**」
  b: 「拡大する**公算が大きい**」
  c: 「これまでのところ**〜であった**もの」
  d: 「かなり地味な学術的論争」
  e: 「**世間の注目**を浴びて（**in** が正）」
lures:
  - opt: a
    tags: [LEXICAL_NUANCE]
    expl: go on the market＝可。
  - opt: b
    tags: [DISCOURSE_LOGIC]
    expl: is likely to …＝可。
  - opt: c
    tags: [CONNECTIVE_SYNTAX]
    expl: 関係代名詞 what の名詞節＝可。
  - opt: d
    tags: [PREP_COLLOC]
    expl: debate over …＝可。
```

---

### (2025_toshin_1 Q25)
```db
set: 2025_toshin_1
question: 25
correct: a
label: TENSE_ASPECT
sublabels: [DISCOURSE_TIME]
explanation: **Years ago** と現在完了は非整合。→ “(a) culture ministry officials **declared** …” の過去形。
text:
  a: Years ago, culture ministry officials **have declared**
  b: the work of national importance,
  c: meaning that it cannot leave Italy
  d: except on loan.
  e: In the case of a sale, the culture ministry has the right of first refusal …
ja:
  a: 「**数年前**、文化省当局者が…と**宣言した**」（完了×）
  b: 「作品は**国家的重要性**を持つ」
  c: 「つまり、**イタリア国外に出せない**ことを意味する」
  d: 「**貸出の場合**を除き」
  e: 「売却の際は**優先購入権**を持つ」
lures:
  - opt: b
    tags: [NOUN_PHRASE]
    expl: of national importance＝可。
  - opt: c
    tags: [CONNECTIVE_SYNTAX]
    expl: meaning that … の同位説明＝可。
  - opt: d
    tags: [PREP_COLLOC]
    expl: except on loan＝可。
  - opt: e
    tags: [TENSE_ASPECT]
    expl: 恒常的権利を述べる現在＝可。
```