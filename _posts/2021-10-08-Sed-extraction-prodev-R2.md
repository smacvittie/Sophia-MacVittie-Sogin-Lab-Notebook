---
layout: post
title: Sediment Extraction Chemical Protocol Optimization Round 2
date: 2021-09-28
categories: Extraction Sediment
tags: [Extraction, DNA/RNA, microbe, bodega-rhizosphere-prodev]
---

**Objective:** 
This is the second round of experimentation on this project with the goal of further improving the method of extraction on marine sediments with high humic contents.
first round data can be found in the post from [Sept. 14th](Sophia-MacVittie-Sogin-Lab-Notebook/_posts/2021-09-14-Sed-extraction-protocol-chem.md)
## Broader Context
The samples used here were part of the initial sample collection from the scouting trip to Bodega bay in late july. successful optimization of this protocol will allow us to simultaneously collect DNA and RNA from a single sample to be used in multiple downstream analyses such as simultaneous metagenomics and metabolomics

## Protocol 
The protocol used followed the same protocol as that from the experiment on [Sept. 14th](Sophia-MacVittie-Sogin-Lab-Notebook/_posts/2021-09-14-Sed-extraction-protocol-chem.md) with the following modifications.
 - In step 1C liquid weight was used as an approximation for gram weight. 200μL of sediment regardless of wehther it was stored in Zymo research's DNA/RNA Shield or frozen directly. tubes were weighed upon sediment addition to determine accuracy, samples ranged between 0.18g and 0.23g
 - 250μL of 0.04M sodium hexametaphosphate solution was added to the sample, essentially halfing the amount of phosphate to the sample at 50μM/ g phosphate compared to the the previous 100μM/ g phosphate.
 - In step 4c the speed vac was run for 45 min
## Raw Data

| Sample notation | Storage | NA Type | Conc. ng/ul | 260/280 | 260/230 |
| --------------- | ------- | ------- | ----------- | ------- | ------- |
| S1              | Frozen  | DNA     | 9.7         | 1.82    | 0.28    |
| S1              | Frozen  | RNA     | 22.5        | 1.58    | 0.62    |
| S2              | Frozen  | DNA     | 8.7         | 1.85    | 0.12    |
| S2              | Frozen  | RNA     | 12.7        | 1.56    | 0.18    |
| S3              | Frozen  | DNA     | 9.5         | 1.79    | 0.19    |
| S3              | Frozen  | RNA     | 21.4        | 1.79    | 1.66    |
| S4              | Zymo    | DNA     | 1.3         | 1.48    | 0.01    |
| S4              | Zymo    | RNA     | 2           | 1.18    | 0.02    |
| S5              | Zymo    | DNA     | 2.2         | 1.85    | 0.02    |
| S5              | Zymo    | RNA     | 3.2         | 1.39    | 0.1     |
| S6              | Zymo    | DNA     | 0.2         | 0.49    | 0       |
| S6              | Zymo    | RNA     | 7           | 1.52    | 0.16    |
| S7              | Zymo    | DNA     | \-11.5      | 2.23    | 0.02    |
| S7              | Zymo    | RNA     | 0.9         | 1.11    | 0.02    |
| S8              | Zymo    | DNA     | \-11.7      | 4.29    | \-0.03  |
| S8              | Zymo    | RNA     | \-0.4       | \-31.85 | \-0.01  |
| S9              | Zymo    | DNA     | 0           | \-0.03  | 0       |
| S9              | Zymo    | RNA     | \-0.02      | 0.7     | \-0.01  |
| S10             | Frozen  | DNA     | 1.5         | 1       | 0.01    |
| S10             | Frozen  | RNA     | 11.5        | 1.85    | 0.27    |
| S11             | Frozen  | DNA     | 1.2         | 0.74    | 0.05    |
| S11             | Frozen  | RNA     | 3.6         | 1.67    | 0.05    |
| S12             | Frozen  | DNA     | 2.3         | 1.06    | 0.05    |
| S12             | Frozen  | RNA     | 4.9         | 1.72    | 0.16    |


## Concluding Thoughts
- After second round it is evident that storage in zymo is not feasible. zymo likely dilutes the sample to much.
- Going forward, reverting back to the 100UM/g phosphate concentration seems to yeild more consisten result
- samples are still not very pure even after running throught the cleen kit step tto address this , and additional CI wash should be done to help further the purify the sample, and potenttiall also a PCI wash but samples may oxidize. so a 3rd CI wash will be tested first
in addition, the Ethanol wash after the isoproanol precipitation step should be increased to help further clean out any remnant alcohol contaminants. to expedite this , EtOH can be pippetted off between rounds rather than being dried down completelely. speed vac will still be utilized after last wash.