---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
### 2025

- **K. Rifa, J. Zhang, A. Imran**, “Swin-KAT: Advancing Swin Transformer with Kolmogorov-Arnold network for CT image quality assessment,” *IEEE International Symposium on Biomedical Imaging (ISBI), 2025*.  
  [Paper](#) | [Code](#) | [ArXiv](#)  

- **K. Rifa, M. Ahamed, J. Zhang, A. Imran**, “Task-focused knowledge transfer from natural images for CT image quality assessment,” *SPIE Medical Imaging: Image Perception, Observer Performance, and Technology Assessment, 2025*.  
  [Paper](#) | [Code](#) | [ArXiv](#)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
