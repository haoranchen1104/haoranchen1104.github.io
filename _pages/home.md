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

Education
======
* Bachelor of Engineering in Information Science, Huazhong University of Science and Technology, 2017-2021
  * GPA: 3.95/4.00 (rank: $$1^{st}$$); National Scholarship (2020)
* Master in Robotics, Systems and Control,  ETH Zürich, 2021-2024 (expected)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include pub-single-cv.html %}
  {% endfor %}</ul>

Internship
======
* Intern of computer vision and machine learning
  * ABB Research Center (Nov. 2022 - Apr. 2023)
  * Main focus: AI-empowered Smart Container Shipping