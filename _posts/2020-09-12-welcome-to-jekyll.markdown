---
layout: post
title:  Naive Bayes assumption
date:   2020-09-12 
categories: jekyll update
---

Reason naive bayes is "naive" is because it treats all orderings of the sequence the same. So in a sentence "Hello, how are you?", the probability of "how are" is the same as "are how".

More explicitly:

$P(X_1, \ldots, X_n\mid Y) = \Pi_i P(X_i\mid Y)$
