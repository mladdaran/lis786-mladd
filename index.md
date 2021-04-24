---
title: Welcome to The UX Journey!
layout: page
description: LEARN. SHARE. CONNECT.
---
## **Hello there & welcome to my UX journey!**

The purpose of this website is to share my UX journey with you. I discovered the UX world my sophomore year of college, more specifically in the fall semester of the 2019-2020 school year. I took a class called INF 130 - Research and Design for Informatics. One can consider this class an intro class to UX. This class started off with learning concepts & methodologies in UX to producing an mobile app prototype on InVision. My partner & I created an app called Self Wind. We built this app prototype specifically for college students with focus on time management & self care habits. After taking that class, it has been life changing for me as I would love to pursue a career in UX.

**Checkout the final project my partner & I did for the INF 130 class!**

Self Wind Mobile App: [Google Drive Folder](https://drive.google.com/drive/folders/1KDjBvgNL-90V-HWfQKFecQ_WxXeZktib?usp=sharing)
- Self Wind App [Video](https://www.youtube.com/watch?v=DKGHDoKX1iw&t=1s)
- Self Wind App [Prototype](https://projects.invisionapp.com/prototype/ck37tw6d6003qel01e3sxl391/play)
- Self Wind [Slide Deck](https://drive.google.com/file/d/1ckfrvSx-cHvsaztGnpVGXufCcoqpmLYt/view?usp=sharing)
- Self Wind [Design Specification](https://drive.google.com/file/d/1iNyZE5q3RhSJxcDvp8n3dlMNscotHS5S/view?usp=sharing)

## **About Me**
**Hello there, I'm Monica!** I started my college journey at Dominican University in August 2018. Originally, I came to DU unsure of what I wanted to study and pursue as a career. I decided to play my first year safely by taking my gen ed courses to get those requirements out of the way. One day, I met my class/friend, Leslie, who introduced me to the informatics major. My first question to her was "What is Informatics?" She explained it to me as "It's sort of like computer science, but less programming and more focused on problem solving and dealing with people." At that instant, I was very intrigued and she caught my attention. As time went on, I took more informatics classes and eventually declared myself as an informatics major. I took one informatics class called INF 130: Research and Design for Informatics and taking this class has made me discover the UX field. In this class I learned about UX concepts and implementing those concepts into a half semester project where I worked with a partner and built an app prototype solving a real world problem.

## **Explore UX**
<p>Browse the topics below:</p>
{% for ux_resources in site.ux_resources %}
  <h2>{{ ux_resources.title }}</h2>
  <p>{{ ux_resources.content | strip_html | truncate: 400, '...' }}</p>
  <a href="{{ ux_resources.source }}" target="_blank">Source</a>
  {% endfor %}

### **<center>Thank you so much for visiting my website, happy exploring!!!</center>**
