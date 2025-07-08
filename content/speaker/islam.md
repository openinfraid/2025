---
title: "Islam Nurul Yakin"
page_header_bg: "images/background/speaker.jpg"
date: 2020-03-14T15:40:24+06:00
designation: "DevOps Engineer @SEVIMA "
image: "images/speakers/islan.png"
description: "This is a placeholder speaker."
draft: false
social:
- name: "linkedin"
  icon: "fa-linkedin"
  link: "https://www.linkedin.com/in/islamnurulyakin/"

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

#### Efficient Logging Solutions with OpenTelemetry and ClickHouse

Materi ini membahas tentang penerapan sistem logging menggunakan OpenTelemetry dan ClickHouse, dengan fokus pada cara mengambil data log dari aplikasi atau file log langsung dan menyimpannya dalam database ClickHouse yang bersifat columnar. Penyimpanan log di ClickHouse memungkinkan efisiensi dalam menjalankan agregasi data, seperti sum atau average, dengan kecepatan yang lebih tinggi dibandingkan dengan metode penyimpanan row database seperti postgresql. Visualisasi data log menggunakan Grafana, yang merupakan tools yang umum digunakan.
Selain OpenTelemetry sebagai collector utama, materi ini juga mengenalkan Fluent Bit sebagai alternatif solusi pengumpulan log. Meskipun keduanya memiliki fitur untuk mengumpulkan log, OpenTelemetry lebih unggul karena selain bisa mengumpulkan log, OpenTelemetry juga supports pengumpulan metric dan tracing. ClickHouse juga memiliki fitur kompresi menggunakan metode seperti ZSTD untuk efisiensi penyimpanan dan pengolahan data dalam jumlah besar.
Pembahasan dalam sesi ini akan mencakup beberapa topik penting, yaitu:
1. Apa itu opentelemtry
2. Penjelasan tentang ClickHouse dan keunggulannya dalam penyimpanan data log.
3. Arsitektur sistem logging yang terintegrasi.
4. Proses integrasi antara OpenTelemetry dan ClickHouse.
Demo tentang pengambilan log dari file log NGINX dan penyimpanannya di ClickHouse.
