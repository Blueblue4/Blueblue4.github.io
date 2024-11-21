---
title: "EarlyBird: Early-Fusion for Multi-View Tracking in the Bird's Eye View"
collection: publications
category: conferences
permalink: /publications/EarlyBird
excerpt: 'We introduce EarlyBird a novel approach for Multi Target Multi Camera (MTMC) tracking the Bird`s Eye View (BEV)'
date:  2023-01-01
venue: 'WACV'
slidesurl: 'https://github.com/Blueblue4/Object-Detection-Confidence-Bias'
paperurl: 'https://openaccess.thecvf.com/content/WACV2023/papers/Gilg_The_Box_Size_Confidence_Bias_Harms_Your_Object_Detector_WACV_2023_paper.pdf'
citation: 'J Gilg, T Teepe, F Herzog, G Rigoll'
---

Multi-view aggregation promises to overcome the occlusion and missed detection challenge in multi-object detection and tracking. Recent approaches in multi-view detection and 3D object detection made a huge performance leap by projecting all views to the ground plane and performing the detection in the Bird's Eye View (BEV). In this paper, we investigate if tracking in the BEV can also bring the next performance breakthrough in Multi-Target Multi-Camera (MTMC) tracking. Most current approaches in multi-view tracking perform the detection and tracking task in each view and use graph-based approaches to perform the association of the pedestrian across each view. This spatial association is already solved by detecting each pedestrian once in the BEV, leaving only the problem of temporal association. For the temporal association, we show how to learn strong Re-Identification (re-ID) features for each detection. The results show that early-fusion in the BEV achieves high accuracy for both detection and tracking. EarlyBird outperforms the state-of-the-art methods and improves the current state-of-the-art on Wildtrack by+ 4.6 MOTA and+ 5.6 IDF1.
