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

### Education

* Master in Robotics, Systems and Control,  ETH Zürich, 2021-2024 (expected)
* Bachelor of Engineering in Information Science, Huazhong University of Science and Technology, 2017-2021
  * GPA: 3.95/4.00 (rank: 1<font size="2"><sup>st</sup></font>); National Scholarship (2020)

### Publications

  <ul>{% for post in site.publications reversed %}
    {% include pub-single-cv.html %}
  {% endfor %}</ul>

### Course Projects
<font size="1"><i>$^*$ denotes equal contribution.</i></font>

  <ul>{% for post in site.projects reversed %}
    {% include proj-single-cv.html %}
  {% endfor %}</ul>

### Internship

* Intern of computer vision and machine learning
  * ABB Research Center (Nov. 2022 - Apr. 2023)
  * Main focus: AI-empowered Smart Container Shipping