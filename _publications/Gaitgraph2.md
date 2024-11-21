---
title: "Towards a deeper understanding of skeleton-based gait recognition"
collection: publications
category: conferences
permalink: /publications/Gaitgraph2
excerpt: 'We propose an efficient GCN-based architecture for skeleton-based gait recognition that combines higher-order inputs and residual networks, achieving state-of-the-art performance and providing insights through visualizations.'
date: 2022-06-01
venue: 'CVPRW'
slidesurl: 'https://github.com/tteepe/GaitGraph2'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2022W/Biometrics/papers/Teepe_Towards_a_Deeper_Understanding_of_Skeleton-Based_Gait_Recognition_CVPRW_2022_paper.pdf'
citation: 'T Teepe, J Gilg, F Herzog, S Hörmann, G Rigoll'
---

Gait recognition is a promising biometric with unique properties for identifying individuals from a long distance by their walking patterns. In recent years, most gait recognition methods used the person's silhouette to extract the gait features. However, silhouette images can lose fine-grained spatial information, suffer from (self) occlusion, and be challenging to obtain in real-world scenarios. Furthermore, these silhouettes also contain other visual clues that are not actual gait features and can be used for identification, but also to fool the system. Model-based methods do not suffer from these problems and are able to represent the temporal motion of body joints, which are real gait features. The advances in human pose estimation started a new era for model-based gait recognition with skeleton-based gait recognition. In this work, we propose an approach based on Graph Convolutional Networks (GCNs) that combines higher-order inputs, and residual networks to an efficient architecture for gait recognition. Extensive experiments on the two popular gait datasets, CASIA-B and OUMVLP-Pose, show a massive improvement (3x) of the state-of-the-art on the largest gait dataset OUMVLP-Pose and strong temporal modeling capabilities. Finally, we visualize our method to understand skeleton-based gait recognition better.