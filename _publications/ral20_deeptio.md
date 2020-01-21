---
title: "DeepTIO: A Deep Thermal-Inertial Odometry with Visual Hallucination"
collection: publications
permalink: /publications/ral20_deeptio
date: 2020-04-20
citation: 'Muhamad Saputra, Pedro Gusmão, <b>Xiaoxuan Lu</b>, Yasin Almalioglu and et al. <i>In ICRA/RA-L 2020.</i>'
---
[[paper]](https://christopherlu.github.io/files/papers/[RAL2020]deeptio.pdf)
[[video]](https://www.youtube.com/watch?v=Uw81ERThI-U&feature=youtu.be)

## Abstract
Visual odometry shows excellent performance in a wide range of environments. However, in visually-denied scenarios (e.g. heavy smoke or darkness), pose estimates degrade or even fail. Thermal cameras are commonly used for perception and inspection when the environment has low visibility. However, their use in odometry estimation is hampered by the lack of robust visual features. In part, this is as a result of the sensor measuring the ambient temperature profile rather than scene appearance and geometry. To overcome this issue, we propose a Deep Neural Network model for thermal-inertial odometry (DeepTIO) by incorporating a visual hallucination network to provide the thermal network with complementary information. The hallucination network is taught to predict fake visual features from thermal images by using Huber loss. We also employ selective fusion to attentively fuse the features from three different modalities, i.e thermal, hallucination, and inertial features. Extensive experiments are performed in hand-held and mobile robot data in benign and smoke-filled environments, showing the efficacy of the proposed model.
