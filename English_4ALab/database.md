
# Rules, Games, and Social Order
set: 2025_UT
title: Rules, Games, and Social Order
answers: 21-a / 22-b / 23-b / 24-c / 25-c

---

### (2025_UT Q21)
```db
set: 2025_UT
question: 21
correct: a
label: PREP_COLLOC
sublabels: [IDIOM_FAKE]
explanation: account は **account for A**。「Aを…として説明する」→ **account for them as …**。*account to* は不可。
text:
  a: to account to them as the mechanisms
  b: the framework that is used to agree on
  c: This idea, put forward
  d: emerged in online discussions about creating
  e: to create in advance rules to cover
ja:
  a: ルールを「合意を生む**仕組み**として**説明する**」
  b: 何が起きたかに**合意するための枠組み**
  c: **提案された**考え
  d: TRPG作成の**オンライン議論で生まれた**
  e: **あらかじめ**作るルールで全状況を網羅するのは不可能
lures:
  - opt: b
    tags: [REL_PRONOUN]
    expl: agree **on** が定型。framework は単数で **that is** も合う。
  - opt: c
    tags: [LEXICAL_NUANCE]
    expl: put forward＝正用。
  - opt: d
    tags: [VERB_VALENCY]
    expl: discussions **about creating** … は可。
  - opt: e
    tags: [WORD_ORDER]
    expl: “create rules **in advance** to cover …” の語順も可。
```

---

### (2025_UT Q22)
```db
set: 2025_UT
question: 22
correct: b
label: REL_PRONOUN
sublabels: [PREP_REL]
explanation: 先行詞は **the field**。→ **in which** / **where** games are utilized。“, **which games are utilized** …” は不可。
text:
  a: rules are not necessarily intended to be fully binding
  b: which games are utilized for goal-oriented purposes
  c: possibly implemented as a computer program
  d: “every possible combination of players’ decisions is thus exactly defined.”
  e: they can sometimes even invent more rules
ja:
  a: ルールは**必ずしも完全拘束**ではないことがある
  b: **その分野では**ゲームが実務目的で用いられる
  c: **コンピュータ実装**される場合もある
  d: あらゆる選択の組合せが**厳密に定義**される
  e: 参加者が**途中で新ルール**を作ることもある
lures:
  - opt: a
    tags: [LEXICAL_NUANCE]
    expl: binding＝拘束力あり。文脈適合。
  - opt: c
    tags: [PARTICIPLE]
    expl: 分詞の挿入句＝可。
  - opt: d
    tags: [QUOTE_ACCURACY]
    expl: 引用内は正。
  - opt: e
    tags: [CONNECTIVE_SYNTAX]
    expl: while … ongoing と整合。
```

---

### (2025_UT Q23)
```db
set: 2025_UT
question: 23
correct: b
label: ADV_ADJ_FORM
sublabels: [ADJ_PARTICIPLE]
explanation: “make playing **more demanding / interesting**”。*more demanded / interested* は形容詞選択誤り。
text:
  a: Not all constraints relating to a game
  b: more demanded or interested
  c: make the game easier and ignore some formal rules
  d: so is the play of power
  e: rules order social reality
ja:
  a: ゲーム関連の制約が**すべて**共有される必要はない
  b: **より難しく／より面白く**
  c: **易しくして**一部の形式ルールを**無視**する
  d: 権力の駆け引きも**同様だ**
  e: ルールは**支配以外の仕方でも**社会的現実を秩序化する
lures:
  - opt: a
    tags: [NEG_POLARITY]
    expl: Not all … の部分否定＝自然。
  - opt: c
    tags: [PARALLEL_COMPAR]
    expl: decide to の省略並列で可。
  - opt: d
    tags: [CONNECTIVE_SYNTAX]
    expl: so is … の倒置＝正。
  - opt: e
    tags: [WORD_CHOICE]
    expl: order＝秩序づける。学術文体で普通。
```

---

### (2025_UT Q24)
```db
set: 2025_UT
question: 24
correct: c
label: PREP_COLLOC
sublabels: [VERB_VALENCY]
explanation: “make A available **to** people / make available **to** people A”。**to** が必須。*make available people* は不可。
text:
  a: that guide people in their everyday behavior
  b: do much more than establish and maintain
  c: They make available people the wisdom of accumulated experience
  d: secure people against the totally unexpected in social encounters
  e: rules originate and persist in the effort to solve
ja:
  a: 日常行動を**導く**規則
  b: **階層の維持**以上の働きをする
  c: **蓄積された経験の知恵を人々に提供する**（to people が要る）
  d: 社会的出会いでの**不意の事態から守る**
  e: 規則は**共同生活の課題を解決する努力**から生まれ持続する
lures:
  - opt: a
    tags: [REL_PRONOUN]
    expl: 二つの that 節の連続は可。
  - opt: b
    tags: [PARALLEL_COMPAR]
    expl: establish **and** maintain の動詞並列＝可。
  - opt: d
    tags: [PREP_COLLOC]
    expl: secure A **against** B は定型で可。
  - opt: e
    tags: [CONNECTIVE_SYNTAX]
    expl: originate and persist in … は自然。
```

---

### (2025_UT Q25)
```db
set: 2025_UT
question: 25
correct: c
label: PHRASAL_PART
sublabels: [WORD_ORDER]
explanation: 代名詞目的語は句動詞の**間に挿入**。→ **pick them up**。*pick up them* は不可。
text:
  a: influence games, for example, through end-user license agreements
  b: gameplay is also constrained by material reality
  c: trying to pick up them
  d: constraints that limit player action
  e: make it possible for the player to perform
ja:
  a: EULAや時間制限を通じて**ゲームに影響**する
  b: ゲームプレイは**物的現実**にも制約される
  c: **それらを拾い上げようとしている**（**pick them up**）
  d: **行為を制限する制約**
  e: **意味ある行為**を可能にする
lures:
  - opt: a
    tags: [PREP_COLLOC]
    expl: influence … through … は自然。
  - opt: b
    tags: [VOICE_PASSIVE]
    expl: is constrained by … は正。
  - opt: d
    tags: [REL_PRONOUN]
    expl: constraints **that** limit … は可。
  - opt: e
    tags: [VERB_VALENCY]
    expl: make it possible **for 人 to** V＝定型。
```



