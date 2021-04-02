---
date: 2017-09-06T20:00:00Z
title: Hacking's Introduction to Probability and Inductive Logic
categories: "Philosophy"
---
<img src="/img/hacking-inductive-logic.jpg" width="400" class="sidenote" />

I recently read through Ian Hacking's "Introduction to Probability and Inductive Logic".  I was interested in learning more about the philosophical basis of different ways of reasoning from experiences/past data. Having come across this book, I was hoping to find some discussion of these ideas, which are addressed in the final part of the book.

The book starts by drawing the connections and differences between deductive logic (risk free: conclusion is true of premises are true) and inductive reasoning (not risk free: i.e. following an argument may lead to the wrong conclusion even if the premises are correct). An interesting analogy drawn is that in inductive reasoning:

> Criticizing the models is like challenging the premises. Criticizing the analysis of the model is like challenging the reasoning.

The second part of the book offers a basic and well written introduction into probability theory. Not much new here, except that I learned that the first axiomatization of probability was by Christiaan Huygens in 1657. Part three discusses decision theory, where I like the use of paradoxes to present various points.

In part four the  dichotomy of belief-type and frequency-type probability is introduced. Both types are then covered separately. When talking about frequency type probability and p-values, Hacking clearly differentiates between p-values and Neyman-Pearson hypothesis testing. Referring to Fisher, Hacking mentions: 

>Above all, he thought that statistics and frequency-type probabilities were an essential tool for the communication of information among scientists working in fields where there may not be very good theories about nature, but where there is a great deal of data which needs to be understood.

I though this was interesting, since, on the one hand, it seems to make sense, but on the other hand, it seems this is exactly what leads to replication problems caused by multiple testing and adaptive data analysis in fields that can not rely on "very good theories".

Hacking then mentions Neyman's argument against regarding confidence intervals and hypothesis testing testing as *inductive inference*, but only as corresponding to *inductive behaviour*: sticking to such methods is a policy that is correct x percent of the time, but says nothing about the current inference. Hacking explains Neyman's strong views on this point make sense in the historical context. The then new concept of the confidence interval was easily mistaken as a probability statement of an individual event occurring. There was also the danger that contemporaneous ideas like fiducial inference may have lead people to believe confidence intervals have a similar interpretation.

## Problem of Induction
This discussion about inductive inference vs. inductive behaviour lead in the final part of the book. Personally, I found this to be by far the most interesting part of the book. Here Hume's problem of induction is introduced: one can not prove that the future will be related to the past without falling back on circular reasoning. To evade this problem of induction, Popper argues to use only conjectures, deductive reasoning and refutation instead of aiming for direct induction, and recognizing the fallibility of all current knowledge.

Similarly, to evade the problem of induction, arguments can be made for both the belief-type framework and the frequency-type framework. In the belief-type framework, the claim is not that Bayesian probability updating leads to a valid inductive inference, but that the way we update the beliefs is rational. Hacking mentions this argument is not complete though: we still need to show that beliefs that are consistent at each point in time are also consistent when we move to the next time point (after seeing evidence). In other words, one needs to be "true to one's former self", which is, as Hacking notes, a type of moral argument. This moralism comes back in the frequentist evasion of the problem of induction as well.

In the frequentist-type framework, one evasion of the problem of induction is that offered by Neyman and discussed above, by only considering inductive behaviour and not inductive inference. Given our assumptions in the model, by using a particular strategy of making decisions, we will be correct most of the time. One issue is of course that in my particular given situation, this long run behaviour does not help me directly. I was especially interested by Peirce's arguments on dealing with this. Essentially, because the number of decisions in our life is always finite, it is hard to argue for long run probabilities unless we consider the collective behaviour of whole community, leading Peirce to morally sounding claim that "Logic is rooted in the social principle". To contrast this with Hume's argument, Hacking concludes:

> Hume thought in a hugely individualistic way, of how *my* beliefs are formed by *my* experiences. Peirce thought in a collective and communal way, in terms of how *our* beliefs are formed on the basis of *our* inquiries"

## Theory of Applied Induction
The book indeed offers an introduction into inductive logic. Overall, I think the book is worth checking out, particularly the first and final chapters (1-2, 20-22). What I would have loved to see, is examples that are more similar to those encountered in actual data analysis and how these relate to the principles of (evading) induction discussed in the book.

In chapter 18, for instance, when discussing significance testing, there is no real discussion about multiple testing. While it is mentioned that a significant result is just one step of the scientific process, it is suggested that this results should then inform new directions of research. But without considering multiple testing and adaptive data analysis, such a strategy might lead us astray. What would therefore be great is the addition of some chapters that bridge the gap between the idealized examples and the messiness of the combination of adaptive and confirmatory data analysis we often deal with in the real world. A discussion of these issues and the role frameworks like [error statistical viewpoint](https://errorstatistics.com), [hypothetico deductive Bayesianism](http://www.stat.columbia.edu/~gelman/research/published/philosophy.pdf) etc. might play here would be very interesting, but is perhaps beyond the scope of an introduction. 

On a related note, I, as Hacking and many others, aim to be statistically eclectic: use the method and inferential framework that best fits your question of interest. Unfortunately, while that sounds nice as a statement of intent, I have seen few people offer much advice on how to actually match methods to research goals. 

The book was an interesting gateway into thinking more about such problems.