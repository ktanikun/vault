```
4 (A) 以下の英文の段落(21)~(25)にはそれぞれ文法上または内容上の誤りがある。修正が必要な下線部を各段落から一つずつ選び、マークシートの(21)~(25)にその記号をマークせよ。

(21) The debate of nature versus nurture has raged (a) for millennia. (a) Are babies comparable to a white page, a blank slate, or (b) an empty bottle that can experience (b) must fill? As early as 400 BCE, in The Republic, Plato was already (c) rejecting the idea (c) that our brains enter the world (d) devoid of any (d) knowledge.  From birth, he claimed, every soul possesses two sophisticated mechanisms: the power of knowledge and (e) the organ by which (e) we acquire instruction. 

(22) As we have just seen, two thousand years later, a remarkably similar conclusion arose from advances in machine learning. Learning is vastly more effective when the machine (a) comes equipped with two features: (a) a vast space of hypotheses, a set of mental models with myriad (b) settings to choose from; (b) and sophisticated algorithms that (c) adjust those settings according to (c) the data received from the outside world. As one of my friends once said, in the debate on nature versus nurture, we (d) have overestimated both. (d) In fact, learning requires two structures: (e) an immense set of (e) potential models  and an efficient algorithm to adjust them to reality.

(23) Artificial neural networks do this (a) on their own way, (a) by entrusting the representation (b) of mental models to (b) millions of adjustable connections. However, these systems, (c) while capturing the rapid (c) and unconscious recognition of image or speech, are not yet able to represent (d) more concrete hypotheses, (d) such as grammar rules or (e) the logic of (e) mathematical operations.

(24) The human brain seems to function differently: our knowledge (a) grows through the combination (a) of symbols. According to this view, we come into the world with a vast number of possible combinations of potential thoughts. (b) This "language of thought", (b) endowed with abstract assumptions and grammar rules, is already (c) in place prior to (c) learning. It generates a vast realm of hypotheses to be (d) put to the test. (d) And to do so, according to the Bayesian brain theory, our brain must act like a scientist, (e) collect statistical data (e) and using them to select the best-fitting generative model.

(25) This view of learning may seem counterintuitive. It suggests that each human baby's brain potentially (a) contains all the languages (a) of the world,  all the objects, all the faces, and all the tools that it will ever encounter, (b) in addition to (b) all the words, all the facts, and all the events that it will ever remember. The combinational analyses of the brain (c) are such that (c) all these objects of thought are potentially already there, along with their (d) respective preexisting (d) probabilities,  as well as (e) the ability to update it (e) when experience says that they need to be revised. Is this how a baby learns?

注
Bayesian ベイズ(の定理)の(18世紀の統計学者である Thomas Bayesの学説を指す)
```


# Nature, Nurture, and Learning
set: 2024_realbattle_2
title: Nature, Nurture, and Learning
answers: 21-b / 22-d / 23-a / 24-e / 25-e

---

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

