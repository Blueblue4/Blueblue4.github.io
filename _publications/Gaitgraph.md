---
title: "Gaitgraph: Graph convolutional network for skeleton-based gait recognition"
collection: publications
category: conferences
permalink: /publications/Gaitgraph
excerpt: 'We propose GaitGraph that combines skeleton poses with Graph Convolutional Network (GCN) to obtain a modern model-based approach for gait recognition.'
date: 2021-02-01
venue: 'ICIP'
slidesurl: 'https://github.com/tteepe/GaitGraph'
paperurl: 'https://arxiv.org/pdf/2101.11228'
citation: "T Teepe, A Khan, J Gilg, F Herzog, S Hörmann, G Rigoll"
---

Gait recognition is a promising video-based biometric for identifying individual walking patterns from a long distance. At present, most gait recognition methods use silhouette images to represent a person in each frame. However, silhouette images can lose fine-grained spatial information, and most papers do not regard how to obtain these silhouettes in complex scenes. Furthermore, silhouette images contain not only gait features but also other visual clues that can be recognized. Hence these approaches can not be considered as strict gait recognition. We leverage recent advances in human pose estimation to estimate robust skeleton poses directly from RGB images to bring back model-based gait recognition with a cleaner representation of gait. Thus, we propose GaitGraph that combines skeleton poses with Graph Convolutional Network (GCN) to obtain a modern model-based approach for gait recognition.