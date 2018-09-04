---
date: 2015-08-05T13:09:13Z
title: Favourite Work at ICML 2015
categories: "Machine Learning"
---

This post is just to remind myself of some of my favourite posters/presentations that I saw while attending ICML. I have undoubtably missed a lot of interesting stuff. If you have any particular suggestions, please let me know!

[The Fundamental Incompatibility of Scalable Hamiltonian Monte Carlo and Naive Data Subsampling](http://jmlr.org/proceedings/papers/v37/betancourt15.pdf)<br/>
*Michael Betancourt*<br/>
I liked the topic and the kind of analysis and I especially liked his clear style of presentation. Moreover, there was quite a lively discussion about whether this incompatibility is actually a problem, or whether it focussed too much on only the bias that is introduced by naive subsampling.

[Markov Chain Monte Carlo and Variational Inference: Bridging the Gap](http://jmlr.org/proceedings/papers/v37/salimans15.pdf)<br/>
*Tim Salimans, Diederik Kingma, Max Welling*<br/>
The presentation and poster were a bit hard for me to follow but the problem seems important.

[Towards a Learning Theory of Cause-Effect Inference](http://jmlr.org/proceedings/papers/v37/lopez-paz15.pdf)<br/>
*David Lopez-Paz, Krikamol Muandet, Bernhard Schölkopf, Iliya Tolstikhin*<br/>
Interesting use of Maximum Mean Discrepancy in a clear analysis of an important problem.

[Weight Uncertainty in Neural Network](http://jmlr.org/proceedings/papers/v37/blundell15.pdf)<br/>
*Charles Blundell, Julien Cornebise, Koray Kavukcuoglu, Daan Wierstra*<br/>
I have not looked into how exactly their approach is different from previous attempts at incorporating weight uncertainty, but the updates for the weight parameters seemed surprisingly simple.

[Convex Calibrated Surrogates for Hierarchical Classification](http://jmlr.org/proceedings/papers/v37/ramaswamy15.pdf)<br/>
*Harish Ramaswamy, Ambuj Tewari, Shivani Agarwal*<br/>
I like this idea of classification calibrated losses and this seems like an interesting extension to hierarchical loss functions.

[Optimizing Non-decomposable Performance Measures: A Tale of Two Classes](http://jmlr.org/proceedings/papers/v37/narasimhana15.pdf)<br/>
*Harikrishna Narasimhan, Purushottam Kar, Prateek Jain*<br/>
The authors consider functions of the true positive rate and true negative rate and come up with two classes of such functions and an approach to maximize them. The one class includes measures like the G-mean and the H-mean, while the other class includes the F-measure and Jaccard coefficient.

[The Kendall and Mallows Kernels for Permutations](http://jmlr.org/proceedings/papers/v37/jiao15.pdf)<br/>
*Yunlong Jiao & Jean-Philippe Vert*<br/>
The authors consider the problem of learning from permutations or rankings instead of vector of real valued numbers. In particular, they construct PSD kernels based on Kendall's coefficient and Mallows kernel in order to apply kernel methods to the problem.

[Enabling scalable stochastic gradient-based inference for Gaussian processes by employing the Unbiased LInear System SolvEr (ULISSE)](http://arxiv.org/pdf/1501.05427v3)<br/> 
*Maurizio Filippone & Raphael Engler*<br/>
This seems to tackle the important problem exact quantification of uncertainty in covariance parameters for gaussian processes with seemingly few constraints on the number type of covariance function.

[Risk and Regret of Hierarchical Bayesian Learners](http://jmlr.org/proceedings/papers/v37/hugginsb15.pdf)<br/>
*Jonathan H. Huggins & Joshua B. Tenenbaum*<br/>
Again, an interesting analysis of an important problem, although it will take me some more time to study the actual result.
