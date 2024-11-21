---
title: "Do We Still Need Non-Maximum Suppression? Accurate Confidence Estimates and Implicit Duplication Modeling with IoU-Aware Calibration"
collection: publications
category: conferences
permalink: /publications/IouAware
excerpt: 'We introduce IoU-aware calibration that iplicitly accounts for the likelihood of each detection being a duplicate and adjusts the detections confidence score accordingly.'
date: 2024-01-03
venue: 'WACV'
slidesurl: 'https://github.com/Blueblue4/IoU-AwareCalibration'
paperurl: 'https://openaccess.thecvf.com/content/WACV2024/papers/Gilg_Do_We_Still_Need_Non-Maximum_Suppression_Accurate_Confidence_Estimates_and_WACV_2024_paper.pdf'
citation: 'J Gilg, T Teepe, F Herzog, P Wolters, G Rigoll'
---

Object detectors are at the heart of many semi-and fully autonomous decision systems and are poised to become even more indispensable. They are, however, still lacking in accessibility and can sometimes produce unreliable predictions. Especially concerning in this regard are the (essentially hand-crafted) non-maximum suppression algorithms that lead to an obfuscated prediction process and biased confidence estimates. We show that we can eliminate classic NMS-style post-processing by using IoU-aware calibration. IoU-aware calibration is a conditional Beta calibration; this makes it parallelizable with no hyper-parameters. Instead of arbitrary cutoffs or discounts, it implicitly accounts for the likelihood of each detection being a duplicate and adjusts the confidence score accordingly, resulting in empirically based precision estimates for each detection. Our extensive experiments on diverse detection architectures show that the proposed IoU-aware calibration can successfully model duplicate detections and improve calibration. Compared to the standard sequential NMS and calibration approach, our joint modeling can deliver performance gains over the best NMS-based alternative while producing consistently better-calibrated confidence predictions with less complexity.