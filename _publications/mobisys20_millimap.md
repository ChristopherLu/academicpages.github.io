---
title: "See Through Smoke: Robust Indoor Mapping with Low-cost mmWave Radar"
collection: publications
permalink: /publications/millimap
date: 2019-06-15
citation: '<b>Chris Xiaoxuan Lu</b>, Stefano Rosa, Peijun Zhao, Bing Wang, Changhao Chen, John A. Stankovic, Niki Trigoni and Andrew Markham. <i>In MobiSys 2020.</i>'
---
[[paper]](https://christopherlu.github.io/files/papers/[MobiSys2020]milliMap.pdf)
[[talk video]](https://www.youtube.com/watch?v=uPVJu1mCTYc&t=4s)
<!-- [[demo]](https://youtu.be/VnxS-jsr4vk) -->
[[slide]](https://christopherlu.github.io/files/slides/mobisys20_slide.pdf))
[[code]](https://github.com/ChristopherLu/milliMap)

## Abstract

This paper presents the design, implementation and evaluation of milliMap, a single-chip millimetre wave (mmWave) radar based indoor mapping system targetted towards low-visibility environments to assist in emergency response. A unique feature of milliMap is that it only leverages a low-cost, off-the-shelf mmWave radar, but can reconstruct a dense grid map with accuracy comparable to lidar, as well as providing semantic annotations of objects on the map. milliMap makes two key technical contributions. First, it autonomously overcomes the sparsity and multi-path noise of mmWave signals by combining cross-modal supervision from a co-located lidar during training and the strong geometric priors of indoor spaces. Second, it takes the spectral response of mmWave reflections as features to robustly identify different types of objects e.g. doors, walls etc. Extensive experiments in different indoor environments show that milliMap can achieve a map reconstruction error less than 0.2m and classify key semantics with an accuracy of $\sim 90\%$, whilst operating through dense smoke. 
