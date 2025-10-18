```
4 (A) 以下の英文の段落(21)~(25)にはそれぞれ文法上または内容上の誤りがある。修正が必要な下線部を各段落から一つずつ選び、マークシートの(21)~(25)にその記号をマークせよ。

(21) Great Nicobar Island in the Northern Indian Ocean is (a) one of the most pristine places on Earth. (a) It is important for its biodiversity conservation. (b) The beach on the island's southern end feature (b) the largest nesting site in the region for endangered Leatherback sea turtles.  More than 2,500 species of the island's plants and animals (c) have been recorded. (c) Of these, 17 percent can only be found there. (d) Its waters, only partially explored by scientists, (d) contain pristine coral reefs with 273 types of stony coral and 256 fish species. The island is also (e) home to tribal groups (e) such as the Great Nicobarese, the Andamans, and the elusive Shompen. 

(22) The members of the Shompen tribe, (a) numbering between 200 and 400, (a) live deep in the interior forest of Great Nicobar. They shun outsiders, and only fragments of their language and culture (b) have been uncovered. (b) Steep hills, dense jungles, and malaria have defeated those who seek to visit their hidden settlements. (c) Still, these travelers' accounts, (c) including those from their Great Nicobarese neighbors, offer a partial view of how the Shompen live. They build huts on platforms, usually near streams. For food, they spear crocodiles, fish, and other animals. They tend groves and, in small patches, cultivate vegetables and gather fruit and other forest edibles. (d) On rare occasions,(d) a few Shompen men visit the Great Nicobarese coastal villages to trade cane and honey for tools, tobacco, cloth, and other goods.  They refuse to (e) allow outsiders not to follow them back (e) into the jungle,  thus protecting their isolation.

(23) What the Shompens don't know is that their lives will soon drastically change. The Indian government, (a) in which inherited Great Nicobar Island (a) from British colonizers in 1950, (b) plans to build a massive transshipment terminal (b) there. The $9 billion free-trade zone will include (c) a port capable of handling  (c) 16 million cargo containers a year,  a city for 350,000 settlers from mainland India, (d) a power plant, and an airport (d) that can handle up to 4,000 passengers an hour.  The project (e) will spread over 244 square kilometers (e) — nearly a fifth of Great Nicobar — and destroy nearly a million rainforest trees.

(24) The effects of this project will be catastrophic for the islanders and wildlife. (a) One destructive aspect (a) is the massive influx of foreigners.  The Shompen are (b) not immune to (b) the diseases that thrive in the outside world and could be devastated by epidemics. New settlers will introduce dogs and cats (c) that prey on vulnerable creatures (c) like sea turtles and nesting birds.  Reducing the forest will lower humidity and precipitation levels, causing water shortages. Toxic runoff from the power plant will poison the soil and rivers, (d) where the Shompen fish (d) and collect drinking water.  Displaced animals will be forced to move upstream. The Shompen (e) will pressed to compete for (e) resources,  sparking a conflict with other groups that have, so far, maintained a peaceful relationship.

(25) Preservation groups within India launched a campaign to save the island (a) from the transshipment terminal. (a) Indigenous leaders from Great Nicobar Island also expressed in a letter to the government that "We feel (b) helpless and abandoned (b) and are extremely anxious about our future."  The Indian government answered by promising to reforest an area of dry hills in western India (c) that has no relation to the island. (c) Their solution for the islanders is to erect a militarized fence (d) surrounded the project territory (d) to keep crime and poachers away from their settlements. Unfortunately, this fence will also prevent people like the Shompen from using the spaces (e) they have occupied for millennia. (e)

注
pristine 原生的な
Leatherback sea turtle オサガメ
hut 小屋
tend …を手入れする
grove 木立
cane 藤(とう)
transshipment 貨物を別の船に積み替えること


```

# Great Nicobar under Threat
set: 2025_toshin_3
title: Great Nicobar under Threat
answers: 21-b / 22-e / 23-a / 24-e / 25-d

---

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