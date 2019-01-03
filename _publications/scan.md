---
title: "SCAN: Learning Speaker Identity From Noisy Sensor Data"
collection: publications
permalink: /publications/scan
date: 2017-04-18
citation: '<b>Chris Xiaoxuan Lu</b>, Hongkai Wen, Sen Wang, Andrew Markham and Niki Trigoni <i>In IPSN 2017.</i>'
---
[[Paper]](https://christopherlu.github.io/files/papers/[IPSN2017]scan.pdf)

## Abstract
Sensor data acquired from multiple sensors simultaneously is featuring increasingly in our evermore pervasive world. Buildings can be made smarter and more efficient, spaces more responsive to users. A fundamental building block towards smart spaces is the ability to understand who is present in a certain area. A ubiquitous way of detecting this is to exploit the unique vocal features as people interact with one another. As an example, consider audio features sampled during a meeting, yielding a noisy set of possible voiceprints. With a number of meetings and knowledge of participation (e.g. through a calendar or MAC address), can we learn to associate a specific identity with a particular voiceprint? Obviously enrolling users into a biometric database is time-consuming and not robust to vocal deviations over time. To address this problem, the standard approach is to perform a clustering step (e.g. of audio data) followed by a data association step, when identity-rich sensor data is available. In this paper we show that this approach is not robust to noise in either type of sensor stream; to tackle this issue we propose a novel algorithm that jointly optimises the clustering and association process yielding up to three times higher identification precision than approaches that execute these steps sequentially. We demonstrate the performance benefits of our approach in two case studies, one with acoustic and MAC datasets that we collected from meetings in a non-residential building, and another from an online dataset from recorded radio interviews.

