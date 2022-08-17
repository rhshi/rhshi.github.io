---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My main research interest is in the foundations of data science, particularly the algorthmic primitives that drive modern data science and machine learning tasks.  This involves a consideration of statistics, high-dimensional probability, algorithms, optimization, and some algebraic geometry.  For example, I like to study the limits of what is possible with decomposition and PCA.

One of my main focuses right now is a study of various tensor problems.  Unlike matrices, much is unknown about tensors, including governing equations for high rank tensors and algorithms for some tensor rank and decomposition problems.  For example, I am interested in probing the qualitative limits of what is known as Comon's conjecture, which asks if the rank and symmetric rank of tensors are always equal.  Though known now to be false, there are many questions yet to be answered, such as if the conjecture is true in the border rank case, if the conjecture is true for generic tensors, if there is a ``minimal counterexample,'' and if there is an upper bound to how much the symmetric rank can exceed the rank, among other questions.  More related to the theoretical computer science community, a recent conjecture has emerged that tensor decomposition exhibits a *statistical to computational gap* with respect to rank; that is, it is information theoretically possible to decompose tensors of a much higher rank than there are known polynomial time algorithms.  However, a study of this phenomenon from the perspective of algebraic geometry, from which of the classical results about tensor deomposition are derived, is sorely lacking.  This potentially connects ideas from property testing, algebraic geometry, statistics, and complexity theory.

Another thing I'm interested in right now is Oja's method, a classic but historically understudied algorithm for streaming PCA.  Predating modern machine learning, it is reminiscent of stochastic gradient descent, and as such is a very good way to study stochastic algorithms for nonconvex objectives.  I am interested in proving gap free rates for Oja's algorithm in more general cases than what is known, in using Oja for testing various properties of matrices, and in extending Oja beyond the i.i.d. setting for use on Markovian data.  These use ideas from probability and optimization.

# Publications

You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=TD6bQDEAAAAJ&hl=en).

## Conference Papers

**SHRIMP: Sparser Random Feature Models via Iterative Magnitude Pruning**  
*Yuege Xie, BS, Hayden Schaeffer, Rachel Ward*  
[\[PDF\]](https://msml22.github.io/msml22papers/shrimp_preprint.pdf)

## Preprints

**Generalization Bounds for Sparse Random Feature Expansions**
*Abolfazl Hashemi, Hayden Schaeffer, BS, Ufuk Topcu, Giang Tran, Rachel Ward*
[\[PDF\]](https://arxiv.org/pdf/2103.03191.pdf)

<!-- {% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->
