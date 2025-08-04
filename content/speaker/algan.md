---
title: "Ali Gandi"
page_header_bg: "images/background/speaker.jpg"
date: 2020-03-14T15:40:24+06:00
designation: "IT Manager @Awan Data Semesta"
image: "images/speakers/algan.png"
description: "This is a placeholder speaker."
draft: false
social:
- name: "linkedin"
  icon: "fa-linkedin"
  link: "https://www.linkedin.com/in/ali-gandi-b4bb46a1/"
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
  videoUrl: "https://www.youtube.com/embed/AzMdFsH0zyQ?si=8IZgBd_FD1nM6tTV"
  slideEmbedPath: "/slides/Ali_Gandi_OID25_CephFS_Pool_Resize_on_PVE.pdf" 
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

#### CephFS Pool Resize on Promox Virtual Environment

Proxmox Virtual Environment (PVE) merupakan platform virtualisasi berbasis open-source yang mendukung integrasi dengan Ceph sebagai distributed storage. Dalam implementasinya, CephFS digunakan sebagai shared filesystem yang fleksibel untuk kebutuhan penyimpanan VM dan container. Namun, dinamika kebutuhan ruang penyimpanan memerlukan mekanisme penyesuaian kapasitas (resize) pada CephFS pool agar tetap optimal dan efisien. Proposal ini membahas proses teknis resize CephFS pool pada cluster Proxmox, mencakup analisis kondisi eksisting, metode penyesuaian kapasitas secara aman, hingga evaluasi performa pasca resize. Tujuan utama dari studi ini adalah untuk meningkatkan efisiensi pemanfaatan storage serta memastikan kestabilan layanan virtualisasi yang berjalan di atas infrastruktur Ceph–Proxmox.
