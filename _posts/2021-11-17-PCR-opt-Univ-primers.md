---
layout: post
title: PCR optimization for 16s Universal Primers
date: 2021-11-05 
categories: Aiptasia
tags: [PCR, 16s, microbiome,]
---
## Objectives:
To optimize PCR conditions for the Sequencing primers for 16s rRNA amplification using the Q5 mastermix Kit from NEB

## Broader Context
These primers will initially be used to sequence and analyze members and stability of the microbiome as part of PRJ-004-Aiptasia-Stab, but will also be utilized for other sequencing projects in the lab
## Protocol

Forward Primer: GM3F.Universal : 
AGA GTT TGA TCM TGG C

Reverse Primer: GM4R.UNIVERSAL :
TAC CTT GTT ACG ACT T

Using the samples t4-t7 a extracted during [lysis matrix optimization](Sophia-Macvittie-Sogin-Lab-Notebook\_posts\2021-11-09-Extraction-matrices-test.md), and a water blank we performed 25 ul reactions with the following ratios
Q5 mastermix (2x) - 12.5ul
10uM forward Primer - 1.25ul
10 uM reverse primer - 1.25ul
Template DNA - 1ul
Nuclease free water - 10 ul
A varying matrix of PCR conditions was tested with the following variations in Profile

Iniitial Denaturation: 98 C for 2 minutes
Denaturation: 98C for 10 seconds
Annealing: 51.3C, 53.1 C and 55C at 30, 60 and 90 and 120s
Extension: 72C for 30, 60, and 90s
Cycles: 30
Final Extebsion 72C for 2 minutes
Infinite hold: 4C
Annealing temperatures were tested using a gradient at each of the different annealing times first with an extension time of 30s
the optimal conditionfor annealing were determined to be 55C for 30 seconds, at which point two more PCRs were ru to determine the optimal annealing time

Final Profile was as follows
Iniitial Denaturation: 98 C for 2 minutes
Denaturation: 98C for 10 seconds
Annealing: 55C for 30s
Extension: 72C for 90s
Cycles: 30
Final Extebsion 72C for 2 minutes
Infinite hold: 4C

All Reactions were checked using a 100ml 1% agarose gel containing 5ul of Sybr safe, which was run at 110V for 85 minutes
