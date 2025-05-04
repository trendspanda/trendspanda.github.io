---
layout: page
title: "BrainFM: A Foundation Model for Multi-modal Brain MRI Data with Applications to Few-shot Disease Detection"
description:  
img: assets/img/researches/Figure2.png
importance: 10
category: work
related_publications: false
---


Multimodal foundational models hold considerable research potential in the medical field, particularly when applied to brain-related structural and functional data. In this study, we propose BrainFM, a foundational multimodal MRI model based on a composite variational auto-encoder (VAE) architecture. The model is trained using paired MRI and functional network connectivity (FNC) data from the ABCD dataset (N=12k) and part of the UK Biobank (N=43k).The model demonstrates remarkable performance in downstream tasks, including the schizophrenia detection task, where equal or superior accuracy is achieved using a mere 20\% of the data previously used for fine-tuning in related studies. Furthermore, we employ attention weights to visualize critical brain regions, facilitating the identification of potential areas associated with schizophrenia. 