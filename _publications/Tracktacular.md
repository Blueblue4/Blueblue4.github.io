---
title: "Lifting Multi-View Detection and Tracking to the Bird's Eye View"
collection: publications
category: conferences
permalink: /publications/Tracktacular
excerpt: 'We present a novel approach that lifts multi-view detection and tracking to the Bird`s Eye View (BEV) and achieves state-of-the-art performance in detection and tracking.'
date: 2024-07-01
venue: 'CVPRW'
slidesurl: 'https://github.com/tteepe/TrackTacular'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2024W/3DMV/papers/Teepe_Lifting_Multi-View_Detection_and_Tracking_to_the_Birds_Eye_View_CVPRW_2024_paper.pdf'
citation: 'T Teepe, P Wolters, J Gilg, F Herzog, G Rigoll'
---

Taking advantage of multi-view aggregation presents a promising solution to tackle challenges such as occlusion and missed detection in multi-object tracking and detection. Recent advancements in multi-view detection and 3D object recognition have significantly improved performance by strategically projecting all views onto the ground plane and conducting detection analysis from a Bird's Eye View (BEV). In this paper we compare modern lifting methods both parameter-free and parameterized to multi-view aggregation. Additionally we present an architecture that aggregates the features of multiple times steps to learn robust detection and combines appearance-and motion-based cues for tracking. Most current tracking approaches either focus on pedestrians or vehicles. In our work we combine both branches and add new challenges to multi-view detection with cross-scene setups. Our method generalizes to three public datasets across two domains:(1) pedestrian: Wildtrack and MultiviewX and (2) roadside perception: Synthehicle achieving state-of-the-art performance in detection and tracking.