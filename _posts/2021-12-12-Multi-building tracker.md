---
title: "Multi-building tracker: Multi-target building tracker for satellite images using deep learning"
layout: post
date: 2021-12-12 00:00
tag:
- classics
- digital classics
- computer science
- python
- Computer vision

image:
headerImage: false
projects: true
hidden: true # don't count this post in blog pagination
description: " Multi-temporal building footprint tracking with satellite images based on deep learning."
jemoji: '<img class="emoji" title=":paper:" alt=":paper:" src="../assets/images/paper-icon.png" height="20" width="20" align="absmiddle">'
author: patrickburns
externalLink: false
---

# Multi-temporal building footprint tracking with satellite images based on deep learning.

Code implementation can be found [*here*](https://github.com/sebasmos/Multi-building-tracker)

{:.paper-section-heading}

## Description
The automatic analysis of satellite imagery has a wide range of applications within the field of urban planning, including fair distribution of resources, effective disaster response, updating of real-time maps and epidemiological vector-borne diseases control. Furthermore, it poses compelling technical challenges that even today are not completely solved. A system for multi-target building tracking using satellite images has been developed following the guidelines pro-posed in the SpaceNet 7 Multi-Temporal Urban Development Challenge and as a continuation of a previous theoretical exploration of the problem. The system was implemented by considering each individual block: a preprocessing stage, a neural network for semantic segmentation, and an algorithm for data assignment as a tracker for static targets. Even thoughthe dataset provides only images with moderate resolution and includes regions with high variability, crowded scenes, and a high number of targets, the model is able to segment correctly most of the buildings and maintain their identities along the sequence with a 62% of Intersection over Union (IoU). The system is able to locate correctly the buildings in the image and to determine accurately their borders with the exception of those too close to each other. Most importantly, the system reacts well to changes, which is an important factor of concern for urban planning purposes. The tracker reaches a MOTA of 0.647 and a F-score of 0.805 on the testing set. This repository has been developed as a tutored research project of the University of Bordeaux, the Autonomous University of Madrid and the Pázmány Catholic Peter's University under MIT license.