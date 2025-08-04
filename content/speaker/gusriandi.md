---
title: "Gusriandi"
page_header_bg: "images/background/speaker.jpg"
date: 2020-03-14T15:40:24+06:00
designation: "Cloud Engineer @Datacomm"
image: "images/speakers/gusriandi.png"
description: "This is a placeholder speaker."
draft: false
social:
- name: "linkedin"
  icon: "fa-linkedin"
  link: "https://www.linkedin.com/in/randifilan/"
- name: "facebook"
  icon: "fa-facebook"
  link: "#"
- name: "twitter"
  icon: "fa-twitter"
  link: "https://twitter.com/"
- name: "instagram"
  icon: "fa-instagram"
  link: "https://www.instagram.com/"

presentation_info:
  enable: true
  videoEnable: true
  videoUrl: "https://www.youtube.com/embed/"
  slideEmbedPath: "/slides/OID25_Gusriandi_OpenStack_Charm_without_MAAS.pdf" 
  anotherPresentationEnable: false

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

#### OpenStack Charm Deployment without Canonical MAAS for Testing & Small Deployment

OpenStack Charms are a collection of Charmed Operators used to deploy and manage enterprise grade OpenStack clouds using Canonical MAAS and Juju, simplifying the deployment and operations of OpenStack.

OpenStack charm required you to have i separated node for MAAS, Juju Controller and Deployer. It will have an issue if you just deploy for testing, or a small openstack deployment with a few Node.

This guide will show you how to Deploy OpenStack Charm without the need of Canonical MAAS and separated Juju controller for testing or small openstack cluster.

It will use the controller node for deployer, juju controller, and it running in LXD Container.
