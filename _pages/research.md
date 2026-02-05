---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My main research interest is in the mathematical foundations of data science, particularly the algorithmic primitives that drive modern data science and machine learning tasks.  This involves statistics, high-dimensional probability, algorithms, optimization and sampling, and some algebra.  

<!-- One of my main focuses right now is a study of various tensor problems.  These include potential statistical-computational gaps in symmetric tensor decomposition, qualitatively studying [Comon's conjecture](https://arxiv.org/abs/1810.09338), and landscape analysis of ODECO tensor decomposition.  These use ideas from property testing, algebraic geometry, statistics, and complexity theory. -->

<!-- Unlike matrices, much is unknown about tensors, including governing equations for high rank tensors and algorithms for some tensor rank and decomposition problems.  For example, I am interested in probing the qualitative limits of what is known as Comon's conjecture, which asks if the rank and symmetric rank of tensors are always equal.  Though known now to be false, there are many questions yet to be answered, such as if the conjecture is true in the border rank case, if the conjecture is true for generic tensors, if there is a "minimal counterexample," and if there is an upper bound to how much the symmetric rank can exceed the rank, among other questions.  More related to the theoretical computer science community, a recent conjecture has emerged that tensor decomposition exhibits a *statistical to computational gap* with respect to rank; that is, it is information theoretically possible to decompose tensors of a much higher rank than there are known polynomial time algorithms.  However, a study of this phenomenon from the perspective of algebraic geometry, from which of the classical results about tensor deomposition are derived, is sorely lacking.  This potentially connects ideas from property testing, algebraic geometry, statistics, and complexity theory. -->

<!-- Another focus is streaming PCA, in particular Oja's algorithm, a classic but historically understudied algorithm for streaming PCA.  This includes extending Oja beyond the i.i.d. setting for use on Markovian data, studying adaptive step-size schedules, and proving more general gap-free rates.  These use ideas from probability and optimization. -->

# Publications

You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=TD6bQDEAAAAJ&hl=en).

## Preprints

**Functional Stochastic Localization**  
*Anming Gu, BS, Kevin Tian*  
[\[arXiv\]](https://www.arxiv.org/abs/2602.03999)

**Perspectives on Stochastic Localization**  
*BS, Kevin Tian, Matthew S. Zhang*  
[\[arXiv\]](https://arxiv.org/abs/2510.04460)

**Efficient Tensor Decomposition via Moment Matrix Extension**  
*BS, Julia Lindberg, Joe Kileel*  
[\[arXiv\]](https://arxiv.org/abs/2506.22564)[\[code\]](https://github.com/rhshi/TensorDecomposition.jl)

## Journal Papers

**Concentration Inequalities for Sums of Markov Dependent Random Matrices**  
*Joe Neeman, BS, Rachel Ward*  
In *Information and Inference*  
[\[journal\]](https://academic.oup.com/imaiai/article-abstract/13/4/iaae032/7917088?redirectedFrom=fulltext)[\[arXiv\]](https://arxiv.org/abs/2303.02150)

**Generalization Bounds for Sparse Random Feature Expansions**  
*Abolfazl Hashemi, Hayden Schaeffer, BS, Ufuk Topcu, Giang Tran, Rachel Ward*  
In *Applied and Computational Harmonic Analysis*  
[\[journal\]](https://www.sciencedirect.com/science/article/pii/S1063520322000653)[\[arXiv\]](https://arxiv.org/abs/2103.03191)[\[code\]](https://github.com/GiangTTran/SparseRandomFeatureExpansion)

## Conference Papers

**SHRIMP: Sparser Random Feature Models via Iterative Magnitude Pruning**  
*Yuege Xie, BS, Hayden Schaeffer, Rachel Ward*  
In *Mathematical and Scientific Machine Learning 2022*  
[\[conference\]](https://proceedings.mlr.press/v190/xie22a.html) [\[arXiv\]](https://arxiv.org/abs/2112.04002) [\[code\]](https://github.com/rhshi/sparse-rf)


<!-- {% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->
