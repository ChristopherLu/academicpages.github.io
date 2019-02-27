---
title: "Autonomous Learning for Face Recognition in the Wild via Ambient Wireless Cues"
collection: publications
permalink: /publications/autotune
date: 2019-05-13
citation: '<b>Xiaoxuan Lu</b>, Xuan Kan, Bowen Du, Changhao Chen, Hongkai Wen, Andrew Markham, Niki Trigoni and John A. Stankovic. <i>In WWW 2019.</i>'
---
[[paper]](https://christopherlu.github.io/files/papers/[WWW2019]autotune.pdf)

## Abstract
Facial recognition is a key enabling component for emerging Internet
of Things (IoT) services such as smart homes or responsive
offices. Through the use of deep neural networks, facial recognition
has achieved excellent performance. However, this is only possibly
when trained with hundreds of images of each user in different
viewing and lighting conditions. Clearly, this level of effort in enrolment
and labelling is impossible for wide-spread deployment and
adoption. Inspired by the fact that most people carry smart wireless
devices with them, e.g. smartphones, we propose to use this
wireless identifier as a supervisory label. This allows us to curate a
dataset of facial images that are unique to a certain domain e.g. a set
of people in a particular office. This custom corpus can then be used
to finetune existing pre-trained models e.g. FaceNet. However, due
to the vagaries of wireless propagation in buildings, the supervisory
labels are noisy and weak.We propose a novel technique, AutoTune,
which learns and refines the association between a face and wireless
identifier over time, by increasing the inter-cluster separation
and minimizing the intra-cluster distance. Through extensive experiments
with multiple users on two sites, we demonstrate the
ability of AutoTune to design an environment-specific, continually
evolving facial recognition system with entirely no user effort.