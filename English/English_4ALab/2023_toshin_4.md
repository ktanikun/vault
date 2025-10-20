```
4 (A) 以下の英文の段落(21)~(25)にはそれぞれ誤りがある。修正が必要な下線部を各段落から一つずつ選び、マークシートの(21)~(25)にその記号をマークせよ。

(21) We like talking and gossiping because language is a form of grooming. For monkeys and apes, grooming is (a)less a matter of hygiene and more (a) an expression of commitment. Its sense (b)is more that of:(b) "I'd rather be here grooming with you (c)than over there with her."(c) It's an essential feature of all intimate relationships. Language is a kind of grooming at a distance and, in many ways, serves (d) much the same kind (d) of purpose. It allows us to make that all-important statement about commitment: "I find you interesting (e) enough to waste time talking." (e)

(22) Of course, language allows us to go one step beyond mere signals of commitment. It allows us to exchange information. (a) Monkeys and apes are restricted (a) to direct observation when it comes to learning (b) about who might make a good friend (b) and who is unreliable, or who is going out with whom. But we can learn (c) about these things at second thought, (c) and that greatly extends our circle of social knowledge. (d) Take a listen to (d) the conversation next to you. It will soon become clear that most of our conversations (e) are concerned with social doings.(e) Sometimes our own, sometimes other people's.

(23) There is, however, (a) a curious asymmetry (a) in the conversations of men and women. Harry, it seems, (b)likes to talk about Dick,(b) but (c)Sally talks about Susan.(c) "Ah," you say, (d)"everyone's stereotypes are confirmed."(d) Well, yes and no. There's no smoke without fire, of course. But the really interesting question is (e) why it should be like this. (e)

(24) (a) Men's and women's preferred conversation topics (a) are often radically different because they are playing rather different games. Listen carefully to what they say, and you soon realize that women's (b) conversations are primarily geared to (b) servicing their social networks, building and maintaining a complex web of relationships in a social world (c)that is forever changing.(c) Keeping up to date on everyone's doings is (d) as important as the implicit suggestion that you are a member of the in-group. (d) It's the very hub of the social merry-go-round, (e) the foundation of which society itself is built. (e)

(25) In contrast, men's conversations seem to be geared (a) as much to advertising as anything else.(a) They talk about themselves or they talk about (b)things they claim to know a lot about. (b) It's a kind of vocal form of the peacock's tail. Peacocks hang about on their mating territories and display their brilliant tails (c) whenever a female goes out of view. (c) Humans, it seems, do all this vocally. Like the peacocks that suddenly raise their tails when a peahen is near, men switch into advertising mode when women are present. Have a listen to the same man when (d) he is talking only to other men(d) and compare it with what he talks about when women are present. When there are women present, his conversational style changes dramatically. (e)It becomes more showy,(e) more designed to stimulate laughter as a response.
```

# Gossip, Gender, and Talk
set: 2023_toshin_4
title: Gossip, Gender, and Talk
answers: 21-e / 22-c / 23-b / 24-e / 25-c

---

### (2023_toshin_4 Q21)
```db
set: 2023_toshin_4
question: 21
correct: e
label: VERB_VALENCY
sublabels: [PREP_COLLOC]
explanation: “talk” は人を目的に取れない。→ “waste time **talking to** you”。前置詞なしは統語価不一致。
text:
  a: less a matter of hygiene and more an expression of commitment
  b: Its sense is more that of:
  c: than over there with her.
  d: serves much the same kind of purpose
  e: enough to waste time **talking**
ja:
  a: 清潔よりもむしろ献身の表明
  b: その意味合いはむしろ…に近い：
  c: 彼女のところにいるよりも
  d: ほぼ同じ種の目的にかなう
  e: 君と話すのに時間を無駄にするほど（to you が要る）
lures:
  - opt: a
    tags: [PARALLEL_COMPAR]
    expl: “less A and more B” は定型。不安だが比較並列として正。
  - opt: b
    tags: [PUNCTUATION, LEXICAL_NUANCE]
    expl: “that of”＋コロンで引用導入は可。硬いが文法上OK。
  - opt: c
    tags: [PARALLEL_COMPAR]
    expl: “rather be here … **than** over there …” は比較の対応が取れており正。
  - opt: d
    tags: [LEXICAL_NUANCE, REDUNDANCY]
    expl: “much the same kind of …” は冗長気味だが許容。文法誤りではない。
```

---

### (2023_toshin_4 Q22)
```db
set: 2023_toshin_4
question: 22
correct: c
label: IDIOM_FAKE
sublabels: [CONTENT_DRIFT]
explanation: 伝聞で学べる趣旨。正しくは “at **second hand**”。“at second thought” は「考え直して」で意味がずれる。
text:
  a: Monkeys and apes are restricted to direct observation
  b: about who might make a good friend … and who is unreliable …
  c: about these things **at second thought**
  d: **Take a listen to** the conversation next to you.
  e: are concerned **with** social doings.
ja:
  a: 霊長類は直接観察に限られる
  b: 誰が良い友人か／誰が信用できないか等について
  c: これらを考え直しで学べる（×）→ 伝聞で
  d: 隣の会話を聞いてみて
  e: 多くは社会的出来事に関する
lures:
  - opt: a
    tags: [PREP_COLLOC]
    expl: be restricted **to** は定型。不安だが正。
  - opt: b
    tags: [PRON_REF, PREP_COLLOC]
    expl: “about who … / with whom” の前置詞・格は許容。口語の who も可。
  - opt: d
    tags: [LEXICAL_NUANCE]
    expl: “take a listen” は口語だが自然。問題なし。
  - opt: e
    tags: [PREP_COLLOC]
    expl: be concerned **with** は定型。under などに置換しない。
```

---

### (2023_toshin_4 Q23)
```db
set: 2023_toshin_4
question: 23
correct: b
label: CONTENT_DRIFT
sublabels: [PRON_REF, REFLEXIVE]
explanation: 非対称性は「男は**自分**の話，女は**女性**の話」。*talk about Dick* だと別男性で趣旨が崩れる → **talk about himself**。
text:
  a: a curious asymmetry
  b: likes to talk about **Dick**
  c: Sally talks about Susan.
  d: “everyone’s stereotypes are confirmed.”
  e: why it should be like this.
ja:
  a: 興味深い非対称性
  b: ハリーは自分自身の話をする（himself が要る）
  c: サリーはスーザンの話をする
  d: 「固定観念が裏づけられた」
  e: なぜこうなのか
lures:
  - opt: a
    tags: [WORD_CHOICE]
    expl: “a curious asymmetry” は自然。修正不要。
  - opt: c
    tags: [PRON_REF]
    expl: “talk about Susan” は文脈適合。誤りにしない。
  - opt: d
    tags: [PUNCTUATION]
    expl: 引用符内の文は独立文で可。句読点も許容。
  - opt: e
    tags: [WORD_ORDER]
    expl: “why it should be like this” の語順は正。倒置不要。
```

---

### (2023_toshin_4 Q24)
```db
set: 2023_toshin_4
question: 24
correct: e
label: PREP_COLLOC
sublabels: [REL_PRONOUN]
explanation: 慣用は “the foundation **on which** society is built”。*of which* は前置詞誤り。
text:
  a: Men’s and women’s preferred conversation topics are often radically different
  b: conversations are primarily **geared to** servicing …
  c: that is forever changing.
  d: as important as …
  e: the foundation **of which** society itself is built.
ja:
  a: 男女の好む話題はしばしば大きく異なる
  b: 会話は主にネットワークの維持に向けられている（geared **to/toward** は可）
  c: 絶えず変化する社会世界で
  d: ～と同じくらい重要
  e: 社会がその上に築かれている基盤（**on** が要る）
lures:
  - opt: a
    tags: [TENSE_ASPECT]
    expl: 現在一般の叙述で自然。OK。
  - opt: b
    tags: [PREP_COLLOC]
    expl: geared **to** は定型。toward でも可。迷っても変更不要。
  - opt: c
    tags: [REL_PRONOUN]
    expl: “world **that** is …” の関係節は可。which でも可。
  - opt: d
    tags: [PARALLEL_COMPAR]
    expl: as A as B の比較は成立。文法上問題なし。
```

---

### (2023_toshin_4 Q25)
```db
set: 2023_toshin_4
question: 25
correct: c
label: CONTENT_REVERSE
sublabels: []
explanation: 文脈は「雌が**現れる**と誇示」。*goes out of view*（視界から消える）は逆。→ **comes into view / is in view**。
text:
  a: geared as much to advertising as anything else.
  b: things they claim to know a lot about.
  c: whenever a female **goes out of view**
  d: he is talking only to other men
  e: It becomes more showy,
ja:
  a: 広告目的にも等しく向けられている
  b: よく知っていると主張する事柄
  c: 雌が視界から消えるたびに（×）→ 視界に入るたびに
  d: 男同士だけで話すとき
  e: より見せびらかすようになる
lures:
  - opt: a
    tags: [LEXICAL_NUANCE]
    expl: “geared as much to … as …” は可。意味はやや比喩的だが正。
  - opt: b
    tags: [PHRASAL_VERB, PREP_COLLOC]
    expl: “know a lot **about** (things)” は定型。about で止める構造は先行詞 things が目的語を担うのでOK。
  - opt: d
    tags: [WORD_ORDER]
    expl: “he is talking only to other men” の only の位置は自然。誤りではない。
  - opt: e
    tags: [WORD_CHOICE]
    expl: showy の語義は文脈に適合。句読点のカンマも接続後続があれば許容。
```