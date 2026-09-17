---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
published: true
redirect_from:
  - /resume
---

## Personal profile

**Junteng Liu** — Ph.D. candidate in Computer Science at the Hong Kong University of Science and Technology (HKUST), working with Professor Junxian He in the HKUST NLP Group. My research focuses on natural language processing and machine learning.

## Education

- **Ph.D. in Computer Science**, Hong Kong University of Science and Technology, 2024–Present. Advisor: Professor Junxian He.
- **B.Eng.**, Shanghai Jiao Tong University, 2020–2024. Graduated June 2024. Professor Junxian He also advised me during my undergraduate studies.

## Research interests

- LLM reasoning and reinforcement learning
- Hallucination in vision-language models (VLMs)
- LLM truthfulness and interpretability

## Research experience

- **Research Intern, MINIMAX**, February 2025–Present.
- **Research Intern, Tencent WXG**, June–September 2024. Advisor: Zifei Shan.
- **Research Intern, Shanghai AI Lab**, June–December 2023. Advisor: Professor Yu Cheng.

## Skills and research focus

The following describe my research areas rather than a list of software proficiencies:

- Natural language processing
- Machine learning
- Large language model reasoning and reinforcement learning
- Vision-language model hallucination and chart understanding
- Large language model truthfulness and interpretability

<!-- Memory does not specify programming languages, frameworks, tools, or proficiency levels. Do not infer them from publications. -->

## Honors

- Zhiyuan Honor Scholarship, Shanghai Jiao Tong University.

## Publications

{% for paper in site.data.personal_publications %}
- **{{ paper.title }}**. {{ paper.authors }}. *{{ paper.venue }}*, {{ paper.year }}.{% if paper.first_author %} **First author.**{% endif %}
{% endfor %}

[View the publications page]({{ '/publications/' | relative_url }}).

## Contact and profiles

- Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- GitHub: [Vicent0205](https://github.com/Vicent0205)
- [Google Scholar](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- X / Twitter: [@junteng88716710](https://x.com/junteng88716710)
