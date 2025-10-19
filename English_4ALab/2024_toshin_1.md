```
4 (A) 以下の英文の段落(21)~(25)にはそれぞれ文法上または内容上の誤りがある。修正が必要な下線部を各段落から一つずつ選び、マークシートの(21)~(25)にその記号をマークせよ。

(21) Is there a precise definition of the word conscience? As with many words, such as vegetable and friend, we (a) know well enough what it means, (a) despite lacking a precise definition. Because the meaning of conscience (b) may vary in different ways (b) across cultures and subcultures, as well as across time, for present purposes I (c) favor adopting this working formulation: (c) conscience is an individual's judgment about what is morally right or wrong, typically, but not always, reflecting (d) some standard of a group which (d) the individual feels attached. The decision of conscience is not solely cognitive, moreover, (e) but has two interdependent elements: (e) feelings that urge us in a general direction, and judgment that shapes the urge into a specific action.

(22) For children, learning the word conscience is not like learning the word dog. Conveniently, for dogs (a) we can point visually obvious examples, (a) and a child can easily generalize from poodles to huskies and corgis. It is not even like (b) learning what inner feeling to call thirst. (b) Conscience is not only more abstract, but it has a social dimension: knowledge of community standards. Especially at first, a child (c) will have only basic knowledge of those. (c) Moreover, learning social customs is often (d) not explicit at all, but implicit, (d) since we commonly mimic a behavior (e) without really being aware of doing so. (e)

(23) As children grow up, they begin to appreciate (a) that social contexts can be rather subtle, (a) even when they have a decent grasp of community standards. Sometimes a kind lie about someone's (b) singing voice is better than the truth, (b) and sometimes a well-intentioned offer to stack a neighbor's woodpile (c) can be perceived as insulting as their fitness. (c) Some parents (d) allow cursing and some forbid it. (d) Social life is full of subtlety: (e) the things you can say or cannot say, (e) and the best way to say the thing you normally should not say.

(24) When does the word conscience typically enter into our conversation, (a) be it inner voice or outer? (a) By and large, it is when we are in a dilemma; for example, when the law requires one thing, yet conforming to the law (b) would violate other strongly held values, (b) such as truthfulness or fairness. As portrayed in Steven Spielberg's movie Schindler's List, Oskar Schindler (c) regularly broke the law by misleading (c) his Nazi pals about the roster of Jews who worked for him in his factories in German-occupied Poland. (d) To those who did figure out that (d) the workers were Jews,  Schindler offered bribes to buy their silence. Normally, of course, breaking the law — not to mention lying and bribing — is regarded as wrong, but sometimes (e) that is why our conscience considers necessary. (e)

(25) We may consult our conscience (a) when winning a game conflicts with fairness, (a) as when a baseball pitcher considers beaning a star player (b) with a fastball to put him out of the game. (b) Or when (c) one is tempted to sacrifice loyalty for honesty, (c) as a staff member might lie (d) to shield his boss from a charge of conspiracy. (d) In 1975, White House counsel John Ehrlichman lied out of longtime loyalty to President Richard Nixon, which he later (e) came to regret when convicted of (e) perjury. 

注
Nazi ナチ党の
roster 名簿
bean (打者の)頭部を狙って投球する
conspiracy 陰謀
perjury 偽証
```

# Conscience and Social Norms
set: 2024_toshin_1
title: Conscience and Social Norms
answer: d-a-c-e-e

### (2024_toshin_1 Q21)
```db
set: 2024_toshin_1
question: 21
correct: d
label: REL_PRONOUN
sublabels: [PREP_COLLOC]
explanation: attach は前置詞 to を要求；前置前置の関係詞で “to which” が必要。
text:
  a: we know well enough what it means,
  b: may vary in different ways
  c: favor adopting this working formulation:
  d: some standard of a group which the individual feels attached.
  e: but has two interdependent elements:
ja:
  a: 「それが何を意味するか」を私たちは“十分によく”知っている
  b: 良心の意味は文化や時代でさまざまに変わり得る
  c: 次の作業定義を採用することを私は支持する
  d: 個人が愛着を感じる集団の基準（→ to which にする）
  e: 認知だけでなく二つの相互依存要素をもつ
lures:
  - opt: a  tags: [LEXICAL_NUANCE, ANXIETY_CUE]  expl: well enough の語感で不安だが可。
  - opt: b  tags: [LEXICAL_NUANCE]  expl: in different ways の冗長感で揺さぶるが可。
  - opt: c  tags: [VERB_VALENCY, SWAP_PREP]  expl: favor of にしたくなるが favor は目的語直取。
  - opt: e  tags: [CONNECTIVE_SYNTAX]  expl: not solely … but … の対比は可。
 ```

### (2024_toshin_1 Q22)
```db
set: 2024_toshin_1
question: 22
correct: a
label: PREP_COLLOC
sublabels: [VERB_VALENCY]
explanation: point は “point to + 具体例” が基本コロケ；to が必要。
text:
  a: we can point visually obvious examples,
  b: learning what inner feeling to call thirst.
  c: will have only basic knowledge of those.
  d: not explicit at all, but implicit,
  e: without really being aware of doing so.
ja:
  a: 犬なら目に見える実例を指し示せる（→ point to）
  b: どの内的感覚を「渇き」と呼ぶべきかを学ぶ（wh-to不定詞で可）
  c: そのような規範について基本的知識しか持たない
  d: 明示的ではなく暗黙的であることが多い
  e: 自覚せずにそうしている
lures:
  - opt: b  tags: [VERB_VALENCY, CONNECTIVE_SYNTAX]  expl: to call→called にしたくなるが構文が変質する。
  - opt: c  tags: [PRON_REF]  expl: those の照応が曖昧に見えるが可。
  - opt: d  tags: [PARALLEL_COMPAR]  expl: not … but … の並列は整合し可。
  - opt: e  tags: [LEXICAL_NUANCE]  expl: doing so に違和感を抱かせるが可。

```
### (2024_toshin_1 Q23)
```
```db
set: 2024_toshin_1
question: 23
correct: c
label: PREP_COLLOC
sublabels: [PARALLEL_COMPAR]
explanation: insulting は “insulting to + 名詞” が自然；as … as 比較ではない。
text:
  a: that social contexts can be rather subtle,
  b: is better than the truth,
  c: can be perceived as insulting as their fitness.
  d: allow cursing and some forbid it.
  e: the things you can say or cannot say,
ja:
  a: 社会的文脈はかなり微妙になり得る
  b: 親切な嘘の方が良い場合もある
  c: 申し出が彼らの体力への侮辱と受け取られることもある（→ insulting to）
  d: 罵りを許す親もいれば禁じる親もいる
  e: 言ってよい／言ってはならないこと
lures:
  - opt: a  tags: [LEXICAL_NUANCE]  expl: rather のニュアンスで揺さぶるが可。
  - opt: b  tags: [PARALLEL_COMPAR]  expl: better than の比較は可。
  - opt: d  tags: [CONNECTIVE_SYNTAX]  expl: allow … / forbid it の対応は可。
  - opt: e  tags: [PARALLEL_COMPAR]  expl: can / cannot の対置で迷わせるが可。
    

### (2024_toshin_1 Q24)
db
set: 2024_toshin_1
question: 24
correct: e
label: VERB_VALENCY
sublabels: [WORD_ORDER]
explanation: consider は “consider it + 形/必要” で it が要る；“that is what … considers necessary” でも可。
text:
  a: be it inner voice or outer?
  b: would violate other strongly held values,
  c: regularly broke the law by misleading
  d: To those who did figure out that
  e: that is why our conscience considers necessary.
ja:
  a: 内なる声であれ外の声であれ
  b: 他の強く保持された価値を侵害することになる
  c: 法を破った（名簿で誤導して）
  d: それがユダヤ人だと見抜いた者たちには
  e: それが良心が必要と見なすものだ（→ considers it necessary / what … considers necessary）
lures:
  - opt: a  tags: [IDIOM_FAKE]  expl: “be it A or B” の倒置に不安を抱かせるが定型で可。
  - opt: b  tags: [LEXICAL_NUANCE]  expl: would＋仮定の語感で迷わせるが可。
  - opt: c  tags: [CONNECTIVE_SYNTAX]  expl: by + V-ing の手段表現で可。
  - opt: d  tags: [TENSE_ASPECT]  expl: did figure out の過去強調で揺さぶるが可。

### (2024_toshin_1 Q25)
db
set: 2024_toshin_1
question: 25
correct: e
label: VOICE_PASSIVE
sublabels: [CONNECTIVE_SYNTAX]
explanation: “when convicted of …” は主語不一致の分詞構文ぎみ；“when he was convicted …”/“after being convicted …” に直す。
text:
  a: when winning a game conflicts with fairness,
  b: with a fastball to put him out of the game.
  c: one is tempted to sacrifice loyalty for honesty,
  d: to shield his boss from a charge of conspiracy.
  e: which he later came to regret when convicted of perjury.
ja:
  a: 勝利が公正さと衝突するとき
  b: 速球で退場させることを考える
  c: 誠実のために忠誠を犠牲にしたくなることもある
  d: 上司を共謀罪の告発から守るために嘘をつく
  e: のちに偽証罪で有罪となった際に後悔することになった（→ when he was convicted / after being convicted）
lures:
  - opt: a  tags: [VERB_VALENCY]  expl: conflict with の固定で迷わせるが可。
  - opt: b  tags: [LEXICAL_NUANCE]  expl: 具体描写で注意を逸らすが可。
  - opt: c  tags: [LEXICAL_NUANCE]  expl: sacrifice A for B の型は可。
  - opt: d  tags: [PREP_COLLOC]  expl: shield A from B の固定は正。誤りに見せる。