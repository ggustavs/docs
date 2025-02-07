---
layout: base
title:  'Statistics of obl:agent in UD_Latin-ITTB'
udver: '2'
---

## Treebank Statistics: UD_Latin-ITTB: Relations: `obl:agent`

This relation is a language-specific subtype of <tt><a href="la_ittb-dep-obl.html">obl</a></tt>.
There are also 3 other language-specific subtypes of `obl`: <tt><a href="la_ittb-dep-obl-arg.html">obl:arg</a></tt>, <tt><a href="la_ittb-dep-obl-lmod.html">obl:lmod</a></tt>, <tt><a href="la_ittb-dep-obl-tmod.html">obl:tmod</a></tt>.

5 nodes (0%) are attached to their parents as `obl:agent`.

3 instances of `obl:agent` (60%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.8.

The following 2 pairs of parts of speech are connected with `obl:agent`: <tt><a href="la_ittb-pos-VERB.html">VERB</a></tt>-<tt><a href="la_ittb-pos-PRON.html">PRON</a></tt> (3; 60% instances), <tt><a href="la_ittb-pos-VERB.html">VERB</a></tt>-<tt><a href="la_ittb-pos-NOUN.html">NOUN</a></tt> (2; 40% instances).


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 3 obl:agent	color:blue
1	ordo	ordo	NOUN	C1|grn1|casA|gen1	Case=Nom|Gender=Masc|InflClass=IndEurX|Number=Sing	9	nsubj	_	_
2	igitur	igitur	ADV	O4	_	9	discourse	_	_
3	quo	qui	PRON	F1|grn1|casF|gen1	Case=Abl|Gender=Masc|InflClass=LatPron|Number=Sing|PronType=Rel	5	obl:agent	_	_
4	corruptibilia	corruptibilis	ADJ	C1|grn1|casJ|gen3	Case=Nom|Gender=Neut|InflClass=IndEurI|Number=Plur	5	nsubj:pass	_	_
5	ordinantur	ordino	VERB	J3|modJ|tem1|gen9	Aspect=Imp|InflClass=LatA|Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Pass	1	acl:relcl	_	TraditionalMood=Indicativus|TraditionalTense=Praesens
6	ad	ad	ADP	S4	_	7	case	_	_
7	hominem	homo	NOUN	C1|grn1|casD|gen1	Case=Acc|Gender=Masc|InflClass=IndEurX|Number=Sing	5	obl:arg	_	SpaceAfter=No
8	,	,	PUNCT	Punc	_	5	punct	_	_
9	requirit	requiro	VERB	L3|modA|tem1|gen6	Aspect=Imp|InflClass=LatX|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	TraditionalMood=Indicativus|TraditionalTense=Praesens
10	quod	quod	SCONJ	O4	_	12	mark	_	_
11	indiuidua	indiuiduus	NOUN	B1|grn1|casJ|gen3	Case=Nom|Gender=Neut|InflClass=IndEurO|Number=Plur	12	nsubj:pass	_	_
12	ordinentur	ordino	VERB	J3|modK|tem1|gen9	Aspect=Imp|InflClass=LatA|Mood=Sub|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Pass	9	ccomp	_	TraditionalMood=Subiunctivus|TraditionalTense=Praesens
13	ad	ad	ADP	S4	_	14	case	_	_
14	speciem	species	NOUN	E1|grn1|casD|gen2	Case=Acc|Gender=Fem|InflClass=IndEurE|Number=Sing	12	obl:arg	_	SpaceAfter=No
15	.	.	PUNCT	Punc	_	9	punct	_	_

~~~


~~~ conllu
# visual-style 22	bgColor:blue
# visual-style 22	fgColor:white
# visual-style 20	bgColor:blue
# visual-style 20	fgColor:white
# visual-style 20 22 obl:agent	color:blue
1	unde	unde	ADV	O4	AdvType=Loc|PronType=Rel	9	advmod:lmod	_	_
2	et	et	CCONJ	O4	_	9	cc	_	_
3	in	in	ADP	S4	_	4	case	_	_
4	his	hic	DET	F1|grn1|casO|gen3|vgr1	Case=Abl|Gender=Neut|InflClass=LatPron|Number=Plur|PronType=Dem	9	obl	_	_
5	quae	qui	PRON	F1|grn1|casM|gen3|vgr1	Case=Acc|Gender=Neut|InflClass=LatPron|Number=Plur|PronType=Rel	7	obj	_	_
6	sacerdotes	sacerdos	NOUN	C1|grn1|casJ|gen1	Case=Nom|Gender=Masc|InflClass=IndEurX|Number=Plur	7	nsubj	_	_
7	agunt	ago	VERB	L3|modA|tem1|gen9	Aspect=Imp|InflClass=LatX|Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	4	acl:relcl	_	SpaceAfter=No|TraditionalMood=Indicativus|TraditionalTense=Praesens
8	,	,	PUNCT	Punc	_	4	punct	_	_
9	utuntur	utor	VERB	L3|modJ|tem1|gen9	Aspect=Imp|InflClass=LatX|Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Pass	0	root	_	TraditionalMood=Indicativus|TraditionalTense=Praesens
10	rebus	res	NOUN	E1|grn1|casO|gen2	Case=Abl|Gender=Fem|InflClass=IndEurE|Number=Plur	9	obl:arg	_	_
11	per	per	ADP	S4	_	12	case	_	_
12	episcopum	episcopus	NOUN	B1|grn1|casD|gen1	Case=Acc|Gender=Masc|InflClass=IndEurO|Number=Sing	13	obl	_	_
13	consecratis	consecro	VERB	J2|modM|tem4|grp1|casO|gen2	Aspect=Perf|Case=Abl|Gender=Fem|InflClass=LatA|InflClass[nominal]=IndEurA|Number=Plur|VerbForm=Part|Voice=Pass	10	acl	_	SpaceAfter=No|TraditionalMood=Participium|TraditionalTense=Perfectum
14	:	:	PUNCT	Punc	_	19	punct	_	_
15	ut	ut	SCONJ	O4|vgr1	PronType=Rel	19	mark	_	_
16	in	in	ADP	S4	_	18	case	_	_
17	eucharistiae	eucharistia	NOUN	A1|grn1|casB|gen2	Case=Gen|Gender=Fem|InflClass=IndEurA|Number=Sing	18	nmod	_	_
18	consecratione	consecratio	NOUN	C1|grn1|casF|gen2|comH	Case=Abl|Gender=Fem|InflClass=IndEurX|Number=Sing	19	obl	_	_
19	utuntur	utor	VERB	L3|modJ|tem1|gen9	Aspect=Imp|InflClass=LatX|Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Pass	9	advcl	_	TraditionalMood=Indicativus|TraditionalTense=Praesens
20	consecratis	consecro	VERB	J2|modM|tem4|grp1|casO|gen3	Aspect=Perf|Case=Abl|Gender=Neut|InflClass=LatA|InflClass[nominal]=IndEurO|Number=Plur|VerbForm=Part|Voice=Pass	19	advcl:pred	_	TraditionalMood=Participium|TraditionalTense=Perfectum
21	per	per	ADP	S4	_	22	case	_	_
22	episcopum	episcopus	NOUN	B1|grn1|casD|gen1	Case=Acc|Gender=Masc|InflClass=IndEurO|Number=Sing	20	obl:agent	_	_
23	calice	calix	NOUN	C1|grn1|casF|gen1	Case=Abl|Gender=Masc|InflClass=IndEurX|Number=Sing	19	obl:arg	_	SpaceAfter=No
24	,	,	PUNCT	Punc	_	25	punct	_	_
25	altari	altare	ADV	C1|grn1|casF|gen3	_	23	conj	_	_
26	et	et	CCONJ	O4	_	27	cc	_	_
27	pallis	palla	NOUN	A1|grn1|casO|gen2	Case=Abl|Gender=Fem|InflClass=IndEurA|Number=Plur	23	conj	_	SpaceAfter=No
28	.	.	PUNCT	Punc	_	9	punct	_	_

~~~


