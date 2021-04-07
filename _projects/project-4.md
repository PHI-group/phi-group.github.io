---
title: Neuroimaing Methodologies

description: |
   <p align="center"><img style="width:90%" src="/img/resourcepic/graicar.png"></p>

   Our current methodology developments aim to tackle the heterogeneity of psychiatric neuroimaging. Our efforts are two folds. First, we attempt to reveal and decompose the inter-individual variability in psychiatric neuroimaging data, with a transdiagnosis philosophy; Second, we are developing imaging paradigms that have a larger effect size in identifying individuals with mental disorders. 

people:
  - yangz
  - huy
  - liqf
  - gaojq

layout: project
last-updated: 2020-09-04
---

Our current methodology developments aim to tackle the heterogeneity of psychiatric neuroimaging. Our efforts are two folds. First, we attempt to reveal and decompose the inter-individual variability in psychiatric neuroimaging data, with a transdiagnosis philosophy; Second, we are developing imaging paradigms that have a larger effect size in identifying individuals with mental disorders. With these aims in mind, we mainly focus on two topics:

## 1. Data-driven methodology for psychiatric imaging

<p align="center"><img style="width:90%" src="/img/resourcepic/graicar.png"></p>

We developed data-driven approaches (gRAICAR) for detecting subject communities based on the inter-subject similarity of functional connectivity networks (Yang et al., 2012; 2014a). A significant feature of this approach is that it avoids assuming all subjects share the same functional networks. Instead, it reveals potential differences among subjects and thus accelerates data-driven discovery. In a few application studies, we have demonstrated its usefulness (Yang et al., 2014b, 2015; 2016). 

Particularly, Yang et al., 2014b demonstrate gRAICAR's clinical application in identifying subtypes of early-onset schizophrenia patients based on a frontotemporal network. Please find the details of gRAICAR here.

We also investigated the impacts of critical parameters, such as the number of components, spatial smoothing of the data, and the mathematical models, on group-level independent component analysis. We found that a combination of low-level spatial smoothing and a high number of components can reliably separate the PCN and DMN in three commonly used group-level ICA algorithms (Hu et al., 2016).

## 2. Naturalistic imaging paradigm for psychiatric imaging

<p align="center"><img style="width:90%" src="/img/publicpic/natural_indiv_psy_imag.png"></p>

Conventional approaches based on comparing group-averages provide insufficient information to support the individualized diagnosis. We developed an individualized imaging methodology that combines naturalistic imaging and the normative model. This paradigm adopts video clips with rich cognitive, social, and emotional contents to evoke synchronized brain dynamics of healthy participants and builds a spatiotemporal response norm. By comparing individual brain responses with the response norm, we could recognize patients using machine learning techniques. 

We applied this methodology to recognizefirst-episode drug-naïve schizophrenia patients in a dataset containing 72 patients and 54 healthy controls. Some segments of the video evoked more synchronized brain activity in the healthy controls than in the schizophrenia patients. We built a spatiotemporal response norm by averaging the brain responses of the healthy controls in a training set, and trained a classier to recognize patients based on the differences between individual brain responses and the norm. The performance of the classier to recognize patients based on the differences between individual brain re- sponses and the norm. The performance of the classifier was then evaluated using an independent test set. The mean accuracies from a 5-fold cross-validation were 0.71–0.78 depending on the parameters such as the number of features and the width of the sliding windows. These findings reflected the potential of this methodology towards a clinical tool for individualized diagnosis.

----

We further examined the reliability of the naturalistic imaging paradigm in representing individual differences. In Gao et al., 2020, we present voxel-wise and parcel-wise test-retest reliability maps of individual variability reflected by brain responses underlying a natural viewing video and an emotional arousing video clip. We found that 1/3 voxels reflected reliable inter-individual similarity in an emotion-evoking movie. 

<p align="center"><img style="width:90%" src="/img/projpic/reliability_nv.png"></p>

Some regions exhibited “trait-like” inter-individual similarity and reliability. That is, the inter-individual similarity remained stable between the two movie-viewing sessions with a 1-week interval, and the reliability of the inter-individual similarity remained consistent across different contents of the emotion-evoking movie. These results support applying naturalistic imaging to individualized study, especially psychiatric imaging. The regions with significant reliability could be the targets for further investigation using natural stimuli.

We share the reliability maps here: https://osf.io/dnkg8/.