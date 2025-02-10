---
title: 'Snowball ICA: A Model Order Free Independent Component Analysis Strategy for
  Functional Magnetic Resonance Imaging Data.'
authors:
- Guoqiang Hu
- Abigail B. Waters
- Serdar Aslan
- Blaise Frederick
- Fengyu Cong
- Lisa D. Nickerson
date: '2020-01-01'
publishDate: '2025-02-10T18:27:28.945377Z'
publication_types:
- article-journal
publication: '*Frontiers in neuroscience*'
doi: 10.3389/fnins.2020.569657
abstract: In independent component analysis (ICA), the selection of model order (i.e.,
  number of components to be extracted) has crucial effects on functional magnetic  resonance
  imaging (fMRI) brain network analysis. Model order selection (MOS)  algorithms have
  been used to determine the number of estimated components.  However, simulations
  show that even when the model order equals the number of  simulated signal sources,
  traditional ICA algorithms may misestimate the spatial  maps of the signal sources.
  In principle, increasing model order will consider  more potential information in
  the estimation, and should therefore produce more  accurate results. However, this
  strategy may not work for fMRI because  large-scale networks are widely spatially
  distributed and thus have increased  mutual information with noise. As such, conventional
  ICA algorithms with high  model orders may not extract these components at all.
  This conflict makes the  selection of model order a problem. We present a new strategy
  for model order  free ICA, called Snowball ICA, that obviates these issues. The
  algorithm collects  all information for each network from fMRI data without the
  limitations of  network scale. Using simulations and in vivo resting-state fMRI
  data, our results  show that component estimation using Snowball ICA is more accurate
  than  traditional ICA. The Snowball ICA software is available at  https://github.com/GHu-DUT/Snowball-ICA.
tags:
- dimension reduction
- functional magnetic resonance imaging
- independent component analysis
- model order
- mutual information
---
