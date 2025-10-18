
# 2025

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

### (2025_pre_1 Q21)

```db
set: 2025_pre_1
question: 21
correct: a
label: PARALLEL_COMPAR
sublabels: []
explanation: 比較は “as tiny as …”／単独なら “so tiny”。“so much tiny as” は不正。
text:
  a: something so much tiny as a living cell
  b: capable of behaviour so complex
  c: It can sense its environment
  d: maintain its structure
  e: know how to do all of this
ja:
  a: 「生きている細胞**ほど小さな**もの」
  b: 「**非常に複雑な**ふるまいを行う**能力がある**」
  c: 「それ（アメーバ）は**環境を感知でき**」
  d: 「**自らの構造を維持し**」
  e: 「細胞が**どうしてこれらすべてを行えるのか**」
lures:
  - opt: b
    tags: [PARALLEL_COMPAR]
    expl: “behaviour **so complex**”＝可（= that is so complex）。“such complex behaviour” も可。
  - opt: c
    tags: [WORD_ORDER]
    expl: 列挙の一部で可。
  - opt: d
    tags: [WORD_ORDER]
    expl: 同一列挙で可。
  - opt: e
    tags: [WORD_CHOICE]
    expl: 擬人的 “know” は科学文で慣用的に可。
```

---

### (2025_pre_1 Q22)

```db
set: 2025_pre_1
question: 22
correct: c
label: PREP_COLLOC
sublabels: []
explanation: “necessary **for** the cell to function” が定型。of は不可。
text:
  a: which constitutes a range of organisms from humans to amoeba
  b: within a structure called the nucleus
  c: necessary of the cell to function
  d: the narrative goes
  e: based on instructions provided by the genes
ja:
  a: 「人間からアメーバまでの**範囲の生物群を構成する**」※文意は“（細胞が）〜に**存在する/見られる**”が自然
  b: 「**核と呼ばれる構造の内部**に」
  c: 「細胞が機能する**ために必要な**」
  d: 「いわば“物語が言うところでは”」
  e: 「遺伝子の与える**指示に基づいて**」
lures:
  - opt: a
    tags: [CONTENT_DRIFT, VERB_VALENCY, ANXIETY_CUE]
    expl: “constitute of” は不可。ここは意味ずれで惑わせる。
  - opt: b
    tags: [PREP_COLLOC]
    expl: within/in はどちらも可。
  - opt: d
    tags: [LEXICAL_NUANCE, ANXIETY_CUE]
    expl: 挿入句 “the narrative goes”＝可。
  - opt: e
    tags: [PREP_COLLOC]
    expl: based **on**＝定型。by と混同しない。
```

---

### (2025_pre_1 Q23)

```db
set: 2025_pre_1
question: 23
correct: e
label: ADV_ADJ_FORM
sublabels: [REL_PRONOUN]
explanation: 名詞修飾には分詞/関係節が要る → “executives **ordering** … / **who order** …”。過去形 ordered は×。
text:
  a: where genes issue instructions
  b: that do the work of the body from day to day
  c: almost word for word
  d: performing the work of
  e: ordered the manual labour of
ja:
  a: 「遺伝子が**指示を出す**“（比喩的）場”」
  b: 「日々**身体の働きを担う**」
  c: 「**ほぼ逐語的に**」
  d: 「〜という**作業を行って**」
  e: 「重労働者の**肉体労働を命じた**」（×）→「**命じる/命じている**」に相当
lures:
  - opt: a
    tags: [REL_PRONOUN]
    expl: where＝in which 相当で可。
  - opt: b
    tags: [LEXICAL_NUANCE]
    expl: do the work of …＝自然。
  - opt: c
    tags: [LEXICAL_NUANCE]
    expl: 定型副詞句で可。
  - opt: d
    tags: [PARALLEL_COMPAR]
    expl: manufacturing/packaging/shipping と並列で可。
```

---

### (2025_pre_1 Q24)

```db
set: 2025_pre_1
question: 24
correct: d
label: VERB_VALENCY
sublabels: []
explanation: 使役 **have + O + V**。→ “would **have us believe**”。to は不可。
text:
  a: present throughout the cell
  b: interact with each other
  c: Nor is the cell obsessed with the economically significant work of 'manufacturing'
  d: would have us to believe
  e: can be thought of as maintaining itself and taking 'care' of other cells
ja:
  a: 「（統制・情報は）**細胞全体に存在**する」
  b: 「（小器官は）**相互作用**する」
  c: 「さらに，細胞は『工場』比喩が示唆する**“製造”偏重**ではない」
  d: 「『工場』の比喩が**私たちに信じさせようとする**」（× to）
  e: 「むしろ多くは**自己維持**と**他細胞のケア**とみなせる」
lures:
  - opt: a
    tags: [PARALLEL_COMPAR]
    expl: “are not restricted … **but (are) present** …” 省略可。
  - opt: b
    tags: [PARALLEL_COMPAR]
    expl: form と interact の動詞並列＝可。
  - opt: c
    tags: [CONNECTIVE_SYNTAX]
    expl: Nor + 倒置／be obsessed with＝正。
  - opt: e
    tags: [WORD_ORDER]
    expl: be thought of **as** V-ing＝定型。“taking care of” も定型。
```

---

### (2025_pre_1 Q25)

```db
set: 2025_pre_1
question: 25
correct: e
label: CONTENT_REVERSE
sublabels: []
explanation: ここは「自然だと**思わせる**」流れ。discourages→**encourages** が筋。
text:
  a: continue to portray the cell
  b: sounds obvious and natural to us
  c: it resonates with our stratified societies
  d: prevent us from understanding
  e: discourages the notion that
ja:
  a: 「細胞を**階層として描き続ける**」
  b: 「この見方は**当然で自然に聞こえる**」
  c: 「それは**階層社会と中央集権**に**響き合う**から」
  d: 「そうした比喩は**理解を妨げる**」
  e: 「科学が社会ヒエラルキーを細胞に投影すると，ヒエラルキーが『自然だ』という**考えをくじく**」（×）→**促す**（○）
lures:
  - opt: a
    tags: [WORD_CHOICE]
    expl: portray A as B＝定型。
  - opt: b
    tags: [LEXICAL_NUANCE]
    expl: sound + adj / to us＝自然。
  - opt: c
    tags: [PREP_COLLOC]
    expl: resonate **with**＝定型。
  - opt: d
    tags: [PREP_COLLOC]
    expl: prevent A **from** -ing＝定型。

```

### (2025_open_1 Q21)
```db
set: 2025_open_1
question: 21
correct: d
label: CONNECTIVE_SYNTAX
sublabels: [TOO_SO_THAT]
explanation: “too … that …” は不可。→ **so** crowded **that** … / **too** crowded **to** …
text:
  a: humanity **sent** around 200 objects into space per year
  b: with no prospects for slowing down
  c: has **filled Earth's orbit** with space trash
  d: The region is already **too crowded that** working satellites run the risk …
  e: adjust its orbit at least 39 times
lures:
  - opt: a — label: TENSE_ASPECT — expl: 叙述の過去「A decade ago … sent」は可。
  - opt: b — label: WORD_CHOICE — expl: prospects for + V-ing は定型。可。
  - opt: c — label: PREP_COLLOC — expl: fill A **with** B が定型。*fill out* ではない（本文は正）。
  - opt: e — label: NUMBER_USAGE — expl: at least 39 times は数量表現として自然。
```

---

### (2025_open_1 Q22)
```db
set: 2025_open_1
question: 22
correct: e
label: REL_PRONOUN
sublabels: [COMMA_SPLICE, NONRESTRICTIVE]
explanation: 直前の名詞句を受ける非制限関係に。→ “generated nearly 2,000 debris fragments, **many of which are** still being tracked …”
text:
  a: larger than 10 centimeters
  b: The more we put up there, the greater the chance that …
  c: creating even more dangerous trash.
  d: the collision **between** the non-functioning … and the functioning …
  e: generated … fragments, **many of them are still** being tracked …
lures:
  - opt: a — label: MEASURE_NP — expl: larger than 10 cm は可。
  - opt: b — label: CORRELATIVE — expl: the more …, the greater … 構文は正。
  - opt: c — label: PARTICIPLE — expl: 分詞結果用法は可。
  - opt: d — label: PREP_COLLOC — expl: between X and Y は正。
```

---

### (2025_open_1 Q23)
```db
set: 2025_open_1
question: 23
correct: c
label: PARALLEL_COMPAR
sublabels: [WRONG_THAN, INFINITIVE_PURPOSE]
explanation: 目的不定詞を比較 **than** にぶつけているのが誤り。→ “aims to **send** tens of thousands more satellites **to provide** global broadband …”
text:
  a: it’s rapidly being consumed by a few dominant organizations
  b: owns and operates the **majority of** all working satellites
  c: aims to send tens of thousands more satellites **than to provide** …
  d: plans to use 3,236 satellites …
  e: What these plans attempt to do **is add** thousands more satellites …
lures:
  - opt: a — label: VOICE_PASSIVE — expl: be consumed by … は可。
  - opt: b — label: LEXICAL_NUANCE — expl: “majority of all” は冗長気味だが許容。
  - opt: d — label: NUMBER_USAGE — expl: 固有数の提示は可。
  - opt: e — label: COMPLEMENT_CLAUSE — expl: “what … do **is (to) add** …” は bare / to 不定詞どちらも可。
```

---

### (2025_open_1 Q24)
```db
set: 2025_open_1
question: 24
correct: e
label: CONTENT_REVERSE
sublabels: [WORD_CHOICE]
explanation: 趣旨は「**無制限の**アクセスを全員に与えると制御不能」。→ “Giving everyone **unlimited** access …”
text:
  a: If we **keep up** this pace
  b: LEO, **which extends up to** 2,000 kilometers …
  c: **When looking** at all orbital regions, we lose services we rely on:
  d: is **equivalent to** a piece of single-use plastic
  e: Giving everyone **limited** access without global coordination …
lures:
  - opt: a — label: PHRASAL_VERB — expl: keep up this pace＝このペースを維持する。可。
  - opt: b — label: REL_PRONOUN — expl: 非制限関係節の説明は正。
  - opt: c — label: PARTICIPLE — expl: 主語 “we” と -ing の照応は取れており文法○。
  - opt: d — label: IDIOM_REAL — expl: be equivalent to … は定型。
```

---

### (2025_open_1 Q25)
```db
set: 2025_open_1
question: 25
correct: d
label: PARALLEL_COMPAR
sublabels: [COORDINATION, INFINITIVE]
explanation: “must **leave** … **and move** toward …” と並列に。× “leave … **and to move** …”
text:
  a: as we **continue to** push the boundaries …
  b: to rethink our approach **to using** the space environment
  c: based on careful monitoring **and sound** waste-management principles
  d: we must leave behind … **and to move toward** a “circular space economy”
  e: that emphasizes the **reuse, recycling, and** efficient management …
lures:
  - opt: a — label: VERB_PATTERN — expl: continue to V は定型。
  - opt: b — label: PREP_COLLOC — expl: approach **to** -ing は名詞 approach の定型。
  - opt: c — label: LEXICAL_NUANCE — expl: sound＝健全な。語義適合。
  - opt: e — label: PARALLEL_NP — expl: reuse / recycling / management は名詞列で並列OK。
```





### (2025_realbattle_1 Q21)
```db
set: 2025_realbattle_1
question: 21
correct: a
label: WORD_CHOICE
sublabels: [LEXICAL_NUANCE]
explanation: *defined impact* は不自然。→ “a **definite / significant / defining** impact”.
text:
  a: has had **a defined impact** on your life
  b: Mike was something of an electronics wizard
  c: they called Mike to fix them
  d: which ended up paying for his first year of college
  e: Mike did what so many great entrepreneurs of his era would do:
ja:
  a: 「**はっきりした／大きな**影響」→ *defined* は語選択ミス
  b: 「ちょっとした電子の達人だった」
  c: 「先生たちは直してもらうため彼に電話した」
  d: 「そのブザーが大学1年の学費を賄った」
  e: 「当時の多くの起業家がしたことを彼もした」
```

---

### (2025_realbattle_1 Q22)
```db
set: 2025_realbattle_1
question: 22
correct: e
label: PRON_REF
sublabels: [PHRASAL_VERB, IDIOM_FAKE]
explanation: 端末を渡す＝**hand it over (to …)**。*hand **him** over* だと「人を引き渡す」の意味になる。
text:
  a: he patented a device … which was so useful …
  b: That was small potatoes compared to his next big invention,
  c: made his firm the fastest-growing company on the planet.
  d: with loyal customers ranging from Bill Gates to Christina Aguilera.
  e: President Obama refused to hand **him** over to the Secret Service.
ja:
  a: 「極めて有用で賞を受けた」
  b: 「それは**大したことない**（慣用）」
  c: 「会社を最速成長企業にした」
  d: 「著名人にも熱狂的顧客」
  e: 「大統領はそれ（端末）を**提出しなかった**べき → **hand it over**」
```

---

### (2025_realbattle_1 Q23)
```db
set: 2025_realbattle_1
question: 23
correct: c
label: PREP_COLLOC
sublabels: [CONNECTIVE_SYNTAX]
explanation: 時の導入は **By** が定型。→ “**By** the summer of 2009, it accounted …”。*As the summer of 2009* は不可。
text:
  a: dreamed up the idea for the BlackBerry
  b: a wireless communication device for sending and receiving emails
  c: **As** the summer of 2009, it
  d: accounted for nearly half of the U.S. smartphone market.
  e: to less than 1 percent.
ja:
  a: 「着想を思いついた」
  b: 「送受信用の無線機器として」
  c: 「**2009年夏までに** が正」
  d: 「米国市場の**ほぼ半分**を占めた」
  e: 「1％未満へと落ちた」
```

---

### (2025_realbattle_1 Q24)
```db
set: 2025_realbattle_1
question: 24
correct: b
label: PREP_COLLOC
sublabels: [VERB_VALENCY]
explanation: **adapt to** a changing environment が定型。本文は前置詞欠落（*adapting a changing environment*）。
text:
  a: we can never pinpoint a single cause of its downfall,
  b: adapting **a** changing environment isn’t something a company does
  c: in the multitude of decisions they make every day.
  d: his thinking may have been the spark that ignited the smartphone revolution,
  e: his struggles with rethinking ended up sucking the oxygen out of his company
ja:
  a: 「唯一の原因は特定できない」
  b: 「**変化する環境に適応する**こと」（**to** が必要）
  c: 「人々が日々下す無数の決定の中で」
  d: 「彼の思考が火付け役だったかもしれない」
  e: 「再考の不全が会社の“酸素”を吸い尽くした」
```

---

### (2025_realbattle_1 Q25)
```db
set: 2025_realbattle_1
question: 25
correct: d
label: PARALLEL_COMPAR
sublabels: [WORD_ORDER]
explanation: “spend **as much time rethinking as** (we do) **thinking**”。後半は動詞省略または **do** 受け。*are thinking* は非並列。
text:
  a: in staying true to our beliefs and opinions
  b: where we get rewarded for having conviction in our ideas
  c: we live in a rapidly changing world,
  d: spend as much time rethinking as **we are thinking**
  e: get them out of the shed and remove the rust
ja:
  a: 「信念や意見に忠実であることにも」
  b: 「確信を持つことで報われる場所／状況で」
  c: 「急速に変化する世界に生きている」
  d: 「**再考に**思考と同じだけ時間を費やす（*are* ではなく省略 or **do**）」
  e: 「道具を物置から出し，錆を落とす（比喩）」
```

### (2025_toshin_2 Q21)
```db
set: 2025_toshin_2
question: 21
correct: e
label: ADV_ADJ_FORM
sublabels: [WORD_CHOICE]
explanation: “not **necessarily** more” が正。*necessary*（形容詞）は不可。
text:
  a: claim you need to take …
  b: the scientific basis for popular health claims is often thin.
  c: is based more on marketing … than science.
  d: **Data point** to clear benefits …
  e: but not **necessary** more.
ja:
  d: 「データ**は**示す」→ Data は複数主語なので **point** 自体は複数形と一致（動詞形は正）。  
  e: 「必ずしもそれ以上ではない」→ **necessarily** が必要。
lures:
  - opt: a
    label: VERB_VALENCY
    expl: claim (that) S V / claim you need to … は可。
  - opt: b
    label: ARTICLE_DET
    expl: basis for A は自然。可。
  - opt: c
    label: PREP_COLLOC
    expl: be based **on** A … than B＝定型。
  - opt: d
    label: SVA_AGREEMENT
    expl: Data＝複数。**point**（原形）=複数一致で正。単数扱いに引っ張る誘導。
```

---

### (2025_toshin_2 Q22)
```db
set: 2025_toshin_2
question: 22
correct: d
label: PREP_COLLOC
sublabels: [PHRASAL_VERB]
explanation: “reach **for** sodas” が定型。*reach to* は不可。
text:
  a: Often popular wisdom turns out to be only sort of true.
  b: The emphasis on so many steps is one instance.
  c: let yourself get too thirsty
  d: may be tempted to **reach to** sodas
  e: shouldn’t worry if we drink only six.
ja:
  a: 「まぁ本当の部分もある」＝自然。
  b: 「〜歩の強調」＝文法的に可。
  d: 「ソーダに**手を伸ばす**」→ **for** が必要。
  e: 「6杯でも**気にする必要はない**」＝可。*be worried* でなくてよい。
lures:
  - opt: a
    label: LEXICAL_NUANCE
    expl: only sort of true は口語的だが容認。
  - opt: b
    label: SVA_AGREEMENT
    expl: emphasis（単数） + is で整合。
  - opt: c
    label: IDIOM_REAL
    expl: let yourself get too thirsty＝可。
  - opt: e
    label: MODAL_USAGE
    expl: shouldn’t worry if … で十分。受動 *be worried* 不要。
```

---

### (2025_toshin_2 Q23)
```db
set: 2025_toshin_2
question: 23
correct: e
label: WORD_CHOICE
sublabels: [PARALLEL_COMPAR]
explanation: **the latter**（後者）が正。*the later* は時系列の「後で」。
text:
  a: to dig a bit into …
  b: often heard health maxims
  c: a nugget of truth that has become seriously exaggerated
  d: stems from outdated and poorly applied evidence
  e: The **later** is what happened …
ja:
  e: 「後者の方が起きた」→ **latter** 必要。
lures:
  - opt: a
    label: PHRASAL_VERB
    expl: dig into … は可。
  - opt: b
    label: ADV_ADJ_FORM
    expl: often-heard に連結ハイフンがより自然だが文法×ではない。
  - opt: c
    label: PARTICIPLE
    expl: has become seriously exaggerated＝可。
  - opt: d
    label: VERB_VALENCY
    expl: stem from … ＝定型。
```

---

### (2025_toshin_2 Q24)
```db
set: 2025_toshin_2
question: 24
correct: d
label: PARALLEL_COMPAR
sublabels: [CORRELATIVE]
explanation: **either A or B** が正。*either … and …* は非対格。
text:
  a: have heard distressing warnings …
  b: We have been repeatedly told that …
  c: so people who want children …
  d: either need to get moving **and** freeze their eggs.
  e: discussions of it are commonplace …
ja:
  d: 「子どもが欲しい人は**〜するか〜するか**」→ **or** 必須。
lures:
  - opt: a
    label: WORD_CHOICE
    expl: distressing の語義は文脈適合。可。
  - opt: b
    label: TENSE_ASPECT
    expl: 現在完了受動（継続）=可。
  - opt: c
    label: CONNECTIVE_SYNTAX
    expl: so（結果/因果）でも接続上許容。誤りではない。
  - opt: e
    label: PREP_COLLOC
    expl: discussion(s) **of** it で可。about も可だが of で問題なし。
```

---

### (2025_toshin_2 Q25)
```db
set: 2025_toshin_2
question: 25
correct: c
label: CONTENT_REVERSE
sublabels: [DISCOURSE_LOGIC]
explanation: 論旨は「30歳以上の**出生率は上昇**していた」。本文は *were going **down*** と逆。→ **were going up**。
text:
  a: a 2004 paper based on records from 1670 through 1830
  b: people are now healthier overall and likely to be more fertile …
  c: fertility rates for women aged 30 and older **were going down.**
  d: started to become more common and more clinics began opening
  e: were being sounded by this growing industry …
ja:
  c: 「下がっていた」→ 文脈は「上がっていた」なので反転。
lures:
  - opt: a
    label: DATE_RANGE
    expl: from … through … の期間表現は可。
  - opt: b
    label: LEXICAL_NUANCE
    expl: healthier overall / more fertile ＝自然。
  - opt: d
    label: PARALLEL_COMPAR
    expl: started to become … **and** more clinics began opening＝時制・並列とも許容。
  - opt: e
    label: VOICE_PASSIVE
    expl: be sounded by …（受動）＝比喩的用法で可。
```

### (2025_toshin_3 Q21)
```db
set: 2025_toshin_3
question: 21
correct: b
label: SVA_AGREEMENT
sublabels: []
explanation: 主語は単数 “The beach …” → 動詞は **features**。*feature*（複数形動詞）は不一致。
text:
  a: one of the most pristine places on Earth
  b: The beach … **feature**
  c: have been recorded
  d: Its waters, only partially explored by scientists, contain …
  e: home to tribal groups such as …
ja:
  a: 「地球でもっとも**手つかず**の場所の一つ」
  b: 「島南端の**その浜は**…を**有する**（× feature → **features**）」
  c: 「2,500種超が**記録されている**」
  d: 「その海域は（科学者により部分的にしか探索されていないが）**…を含む**」
  e: 「…のような**部族の居住地**である」
lures:
  - opt: a
    tags: [LEXICAL_NUANCE]
    expl: pristine の評価語だが文法○。
  - opt: c
    tags: [TENSE_ASPECT]
    expl: 現在完了受動は事実記述として自然。
  - opt: d
    tags: [APPOSITIVE]
    expl: 同格挿入句＋主節動詞は合致。
  - opt: e
    tags: [CONTENT_DRIFT]
    expl: “the Andamans” は地名で語義違和感だが文法×ではない。
```

---

### (2025_toshin_3 Q22)
```db
set: 2025_toshin_3
question: 22
correct: e
label: NEG_POLARITY
sublabels: [VERB_VALENCY]
explanation: **refuse to allow A to V** が定型。*refuse to allow A **not to** V* は二重否定で意味逆転。→ “… **allow outsiders to follow** them back …” を拒む。
text:
  a: numbering between 200 and 400
  b: have been uncovered
  c: Still, these travelers' accounts, …
  d: On rare occasions,
  e: allow outsiders **not to** follow them back
ja:
  a: 「（人数が）**200–400人**である」
  b: 「断片だけが**明らかになっている**」
  c: 「それでも，これら**旅行者の記録**は…を部分的に示す」
  d: 「**まれに**」
  e: 「よそ者が**ついて来**ないことを**許す**（×）→ ついて来るのを**許さない**」
lures:
  - opt: a
    tags: [PARTICIPLE]
    expl: 非制限分詞（numbering …）は可。
  - opt: b
    tags: [VOICE_PASSIVE]
    expl: 受動完了で可。
  - opt: c
    tags: [DISCOURSE_MARKER]
    expl: Still, … の逆接副詞は可。
  - opt: d
    tags: [PUNCTUATION]
    expl: 句読点位置は自然。
```

---

### (2025_toshin_3 Q23)
```db
set: 2025_toshin_3
question: 23
correct: a
label: REL_PRONOUN
sublabels: [PREP_REL]
explanation: 先行詞 “The Indian government” に対し **which**（or “that/which it”）で十分。前置詞 **in** は不要。→ “The Indian government, **which inherited** …, plans …”
text:
  a: **in which** inherited Great Nicobar Island
  b: plans to build a massive transshipment terminal
  c: a port capable of handling 16 million cargo containers …
  d: a power plant, and an airport that can handle …
  e: will spread over 244 square kilometers
ja:
  a: 「**それ（政府）が継承した**」の意で **which inherited** が正（“in” は不要）
  b: 「巨大な**積替えターミナル**を建設する計画」
  c: 「年間1,600万コンテナを扱える港」
  d: 「1時間4,000人を処理可能な空港」
  e: 「総面積**244平方km**に及ぶ」
lures:
  - opt: b
    tags: [LEXICAL_NUANCE]
    expl: 語法は自然。
  - opt: c
    tags: [MODIFIER]
    expl: capable of -ing の補語は正。
  - opt: d
    tags: [REL_PRONOUN]
    expl: 限定用法 that は適切。
  - opt: e
    tags: [TENSE_ASPECT]
    expl: will spread … and destroy … の未来叙述で可。
```

---

### (2025_toshin_3 Q24)
```db
set: 2025_toshin_3
question: 24
correct: e
label: VOICE_PASSIVE
sublabels: [AUX_BE]
explanation: 受動に **be** が要る。→ “The Shompen **will be pressed** to compete for resources.”
text:
  a: One destructive aspect
  b: not immune to
  c: that prey on vulnerable creatures
  d: rivers, where the Shompen **fish** and collect drinking water
  e: will **pressed** to compete for
ja:
  a: 「破壊的側面の**一つ**」
  b: 「〜に**免疫がない**」
  c: 「弱い生物を**捕食する**」
  d: 「（河川で）ショムペンが**漁をし**飲料水を**集める**場所」
  e: 「ショムペンは資源を巡って**争わざるを得なくなる**（× be 不足）」
lures:
  - opt: a
    tags: [ARTICLE_DET]
    expl: one + 名詞は可。
  - opt: b
    tags: [PREP_COLLOC]
    expl: be immune **to** N は定型。
  - opt: c
    tags: [REL_PRONOUN]
    expl: that 節で先行詞 creatures を修飾＝可。
  - opt: d
    tags: [PREP_REL]
    expl: where = “in which” の意味で可（from which の省略含意）。
```

---

### (2025_toshin_3 Q25)
```db
set: 2025_toshin_3
question: 25
correct: d
label: ADJ_PARTICIPLE
sublabels: [VERB_FORM]
explanation: 名詞 “fence” を後置修飾するなら **surrounding** / “that **surrounds**”。*surrounded* は完了受動の形で構造不一致。
text:
  a: from the transshipment terminal
  b: helpless and abandoned
  c: that has no relation to the island
  d: a militarized fence **surrounded** the project territory
  e: they have occupied for millennia
ja:
  a: 「積替えターミナル**から**島を守るため」
  b: 「**無力で見捨てられた**と感じる」
  c: 「島と**無関係な**地域（を植林）」
  d: 「計画区域を**取り囲む**有刺化フェンス（× surrounded → **surrounding / that surrounds**）」
  e: 「彼らが**何千年も占有してきた**空間」
lures:
  - opt: b
    tags: [ADJ_PARTICIPLE]
    expl: abandoned は形容詞用法で可。
  - opt: c
    tags: [REL_PRONOUN]
    expl: 関係節 that … は可。
  - opt: e
    tags: [TENSE_ASPECT]
    expl: 現在完了継続（have occupied）で可。
```

# 2024

### (2024_UT Q21)
```db
set: 2024_UT
question: 21
correct: b
label: PARALLEL_COMPAR
sublabels: [CORRELATIVE]
explanation: **either A or B** が定型。→ “to feel **either** slower **or** faster”。“either … and …” は誤り。
text:
  a: anything but constant
  b: to feel either slower and faster
  c: have uncovered corresponding findings
  d: influences our perception of time as it passes
  e: look at the experience of time in isolation from the body
ja:
  a: 「一定どころではない」
  b: 「**より遅く**または**より速く**感じさせる」
  c: 「一致する所見を明らかにした」
  d: 「時の流れ**そのもの**に影響する」
  e: 「体から切り離して考えることはできない」
lures:
  - opt: a
    tags: [IDIOM_FAKE]
    expl: anything but + 形容詞＝強い否定で正。
  - opt: c
    tags: [LEXICAL_NUANCE]
    expl: corresponding findings＝文脈適合。
  - opt: d
    tags: [CONNECTIVE_SYNTAX]
    expl: as it passes＝時間の経過を指す挿入で可。
  - opt: e
    tags: [PREP_COLLOC]
    expl: in isolation from ~＝定型。
```

---

### (2024_UT Q22)
```db
set: 2024_UT
question: 22
correct: e
label: VOICE_PASSIVE
sublabels: [FINITE_VERB]
explanation: 受動の **be** が必要。→ “One item … **was** presented for 200 milliseconds”。並列でlastedは能動態なので注意。
text:
  a: reported that time perception changes
  b: with each heartbeat
  c: learned to distinguish the duration of
  d: two visual or two auditory stimuli
  e: One item … **presented** for 200 milliseconds
ja:
  a: 「時間知覚が変化すると報告した」
  b: 「各心拍ごとに」
  c: 「持続時間の**識別**を学習した」
  d: 「視覚刺激2つ**または**聴覚刺激2つ」
  e: 「各ペアの一方は**200ms提示された**」（be なしは×）
lures:
  - opt: a
    tags: [TENSE_ASPECT]
    expl: reported that + 一般現在（通時的事実）＝可。
  - opt: b
    tags: [PREP_COLLOC]
    expl: with each heartbeat＝可。
  - opt: c
    tags: [VERB_VALENCY]
    expl: distinguish the duration of …＝可。
  - opt: d
    tags: [PARALLEL_COMPAR]
    expl: two A **or** two B の並列＝可。
```

---

### (2024_UT Q23)
```db
set: 2024_UT
question: 23
correct: a
label: CONNECTIVE_SYNTAX
sublabels: [INDIRECT_QUESTION]
explanation: 間接疑問は “**whether** it felt shorter or longer / **how long** it felt”。“how the presentation felt shorter or longer” は型崩れ。
text:
  a: how the presentation felt shorter or longer
  b: matched with a particular moment
  c: during the heartbeat
  d: perceived time duration to be shorter than it actually was
  e: the exact opposite was true
ja:
  a: 「提示が**短く感じたか長く感じたか**を」（how ではなく whether / how long）
  b: 「心拍リズムの特定の瞬間に**対応づけられた**」
  c: 「心拍**の間に**」
  d: 「**実際より短いと**知覚した」
  e: 「拡張期では**まったく逆**だった」
lures:
  - opt: b
    tags: [VERB_VALENCY]
    expl: match A with B＝可。
  - opt: c
    tags: [PREP_COLLOC]
    expl: during the heartbeat＝可。
  - opt: d
    tags: [WORD_ORDER]
    expl: perceive (the) duration to be … は許容。
  - opt: e
    tags: [DISCOURSE_LOGIC]
    expl: 対比句として自然。
```

---

### (2024_UT Q24)
```db
set: 2024_UT
question: 24
correct: e
label: CONTENT_REVERSE
sublabels: []
explanation: コーネル結果は「**間隔が長いほど時間は遅く感じる**」。本文 e は「間隔が長い → 速く動く」と逆極性。
text:
  a: explained by the fact that
  b: affect its capacity to process incoming information
  c: This increase in sensory impressions could make time feel longer.
  d: focused on differences … between single heartbeats
  e: When there is more time between two beats, time seems to move faster.
ja:
  a: 「〜という事実で説明されうる」
  b: 「脳の**処理能力**に影響する」
  c: 「感覚入力の増加で**長く感じる**可能性」
  d: 「**心拍間**の差異に注目した」
  e: 「**拍間が長いほど**時間は**速く**進む」（×）→ **遅く感じる**
lures:
  - opt: a
    tags: [CONNECTIVE_SYNTAX]
    expl: explained by the fact that …＝可。
  - opt: b
    tags: [PRON_REF]
    expl: its＝the brain の照応で可。
  - opt: c
    tags: [DISCOURSE_LOGIC]
    expl: 直前の説明と整合して可。
  - opt: d
    tags: [PREP_COLLOC]
    expl: differences **between** A **and** B／ここは単位 “between single heartbeats” で可。
```

---

### (2024_UT Q25)
```db
set: 2024_UT
question: 25
correct: e
label: PARALLEL_COMPAR
sublabels: [AS_AS]
explanation: 比較構文は **as A as B**。→ “something **as fundamental as** the passage of time”。“similarly fundamental as” は不適切。
text:
  a: including our emotion and attention
  b: at a totally different scale
  c: of growing interest in neuroscience
  d: comfortable with the idea that the brain can influence what the heart does
  e: something **similarly fundamental as** the passage of time
ja:
  a: 「感情・注意**など**を含む」
  b: 「まったく**別の尺度**で起きる」
  c: 「神経科学で**関心が高まりつつある**」
  d: 「脳が心臓に影響しうるという考えに**抵抗がない**」
  e: 「時間の経過と**同じくらい根源的な**もの」（構文×）
lures:
  - opt: a
    tags: [NOUN_CHOICE]
    expl: emotion/attention は不可算扱いで可。
  - opt: b
    tags: [LEXICAL_NUANCE]
    expl: at a different scale＝可。
  - opt: c
    tags: [PREP_COLLOC]
    expl: of growing interest in …＝可。
  - opt: d
    tags: [CLAUSAL_COMP]
    expl: the idea **that** S V の名詞節＝可。
```

### (2024_pre_1 Q21)
```db
set: 2024_pre_1
question: 21
correct: b
label: VERB_VALENCY
sublabels: [PREP_COLLOC]
explanation: “tactics **used to fight** / **used for fighting** wildfires”。“used **to fighting**”＝「〜に慣れている」の誤転用。againstとかはいらない。
text:
  a: carelessly discarded cigarettes
  b: used to fighting wildfires
  c: have changed little in recent decades
  d: to try to dampen the flames
  e: fire lines that the conflagration cannot cross
ja:
  a: 不注意に捨てられたタバコ
  b: 山火事を**消火するために用いられる**戦術（× 戦い**慣れている**）
  c: 近年ほとんど変わっていない
  d: 炎を弱めようとする
  e: 火勢が越えられない防火帯
lures:
  - opt: a
    tags: [ADV_ADJ_FORM]
    expl: 副詞＋分詞形容詞で可。
  - opt: c
    tags: [TENSE_ASPECT]
    expl: 一般現在の事実叙述で可。
  - opt: d
    tags: [LEXICAL_NUANCE]
    expl: dampen the flames＝自然。
  - opt: e
    tags: [REL_PRONOUN]
    expl: 関係節 that … cannot cross は適切。
```

---

### (2024_pre_1 Q22)
```db
set: 2024_pre_1
question: 22
correct: c
label: ADV_ADJ_FORM
sublabels: []
explanation: 定型は “get **near** enough to V”。“get **nearly** enough to …” は名詞補完なしで不自然。
text:
  a: too much energy to be fought
  b: before it reaches the flames
  c: impossible to get nearly enough to contain the blaze
  d: little to do but wait
  e: that might make the fire controllable
ja:
  a: （意味上やや不自然だが決定的誤りではない）
  b: それが炎に届く前に
  c: **十分近づくことが不可能**（near が要る／nearly は不可）
  d: **待つしかほとんどやることがない**
  e: 火を**再び制御可能**にするかもしれない
lures:
  - opt: a
    tags: [LEXICAL_NUANCE]
    expl: fires are too energetic to be fought なら自然。
  - opt: b
    tags: [PREP_COLLOC]
    expl: reach＋目的語（前置詞不要）で正。
  - opt: d
    tags: [IDIOM_FAKE]
    expl: little to do but V＝定型。
  - opt: e
    tags: [LEXICAL_NUANCE]
    expl: make A controllable＝可。
```

---

### (2024_pre_1 Q23)
```db
set: 2024_pre_1
question: 23
correct: d
label: REL_PRONOUN
sublabels: []
explanation: 非制限用法は **which**。コンマ後 “, **which** was the worst year …”。“, that …” は不可。
text:
  a: no longer seems sufficient
  b: that become large and difficult to contain
  c: those that do get big
  d: that was the worst year
  e: in places already prone to burning
ja:
  a: もはや十分とは思えない
  b: 大規模化して制御困難になる
  c: 実際に大きくなるものは
  d: **それは**最悪の年だった（×）→ **which was** …
  e: もともと燃えやすい地域で
lures:
  - opt: a
    tags: [CONTENT_DRIFT]
    expl: 文脈整合。逆ではない。
  - opt: b
    tags: [REL_PRONOUN]
    expl: 制限用法 that 節＝可。
  - opt: c
    tags: [PARALLEL_COMPAR]
    expl: those that … の対照提示＝可。
  - opt: e
    tags: [WORD_ORDER]
    expl: already の位置は自然。
```

---

### (2024_pre_1 Q24)
```db
set: 2024_pre_1
question: 24
correct: e
label: VOICE_PASSIVE
sublabels: []
explanation: “all conflagrations **could, and should, be extinguished**” が正。be 欠落で能動化。
text:
  a: is increasingly being questioned
  b: results in greater stores of unburned fuel
  c: allowed smaller wildfires to burn
  d: created the illusion that
  e: could, and should, extinguish
ja:
  a: 鎮火政策は**ますます疑問視**されている
  b: **未燃の燃料がたまりやすく**なる
  c: **小規模火災をそのまま燃やす**こともあった
  d: 技術が「**すべての大火は**…でき／すべきだ」という**幻想を生んだ**
  e: 「**消火されうる／されるべき**」（× 自動）
lures:
  - opt: a
    tags: [TENSE_ASPECT]
    expl: 進行形受動＝可。
  - opt: b
    tags: [VERB_VALENCY]
    expl: result in＝定型。
  - opt: c
    tags: [LEXICAL_NUANCE]
    expl: allow A to burn＝可。
  - opt: d
    tags: [CONNECTIVE_SYNTAX]
    expl: illusion that S V＝可。
```

---

### (2024_pre_1 Q25)
```db
set: 2024_pre_1
question: 25
correct: e
label: TENSE_ASPECT
sublabels: []
explanation: “since（それ以来）” は**現在完了**が原則 → “Portugal **has not suffered** a disastrous blaze since.”
text:
  a: a shift from suppressing to managing
  b: breaks that fires cannot cross
  c: the deadliest in its history
  d: when they can be controlled
  e: had not suffered a disastrous blaze since
ja:
  a: **消火から管理への**転換
  b: 火が**越えられない遮断帯**
  c: **史上最悪**
  d: **冬には**それらが**制御可能**なとき
  e: それ以来**壊滅的な火災を被っていない**（× 過去完了）
lures:
  - opt: a
    tags: [PARALLEL_COMPAR]
    expl: from A to B＝並列整合。
  - opt: b
    tags: [REL_PRONOUN]
    expl: that … cannot cross＝可。
  - opt: c
    tags: [LEXICAL_NUANCE]
    expl: 自然。
  - opt: d
    tags: [CONNECTIVE_SYNTAX]
    expl: when（時間の関係詞）＝可。
```

### (2024_open_1 Q21)
```db
set: 2024_open_1
question: 21
correct: b
label: REL_PRONOUN
sublabels: [PRON_REF]
explanation: 関係節で目的語 it を再出しない。→ “… environments **(that) we have created** for ourselves”。
text:
  a: getting in the way of listening
  b: we have created it
  c: with few walls
  d: contributes to
  e: much less pay full attention
ja:
  a: 「聞くことを妨げている」
  b: 「私たちが**作り上げた**（× it）」
  c: 「壁が**ほとんどない**」
  d: 「〜に拍車をかける」
  e: 「（Xするのも難しい）**まして**Yはなおさら」
lures:
  - opt: a
    tags: [IDIOM_FAKE]
    expl: get in the way of ~ は正しい慣用。
  - opt: c
    tags: [LEXICAL_NUANCE]
    expl: with + 名詞列＝付帯状況で可。
  - opt: d
    tags: [SVA_AGREEMENT]
    expl: “every A, B, and C”→単数扱いで contributes。
  - opt: e
    tags: [CONNECTIVE_SYNTAX]
    expl: hard to X, much less Y＝定型。
```

---

### (2024_open_1 Q22)
```db
set: 2024_open_1
question: 22
correct: a
label: CONTENT_REVERSE
sublabels: []
explanation: 文脈は「静かな会話は**難しい**」。→ “is even **less** likely / harder”。“more likely” は逆。
text:
  a: is even more likely
  b: have sound levels that exceed 90 decibels
  c: you can't go to a coffee shop
  d: which even at low levels divides attention
  e: more prone to unplanned purchases
ja:
  a: 「いっそう**起こりやすい**」（×）
  b: 「90dB**超**」
  c: 「BGMなしでは済まない」
  d: 「低音量でも**注意を分散**」
  e: 「**衝動買いしやすい**」
lures:
  - opt: b
    tags: [CONTENT_DRIFT]
    expl: 事実強調だが文法上正。
  - opt: c
    tags: [CONNECTIVE_SYNTAX]
    expl: can’t … without … は定型。
  - opt: d
    tags: [SVA_AGREEMENT, PARALLEL_COMPAR]
    expl: music→単数で divides／後続 makes と並列。
  - opt: e
    tags: [WORD_CHOICE]
    expl: prone to -ing＝定型。
```

---

### (2024_open_1 Q23)
```db
set: 2024_open_1
question: 23
correct: e
label: VERB_VALENCY
sublabels: []
explanation: shows that 節は完全文。→ “you **cannot**”。“you cannot **be**” は補語欠落。cannot do so. とかならよい. そもそもbe動詞は前の文にない.
text:
  a: haven't made their homes refuges from noise
  b: are almost always on
  c: some form of sound system
  d: listen closely to a family member or friend
  e: shows that you cannot be
ja:
  a: 「家を**静けさの避難所にしていない**」
  b: 「テレビは**ほぼ常時**オン」
  c: 「**何らかの**音響設備」
  d: 「家族や友人に**注意深く**耳を傾ける」
  e: 「研究は**〜できない**と示す（× be）」
lures:
  - opt: a
    tags: [VERB_VALENCY]
    expl: make A B 構文＝可。
  - opt: b
    tags: [ASPECT]
    expl: 一般現在で可。
  - opt: c
    tags: [ARTICLE_DET]
    expl: some form of + 単数＝可。
  - opt: d
    tags: [LEXICAL_NUANCE]
    expl: listen closely to〜＝可。
```

---

### (2024_open_1 Q24)
```db
set: 2024_open_1
question: 24
correct: d
label: PARALLEL_COMPAR
sublabels: [CONNECTIVE_SYNTAX]
explanation: **as much about A as B** が正。本文は “as much **as about** …” の語順誤り。
text:
  a: dispose of a limited budget of attention
  b: try to go beyond your budget
  c: that you must cultivate the right environment
  d: which is as much as about a receptive physical space as a receptive state of mind
  e: freedom from interruption
ja:
  a: 「注意という**限られた予算**を持つ」
  b: 「予算を**超えよう**とすれば失敗する」
  c: 「**適切な環境を整え**るべき」
  d: 「（聞くことは）**物理的空間**についてと同じくらい**心の状態**についてのもの（語順×）」
  e: 「**中断のない自由**」
lures:
  - opt: a
    tags: [LEXICAL_NUANCE, ANXIETY_CUE]
    expl: dispose of＝“have at one’s disposal” の意で可。
  - opt: b
    tags: [WORD_CHOICE]
    expl: go beyond your budget＝自然。
  - opt: c
    tags: [CONNECTIVE_SYNTAX]
    expl: All this is to say that …＝定型。
  - opt: e
    tags: [NOUN_PHRASE]
    expl: freedom from + 名詞＝定型。
```

---

### (2024_open_1 Q25)
```db
set: 2024_open_1
question: 25
correct: d
label: CONNECTIVE_SYNTAX
sublabels: [PARALLEL_COMPAR]
explanation: 条件・二択明示が必要。→ “**Whether** the conversation is about business **or** more personal matters, …”（または “**Even if** the conversation is brief, …”）。本文 “Even the conversation …” は接続不全。
text:
  a: It’s not that you can only effectively interact with people in soundproof spaces.
  b: keep it out of sight
  c: your willingness to listen to what someone has to say
  d: Even the conversation is brief
  e: a better opportunity to connect
ja:
  a: 「**防音室でしか**交流できないわけではない」
  b: 「それ（スマホ）を**視界から外す**」
  c: 「相手の**言いたいこと**に耳を傾ける意思」
  d: 「**会話が仕事か私事かにかかわらず**（Whether … or …）／**たとえ短くても**（Even if …）」
  e: 「**つながる好機**を作る」
lures:
  - opt: a
    tags: [WORD_ORDER]
    expl: It’s not that S V…＝定型。
  - opt: b
    tags: [LEXICAL_NUANCE]
    expl: keep A out of sight＝定型。
  - opt: c
    tags: [IDIOM_FAKE]
    expl: what someone has to say＝“言いたいこと”。意味混乱を誘うが正。
  - opt: e
    tags: [NOUN_PHRASE]
    expl: a better opportunity to V＝自然。
```

### (2024_toshin_3 Q21)
```db
set: 2024_toshin_3
question: 21
correct: d
label: PREP_COLLOC
sublabels: [LEXICAL_NUANCE]
explanation: “perceive A **as** B” は可だが，*fashion* と組む定型は **in a … fashion**。→ “was perceived **in** a rather linear fashion.”
text:
  a: have long considered ourselves
  b: due to our exceptional cognitive capabilities
  c: that have enabled us to reach space,
  d: was perceived as a rather linear fashion
  e: like those of bright individuals like Albert Einstein
ja:
  a: 私たちは長らく自分たちを最も賢い種だと考えてきた
  b: 卓越した認知能力と言語使用のために
  c: それらの能力が宇宙到達などを可能にした
  d: 知能は**かなり直線的な様式**で理解**された**（前置詞×）
  e: たとえばアインシュタインのような才人の能力のようなもの
lures:
  - opt: a
    tags: [REFLEXIVE, VERB_VALENCY]
    expl: consider oneself … は正用。
  - opt: b
    tags: [PREP_COLLOC]
    expl: due to + 名詞句＝可。
  - opt: c
    tags: [REL_PRONOUN]
    expl: 強調構文部（that）は問題なし。
  - opt: e
    tags: [LEXICAL_NUANCE, ANXIETY_CUE]
    expl: like … like の反復は冗長だが文法×ではない。
```

---

### (2024_toshin_3 Q22)
```db
set: 2024_toshin_3
question: 22
correct: e
label: CONTENT_REVERSE
sublabels: []
explanation: 各知能は**環境や実践に適合した**課題を解く文脈。irrelevant は極性逆。→ **relevant to** / **suited to**。
text:
  a: is now understood to be far more varied and intricate.
  b: acknowledges multiple intelligences besides the logical-mathematical type,
  c: which dancers and surgeons exhibit,
  d: which is seen in composers and musicians.
  e: problems **irrelevant to** their specific environments and practices.
ja:
  a: 今やはるかに多様で複雑だと理解されている
  b: 論理数学型以外の多重知能を認める
  c: ダンサーや外科医が示す（身体運動感覚）
  d: 作曲家や音楽家に見られる（音楽的）
  e: それぞれの環境・実践に**無関係な**問題（×）→ **関係する**問題
lures:
  - opt: a
    tags: [TENSE_ASPECT]
    expl: is understood to be … は可。
  - opt: b
    tags: [PARALLEL_COMPAR]
    expl: besides A, such as B … は可。
  - opt: c
    tags: [REL_PRONOUN]
    expl: which + 動詞＝可。
  - opt: d
    tags: [REL_PRONOUN]
    expl: which is seen in …＝可。
```

---

### (2024_toshin_3 Q23)
```db
set: 2024_toshin_3
question: 23
correct: b
label: IDIOM_FAKE
sublabels: [PARALLEL_COMPAR]
explanation: 比較構文の型が崩れている。“predict **better than** health outcomes” は偽定型。→ “predict **better health** outcomes” / “predict X **better than** Y”。
text:
  a: the capacity for intelligence in other species.
  b: whether enhanced cognitive abilities can predict **better than** health outcomes
  c: that is adopting broader definitions of intelligence:
  d: an interesting result of thinking about intelligence
  e: we can attribute intelligence broadly across a group of individuals,
ja:
  a: 他種における知能の可能性
  b: 強化された認知能力が**より良い健康転帰を予測できるか**／Xよりうまく予測できるか（構文直し要）
  c: 知能の定義拡張を採用しているという動き
  d: そう考えることの興味深い帰結
  e: 個人ではなく**集団**全体に広く知能を帰属しうる
lures:
  - opt: a
    tags: [PREP_COLLOC]
    expl: capacity **for** は定型。
  - opt: c
    tags: [REL_PRONOUN]
    expl: that is adopting …（現在進行の記述）可。
  - opt: d
    tags: [LEXICAL_NUANCE]
    expl: 名詞句として自然。
  - opt: e
    tags: [CONNECTIVE_SYNTAX]
    expl: means (that) … の that 省略は可。
```

---

### (2024_toshin_3 Q24)
```db
set: 2024_toshin_3
question: 24
correct: d
label: CONNECTIVE_SYNTAX
sublabels: [DISCOURSE_MARKER]
explanation: **meanwhile** は独立副詞（場面転換）。対比従属には **while/whereas/although** が必要。→ “… **while** we would not expect …”
text:
  a: which was coined by some researchers
  b: are not indicative of individual intelligence.
  c: from a complex interplay of interactions
  d: **meanwhile** we would not expect a hive of bees to conceptualize
  e: tuned to ensure their survival and success
ja:
  a: 一部研究者により**提唱された**用語
  b: それらは**個体知能の指標ではない**
  c: 集団内の**複雑な相互作用**から生じる
  d: **その一方で**ハチの群れが月探査計画を構想することはない（接続語×）
  e: 生存と成功を**確保するよう**精緻に調整されている
lures:
  - opt: a
    tags: [LEXICAL_NUANCE]
    expl: coin a term は定型。
  - opt: b
    tags: [WORD_CHOICE]
    expl: be indicative of … は可。
  - opt: c
    tags: [REDUNDANCY]
    expl: “interplay of interactions” は冗語だが文法×ではない。
  - opt: e
    tags: [VERB_VALENCY]
    expl: be tuned to V は可。
```

---

### (2024_toshin_3 Q25)
```db
set: 2024_toshin_3
question: 25
correct: c
label: CONNECTIVE_SYNTAX
sublabels: [COMPLEMENTIZER]
explanation: discover の内容節は **that** 節が基本。“have discovered **that** human brains synchronize …”。× “discovered **what** human brains synchronize …”
text:
  a: at both individual and collective levels.
  b: moving towards understanding the neural basis
  c: neuroscientists have discovered **what** human brains synchronize with one another
  d: the extent **to which** such neural synchronization plays a role
  e: remains an open question for future research.
ja:
  a: 個体レベルと集団レベルの両方で
  b: 個人中心から離れ**群知能の神経基盤**の理解へ
  c: 脳は協力時に**同期することを発見した**（**that** が必要）
  d: その同期がどの程度役割を果たすかという**程度構文**
  e: それは今後の研究に残された**未解決の問題**である
lures:
  - opt: a
    tags: [PREP_COLLOC]
    expl: at both A and B＝可。
  - opt: b
    tags: [NOMINALIZATION]
    expl: move towards understanding … は可。
  - opt: d
    tags: [REL_PRONOUN]
    expl: extent **to which** … は定型。
  - opt: e
    tags: [TENSE_ASPECT]
    expl: remains＝現在時制の一般叙述で可。
```

### (2024_open_2 Q21)
```db
set: 2024_open_2
question: 21
correct: e
label: IDIOM_FAKE
sublabels: [PREP_COLLOC]
explanation: 成句は **make sense of ~**。× *make their sense of ~*。
text:
  a: a remark made by her two-year-old son
  b: in some ways babies could take the perspectives of other people
  c: is described as theory of mind
  d: that other people have their own minds and preferences
  e: children make their sense of the world
ja:
  a: ２歳の息子の発言
  b: 乳児は場合により他者の視点を取れる
  c: その能力は「心の理論」と呼ばれる
  d: 他者には独自の心と好みがあるという理解
  e: 子どもは**世界を理解する（make sense of the world）**
lures:
  - opt: a
    tags: [LEXICAL_NUANCE, ANXIETY_CUE]
    expl: form/gain insight from … は可。
  - opt: b
    tags: [VERB_VALENCY]
    expl: take the perspective(s) of … 可。
  - opt: c
    tags: [ARTICLE_DET]
    expl: describe A as **“theory of mind”**（固有名扱い）可。冠詞付与は不要。
  - opt: d
    tags: [CONNECTIVE_SYNTAX]
    expl: appreciation **that** SV 構文は可。
```

---

### (2024_open_2 Q22)
```db
set: 2024_open_2
question: 22
correct: d
label: CONNECTIVE_SYNTAX
sublabels: [TENSE_ASPECT]
explanation: 時間関係は **didn’t … until ~**。× *since they were about seven*。
text:
  a: sees babies as different
  b: more alert to their surroundings than grown-ups and more active learners than scientists
  c: They are designed to learn about the world …
  d: didn’t develop the ability … since they were about seven years old
  e: how to demonstrate that babies have this skill
ja:
  a: 乳児を「異なる存在」と見る
  b: 大人より敏感で，科学者より能動的学習者
  c: 世界について学ぶよう“設計”されている
  d: この能力は**７歳まで**発達しない（until が要る）
  e: 乳児にこの技能があることをどう示すか
lures:
  - opt: a
    tags: [LEXICAL_NUANCE, ANXIETY_CUE]
    expl: see A as **different**（from 省略可）。
  - opt: b
    tags: [PARALLEL_COMPAR]
    expl: than〜 and more … than … の並列は正。
  - opt: c
    tags: [CONTENT_DRIFT]
    expl: 目的論的比喩だが文法上は可。
  - opt: e
    tags: [VERB_VALENCY]
    expl: know **how to** V / demonstrate **that** … は可。
```

---

### (2024_open_2 Q23)
```db
set: 2024_open_2
question: 23
correct: a
label: CONNECTIVE_SYNTAX
sublabels: [WORD_ORDER, SVA_AGREEMENT]
explanation: 叙述転換の倒置 **Then came a fateful day …**。× *came to a fateful day*（to 余分／VS倒置が崩れる）。
text:
  a: came to a fateful day when
  b: made a fancy dessert
  c: had a taste of it
  d: for weeks afterward, … say;
  e: turned her son's comment into an experiment
ja:
  a: **その後，運命の日がやって来た**（when … hosting）
  b: 凝ったデザートを作った
  c: それを味見した
  d: その後数週間，突然こう言った；
  e: 発言を実験「ブロッコリーと金魚クラッカー」に転用した
lures:
  - opt: b
    tags: [WORD_CHOICE]
    expl: make a dessert＝可。
  - opt: c
    tags: [PREP_COLLOC]
    expl: have a taste **of** it＝可。
  - opt: d
    tags: [CONNECTIVE_SYNTAX, ANXIETY_CUE]
    expl: 句読点の揺れは採点点ではない。
  - opt: e
    tags: [LEXICAL_NUANCE]
    expl: turn A into B＝可。
```

---

### (2024_open_2 Q24)
```db
set: 2024_open_2
question: 24
correct: c
label: SVA_AGREEMENT
sublabels: []
explanation: **each of + 複数名詞**。→ each of the **bowls**。
text:
  a: had them try some of each
  b: They all liked the crackers more than the broccoli.
  c: took a bit of food from each of the bowl
  d: made either a disgusted face or a happy face
  e: the other half of the time it was reversed
ja:
  a: それぞれを少しずつ**食べさせた**（have + O + V）
  b: 皆が**クラッカーのほうを**好んだ
  c: **各ボウル**から少量を取った（単数×）
  d: **嫌悪/満足**の表情を作った
  e: 残り半分は**逆パターン**にした
lures:
  - opt: a
    tags: [VERB_VALENCY, CAUSATIVE_BARE_V]
    expl: have + O + V（to 付けない）で正。
  - opt: b
    tags: [ARTICLE_DET]
    expl: the broccoli は対比用法で可。
  - opt: d
    tags: [IDIOM_FAKE]
    expl: make a … face は定型。
  - opt: e
    tags: [CONNECTIVE_SYNTAX]
    expl: the other half of the time … は自然。
```

---

### (2024_open_2 Q25)
```db
set: 2024_open_2
question: 25
correct: d
label: CONTENT_REVERSE
sublabels: [PARALLEL_COMPAR]
explanation: 18か月児は**共感を示す**が14か月児は**示さない**。× “but also fourteen-month-olds”。
text:
  a: put her hand out to the baby and ask for some food
  b: not the crackers that they liked
  c: just got confused … then they offered the crackers
  d: but also fourteen-month-olds
  e: opened the way for psychologists to make discoveries
ja:
  a: 手を差し出し**食べ物を求めた**
  b: **自分らの好むクラッカーではなく**
  c: 14か月児は**混乱**し，結局クラッカーを差し出した
  d: **14か月児もまた**（×）→ **14か月児はそうではない**
  e: こうした実験が**研究の道を開いた**
lures:
  - opt: a
    tags: [VERB_VALENCY]
    expl: ask **for** some food＝可。
  - opt: b
    tags: [WORD_ORDER]
    expl: not A（自分の好み） but B（相手の好み）対比の一部で可。
  - opt: c
    tags: [CONNECTIVE_SYNTAX]
    expl: when … and then … の連結は可。
  - opt: e
    tags: [IDIOM_FAKE]
    expl: open/pave the way **for 人 to V**＝定型（本文は可）。
```

### (2024_realbattle_2 Q21)
```db
set: 2024_realbattle_2
question: 21
correct: b
label: CLAUSE_SYNTAX
sublabels: [REL_CLAUSE, MODAL_MISUSE]
explanation: 先行詞 *an empty bottle* を受ける関係節は **that experience must fill** が自然。× *that can experience must fill*（can の余計な情態で構文破綻）。
text:
  a: for millennia
  b: an empty bottle **that can experience must fill**
  c: rejecting the idea
  d: devoid of any
  e: the organ by which we acquire instruction
ja:
  b: 「経験が満たすべき**空の瓶**」＝**that experience must fill**
lures:
  - opt: a — tags: [TIME_PP] — expl: for millennia は定型。OK。
  - opt: c — tags: [VERB_PATTERN] — expl: reject + the idea that … でOK。
  - opt: d — tags: [PREP_COLLOC] — expl: devoid **of** any knowledge は定型。
  - opt: e — tags: [REL_PRONOUN] — expl: the organ **by which** … は硬いが文法上OK。
```

---

### (2024_realbattle_2 Q22)
```db
set: 2024_realbattle_2
question: 22
correct: d
label: CONTENT_REVERSE
sublabels: [LOGIC]
explanation: 趣旨は「どちらか一方ではなく**両方が必要**」。→ **we have underestimated both** が筋。*overestimated* は論旨逆。
text:
  a: comes equipped with two features:
  b: settings to choose **from**
  c: adjust those settings according to the data
  d: we **have overestimated** both.
  e: an immense set of potential models …
ja:
  d: 「両方を**過小評価**してきた」が文脈筋。
lures:
  - opt: a — tags: [VERB_PATTERN] — expl: come equipped with … は定型。
  - opt: b — tags: [PREP_COLLOC] — expl: choose **from** は定型。OK。
  - opt: c — tags: [PREP_COLLOC] — expl: according **to** は定型。
  - opt: e — tags: [ARTICLE_DET] — expl: an immense set of … は自然。
```

---

### (2024_realbattle_2 Q23)
```db
set: 2024_realbattle_2
question: 23
correct: a
label: IDIOM_FAKE
sublabels: [PREP_COLLOC]
explanation: 慣用は **in** their own way。× *on their own way*。
text:
  a: do this **on** their own way
  b: entrusting the representation **of** mental models **to** millions of adjustable connections
  c: while capturing the rapid and unconscious recognition …
  d: more concrete hypotheses
  e: the logic of mathematical operations
ja:
  a: 「**自分たちなりのやり方で**」＝**in** their own way
lures:
  - opt: b — tags: [PREP_COLLOC] — expl: representation **of** A / entrust A **to** B は定型。OK。
  - opt: c — tags: [MODIFIER] — expl: rapid が recognition を修飾。OK。
  - opt: d — tags: [WORD_CHOICE] — expl: more concrete hypotheses は自然。
  - opt: e — tags: [ARTICLE_USE] — expl: the logic of … は文脈許容。
```

---

### (2024_realbattle_2 Q24)
```db
set: 2024_realbattle_2
question: 24
correct: e
label: SVA_AGREEMENT
sublabels: [COORDINATION]
explanation: **collect … and use them** と同形並列に。× *collect … and using them*（非並行）。
text:
  a: grows through the combination of symbols
  b: This "language of thought",
  c: is already in place prior to learning
  d: to be put to the test
  e: collect statistical data **and using** them …
ja:
  e: 「統計データを**集め**，それを**用いる**」＝**collect … and use them**
lures:
  - opt: a — tags: [NOUN_PHRASE] — expl: the combination of … は可。
  - opt: b — tags: [APPOSITIVE] — expl: 挿入同格は可。
  - opt: c — tags: [IDIOM_REAL] — expl: in place（整っている）は可。不安だがOK。
  - opt: d — tags: [INFINITIVE_PASSIVE] — expl: to be put to the test は定型。
```

---

### (2024_realbattle_2 Q25)
```db
set: 2024_realbattle_2
question: 25
correct: e
label: PRON_REF
sublabels: [NUMBER_AGREEMENT]
explanation: 直前の複数 *probabilities* を受ける代名詞は **them**。× *update **it***。
text:
  a: contains all the languages …
  b: in addition to …
  c: The combinational analyses of the brain **are** such that …
  d: their respective preexisting probabilities
  e: the ability to update **it**
ja:
  e: 「その確率**それら**を更新する能力」＝**update them**
lures:
  - opt: a — tags: [MODAL_SEMANTICS] — expl: 可能性の誇張表現で文法上はOK。
  - opt: b — tags: [CONNECTIVE] — expl: in addition to … は可。
  - opt: c — tags: [SVA_AGREEMENT] — expl: analyses（複）→ **are** で一致。OK。
  - opt: d — tags: [ADJ_ORDER] — expl: respective / preexisting の並置は可。
```



### (2024_pre_2 Q21)
```db
set: 2024_pre_2
question: 21
correct: d
label: PARALLEL_COMPAR
sublabels: [CONNECTIVE_SYNTAX]
explanation: “Just as …, so …” が正。“as” は不可。
text:
  a: allowing errors to go undetected could be much costlier
  b: It's not just private technology companies that invest
  c: who found weaknesses in its networks
  d: Just as many industries devote hefty funding to incentivizing people to find and report bugs and glitches, as the science community should reward the detection and correction of errors in the scientific literature
  e: the costs of undetected errors are staggering
lures:
  - opt: a
    tags: [WORD_CHOICE]
    expl: costlier＝可。moreに直す不要。
  - opt: b
    tags: [WORD_ORDER, ANXIETY_CUE]
    expl: “It’s not just … that …”＝可。invest in＝定型。
  - opt: c
    tags: [TENSE_ASPECT]
    expl: found は過去範囲に一致。
  - opt: e
    tags: [LEXICAL_NUANCE]
    expl: staggering は自然。
```

---

### (2024_pre_2 Q22)
```db
set: 2024_pre_2
question: 22
correct: a
label: CONNECTIVE_SYNTAX
sublabels: [CONTENT_DRIFT]
explanation: “That’s why …” が適切。“That’s because …” は因果の型が違う。
text:
  a: That's because I have joined
  b: pays specialists to check highly cited published papers
  c: for each paper they check
  d: the greater the reward
  e: to cover the work needed to
lures:
  - opt: b
    tags: [DANGLING_MOD, ANXIETY_CUE]
    expl: starting with … は許容の分詞句。
  - opt: c
    tags: [PREP_COLLOC]
    expl: for each＝定型。perへの置換不要。
  - opt: d
    tags: [PARALLEL_COMPAR]
    expl: “The … the …” 相関比較＝正。
  - opt: e
    tags: [PARALLEL_COMPAR]
    expl: to の下で “prepare … or answer …” 並列＝可。
```

---

### (2024_pre_2 Q23)
```db
set: 2024_pre_2
question: 23
correct: e
label: CONTENT_REVERSE
explanation: 直前主張と逆。“sufficient” → “insufficient”。
text:
  a: will run for at least four years
  b: we have sent out
  c: agreed to have their papers assessed
  d: revealing minor errors
  e: because current checks are sufficient
lures:
  - opt: a
    tags: [TENSE_ASPECT]
    expl: launched＋will run の時制整合。
  - opt: b
    tags: [WORD_CHOICE]
    expl: send out＝自然。置換不要。
  - opt: c
    tags: [VERB_VALENCY]
    expl: agree to have O p.p.＝可。
  - opt: d
    tags: [ADV_ADJ_FORM]
    expl: 分詞構文＝許容。
```

---

### (2024_pre_2 Q24)
```db
set: 2024_pre_2
question: 24
correct: c
label: ADV_ADJ_FORM
sublabels: [VERB_VALENCY, WORD_ORDER]
explanation: “papers **looked** for” → “**looking** for / **to look** for”。
text:
  a: Unpaid peer reviewers are overburdened
  b: or go through computer code line by line
  c: published papers looked for errors
  d: There is no financial compensation for highlighting errors
  e: can see people marked out as troublemakers
lures:
  - opt: a
    tags: [LEXICAL_NUANCE, ANXIETY_CUE]
    expl: overburdened＝適切。
  - opt: b
    tags: [PARALLEL_COMPAR]
    expl: examine/comb/go through の並列＝可。
  - opt: d
    tags: [PREP_COLLOC]
    expl: compensation for＝定型。
  - opt: e
    tags: [VOICE_PASSIVE, WORD_ORDER]
    expl: see + O + p.p. の受け身的用法＝可。
```

---

### (2024_pre_2 Q25)
```db
set: 2024_pre_2
question: 25
correct: e
label: VERB_VALENCY
sublabels: [WORD_ORDER]
explanation: “make A **part of** B” が定型。“being” 不要。
text:
  a: comes at a huge cost
  b: building their work on an erroneous finding
  c: run to six figures
  d: another project is not pursued
  e: making error detection and correction being part of
lures:
  - opt: a
    tags: [LEXICAL_NUANCE]
    expl: come at a cost＝定型。
  - opt: b
    tags: [PREP_COLLOC, SVA_AGREEMENT]
    expl: build A on B＝定型。 "their"→singular they の活用。(genderをぼかす)
  - opt: c
    tags: [WORD_CHOICE]
    expl: run to six figures＝自然。
  - opt: d
    tags: [VOICE_PASSIVE]
    expl: 受動は文脈適切。
```

# 2023
### (2023_UT Q21)
```db
set: 2023_UT
question: 21
correct: d
label: IDIOM_FAKE
sublabels: [LEXICALIZED_PATTERN]
explanation: 慣用は **be no exception**。× “The English language **has** no exception …” → “The English language **is** no exception …”
text:
  a: one particular language over another
  b: more neutral **in** a given context **by** certain speakers
  c: a politically loaded and biased choice
  d: The English language **has** no exception
  e: its often unquestioned status as a global lingua franca … make it seem to be such
lures:
  - opt: a
    label: WORD_CHOICE
    expl: 対比 “one … over another” は定型。問題なし。
  - opt: b
    label: PARALLEL_COMPAR
    expl: “neutral **in** context / **by** speakers” の前置詞切替は自然。後段と表現差があっても×ではない。
  - opt: c
    label: WORD_CHOICE
    expl: “politically loaded and biased” は語法良好。
  - opt: e
    label: LEXICAL_NUANCE
    expl: “often-unquestioned” にハイフン可。“seem to be such” はやや重いが容認。
```

---

### (2023_UT Q22)
```db
set: 2023_UT
question: 22
correct: a
label: VOICE_PASSIVE
sublabels: [AUX_BE_MISSING]
explanation: 受動は **has often been portrayed**。× “has often portrayed …”
text:
  a: has often portrayed as a 'neutral' medium
  b: far from a generally 'neutral' medium
  c: the non-neutral and ambiguous nature of the way
  d: interpret English ways of speaking
  e: the least disputed, most defining, and yet insufficiently acknowledged feature
lures:
  - opt: b
    label: LEXICAL_NUANCE
    expl: far from (a) neutral medium は可。generally の位置も許容。
  - opt: c
    label: CONNECTIVE_SYNTAX
    expl: “nature **of the way** S V” は重いが可。
  - opt: d
    label: VERB_VALENCY
    expl: interpret + N は可。“as a way of speaking” にしなくても成立。
  - opt: e
    label: PARALLEL_COMPAR
    expl: 形容の並列良好。単数 feature でOK。
```

---

### (2023_UT Q23)
```db
set: 2023_UT
question: 23
correct: d
label: ADV_ADJ_FORM
sublabels: [DERIVATIONAL]
explanation: 形容詞ではなく副詞が必要。→ “seem**ingly** contradictory positions”
text:
  a: to reassess how they view
  b: attempt to make sense of an ever-changing world
  c: For linguistic anthropologists there is a benefit in observing
  d: seeming contradictory positions
  e: not only in international … but within national boundaries
lures:
  - opt: a
    label: CONNECTIVE_SYNTAX
    expl: “how they view …” は自然。
  - opt: b
    label: IDIOM_REAL
    expl: make sense of ~ は定型。問題なし。
  - opt: c
    label: PREP_COLLOC
    expl: a benefit **in** V-ing も **to** V-ing も可。in でもOK。
  - opt: e
    label: PARALLEL_COMPAR
    expl: “not only … but (also) …” で **also** は省略可。×ではない。
```

---

### (2023_UT Q24)
```db
set: 2023_UT
question: 24
correct: b
label: SVA_AGREEMENT
sublabels: [COMPLEX_SUBJECT]
explanation: 主語は単数 “The coexistence …” → 動詞は **creates**。× “create”
text:
  a: are all marked by various levels of competencies …
  b: The coexistence … **create** complex power dynamics
  c: were to exclude interactions where …
  d: is, to some extent, a type of communication
  e: which serves as the platform of interaction by a group …
lures:
  - opt: a
    label: WORD_CHOICE
    expl: “levels of competence(s)” は可。複数 “competencies” も容認。
  - opt: c
    label: CONNECTIVE_SYNTAX
    expl: 仮定法の “were to exclude …” は適切な慎重表現。be to の用法OK。
  - opt: d
    label: LEXICAL_NUANCE
    expl: “to some extent” の挿入も構文OK。
  - opt: e
    label: PREP_COLLOC
    expl: “platform **for** interaction” がより自然だが “of” でも意味は通る。“by a group” も受動含意で容認。
```

---

### (2023_UT Q25)
```db
set: 2023_UT
question: 25
correct: b
label: PREP_COLLOC
sublabels: [NOMINAL_GOVERNMENT]
explanation: collocation は **impact on** N。× “impact **to** the politics of language”
text:
  a: essentially, but not only, about power and ideology
  b: a fundamental **impact to** the politics of language
  c: fundamentally based on a dialogue of unequal power relations
  d: have been discriminated against throughout history
  e: racial identity politics in **its** multiple forms
lures:
  - opt: a
    label: LEXICAL_NUANCE
    expl: “essentially, but not only,” は重いが意味明確。×ではない。
  - opt: c
    label: WORD_CHOICE
    expl: “based on a dialogue of …” はやや不自然だが文法的には許容。
  - opt: d
    label: PHRASAL_VERB
    expl: discriminate **against** は定型。前置詞位置もOK。
  - opt: e
    label: PRON_REF
    expl: “politics” を単数概念扱い→ **its** で照応可。冗長ではない。
```

### (2023_realbattle_1 Q21)
```db
set: 2023_realbattle_1
question: 21
correct: c
label: VOICE_PASSIVE
sublabels: [VERB_VALENCY, TENSE_ASPECT]
explanation: suffer は自動詞。受動不可→“was suffering from …” が正。
text:
  a: developed a cough, which seemed like just a minor inconvenience
  b: until it got worse
  c: was suffered from great pain
  d: begging him to come see her
  e: her condition had worsened further
ja:
  a: せきが出るようになり，ささいな不便に思えた
  b: それが悪化するまで
  c: ひどい痛みに「苦しめられた」（×）→苦しんでいた（○）
  d: 彼に来て診てくれるよう懇願し
  e: 3日後さらに悪化していた
lures:
  - opt: a
    tags: [LEXICAL_NUANCE, REL_PRONOUN]
    expl: “which seemed …” は過去形で自然。“had seemed”不要。
  - opt: b
    tags: [CONNECTIVE_SYNTAX]
    expl: until＝継続→転換で適合。
  - opt: d
    tags: [VERB_VALENCY, WORD_ORDER]
    expl: come (and) see＝定型。to追加不要。
  - opt: e
    tags: [TENSE_ASPECT]
    expl: 文中基準点より前を示す過去完了は可。
```

---

### (2023_realbattle_1 Q22)
```db
set: 2023_realbattle_1
question: 22
correct: c
label: PARALLEL_COMPAR
sublabels: []
explanation: “as many …” は比較相手が要る。単独なら as を削除。
text:
  a: Mill sat alone with her body
  b: that blessing was mine
  c: as many words of gratitude to Harriet
  d: which bears my name
  e: that was not several times gone through
ja:
  a: ミルは彼女の遺体と一人で座っていた
  b: その祝福は私のものだった
  c: ハリエットへの多くの感謝の言葉（as不要）
  d: 私の名を冠する
  e: 何度も我々で読み通された
lures:
  - opt: a
    tags: [LEXICAL_NUANCE, ANXIETY_CUE]
    expl: alone with … は語感強めだが可。
  - opt: b
    tags: [ARTICLE_DET]
    expl: that の指示用法は適切。
  - opt: d
    tags: [TENSE_ASPECT, REL_PRONOUN]
    expl: 現在の一般真実→bears（現在形）で自然。
  - opt: e
    tags: [SVA_AGREEMENT, TENSE_ASPECT]
    expl: 単数一致・過去受動は適合。
```

---

### (2023_realbattle_1 Q23)
```db
set: 2023_realbattle_1
question: 23
correct: a
label: SVA_AGREEMENT
sublabels: []
explanation: one of + **複数名詞**。document→documents。
text:
  a: the founding document of our liberal world order
  b: whom to marry, where to live, what to believe, what to say
  c: provided that the person isn't harming anyone else
  d: the space to live our fullest life
  e: the rocks upon which we built flourishing nations
ja:
  a: 私たちのリベラル秩序の「創設文書の一つ」
  b: 誰と結婚/どこに住む/何を信じ/何を言うか
  c: 他者に害を与えない限り
  d: 最も充実した人生を送るための余地
  e: 私たちが国家を築いた岩（基盤）の上に
lures:
  - opt: b
    tags: [VERB_VALENCY]
    expl: 疑問詞+不定詞の対応は正。
  - opt: c
    tags: [VERB_VALENCY]
    expl: harm は他動。構文正。
  - opt: d
    tags: [WORD_ORDER]
    expl: 不定詞の形容詞用法で正。
  - opt: e
    tags: [REL_PRONOUN]
    expl: 前置詞+関係代名詞（upon which）＝正。
```

---

### (2023_realbattle_1 Q24)
```db
set: 2023_realbattle_1
question: 24
correct: c
label: PRON_REF
sublabels: [VERB_VALENCY]
explanation: 主語we＝目的語も自分→us→**ourselves**。
text:
  a: The liberalism that the Mills advocated
  b: greet a great variety of social types
  c: throw us into the messy clash of ideas
  d: that we defend when we back one country in a fight against another
  e: to those who would impose speech codes
ja:
  a: ミル夫妻が提唱したリベラリズム
  b: 多様な人々に出会う
  c: 私たちを（×）→自分たち自身を思想の混戦へ投げ込む
  d: 我々が一国を支持して他国と戦うとき守るもの
  e: 言論規制を課そうとする者たちへ
lures:
  - opt: a
    tags: [REL_PRONOUN]
    expl: 目的格that＝可。
  - opt: b
    tags: [PARALLEL_COMPAR]
    expl: walk と greet の並列は正。
  - opt: d
    tags: [CONNECTIVE_SYNTAX]
    expl: 強調構文 It is … that の内側として自然。
  - opt: e
    tags: [PREP_COLLOC]
    expl: stand up to ～ / to those ～ の並列一致。
```

---

### (2023_realbattle_1 Q25)
```db
set: 2023_realbattle_1
question: 25
correct: e
label: REL_PRONOUN
sublabels: [TENSE_ASPECT]
explanation: legacy を先行詞に関係節が必要→“**that has guided** …”。
text:
  a: a house overlooking the cemetery
  b: and filled it with furniture
  c: for the rest of his life
  d: him gazing down at her grave from the window
  e: guided humanity another step forward
ja:
  a: 墓地を見下ろす家
  b: その家を彼女が亡くなった部屋の家具で満たし
  c: 残りの生涯ずっと
  d: 彼が窓から彼女の墓を見下ろしている
  e: 人類をもう一歩前へ導いた（→関係節にする）
lures:
  - opt: a
    tags: [ADV_ADJ_FORM]
    expl: 分詞形容詞 over­looking＝可。
  - opt: b
    tags: [PARALLEL_COMPAR]
    expl: bought と filled の並列＝可。
  - opt: c
    tags: [ARTICLE_DET]
    expl: the rest of his life＝定型。
  - opt: d
    tags: [VERB_VALENCY]
    expl: 動名詞の意味上主語 him は可。
```

