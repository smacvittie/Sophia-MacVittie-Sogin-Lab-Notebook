---
layout: post
title: PCR optimization for 16s Universal primers
date: 2021-11-05 
categories: Aiptasia
tags: [PCR, 16s, microbiome,]
---
## Objectives:
to optimize PCR conditions for the Universal primers for 16s rRNA amplification using the Q5 mastermix Kit from NEB

## Broader Context
These primers will initially be used to check the success of microbiome knockdown for PRJ002-Aiptasia-MM, but are flexible and can be used by members of the lab for other microbial experiments.

## Protocol
We developed a variable set of conditions based on reccomendations for our primer type and NEB's Q5 master mix to optimization to test out over the course of two days.
Using the samples t4-t7 extracted during [lysis matrix optimization](Sophia-Macvittie-Sogin-Lab-Notebook\_posts\2021-11-09-Extraction-matrices-test.md) we performed 25 ul reactions with the following ratios
Q5 mastermix (2x) - 12.5ul
10uM forward Primer - 1.25ul
10 uM reverse primer - 1.25ul
Template DNA - 1ul
Nuclease free water - 10 ul
 We ran a total of 5 different PCRs. The first 4 had a gradient of  Annealing temperatures with samples being tested at 51.3 degrees, 53.1 degrees and 55 degrees. Each of these PCRS was also run with a different annealing time of 30, 60, 90, or 120 seconds.
 a 100ml 1% agarose gel was run at 110V for 85 minutes to check for band presence with a 1 kb ladder from NEB to confirm appropirate fragment size, and 5ul of SYBR- safe used for the dye. Based on these gels we determined that an annealing temperature of 55 degrees and an anealing time of 30 seconds was optimal.


 The fifth PCR run used the determined annealing conditions to optimize the extension time, with tests of 30, 60 and 90 seconds and found 90 seconds to be the  ost optimal

 the full finalized profile for the thermal cycler is as follows
 Initial denaturation : 98 degrees for 2 minutes
 denaturation: 98 degrees for 30 seconds
 annealing: 55 degrees for 30 seconds
 Extension: 72 degrees for 90 seconds
 Cycles: 30
 Final extension: 72 degrees for 2 minutes
 Infinite hold at 4 degrees until removed from the thermal cycler.


