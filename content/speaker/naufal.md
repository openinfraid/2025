---
title: "Naufal Gholib Shiddiq"
page_header_bg: "images/background/speaker.jpg"
date: 2020-03-14T15:40:24+06:00
designation: "Cloud Engineer @Btech"
image: "images/speakers/naufal.jpg"
description: "This is a placeholder speaker."
draft: false
social:
- name: "linkedin"
  icon: "fa-linkedin"
  link: "https://www.linkedin.com/in/naufal-gholib-shiddiq/"

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

#### Enhancing Ceph Security: Encrypting OSDs with HashiCorp Vault Integration

Storage encryption di production environment memerlukan pendekatan yang lebih matang dari sekadar mengandalkan local encryption. Sesi ini akan membahas implementasi enkripsi Ceph OSD menggunakan HashiCorp Vault sebagai backend key management, memberikan alternatif yang lebih scalable dan secure.

Latar Belakang & Motivasi: 
Meskipun Juju charmed-ceph-osd menyediakan fitur otomatis untuk enkripsi OSD dengan Vault, memahami mekanisme di balik automation tersebut sangat penting untuk deployment production yang robust. Sesi ini menghadirkan implementasi manual step-by-step, memberikan 'full control' dan pemahaman lebih mendalam tentang arsitektur keamanan storage yang modern.

Yang Akan Dibahas: 
• Implementasi praktis - Manual setup Vault-backed encryption dari nol 
• Architecture comparison - Native Ceph encryption vs. centralized key management
• Performance analysis - Benchmark dan impact assessment 
• Production insights - Lessons learned dan best practices deployment 
• Operational considerations - Key rotation, disaster recovery, dan troubleshooting

Takeaway: Peserta akan mendapatkan gambaran mengenai step by step implementation, comparative analysis, dan practical knowledge untuk deploy secure Ceph storage dan bahkan use case nya bisa diterapkan diluar ceph environment.