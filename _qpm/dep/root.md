---
layout: relation
title:  'root'
shortdef: 'root'
udver: '2'
---


The `root` grammatical relation points to the root of the sentence. A fake node ROOT is used as the governor. The ROOT node is indexed with “0”, since the indexing of real words in the sentence starts at 1. (The ROOT node is not represented explicitly in CoNLL-U.). Note that in every tree there should only be one root dependency relation: 

~~~ sdparse
magáreno je stáro 
the donkey is old
root (stáro)
nsubj (stáro, magáreno)     
~~~ 
