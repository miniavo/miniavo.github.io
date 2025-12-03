---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

🐳 About Me
=====
I am an undergraduate student at [Yonsei University](https://www.yonsei.ac.kr/sites/en_sc/index.do), majoring in Artificial Intelligence. Currently, I am an undergraduate researcher at [Computer Vision Lab (CVLAB)](https://cvlab.kaist.ac.kr/home), advised by Prof. Seungryong Kim. My research interests lie in the intersection of computer vision and machine learning, particulary in generative models, representation learning and multi-modal learning. I aim to develop intelligent systems that can understand, generate, and reason about visual and multi-modal data, bridging the gap between human-like perception and machine learning models.

---

🎓 Education
======
{% for edu in site.data.education %}
  {% include edu_item.html 
     logo=edu.logo
     title=edu.title
     degree=edu.degree
     period=edu.period
     coursework=edu.coursework %}
{% endfor %}

---

📑 Publication
=====
{% for pub in site.data.publications %}
  {% include publications.html 
      image=pub.image
      title=pub.title
      authors=pub.authors
      venue=pub.venue
      arxiv=pub.arxiv
      project=pub.project
  %}
{% endfor %}
---

💼 Experience
======
{% for exp in site.data.experience %}
  {% include experience.html 
     role=exp.role
     company=exp.company
     period=exp.period
     responsibilities=exp.responsibilities %}
{% endfor %}
---

🤖 Projects
======
{% include project.html %}

---

🎯 Extracurricular Activities
======
- **Yonsei Artificial Intelligence Club**
  - Member, Executive Member (2023.07 - Present)
  - Completed Standalone-DeepLearning course, gaining a comprehensive understanding of fundamental deep learning
concepts and core models
  - Reviewed and discussed various computer vision research papers with other club members

- **GDSC (Google Developer Students Clubs) Yonsei**
  - Front-End Member (2023.09 - 2024.07)
  - In-depth study in web browser’s functionality, rendering engine and web page optimization, along with other
advanced topics related to web development
  - Actively collaborated with developers from other teams within the club

---

🔎 Skills
======
{% include skill.html %}