---
title: "Nowhere to Hide: Cross-modal Identity Leakage between Biometrics and Devices"
collection: publications
permalink: /publications/www20_nowhere
date: 2020-04-20
citation: '<b>Xiaoxuan Lu</b>, Yang Li, Yuanbo Xiangli and Zhengxiong Li  <i>In WWW 2020.</i>'
---
[[paper]](https://christopherlu.github.io/files/papers/[WWW2020]nowhere.pdf)
[[code]](https://github.com/zjzsliyang/CrossLeak)

## Abstract
Along with the benefits of Internet of Things (IoT) come potential privacy risks, since billions of the connected devices are granted permission to track information about their users and communicate it to other parties over the Internet. Of particular interest to the adversary is the user identity which constantly plays an important role in launching attacks.
While the exposure of a certain type of physical biometrics or device identity is extensively studied, the compound effect of leakage from both sides remains unknown in multi-modal sensing environments.
In this work, we explore the feasibility of the compound identity leakage across cyber-physical spaces and unveil that co-located smart device IDs (e.g., smartphone MAC addresses) and physical biometrics (e.g., facial/vocal samples) are side channels to each other. 
It is demonstrated that our method is robust to various observation noise in the wild and an attacker can comprehensively profile victims in multi-dimension with nearly zero analysis effort.
Two real-world experiments on different biometrics and device IDs show that the presented approach can compromise more than 70% of device IDs and harvests multiple biometric clusters with ~94% purity at the same time. 