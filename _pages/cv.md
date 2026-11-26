---
layout: archive
title: 'CV'
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Junteng Liu

First-year PhD candidate at HKUST NLP Group.

## Personal Details

- Name: Junteng Liu
- Current status: First-year PhD candidate at HKUST NLP Group
- Academic affiliation: Hong Kong University of Science and Technology
- Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- GitHub: [https://github.com/Vicent0205](https://github.com/Vicent0205)
- Google Scholar: [https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- X (Twitter): [@junteng88716710](https://twitter.com/junteng88716710)

## Education

- **Ph.D. in Computer Science (2024-Present)**, Hong Kong University of Science and Technology.
  - HKUST NLP Group.
  - Ph.D. supervisor: Professor Junxian He, who previously advised Junteng Liu during undergraduate studies at SJTU.
- **B.Eng. (2020-2024)**, Shanghai Jiao Tong University. Graduated in June 2024.

## Research Experience

- **Research Intern, MINIMAX** (February 2025 - Present)
- **Research Intern, Tencent WXG** (June 2024 - September 2024)
  - Advisor: Zifei Shan (Tencent WXG).
- **Research Intern, Shanghai AI Lab** (June 2023 - December 2023)
  - Advisor: Prof. Yu Cheng (Shanghai AI Lab).

## Skills and Research Interests

- Natural Language Processing
- Machine Learning
- LLM Reasoning and Reinforcement Learning
- Hallucination in Vision-Language Models (VLM)
- LLM Truthfulness and Interpretability

## Honors and Awards

- Zhiyuan Honor Scholarship, awarded by Shanghai Jiao Tong University.

## Publications

{% assign cv_publications = site.publications | sort: 'display_order' %}
<ol>
{% for publication in cv_publications %}
  <li>{{ publication.citation | markdownify }}</li>
{% endfor %}
</ol>

## Contact

- Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- GitHub: [Vicent0205](https://github.com/Vicent0205)
- Google Scholar: [Profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- X (Twitter): [@junteng88716710](https://twitter.com/junteng88716710)
