```
4 (A) 以下の英文の段落(21)~(25)にはそれぞれ文法上または内容上の誤りがある。修正が必要な下線部を各段落から一つずつ選び、マークシートの(21)-(25)にその記号をマークせよ。

  

(21) We humans (a)  have long considered ourselves (a)  the most intelligent species, largely (b)  due to our exceptional cognitive capabilities (b)  and sophisticated use of language. It is these unique abilities (c)  that have enabled us to reach space,(c)  extend our lifespans, and unlock many mysteries of the world. Traditionally, intelligence (d) was perceived as a rather linear fashion(d) , with a strong focus on logical and mathematical abilities, (e)  like those of bright individuals like Albert Einstein, (e)  as the indicators of a high intellect.

  

(22) However, the landscape of intelligence is now understood (a)  to be far more varied and intricate.(a)  This enriched understanding acknowledges (b)  multiple intelligences besides the logical-mathematical type,(b)  such as emotional intelligence, which allows us to navigate social complexities, bodily-kinesthetic intelligence, (c)  which dancers and surgeons exhibit,(c)  visual-spatial intelligence, which is vital for architects and artists, and musical intelligence, (d) which is seen in composers and musicians.(d)  Each type of intelligence enables individuals to solve (e)  problems irrelevant to their specific environments and practices.(e) 

  

(23) And beyond the different varieties of intelligence among humans, scientists are starting to understand (a)  the capacity for intelligence in other species. (a)  Rosalind Arden from the London School of Economics and Political Science studies intelligence in humans and canines. She is especially interested in (b)  whether enhanced cognitive abilities can predict better than health outcomes within a species. (b)   This shift is part of a larger movement in the scientific community (c)  that is adopting broader definitions of intelligence: (c)  the ability to learn, adapt, and solve species-specific problems that are crucial for survival, for example, or the ability to achieve goals in different ways. And (d) an interesting result of thinking about intelligence (d)  in these terms means (e)  we can attribute intelligence broadly across a group of individuals,(e)  rather than to a single individual alone.

  

(24) This perspective has given rise to the term collective intelligence, (a)  which was coined by some researchers(a)  to describe how groups of animals, such as bee colonies or ant swarms, demonstrate remarkable problem-solving abilities. Arden points out that these collective behaviors (b)  are not indicative of individual intelligence.(b)  Rather, they arise (c) from a complex interplay of interactions(c)  within the group. For example, (d)  meanwhile we would not expect a hive of bees to conceptualize(d)  a mission to the moon, their collaborative efforts are finely (e)  tuned to ensure their survival and success(e)  within their ecological niche.

  

(25) Neurological studies are shedding light on the intricacies of intelligence (a)  at both individual and collective levels.(a)  Pioneering research by scientists like Julia Sliwa from the Paris Brain Institute is steering away from the traditional focus on individual cognition and (b)  moving towards understanding the neural basis(b)  of group intelligence. With the help of brain imaging technologies like electroencephalography, which measures electrical activity in the brain, (c)  neuroscientists have discovered what human brains synchronize with one another(c)  when people cooperate on a task. This synchronization, observed in humans and other mammals, may be a fundamental mechanism of social intelligence. The extent (d)  to which such neural synchronization plays a role(d)   in the social intelligence of insects (e)  remains an open question for future research.(e) 

  

bodily-kinesthetic 身体運動感覚的な
canine イヌ科の動物 
electroencephalography 腦波記録法 
```

# Collective Intelligence
set: 2024_toshin_3
title: Collective Intelligence
answers: 21-d / 22-e / 23-b / 24-d / 25-c

---

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