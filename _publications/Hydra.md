---
title: "Unleashing Hydra: Hybrid fusion, depth consistency and radar for unified 3D perception"
collection: publications
category: preprint
permalink: /publications/Hydra
excerpt: 'We introduce Hydra, a novel dense camera-radar fusion architecture for diverse 3D perception tasks.'
date: 2024-03-01
venue: 'arXiv'
paperurl: 'https://arxiv.org/pdf/2403.07746'
citation: 'P Wolters, J Gilg, T Teepe, F Herzog, A Laouichi, M Hofmann, G Rigoll'
---

Low-cost, vision-centric 3D perception systems for autonomous driving have made significant progress in recent years, narrowing the gap to expensive LiDAR-based methods. The primary challenge in becoming a fully reliable alternative lies in robust depth prediction capabilities, as camera-based systems struggle with long detection ranges and adverse lighting and weather conditions. In this work, we introduce HyDRa, a novel camera-radar fusion architecture for diverse 3D perception tasks. Building upon the principles of dense BEV (Bird's Eye View)-based architectures, HyDRa introduces a hybrid fusion approach to combine the strengths of complementary camera and radar features in two distinct representation spaces. Our Height Association Transformer module leverages radar features already in the perspective view to produce more robust and accurate depth predictions. In the BEV, we refine the initial sparse representation by a Radar-weighted Depth Consistency. HyDRa achieves a new state-of-the-art for camera-radar fusion of 64.2 NDS (+1.8) and 58.4 AMOTA (+1.5) on the public nuScenes dataset. Moreover, our new semantically rich and spatially accurate BEV features can be directly converted into a powerful occupancy representation, beating all previous camera-based methods on the Occ3D benchmark by an impressive 3.7 mIoU.
