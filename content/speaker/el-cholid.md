---
title: "El Muhammad C.H."
page_header_bg: "images/background/speaker.jpg"
date: 2020-03-14T15:40:24+06:00
designation: "IT Consultant"
image: "images/speakers/el-cholid-fix.png"
description: "This is a placeholder speaker."
draft: false
social:
- name: "linkedin"
  icon: "fa-linkedin"
  link: "https://www.linkedin.com/in/eltrovert/"

presentation_info:
  enable: false
  videoEnable: false
  videoUrl: ""
  slideEmbedPath: ""
  description: ""
  anotherPresentationEnable: false
  anotherPresentation:
    - title: None
      link: None

personal_info:
  enable : false
  title : "Personal Information"
  content : ""

skills:
  enable : false
  title : "Personal Skills"
  content : ""
  skillbars: []
---

#### Distributed Data + Training on Kubernetes: How We Use the Ray Stack at Scale

Building 3D scene reconstructions from 2D CCTV footage—like how autonomous vehicles perceive traffic environments—is no small feat, especially when you're a small team processing millions of videos. In this talk, I’ll share how we leverage the Ray ecosystem on Kubernetes to scale our AI development workflows for robotics and computer vision.

Our pipeline begins at the edge: videos are streamed into cloud storage, filtered through a preprocessing layer, and uploaded to a labeling platform for annotation. From there, we kick off intensive 3D reconstruction processes—generating keypoint annotations, vposer labels, and MCAP files for both 2D and 3D contexts. These outputs fuel downstream model development and training.

To handle this at scale, we run tens of thousands of RayJobs simultaneously for data prep and training. Using KubeRay, RayCluster, RayJob, RayData, and RayTrain, we orchestrate a distributed workflow that balances flexibility for experimentation with the raw throughput needed to process massive datasets efficiently.

This session is for ML engineers, MLOps practitioners, and platform teams interested in scaling complex, multi-stage AI pipelines—especially when compute is cheap, but orchestration isn’t.
