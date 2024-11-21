---
title: "The box size confidence bias harms your object detector"
collection: publications
category: conferences
permalink: /publications/Boxsize
excerpt: 'We investigate the impact of the box size confidence bias on the performance of object detectors.'
date:  2023-01-01
venue: 'WACV'
slidesurl: 'https://github.com/Blueblue4/Object-Detection-Confidence-Bias'
paperurl: 'https://openaccess.thecvf.com/content/WACV2023/papers/Gilg_The_Box_Size_Confidence_Bias_Harms_Your_Object_Detector_WACV_2023_paper.pdf'
citation: 'J Gilg, T Teepe, F Herzog, G Rigoll'
---

Countless applications depend on accurate predictions with reliable confidence estimates from modern object detectors. However, it is well known that neural networks, including object detectors, produce miscalibrated confidence estimates. Recent work even suggests that detectors' confidence predictions are biased with respect to object size and position. In object detection, the issues of conditional biases, confidence calibration, and task performance are usually explored in isolation, but, as we aim to show, they are closely related. We formally prove that the conditional confidence bias harms the performance of object detectors and empirically validate these findings. Specifically, to quantify the performance impact of the confidence bias on object detectors, we modify the histogram binning calibration to avoid performance impairment and instead improve it through calibration conditioned on the bounding box size. We further find that the confidence bias is also present in detections generated on the training data of the detector, which can be leveraged to perform the de-biasing. Moreover, we show that Test Time Augmentation (TTA) confounds this bias, which results in even more significant performance impairments on the detectors. Finally, we use our proposed algorithm to analyze a diverse set of object detection architectures and show that the conditional confidence bias harms their performance by up to 0.6 mAP and 0.8 mAP50.