---
title: "IONet: Learning to Cure the Curse of Drift in Inertial Odometry"
collection: publications
permalink: /publications/ionet
date: 2018-02-02
citation: 'Changhao Chen‚ <b>Chris Xiaoxuan Lu</b>‚ Andrew Markham and Niki Trigoni. <i>In AAAI 2018.</i>'
---
[[Paper]](https://christopherlu.github.io/files/papers/[AAAI2018]ionet.pdf)

## Abstract
Inertial sensors play a pivotal role in indoor localization, which in turn lays the foundation for pervasive personal applications. However, low-cost inertial sensors, as commonly found in smartphones, are plagued by bias and noise, which leads to unbounded growth in error when accelerations are double integrated to obtain displacement. Small errors in state estimation propagate to make odometry virtually unusable in a matter of seconds. We propose to break the cycle of continuous integration, and instead segment inertial data into independent windows. The challenge becomes estimating the latent states of each window, such as velocity and orientation, as these are not directly observable from sensor data. We demonstrate how to formulate this as an optimization problem, and show how deep recurrent neural networks can yield highly accurate trajectories, outperforming state-of-the-art shallow techniques, on a wide range of tests and attachments. In particular, we demonstrate that IONet can generalize to estimate odometry for non-periodic motion, such as a shopping trolley or baby-stroller, an extremely challenging task for existing techniques.