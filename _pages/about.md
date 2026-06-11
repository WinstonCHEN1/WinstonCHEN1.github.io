---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# About Me

I am a third-year undergraduate student at Southwest University.

My research interests include:
- Retrieval-Augmented Generation*
- Large Language Models
- AI Safety
- Multi-Agent Systems

I am looking for a direct PhD offer; please feel free to contact me.

# News

- **2026.05** Started my internship at Tencent CSIG.
- **2026.01** One paper accepted to WWW 2026 Demo.
- **2025.11** One paper accepted to AAAI 2026.
- **2023.09** Started my Undergraduate at Southwest University.

# Selected Publications

{% assign selected_pubs = site.publications | reverse | limit: 5 %}
{% for post in selected_pubs %}
  {% include archive-single.html %}
{% endfor %}