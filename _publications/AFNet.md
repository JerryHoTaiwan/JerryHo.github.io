---
title: "On the Distinction between Phase images and Two-View LightField for PDAF of Mobile Imaging"
collection: publications
permalink: /publication/TVLF
excerpt: 'A phase detection autofocus (PDAF) algorithm iteratively estimates the phase shift between the left and right phase images captured in an autofocus process and uses it to determine the lens movement until the estimated in-focus lens position is reached. Such phase images have been assumed to be equivalent to a two-view light field. If the assumption is true, then the phase shift between the two phase images can be obtained by stereo matching or similar techniques. In this paper, we argue that it is a wrong assumption and provide insights into the distinctions between phase images and two-view light field from the autofocus perspective. We also support our argument by conducting an experiment to show that both stereo matching and optical flow result in inferior PDAF performance than the phase correlation technique and the AF-Net technique that specifically target phase images.'
date: 2020-01-26
venue: 'Electronic Imaging'

citation: 'Chi-Jui, Ho and Homer H. Chen, &quot;On the Distinction between Phase images and Two-View LightField for PDAF of Mobile Imaging&quot; <i>Electronic Imaging 2020</i>.'
---

It is important for an autofocus system to accurately and quickly find the in-focus lens position so that sharp images can be captured without human intervention. Phase detectors have been embedded in image sensors to improve the performance of autofocus; however, the phase shift estimation between the left and right phase images is sensitive to noise. In this paper, we propose a robust model based on convolutional neural network to address this issue. Our model includes four convolutional layers to extract feature maps from the phase images and a fully-connected network to determine the lens movement. The final lens position error of our model is five times smaller than that of a state-of-the-art statistical PDAF method. Furthermore, our model works consistently well for all initial lens positions. All these results verify the robustness of our model.
<!-- paperurl: 'http://academicpages.github.io/files/paper1.pdf' -->
