---
abstract: Single-cell RNA sequencing (scRNA-seq) technologies have enabled a greater
  understanding of previously unexplored biological diversity. By design of such experiments,
  individual cells from scRNA-seq datasets can often be attributed to non-overlapping
  “groups”. For example, these group labels may denote the cell’s tissue or cell line
  of origin. In this setting, one important problem consists in discerning patterns
  in the data that are shared across groups versus those that are group-specific.
  However, existing methods for this type of analysis are mainly limited to (generalized)
  linear latent variable models. Here we introduce multiGroupVI, a deep generative
  model for analyzing grouped scRNA-seq datasets that decomposes the data into shared
  and group-specific factors of variation. We first validate our approach on a simulated
  dataset, on which we significantly outperform state-of-the-art methods. We then
  apply it to explore regional differences in an scRNA-seq dataset sampled from multiple
  regions of the mouse small intestine. We implemented multiGroupVI using the scvi-tools
  library, and released it as open-source software at www.placeholder.com.
title: Disentangling shared and group-specific variations in single-cell transcriptomics
  data with multiGroupVI
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: weinberger22a
month: 0
tex_title: Disentangling shared and group-specific variations in single-cell transcriptomics
  data with multiGroupVI
firstpage: 16
lastpage: 32
page: 16-32
order: 16
cycles: false
bibtex_author: Weinberger, Ethan and Lopez, Romain and Huetter, Jan-Christian and
  Regev, Aviv
author:
- given: Ethan
  family: Weinberger
- given: Romain
  family: Lopez
- given: Jan-Christian
  family: Huetter
- given: Aviv
  family: Regev
date: 2022-12-19
address:
container-title: Proceedings of the 17th Machine Learning in Computational Biology
  meeting
volume: '200'
genre: inproceedings
issued:
  date-parts:
  - 2022
  - 12
  - 19
pdf: https://proceedings.mlr.press/v200/weinberger22a/weinberger22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
