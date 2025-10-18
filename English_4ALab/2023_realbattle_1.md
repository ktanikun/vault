4 (A) 以下の英文の段落(21)~(25)にはそれぞれ誤りがある。修正が必要な下線部を各段落から一つずつ選び、マークシートの(21)~(25)にその記号をマークせよ。

(21) In October of 1858, John Stuart Mill and his wife, Harriet, were traveling near Avignon, France. She (a) developed a cough, which seemed (a) like just a minor inconvenience, (b) until it got worse. (b) Soon Harriet (c) was suffered from great pain, (c) not able to sleep or even lie down. Mill desperately wrote to a doctor in Nice, (d) begging him to come see her. (d) Three days later (e) her condition had worsened further, (e) and Mill telegraphed his fears to his stepdaughter. Harriet died in their hotel room on November 3.

(22) (a) Mill sat alone with her body (a) in their room for a day. He was depressed over the loss of his marriage: "For seven and a half years (b) that blessing was mine. (b) For seven and a half years only!" Later the same month, he sent a manuscript to his publisher, which began with (c) as many words of gratitude to Harriet. (c) He subsequently wrote that she had been more than his muse; she had been his co-author. The book was, he said, "more directly and literally our joint production than anything else (d) which bears my name, (d) for there was not a sentence of it (e) that was not several times gone through (e) by us together." The book's "whole mode of thinking," he continued, "was emphatically hers."

(23) The book was called On Liberty. It is one of (a) the founding document of our liberal world order. (a) Individuals, the Mills argued, have the right to be the architect of their own life, to choose (b) whom to marry, where to live, what to believe, (b) what to say. The state has no right to violate a citizen's individual freedom of choice, (c) provided that the person isn't harming anyone else. (c) A society organized along these lines, the Mills hoped, would produce a rich variety of creative and daring individuals. You wouldn't have to agree with my mode of life, and I wouldn't have to agree with yours, but we would give each other (d) the space to live our fullest life. (d) Individual autonomy and freedom of choice would be (e) the rocks upon which we built flourishing nations. (e)

(24) (a) The liberalism that the Mills advocated (a) is what we enjoy today as we walk down the street and (b) greet a great variety of social types. (b) It's what we enjoy when we get on the internet and (c) throw us into the messy clash of ideas. (c) It is this liberalism (d) that we defend when we back one country in a fight against another, (d) or when we stand up to authoritarians on the right and the left, (e) to those who would impose speech codes,(e) ban books, and subvert elections. 

(25) After he sent in the manuscript, Mill bought (a) a house overlooking the cemetery (a) where Harriet was buried, (b) and filled it with furniture (b) from the room in which she'd died. He visited the house every year (c) for the rest of his life. (c) It's a sad scene to imagine — (d) him gazing down at her grave from the window (d) — but the couple left us an intellectual legacy (e) guided humanity another step forward (e) in civilization's advance.

注
stepdaughter 義理の娘
muse ミューズ(ギリシャ神話における芸術の9人の女神の1人)
authoritarian 権威主義者



# OnLiberty_Legacy
set: 2023_realbattle_1
title: On Liberty and Its Legacy
answers: 21-c / 22-c / 23-a / 24-c / 25-e

---

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

