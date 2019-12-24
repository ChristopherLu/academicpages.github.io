---
title: "Deep Neural Network Based Inertial Odometry Using Low-cost Inertial Measurement Units
"
collection: publications
permalink: /publications/tmc20_ionet
date: 2019-12-20
citation: 'Changhao Chen, <b>Chris Xiaoxuan Lu<sup>&#42;</sup></b>, Johan Wahlstrom, Andrew Markham, Niki Trigoni. <i>In IEEE Transactions on Mobile Computing (TMC), 2020.</i>'
---
[[Paper]](https://christopherlu.github.io/files/papers/[TMC20]ionet.pdf)

## Abstract
Inertial measurement units (IMUs) have emerged as an essential component in many of today’s indoor navigation solutions due to their low cost and ease of use. However, despite many attempts for reducing the error growth of navigation systems based on commercial-grade inertial sensors, there is still no satisfactory solution that produces navigation estimates with long-time stability in widely differing conditions. This paper proposes to break the cycle of continuous integration used in traditional inertial algorithms, formulate it as an optimization problem, and explore the use of deep recurrent neural networks for estimating the displacement of a user over a specified time window. By training the deep neural network using inertial measurements and ground truth displacement data, it is possible to learn both motion characteristics and systematic error drift. As opposed to established context-aided inertial solutions, the proposed method is not dependent on either fixed sensor positions or periodic motion patterns. It can reconstruct accurate trajectories directly from raw inertial measurements, and predict the corresponding uncertainty to show model confidence. Extensive experimental evaluations demonstrate that the neural network produces position estimates with high accuracy for several different attachments, users, sensors, and motion types. As a particular demonstration of its flexibility, our deep inertial solutions can estimate trajectories for non-periodic motion, such as the shopping trolley tracking. Further more, it works in highly dynamic conditions, such as running, remaining extremely challenging for current techniques.