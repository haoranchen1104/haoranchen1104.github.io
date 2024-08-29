---
permalink: /
title: "Homepage"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /home/
  - /home.html
---

{% include base_path %}

---

Hi, I am Haoran Chen, currently a research associate at <a href='http://generalroboticslab.com/'> General Robotics Lab</a> at Duke University, advised by Prof. <a href='http://boyuanchen.com/'>Boyuan Chen</a>.


Before that, I obtained my master degree (MS RSC) from ETH Zürich, where I mainly worked on 3D robot perception and scene understanding in <a href='https://asl.ethz.ch/'>Autonomous Systems Lab</a>, supervised by Prof. <a href='https://asl.ethz.ch/the-lab/people/person-detail.Mjk5ODE=.TGlzdC8yMDI4LDEyMDExMzk5Mjg=.html'>Roland Siegwart</a>. I had great pleasure doing research with Dr. <a href='https://keke.dev/'>Kenneth Blomqvist</a>, <a href='https://scholar.google.com/citations?user=qwSANZoAAAAJ&hl=it'>Francesco Milano</a> and Dr. <a href='https://schmluk.github.io/'>Lukas Schmid</a>. 

Prior to ETH Zürich, I graduated from <a href='https://english.hust.edu.cn/'>Huazhong University of Science and Technology</a> with BS EE, where I worked on ML in FPGA advised by Prof. Donghong Zuo, and robot design advised by Prof. Yujiang Zeng.

---
✨ news ✨

\[2024-07\] Joined General Robotics Lab at Duke University

\[2024-01\] "Panoptic Vision-Language Feature Fields" is accepted by _IEEE RAL_.

---

### Publication

  <ul>{% for post in site.publications reversed %}
    {% include pub-single-cv.html %}
  {% endfor %}</ul>

### Course Projects
<font size="1"><i>$^*$ denotes equal contribution.</i></font>

  <ul>{% for post in site.projects reversed %}
    {% include proj-single-cv.html %}
  {% endfor %}</ul>

### Internship

<ul>{% for post in site.internships reversed %}
    {% include proj-single-cv.html %}
  {% endfor %}</ul>

### Competitions
<font size="1"><i>$^*$ denotes equal contribution.</i></font>

<ul>{% for post in site.competitions reversed %}
    {% include proj-single-cv.html %}
  {% endfor %}</ul>