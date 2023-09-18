---
title: "Profiling Dosen Pengajar"
date: 2023-09-18T07:44:00+07:00
authors: ['Zafran Marvis / CODENAME 300']
tags: ['xx1000']
draft: false
math: true
url: "0048"
---
{{< toc >}}

## Profile
![GAMBAR DOSEN](https://pengabdian.lppm.itb.ac.id/images/images_dosen/sparisoma%20viridi.png)
- **Nama :** Dr. rer. nat. Sparisoma Viridi, S.Si. 
- ** Pekerjaan: ** Ahli Nuklir, Engineer, Dosen

## YT
{{< youtube RZ1rSae0vqI >}}

## Diagram
{{< mermaid >}}
flowchart LR
	B --> P --> E
	B(("S1 ITB, Bandung - Indonesia"))
	P[/"S2 ITB, Bandung - Indonesia"/]
	E(("S3 Die Universitat Dortmund, Dortmund - Jerman"))
{{< /mermaid >}}


## table 
Nomor | Tingkat Pendidikan | Institusi | Tahun
:-: | :- | -: | :-:
1 | S1 (Fisika) | ITB | 1992 - 1998
2 | S2 (Fisika) | ITB | 1998 - 2001
3 | S3 (Fisika Granular) | Technische Universitat Dortmund | 2004 - 2007


## Source Data
+ [Research Gate](https://www.researchgate.net/profile/Sparisoma-Viridi)
+ [ITB](https://www.itb.ac.id/staf/profil/sparisoma-viridi)

## Animation with SVG
{{< html >}}
<svg width="200" height="200" xmlns="http://www.w3.org/2000/svg">
  <!-- Rectangle with animation -->
  <rect x="10" y="10" width="50" height="50" fill="blue">
    <animate attributeName="width" from="50" to="150" dur="2s" begin="0s" repeatCount="indefinite" />
    <animate attributeName="height" from="50" to="150" dur="2s" begin="0s" repeatCount="indefinite" />
    <animate attributeName="fill" values="blue;red;green;blue" dur="4s" begin="0s" repeatCount="indefinite" />
  </rect>
</svg>
{{< /html >}}

## Complex SVG with Styled Rect
{{< html >}}
<svg width="400" height="300" xmlns="http://www.w3.org/2000/svg">
  <!-- Rectangle with gradients -->
  <defs>
    <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:rgb(255,0,0);stop-opacity:1" />
      <stop offset="100%" style="stop-color:rgb(0,0,255);stop-opacity:1" />
    </linearGradient>
  </defs>

  <rect x="20" y="20" width="200" height="100" fill="url(#grad1)" stroke="green" stroke-width="3" />

  <!-- Text element -->
  <text x="30" y="160" font-family="Arial" font-size="24" fill="black">Complex SVG</text>

  <!-- Circle with animation -->
  <circle cx="250" cy="150" r="20" fill="orange">
    <animate attributeName="r" from="20" to="50" dur="2s" begin="0s" repeatCount="indefinite" />
  </circle>
</svg>
{{< /html >}}
