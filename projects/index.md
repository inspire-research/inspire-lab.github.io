---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

Our projects page showcases a diverse range of innovative research initiatives aimed at advancing AI, NLP, and intelligent systems. From enhancing search relevance with large language models to developing unbiased ranking systems, each project tackles real-world challenges with cutting-edge technology. Explore efforts in combating AI misinformation, personalizing user experiences through adaptive systems, leveraging graph theory for search optimization, and advancing digital security with AI forensics. These projects reflect our commitment to creating impactful, user-centric solutions that drive progress across various domains.

{% include tags.html tags="AI, retrieval, innovation, smart systems, personalization, misinformation, ethics, fairness, ranking, graphs, search, forensics, security" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
