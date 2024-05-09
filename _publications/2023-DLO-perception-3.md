---
title: "A Robust Deformable Linear Object Perception Pipeline in 3D: From Segmentation to Reconstruction"
collection: publications
permalink: /publication/2023-DLO-perception-3
excerpt: 'Detect cable-like objects in 3D from a RGBD image with occulusions.'
date: 2023-12-01
venue: 'IEEE Robotics and Automation Letters'
paperurl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10333979'
citation: 'Zhaole, Sun, Hang Zhou, Li Nanbo, Longfei Chen, Jihong Zhu, and Robert B. Fisher. "A Robust Deformable Linear Object Perception Pipeline in 3D: From Segmentation to Reconstruction." IEEE Robotics and Automation Letters 9, no. 1 (2023): 843-850.'
---

Abstract:

3D perception of deformable linear objects (DLOs) is crucial for DLO manipulation. However, perceiving DLOs in 3D from a single RGBD image is challenging. Previous DLO perception methods fail to extract a decent 3D DLO model due to different textures, occlusions, sparse and false depth information. To address these problems and provide a more robust DLO perception initialization for downstream tasks like tracking and manipulation in complex scenarios, this letter proposes a 3D DLO perception pipeline to first segment a DLO in 2D images and post-process masks to eliminate false positive segmentation, reconstruct the DLO in 3D space to predict the occluded part of the DLO, and physically smooth the reconstructed DLO. By testing on a synthetic DLO dataset and further validating on a real-world dataset with seven different DLOs, we demonstrate that the proposed method is an effective and robust 3D perception pipeline solution with better performance on 2D DLO segmentation and 3D DLO reconstruction compared to State-of-the-Art algorithms.

Demo Figures: