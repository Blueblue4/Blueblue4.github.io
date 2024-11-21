---
title: "Spatial-Temporal Multi-Cuts for Online Multiple-Camera Vehicle Tracking"
collection: publications
category: preprint
permalink: /publications/STMC
excerpt: 'We introduce STMC a Spatial-Temporal Multi-Cuts approach for graph-based multiple-target multiple-camera tracking approach.'
date: 2024-10-01
venue: 'arXiv'
paperurl: 'https://arxiv.org/pdf/2410.02638?'
citation: 'F Herzog, J Gilg, P Wolters, T Teepe, G Rigoll'
---

Accurate online multiple-camera vehicle tracking is essential for intelligent transportation systems, autonomous driving, and smart city applications. Like single-camera multiple-object tracking, it is commonly formulated as a graph problem of tracking-by-detection. Within this framework, existing online methods usually consist of two-stage procedures that cluster temporally first, then spatially, or vice versa. This is computationally expensive and prone to error accumulation. We introduce a graph representation that allows spatial-temporal clustering in a single, combined step: New detections are spatially and temporally connected with existing clusters. By keeping sparse appearance and positional cues of all detections in a cluster, our method can compare clusters based on the strongest available evidence. The final tracks are obtained online using a simple multicut assignment procedure. Our method does not require any training on the target scene, pre-extraction of single-camera tracks, or additional annotations. Notably, we outperform the online state-of-the-art on the CityFlow dataset in terms of IDF1 by more than 14%, and on the Synthehicle dataset by more than 25%, respectively.
