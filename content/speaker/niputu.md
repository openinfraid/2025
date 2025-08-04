---
title: "Ni Putu Sintia Wati"
page_header_bg: "images/background/speaker.jpg"
date: 2020-03-14T15:40:24+06:00
designation: "Infra Engineer @Zero One Group"
image: "images/speakers/niputu.jpeg"
description: "This is a placeholder speaker."
draft: false
social:
- name: "linkedin"
  icon: "fa-linkedin"
  link: "https://www.linkedin.com/in/putusintia/"
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
  slideEmbedPath: "/slides/OID25_Sintia.pdf" 
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

#### lesson learned: Things you should know before your first IaC setup

Mendapat tugas untuk setup Infrastructure as Code (IaC) di sebuah proyek seringkali terasa menegangkan—terutama jika menyangkut environment production. Meskipun setup awal dilakukan oleh rekan kerja, kita tetap harus siap jika suatu saat terjadi handover. Dalam sesi ini saya akan membagikan pengalaman pribadi saat pertama kali mengimplementasikan IaC menggunakan OpenTofu, mulai dari hal-hal yang harus diperhatikan seperti memahami dokumentasi, pemilihan cloud provider (karena beda provider, beda autentikasi), hingga manajemen state dari lokal ke remote seperti S3. Saya juga akan membahas pentingnya memahami service yang ingin dibuat (compute, network, database, dll), serta tips seperti penggunaan --target dan analisis plan sebelum melakukan perubahan.
