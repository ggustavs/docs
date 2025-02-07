---
layout: base
title:  'Statistics of parataxis in UD_Teko-TuDeT'
udver: '2'
---

## Treebank Statistics: UD_Teko-TuDeT: Relations: `parataxis`

This relation is universal.

40 nodes (3%) are attached to their parents as `parataxis`.

39 instances of `parataxis` (98%) are left-to-right (parent precedes child).
Average distance between parent and child is 2.8.

The following 8 pairs of parts of speech are connected with `parataxis`: <tt><a href="eme_tudet-pos-VERB.html">VERB</a></tt>-<tt><a href="eme_tudet-pos-VERB.html">VERB</a></tt> (25; 63% instances), <tt><a href="eme_tudet-pos-NOUN.html">NOUN</a></tt>-<tt><a href="eme_tudet-pos-NOUN.html">NOUN</a></tt> (4; 10% instances), <tt><a href="eme_tudet-pos-NOUN.html">NOUN</a></tt>-<tt><a href="eme_tudet-pos-VERB.html">VERB</a></tt> (4; 10% instances), <tt><a href="eme_tudet-pos-NOUN.html">NOUN</a></tt>-<tt><a href="eme_tudet-pos-ADP.html">ADP</a></tt> (2; 5% instances), <tt><a href="eme_tudet-pos-VERB.html">VERB</a></tt>-<tt><a href="eme_tudet-pos-NOUN.html">NOUN</a></tt> (2; 5% instances), <tt><a href="eme_tudet-pos-ADV.html">ADV</a></tt>-<tt><a href="eme_tudet-pos-ADV.html">ADV</a></tt> (1; 3% instances), <tt><a href="eme_tudet-pos-PRON.html">PRON</a></tt>-<tt><a href="eme_tudet-pos-VERB.html">VERB</a></tt> (1; 3% instances), <tt><a href="eme_tudet-pos-PROPN.html">PROPN</a></tt>-<tt><a href="eme_tudet-pos-PRON.html">PRON</a></tt> (1; 3% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 5 parataxis	color:blue
1	"	"	PUNCT	punct	_	2	punct	_	_
2	daʔudʒi	ʔu	VERB	v	Number=Sing|Person=1|Polarity=Neg	0	root	_	_
3	"	"	PUNCT	punct	_	2	punct	_	_
4	,	,	PUNCT	punct	_	5	punct	_	_
5	eʔi	eʔi	VERB	v	Person=3	2	parataxis	_	_
6	idʒupe	dʒupe	ADP	posp	Case=Dat|Rel=NCont	5	obl	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 3 parataxis	color:blue
1	porowaratewe	porowar	NOUN	n	Also=Yes|Case=Ref|Foc=Yes	0	root	_	_
2	,	,	PUNCT	punct	_	1	punct	_	_
3	diakaŋi	akaŋ	NOUN	n	Polarity=Neg|Rel=NCont	1	parataxis	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 4 parataxis	color:blue
1	apamanẽ	apam	NOUN	n	Case=Ref|Contrast=Yes	2	nsubj	_	_
2	nõdeapisitanẽ	apisi	NOUN	n	Clusivity=In|Mood=Des|Person=1	0	root	_	_
3	,	,	PUNCT	punct	_	2	punct	_	_
4	eʔi	eʔi	VERB	v	Person=3	2	parataxis	_	_
5	tekokom	teko	PROPN	propn	Number=Plur	4	nsubj	_	_

~~~


