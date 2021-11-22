---
layout: post
title: PCR optimization for 16s Sequencing Primers
date: 2021-11-19 
categories: Aiptasia
tags: [PCR, 16s, microbiome,]
---
## Objectives:
To optimize PCR conditions for the Sequencing primers for 16s rRNA amplification using the Q5 mastermix Kit from NEB

## Broader Context
These primers will initially be used to sequence and analyze members and stabilit of the microbiome as part of PRJ-004-Aiptasia-Stab, but will also be utilized for other sequencing projects in the lab
## Protocol

Forward Primer: 515FB.A501 : 
AAT GAT ACG GCG ACC ACC GAG ATC TAC ACA TCG TAC GTA TGG TAA TTG TGT GYC

Reverse Primer: 806RB_SA701 :
CAA GCA GAA GAC GGC ATA CGA GAT AAC TCT CGA GTC AGT CAG CCG GAC TAC NVG

Using the samples t4-t6 a extracted during [lysis matrix optimization](Sophia-Macvittie-Sogin-Lab-Notebook\_posts\2021-11-09-Extraction-matrices-test.md), and a water blank we performed 25 ul reactions with the following ratios
Q5 mastermix (2x) - 12.5ul
10uM forward Primer - 1.25ul
10 uM reverse primer - 1.25ul
Template DNA - 1ul
Nuclease free water - 10 ul
The PCR Conditions were based on [Becker et. al 2021](https://sfamjournals.onlinelibrary.wiley.com/doi/epdf/10.1111/1462-2920.15718).
with modified denaturing and and infinite hold temperatures.

Final Profile was as follows
Iniitial Denaturation: 98 C for 2 minutes
Denaturation: 98C for 10 seconds
Annealing: 55C for 15s
Extension: 72C for 5 minutes
Cycles: 30
Final Extebsion 72C for 10 minutes
Infinite hold: 4C

A second profile was tested with the following conditions in an attempt to shorten the extension times, but this profile was unsuccessful based on a lack of bands present in the gel.
Final Profile was as follows
Iniitial Denaturation: 98 C for 2 minutes
Denaturation: 98C for 10 seconds
Annealing: 55C for 15s
Extension: 72C for 2 minutes
Cycles: 27
Final Extebsion 72C for 5 minutes
Infinite hold: 4C

A more detailed optimization to try and shorten the cycle time will be run after thanksgiving