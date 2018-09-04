---
date: 2018-08-31T20:00:00Z
title: Peirce in the Garden
categories: "Philosophy"
draft: true
---

After [reading Ian Hacking's book](/articles/hacking-inductive-logic/) I got interested in C.S. Peirce's ideas on inductive inference. I had not heard of Peirce before. Another recent interest is Deborah Mayo's error statistical philosopy. Luckily, Mayo turns out to be an adminirer of Peirce and wrote a paper connecting her arguments about so-called severe testing to Peirce's ideas on self correcting science.

As I was not familiar with Peirce's SCT theory and its criticisms, I can't really comment on the validity of the nicely explained connection that Mayo is making. However, the following passage from Peirce stood out to me (emphasis mine):

> This account of the rationale of induction is distinguished from others in that it has as its consequences two rules of inductive inference which are very frequently violated  namely, that the sample be (approximately) random and that the **property being tested not be determined by the particular sample** --- i.e., predesignation.

As Mayo notes below this passage "when the null hypothesis is tested on the same data that led it to be chosen for testing, it is well known, a spurious impression of a genuine effect easily result". The way Peirce formulates it, however, reminded me of Loken & Gelman's Garden of Forking paths paper.  Of course, Loken & Gelman's claim is more subtle. They argue that during an analysis, the data at hand may inform the analysis that is done leading to one analysis path among many potential analysis paths. Had the data looked slightly different we might have made slightly different choices leading to a different analysis. 

Peirce's comment points out that in these cases the rationale for induction breaks down. Only under particular assumptions do conclusions make sense. At the very least, in Mayo's terminology the tests become less 'severe'. I find it interesting Peirce already notes this important point before Neyman-Pearson testing was invented, let alone as commonly applied and (mis-)used as it is today, before we strayed into the gardens of forking paths. The passage also reinforces the idea that it requires some thinking to connect the numbers that your favourite statistical programme calculates for you with what it is we have actually learned from the data. 

### References
>Mayo, D. G. (2005). Peircean Induction and the Error-Correcting Thesis Error-Correcting Thesis. Transactions of the Charles S. Peirce Society, 41(2), 299–319. [Link](https://doi.org/10.1353/csp.2011.0039)

>Mayo, D. G., & Spanos, A. (2011). Error Statistics. Philosophy of Statistics, 7, 153–198. [Link](https://doi.org/10.1016/B978-0-444-51862-0.50005-8)

>Gelman, A., & Loken, E. (2013). The garden of forking paths: Why multiple comparisons can be a problem, even when there is no “fishing expedition” or “p-hacking” and the research hypothesis, 1–17. [Link](https://doi.org/10.1037/a0037714)