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

Hi, I am currently a master student at ETH Zürich, working closely with <a href='https://asl.ethz.ch/'>Autonomous Systems Lab</a>. I am passionate about 3D scene reconstruction and understanding.
<br/><br/>
✨ news ✨

\[2024-01-01\] "Panoptic Vision-Language Feature Fields" is accepted by _IEEE Robotics and Automation Letters_.

---

### Education

* Master in Robotics, Systems and Control,  ETH Zürich, 2021-2024 (expected)
* Bachelor of Engineering in Information Science, Huazhong University of Science and Technology, 2017-2021
  * GPA: 3.95/4.00 (rank: 1<font size="2"><sup>st</sup></font>); National Scholarship (2020)

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