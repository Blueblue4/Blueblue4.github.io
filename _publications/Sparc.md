---
title: "SpaRC: Sparse Radar-Camera Fusion for 3D Object Detection"
collection: publications
category: preprint
permalink: /publications/Sparc
excerpt: 'We present SpaRC, a novel Sparse fusion transformer for 3D perception that integrates multi-view image semantics with Radar and Camera point features.'
date: 2024-03-01
venue: 'arXiv'
paperurl: 'https://arxiv.org/pdf/2411.19860'
citation: 'P Wolters, J Gilg, T Teepe, F Herzog, F Fent, G Rigoll'
---

We present SpaRC, a novel Sparse fusion transformer for 3D perception that integrates multi-view image semantics with Radar and Camera point features. The fusion of radar and camera modalities has emerged as an efficient perception paradigm for autonomous driving systems. While conventional approaches utilize dense Bird's Eye View (BEV)-based architectures for depth estimation, contemporary query-based transformers excel in camera-only detection through object-centric methodology. However, these query-based approaches exhibit limitations in false positive detections and localization precision due to implicit depth modeling. We address these challenges through three key contributions: (1) sparse frustum fusion (SFF) for cross-modal feature alignment, (2) range-adaptive radar aggregation (RAR) for precise object localization, and (3) local self-attention (LSA) for focused query aggregation. In contrast to existing methods requiring computationally intensive BEV-grid rendering, SpaRC operates directly on encoded point features, yielding substantial improvements in efficiency and accuracy. Empirical evaluations on the nuScenes and TruckScenes benchmarks demonstrate that SpaRC significantly outperforms existing dense BEV-based and sparse query-based detectors. Our method achieves state-of-the-art performance metrics of 67.1 NDS and 63.1 AMOTA.
