---
title: "milliEgo: Single-chip mmWave Aided Egomotion Estimation with Deep Sensor Fusion"
collection: publications
permalink: /publications/milliego
date: 2020-11-15
citation: '<b>Chris Xiaoxuan Lu</b>, Muhamad Risqi U. Saputra, Peijun Zhao, Yasin Almalioglu, Pedro P. B. de Gusmao, Changhao Chen, Ke Sun, Niki Trigoni, Andrew Markham. <i>In SenSys 2020.</i>'
---
[[paper]](https://christopherlu.github.io/files/papers/[SenSys2020]milliEgo.pdf)
[[talk video]](https://www.youtube.com/watch?v=5LG-PbrUSO8&feature=youtu.be)
<!-- [[teaser video]](https://youtu.be/I9vjoKGY2ts) -->
[[slide]](https://christopherlu.github.io/files/slides/sensys20_slide.pdf)
[[code]](https://github.com/ChristopherLu/milliEgo)

## Abstract

Robust and accurate trajectory estimation of mobile agents such as people and robots is a key requirement for providing spatial awareness for emerging capabilities such as augmented reality or autonomous interaction. Although currently dominated by optical techniques e.g., visual-inertial odometry, these suffer from challenges with scene illumination or featureless surfaces. As an alternative, we propose milliEgo, a novel deep-learning approach to robust egomotion estimation which exploits the capabilities of low-cost mmWave radar. Although mmWave radar has a fundamental advantage over monocular cameras of being metric i.e., providing absolute scale or depth, current single chip solutions have limited and sparse imaging resolution, making existing point-cloud registration techniques brittle. We propose a new architecture that is optimized for solving this challenging pose transformation problem. Secondly, to robustly fuse mmWave pose estimates with additional sensors, e.g. inertial or visual sensors we introduce a mixed attention approach to deep fusion. Through extensive experiments, we demonstrate our proposed system is able to achieve 1.3% 3D error drift and generalizes well to unseen environments. We also show that the neural architecture can be made highly efficient and suitable for real-time embedded applications.
