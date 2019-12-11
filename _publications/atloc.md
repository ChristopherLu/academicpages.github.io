---
title: "AtLoc: Attention Guided Camera Localization"
collection: publications
permalink: /publications/atloc
date: 2018-02-02
citation: 'Bing Wang, Changhao Chen‚ <b>Chris Xiaoxuan Lu</b>‚ Peijun Zhao, Niki Trigoni and Andrew Markham. <i>In AAAI 2020.</i>'
---
[[paper]](https://christopherlu.github.io/files/papers/[AAAI2020]atloc.pdf)
[[demo]](https://www.youtube.com/watch?v=_8NQXBadklU&feature=youtu.be)
[[code]](https://github.com/BingCS/AtLoc)

## Abstract
Deep learning has achieved impressive results in camera localization, but current single-image techniques typically suffer from a lack of robustness, leading to large outliers. To some extent, this has been tackled by sequential (multi-images) or geometry constraint approaches, which can learn to reject dynamic objects and illumination conditions to achieve better performance. In this work, we show that attention can be used to force the network to focus on more geometrically robust objects and features, achieving state-of-the-art performance in common benchmark, even if using only a single image as input. Extensive experimental evidence is provided through public indoor and outdoor datasets. Through visualization of the saliency maps, we demonstrate how the network learns to reject dynamic objects, yielding superior global camera pose regression performance.