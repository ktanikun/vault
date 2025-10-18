
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