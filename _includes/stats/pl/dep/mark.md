

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Polish)

This relation is universal.

846 nodes (1%) are attached to their parents as `mark`.

835 instances of `mark` (99%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.88416075650118.

The following 8 pairs of parts of speech are connected with `mark`: [pl-pos/VERB]()-[pl-pos/SCONJ]() (793; 94% instances), [pl-pos/ADJ]()-[pl-pos/SCONJ]() (30; 4% instances), [pl-pos/AUX]()-[pl-pos/SCONJ]() (6; 1% instances), [pl-pos/NOUN]()-[pl-pos/SCONJ]() (6; 1% instances), [pl-pos/VERB]()-[pl-pos/ADP]() (4; 0% instances), [pl-pos/VERB]()-[pl-pos/PART]() (4; 0% instances), [pl-pos/ADV]()-[pl-pos/SCONJ]() (2; 0% instances), [pl-pos/VERB]()-[pl-pos/CCONJ]() (1; 0% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 5 mark	color:blue
1	Bartek	Bartek	PROPN	subst:sg:nom:m1	Animacy=Hum|Case=Nom|Gender=Masc|Number=Sing	2	nsubj	_	_
2	sprzedaje	sprzedawać	VERB	fin:sg:ter:imperf	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
3	książki	książka	NOUN	subst:pl:acc:f	Case=Acc|Gender=Fem|Number=Plur	2	obj	_	SpaceAfter=No
4	,	,	PUNCT	interp	_	6	punct	_	_
5	bo	bo	SCONJ	comp	_	6	mark	_	_
6	chce	chcieć	VERB	fin:sg:ter:imperf	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	2	advcl	_	_
7	się	się	PRON	qub	PronType=Prs|Reflex=Yes	11	expl:pv	_	_
8	ich	on	PRON	ppron3:pl:gen:f:ter:akc:npraep	Case=Gen|Gender=Fem|Number=Plur|Person=3|PrepCase=Npr|PronType=Prs|Variant=Long	11	obj	_	_
9	po	po	ADP	prep:acc	AdpType=Prep|Case=Acc	11	advmod	_	_
10	prostu	prosty	ADJ	adjp	PrepCase=Pre	9	case	_	_
11	pozbyć	pozbyć	VERB	inf:perf	Aspect=Perf|VerbForm=Inf	6	xcomp	_	SpaceAfter=No
12	.	.	PUNCT	interp	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 7 mark	color:blue
1	Najmłodsi	młody	ADJ	adj:pl:nom:m1:sup	Animacy=Hum|Case=Nom|Degree=Sup|Gender=Masc|Number=Plur	4	amod	_	_
2	w	w	ADP	prep:loc:nwok	AdpType=Prep|Case=Loc|Variant=Short	3	case	_	_
3	Lubinie	Lubin	PROPN	subst:sg:loc:m3	Animacy=Inan|Case=Loc|Gender=Masc|Number=Sing	1	obl	_	_
4	handlowcy	handlowiec	NOUN	subst:pl:nom:m1	Animacy=Hum|Case=Nom|Gender=Masc|Number=Plur	5	nsubj	_	_
5	oceniają	oceniać	VERB	fin:pl:ter:imperf	Aspect=Imp|Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	SpaceAfter=No
6	,	,	PUNCT	interp	_	10	punct	_	_
7	że	że	SCONJ	comp	_	10	mark	_	_
8	popyt	popyt	NOUN	subst:sg:nom:m3	Animacy=Inan|Case=Nom|Gender=Masc|Number=Sing	10	nsubj	_	_
9	jest	być	AUX	fin:sg:ter:imperf	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	10	cop	_	_
10	duży	duży	ADJ	adj:sg:nom:m3:pos	Animacy=Inan|Case=Nom|Degree=Pos|Gender=Masc|Number=Sing	5	advcl	_	SpaceAfter=No
11	.	.	PUNCT	interp	_	5	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 3 mark	color:blue
1	Był	być	AUX	praet:sg:m1:imperf	Animacy=Hum|Aspect=Imp|Gender=Masc|Number=Sing|Tense=Past|VerbForm=Part|Voice=Act	4	aux	_	_
2	to	to	AUX	pred	_	4	cop	_	_
3	bowiem	bowiem	SCONJ	comp	_	4	mark	_	_
4	chłopak	chłopak	NOUN	subst:sg:nom:m1	Animacy=Hum|Case=Nom|Gender=Masc|Number=Sing	0	root	_	_
5	mądry	mądry	ADJ	adj:sg:nom:m1:pos	Animacy=Hum|Case=Nom|Degree=Pos|Gender=Masc|Number=Sing	4	amod	_	_
6	i	i	CCONJ	conj	_	8	cc	_	_
7	bardzo	bardzo	ADV	adv:pos	Degree=Pos	8	advmod	_	_
8	przenikliwy	przenikliwy	ADJ	adj:sg:nom:m1:pos	Animacy=Hum|Case=Nom|Degree=Pos|Gender=Masc|Number=Sing	5	conj	_	SpaceAfter=No
9	.	.	PUNCT	interp	_	4	punct	_	_

~~~

