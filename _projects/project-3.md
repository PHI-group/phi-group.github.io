---
title: The Precuneus Network

description: |
  <p align="center"><img style="width:90%" src="/img/projpic/precuneus_network.png"></p>
  
  The precuneus network (PCN), or parietal memory network in some studies, refers to an intrinsic connectivity network anchors at the dorsal precuneus and the ventral posterior cingulate. In previous methodological studies, we discovered that this network and the default mode network (DMN) could be separated using ICA, and the PCN and DMN exhibited different cross-lifespan changes (Yang et al., 2012; 2014). This project aims to investigate why and how to separate PCN from DMN. We provide evidence from cross-lifespan development, heritability, clinical applications, and methodology to support that PCN stands as a different intrinsic connectivity network from DMN. Please see the "Read more" for a series of findings regarding this topic. We are still working on characterizing the specific functions of PCN.  

people:
  - pi-1
  - faculty-1
  - postdoc-1
  - postdoc-2

layout: project
last-updated: 2020-08-12
---

**Goal:** 

The precuneus network (PCN), or parietal memory network in some studies, is a relatively new name that refers to an intrinsic connectivity network in the brain that anchors at two parietal areas, including the precuneus and the posterior cingulate. The PCN and default mode network (DMN) is spatially adjacent and even overlap in posterior midline regions, so that seed voxel-based functional analyses may have the risk of merging the two networks as one. This project aims to investigate why and how to separate PCN from DMN. We provide evidence from cross-lifespan development, heritability, clinical applications, and methodology to support that PCN standands as a different intrinsic connectivity network from DMN (Figure 1). We are still working on characterizing the specific functions of PCN.

<p align="center"><img style="width:90%" src="/img/projpic/PCN_summary.png"></p>
<p align="center"><b>Figure 1.</b> A summary of our findings on differences between PCN and DMN</p>

**Finding 1: Lifespan development**

During the development of functional network-informed subject-community detetion algorithm (gRAICAR, Yang et al., 2012), we found an instrinsic connectivity network centered at the precuneus represents an individual similarity pattern that reflects age differences of subjects (see Figure 1 below). Importantly, this PCN is separatable from the DMN that exhibited consistency across individuals regardless of age (see Figure 2)

<p align="center"><img style="width:90%" src="/img/projpic/PCN_individual_differences.png"></p>
<p align="center"><b>Figure 2.</b> A precuneus network representing individual difference that distinguishes young and old subjects.</p>

<p align="center"><img style="width:90%" src="/img/projpic/patterninDMN_PCN.png"></p>
<p align="center"><b>Figure 3.</b> DMN and PCN reflects different patterns of inter-subject consistency.</p>

We further investigated the difference between PCN and DMN in a cross-lifespan neuroimaging dataset. In 126 subjects (age 7-85), we found that PCN is more consistent between young subjects than between elder ones, while DMN is consistent across the lifespan. Therefore, we proposed that the two intrinsic networks, although they may overlap in some part of the precuneus, should be considered separately, because they exhibit different cross-lifespan development (Figure 4). See details in Yang et al. 2014a.

<p align="center"><img style="width:90%" src="/img/projpic/PCN_proposed_separation.png"></p>
<p align="center"><b>Figure 4.</b> Proposed spatial separation of PCN (PCU ICN in figuree) and DMN.</p>

**Finding 2: Heritability**

In a twin study with resting-state fMRI data from 200 pairs of twins, we estimated the heritability of the activity levels of seven major intrinsic connectivity networks as well as their functional network connectivity. We found that the activity level of PCN is the most heritable (51%), and that of DMN is not as heritable (23%). Further, the functional network connectivity between PCN and all other networks exhibited significant environmental dependence. These results suggest that the PCN carries a different heritability background from DMN (Figure 5). See details in Yang et al., 2016.

<p align="center"><img style="width:90%" src="/img/projpic/hertiability_estimation.png"></p>
<p align="center"><b>Figure 5.</b> Hertiability estimation of activity level and connectivity of intrinsic connectivity networks</p>

**Finding 3: Abnormality in AD**

We investigated the clinical benefit of considering PCN and DMN as different intrinsic connectivity networks. In a neuroimaging study comparing resting-state networks between Alzheimer's Disease and healthy aging populations, we found that the integrity of PCN had an effect size (cohen's d = 1.24) in differentiating the two populations, while DMN had an effect size of 0.76 (Figure 6). These findings support that the PCN and DMN play different roles in the neurodegeneration progress in Alzheimer's Disease. See details in Hu et al., 2019.

<p align="center"><img style="width:90%" src="/img/projpic/higher_effectsize.png"></p>
<p align="center"><b>Figure 6.</b> PCN has a higher effect size than DMN in distinguishing Alzheimer's Disease and healthy aging samples.</p>

**Finding 4: Abnormality in Schizophrenia with Auditory Hallucinations**

In a sample of first-episode drug-naive schizophrenia patients and matched healthy controls, we found that the functional connectivity within PCN distinguishes the schizophrenia patients with auditory hallucinations from those without auditory hallucinations and the healthy controls. In contrast, we did not detect a significant inter-group difference in the functional connectivity of DMN. These findings support different roles of PCN and DMN in functional connectivity deficits in schizophrenia (Figure 7). See Guo et al., 2020, for details.

<p align="center"><img style="width:90%" src="/img/projpic/selective_deficts.png"></p>
<p align="center"><b>Figure 7.</b> PCN (PMN in this figure) exhibits seletive deficits in schzophrenia patients with auditory hallucinations (AH+ in this figure).</p>

**Finding 5: Resposes to naturalistic stimuli**

We compared the activity levels of PCN and DMN when subjects are watching a movie and its temporally shuffled version. We found: (1) scrambling the contextual information altered the fluctuation level of DMN and PCN in reversed ways (Figure 8); (2) compared to DMN, the FC within PCN showed significantly higher sensitivity to the contextual continuity; (3) PCN exhibited a significantly stronger functional network connectivity with the primary visual regions than DMN. These findings provide evidence for the distinct functional roles of PCN and DMN in processing context-rich information. See Deng et al., 2019, for details.

<p align="center"><img style="width:90%" src="/img/projpic/activity_levels.png"></p>
<p align="center"><b>Figure 8.</b> Activity levels when watching a normal movie and the random-shuffled version reveal different roles of PCN (PCUN in this figure) and DMN in real-life information processing.</p>

**Finding 6: Methodology to separate PCN and DMN**

Since there may be spatial overlap at the precuneus between PCN and DMN, seed-based functional connectivity usually merges the two networks. Spatial independent component analysis (ICA) has shown the capability to separate the two networks into two spatial components (Yang et al., 2012; 2014a; 2014b; 2015; 2016; Wang et al., 2018; Hu et al., 2019; Guo et al., 2020). However, the results of ICA depend on two key parameters, number of components and smoothness of data. We found that a combination of low-level spatial smoothing and a high number of components can reliably separate the PCN and DMN in three commonly used group-level ICA algorithms. See Hu et al., 2016, for details.
