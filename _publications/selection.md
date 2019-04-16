---
title: "Selective Sensor Fusion for Neural Visual Inertial Odometry"
collection: publications
permalink: /publications/selection
date: 2019-03-12
citation: 'Changhao Chen‚ Stefano Rosa‚ Yishu Miao‚ <b>Chris Xiaoxuan Lu</b>‚ Wei Wu, Andrew Markham and Niki Trigoni. <i>In CVPR 2019.</i>'
---
[[Paper]](https://christopherlu.github.io/files/papers/[CVPR2019]selection.pdf)
[[demo]](https://www.youtube.com/watch?v=w8y5L-1hgbw)

## Abstract
Deep learning approaches for Visual-Inertial Odometry (VIO) have proven successful, but they rarely focus on incorporating robust fusion strategies for dealing with imperfect input sensory data.
We propose a novel end-to-end selective sensor fusion framework for monocular VIO, which fuses monocular images and inertial measurements in order to estimate the trajectory whilst improving robustness to real-life issues, such as missing and corrupted data or bad sensor synchronization.  In particular, we propose two fusion modalities based on different masking strategies: deterministic soft fusion and stochastic hard fusion, and we compare with previously proposed direct fusion baselines.
During testing, the network is able to selectively process the features of the available sensor modalities and produce a trajectory at scale.  We present a thorough investigation on the performances on three public autonomous driving, Micro Aerial Vehicle (MAV) and hand-held VIO datasets.
The results demonstrate the effectiveness of the fusion strategies, which offer better performances compared to direct fusion, particularly in presence of corrupted data.
In addition, we study the interpretability of the fusion networks by visualising the masking layers in different scenarios and with varying data corruption, revealing interesting correlations between the fusion networks and imperfect sensory input data.