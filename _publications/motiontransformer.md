---
title: "MotionTransformer: Transferring Neural Inertial Tracking Between Domains"
collection: publications
permalink: /publications/motiontransformer
date: 2019-01-27
citation: 'Changhao Chen‚ Yishu Miao‚ <b>Chris Xiaoxuan Lu</b>‚ Linhai Xie‚ Phil Blunsom‚ Andrew Markham and Niki Trigoni <i>In AAAI 2019.</i>'
---
[[Paper]](https://christopherlu.github.io/files/papers/[AAAI2019]motiontransformer.pdf)

## Abstract
Inertial information processing plays a pivotal role in egomotion awareness for mobile agents, as inertial measurements are entirely egocentric and not environment dependent. However, they are affected greatly by changes in sensor placement/orientation or motion dynamics, and it is infeasible to collect labelled data from every domain. To overcome the challenges of domain adaptation on long sensory sequences, we propose MotionTransformer - a novel framework that extracts domain-invariant features of raw sequences from arbitrary
domains, and transforms to new domains without any paired data. Through the experiments, we demonstrate that it is able to efficiently and effectively convert the raw sequence from a new unlabelled target domain into an accurate inertial trajectory, benefiting from the motion knowledge transferred from the labelled source domain. We also conduct real-world experiments to show our framework can reconstruct physically meaningful trajectories from raw IMU measurements obtained with a standard mobile phone in various attachments.