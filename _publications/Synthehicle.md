---
title: "Synthehicle: Multi-vehicle multi-camera tracking in virtual cities"
collection: publications
category: conferences
permalink: /publications/Synthehicle
excerpt: 'Synthehicle is a massive CARLA-based synthehic multi-vehicle multi-camera tracking dataset and includes ground truth for 2D detection and tracking, 3D detection and tracking, depth estimation, and semantic, instance and panoptic segmentation.'
date: 2023-01-01
venue: 'WACVW'
slidesurl: 'https://github.com/fubel/synthehicle'
paperurl: 'https://openaccess.thecvf.com/content/WACV2023W/RWS/papers/Herzog_Synthehicle_Multi-Vehicle_Multi-Camera_Tracking_in_Virtual_Cities_WACVW_2023_paper.pdf'
citation: 'F Herzog, J Chen, T Teepe, J Gilg, S Hörmann, G Rigoll'
---

Smart City applications such as intelligent traffic routing, accident prevention or vehicle surveillance rely on computer vision methods for exact vehicle localization and tracking. Privacy issues make collecting real data difficult, and labeling data is a time-consuming and costly process. Due to the scarcity of accurately labeled data, detecting and tracking vehicles in 3D from multiple cameras proves challenging to explore. We present a massive synthetic dataset for multiple vehicle tracking and segmentation in multiple overlapping and non-overlapping camera views. Unlike existing datasets, which only provide tracking ground truth for 2D bounding boxes, our dataset additionally contains perfect labels for 3D bounding boxes in camera-and world coordinates, depth estimation, and instance, semantic and panoptic segmentation. The dataset consists of 17 hours of labeled video material, recorded from 340 cameras in 64 diverse day, rain, dawn, and night scenes, making it the most extensive dataset for multi-target multi-camera tracking so far. We provide baselines for detection, vehicle re-identification, and single-and multi-camera tracking.