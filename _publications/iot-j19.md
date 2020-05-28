---
title: "Autonomous Learning of Speaker Identity and WiFi Geofence from Noisy Sensor Data"
collection: publications
permalink: /publications/iot-j19
date: 2019-06-21
citation: '<b>Chris Xiaoxuan Lu</b>, Yuanbo Xiangli, Peijun Zhao, Changhao Chen, Niki Trigoni and Andrew Markham. <i>In IEEE Internet of Things Journal (IoT-J) 2019.</i>'
---
[[Paper]](https://christopherlu.github.io/files/papers/iot-j19.pdf)

## Abstract
A fundamental building block towards intelligent environments is the ability to understand who is present in a certain area. A ubiquitous way of detecting this is to exploit  unique vocal characteristics as people interact with one another in common spaces. However, manually enrolling users into a biometric database is time-consuming and not robust to vocal deviations over time. Instead, consider audio features sampled during a meeting, yielding a noisy set of possible voiceprints. With a number of meetings and knowledge of participation, e.g., sniffed wireless Media Access Control (MAC) addresses, can we learn to associate a specific identity with a particular voiceprint? 
To address this problem, this paper advocates an Internet of Things (IoT) solution and proposes to use \emph{co-located} WiFi as supervisory weak labels to automatically bootstrap the labelling process. In particular, a novel cross-modality labelling algorithm is proposed that jointly optimises the clustering and association process, which solves the inherent mismatching issues arising from heterogeneous sensor data. At the same time, we further propose to reuse the labelled data to iteratively update wireless geofence models and curate device specific thresholds. Extensive experimental results from two different scenarios demonstrate that our proposed method is able to achieve 2-fold improvement in labelling compared with conventional methods and can achieve reliable speaker recognition in the wild. 