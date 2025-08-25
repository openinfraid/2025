---
title: "Ananda Fikri I.A"
page_header_bg: "images/background/speaker.jpg"
date: 2020-03-14T15:40:24+06:00
designation: "DevOps Engineer @i3"
image: "images/speakers/anandafik.png"
description: "This is a placeholder speaker."
draft: false
social:
- name: "linkedin"
  icon: "fa-linkedin"
  link: "https://www.linkedin.com/in/ananda-fikri"
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
  videoUrl: "https://www.youtube.com/embed/ntaqIUMu53g?si=9qoEdAHdLO3WRb9N"
  slideEmbedPath: "/slides/OID25_THE_DARK_SIDE_OF_DEVSECOPS_GHOST_IN_THE_DEPLOYMENT_PROCESS.pdf" 
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

#### The Dark Side of DevSecOps: Ghost in the Deployment Process

DevSecOps telah menjadi paradigma utama dalam mengintegrasikan keamanan ke dalam proses software delivery and deployment. Namun, implementasinya sering terjebak dalam pola pikir berbasis compliance, dimana otomasi keamanan dilakukan secara dangkal dan berorientasi alat, tanpa pemahaman mendalam terhadap konteks serta pemodelan ancaman. Pembahasan ini akan berfokus pada gambaran investigasi titik-titik lemah yang sering terabaikan dalam pipeline CI/CD dan bagaimana pelaku ancaman mengeksploitasinya, baik dalam pendekatan shift-left maupun shift-right.

Konsep “GHOST IN THE DEPLOYMENT PROCESS” menjadi gambaran ancaman tersembunyi pasca-deploy, seperti poisoned dependencies, misconfigured application, atau trojanized build artifacts. Dalam hal ini, perlu dipelajari konsep kerangka kerja otomasi keamanan yang komprehensif dan dapat diterapkan, yang menggabungkan analisis statis dan dinamis, intelijen ancaman, serta inspeksi malware pada level biner. Kerangka ini memanfaatkan alat open-source seperti Trivy, Semgrep, Checkov, Renovate, Dependabot, OWASP ZAP, dan lain sebagainya.

Melalui ilustrasi simulasi serangan terhadap pipeline DevSecOps akan ditunjukkan bagaimana pendekatan ini mendeteksi jenis-jenis proses ancaman sebelum mencapai prduction. Pembahasan ini menekankan bahwa kematangan DevSecOps bukan terletak pada seberapa mahal atau banyaknya alat yang digunakan, melainkan pada proses alur integrasi wawasan ofensif ke dalam otomasi defensif yang adaptif.

