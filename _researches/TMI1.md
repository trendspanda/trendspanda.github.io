---
layout: page
title: "A Hybrid Latent Diffusion Model for Multimodal Fusion and Prediction from Neuroimaging Data"
description:  
img: assets/img/researches/Figure1.png
importance: 10
category: work
related_publications: false
---

Neuroimaging generates high-dimensional structural and functional data, yet existing models often oversimplify or fail to capture their complex and nonlinear relationships. This study introduces an advanced artificial intelligence (AI) framework leveraging multimodal neuroimaging (structural and functional MRI data) from multiple sites to perform predictive neuroimaging for identifying brain-based biomarkers. We developed a hybrid latent diffusion model (HLDM), a novel data augmentation technique utilizing an autoencoder pre-trained on 53.2k samples to generate high-fidelity paired gray matter (GM) and functional network connectivity (FNC) data, enhancing model robustness. Our classification model, MultiViT2, employs modality-specific CNN-Transformer and graph transformer architectures, fused via a bi-cross-attention mechanism for robust disease prediction. Additionally, a multi-scale attention mapping technique, using gradients and attention weights, enhances interpretability by localizing disease-relevant brain regions and connections. Applied to schizophrenia--a disorder marked by intricate structural and functional brain changes--our approach achieved state-of-the-art performance (AUC 0.906), surpassing previous benchmarks (AUC 0.833). HLDM-driven augmentation significantly improved accuracy without additional real data, while multi-scale attention effectively reduced noise and identified critical biomarkers. Our study highlight the hippocampus, cerebellum, and insula, as of particularly relevance to the prediction of schizophrenia. In sum, our framework advances multimodal data integration, biomarker discovery, and interpretable AI for complex neuropsychiatric disorders.

 

