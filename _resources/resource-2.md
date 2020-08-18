---
title: gRAICAR

description: |
  <p align="center"><img style="width:90%" src="/img/resourcepic/graicar.png"></p>
  
  gRAICAR is a Matlab package for data-driven subject community detection based on functional networks.
   
  When we cannot assume that all subjects share the same functional networks, we may want to look into the inter-subject similarity on each network. gRAICAR provides a tool for realizing such a purpose. gRAICAR first decomposes fMRI data into spatial components using independent component analysis (ICA), then aligns the spatial maps across the subjects, yielding an inter-subject similarity matrix for each aligned, group-level component. According to many ICA studies, some of these aligned components represent functional connectivity networks.

  The gRAICAR inter-subject similarity matrices reveal potential differences among subjects and thus accelerate data-driven discovery. Further, community detection algorithms applied to the gRAICAR intersubject similarity matrices can provide more quantitative metrics to characterize the associations between individual differences in functional networks and behaviors.

  The gRAICAR code and a tutorial with examples: [Github link](https://github.com/yangzhi-psy/gRAICAR)

  Please consider to cite the following publications:

  **Original algorithms:**
  - Yang Z, Zuo X, Wang P, Li Z, Laconte S, Bandettini PA, Hu X (2012).  Generalized RAICAR: Discover homogeneous subject (sub)groups by  reproducibility of their intrinsic connectivity networks. NeuroImage 63,  403-414 [full page link](https://doi.org/10.1016/j.neuroimage.2012.06.060)
  - Yang Z, LaConte S, Weng X, and Hu X (2008). Ranking and averaging  independent component analysis by reproducibility (RAICAR). Human Brain  Mapping 29, 711-25 [full page link](https://doi.org/10.1002/hbm.20432)

  **Improvements and applications:**
  - Yang Z, Chang C, Xu T, Jiang L, Handwerker D, Castellanos F, Milham  M, Bandettini P, Zuo X (2014). Connectivity Trajectory across Lifespan Differentiates the Precuneus from the Default Network. NeuroImage 89,  45-56. [full page link](https://doi.org/10.1016/j.neuroimage.2013.10.039)
  - Yang Z, Xu Y, Xu T, Hoy C, Handwerker D, Chen G, Northoff G, Zuo X,  Bandettini P (2014). Brain network informed subject community detection  in early-onset schizophrenia. Scientific Reports 4, 5549. [full page link](https://doi.org/10.1038/srep05549)

layout: resource
last-updated: 2020-08-12
---