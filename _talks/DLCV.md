---
title: "Object Detection"
collection: talks
type: "Talk"
permalink: /talks/DLCV
excerpt: "<br/><img src='/images/DLCV.PNG' width='600' >"
venue: "NTU"
date: 2019-06-01
location: "Taipei, Taiwan"
---
This is my final project of _Deep Learning on Computer Vision_ course. In fact, it is a work on few-shot learning. <br/>

We implemented a Siamese Network to compute the similarit score between images. However, we found it difficult to directly train a Siemese Network on the whole dataset. Thus, we designed a training schedule that gradually increases the training difficulty. After it converges, we fine-tuned the network on the images which has few labels. Through this special training schedule, we pass all the requirements in this task.

<img src='/images/DLCV.PNG' width='600' >

[Technical Poster](http://JerryHoTaiwan.github.io/files/DLCV_Report.pdf)