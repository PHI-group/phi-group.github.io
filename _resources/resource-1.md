---
title: PHI-pipe

description: |
  <p align="center"><img style="width:90%" src="/img/resourcepic/phipipe.jpg"></p>

  The PHI-pipe is a multi-modal brain MRI data processing pipeline developed in PHI. Remarkable features of this pipeline include:
   - A multi-modal pipeline for preprocessing of T1-3D, resting-state fMRI, and DWI data. This is a one-stop solution if you have scanned multi-modal images. Supported modality combinations are T1, T1+rest, and T1+DWI.
   - Supports automatic parallel computing. Make good use of computational power to automatically accelerate the processing.
   - Gives multiple levels of results. You can get preprocessed images for your customized further analyses or just tables of parcel-wise measures (such as parcel-wise cortical thickness, reho, and functional connectivity matrices) for your statistical comparisons without touching the images.
   - Makes quality control and quality check easy. The pipeline automatically evaluates and reports the quality of your data, and it generates figures for your visual check.
   - Supports web-interface. We have implemented an easy-to-use website in our center, called WeProMRI, where users can do "one-click image preprocessing"

   <p align="center"><img style="width:90%" src="/img/resourcepic/wepromri_2.png"></p>

   The source code of the basic version of PHI-pipe can be downloaded at [github release page](https://github.com/PHI-group/PhiPipe-release) Here is a [user's manual](https://github.com/PHI-group/PhiPipe-release/blob/main/PhiPipe_manual_v1.2.0.pdf).
    ## Reference paper
   Details of the PhiPipe as well various validations and comparisons are documented in our paper.
  
    ## Reliability and Validity Database
    We further evaluated the test-retest reliability and predictive validity of PhiPipe's brain features. We provide an online database to make the access to the reliability and validity measures easier. Users can query the reliability and validity measures for specific brain regions and image features here:
    [PhiPipe Reliability and Validity Database](https://yangzhi-psy.shinyapps.io/NeuroImageFeatureQualityViewer/)




layout: resource
last-updated: 2022-12-27
---
