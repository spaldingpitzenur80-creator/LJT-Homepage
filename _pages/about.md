---
permalink: /
title: "Junteng Liu"
author_profile: true
---

I am a first-year Ph.D. candidate at the HKUST NLP Group. My research focuses on natural language processing and machine learning.

Research Interests
======
* LLM Reasoning and Reinforcement Learning
* Hallucination in Vision-Language Models (VLM)
* LLM Truthfulness and Interpretability

Academic Background
======
* Ph.D. in Computer Science (2024 - Present), Hong Kong University of Science and Technology
  * First-year Ph.D. candidate at HKUST NLP Group
* B.Eng. (2020 - 2024), Shanghai Jiao Tong University

Research Experience
======
* Research Intern, MINIMAX (February 2025 - Present)
* Research Intern, Tencent WXG (June 2024 - September 2024)
  * Advisor: Zifei Shan
* Research Intern, Shanghai AI Lab (June 2023 - December 2023)
  * Advisor: Prof. Yu Cheng

Publications
======
* My publications are also available on my [Google Scholar profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate).

{% include base_path %}

<ul>
  {% for post in site.publications reversed %}
    <li>
      <p><b>{{ post.title }}</b><br />
      {% if post.excerpt %}{{ post.excerpt }}<br />{% endif %}
      <i>{{ post.venue }}</i>, {{ post.date | date: "%Y" }}
      {% if post.paperurl %} &middot; <a href="{{ post.paperurl }}">Code</a>{% endif %}
      </p>
    </li>
  {% endfor %}
</ul>

* My first-author publications are marked with a <b>bold</b> title.

Awards
======
* Zhiyuan Honor Scholarship, awarded by Shanghai Jiao Tong University

Contact
======
* Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
* GitHub: [Vicent0205](https://github.com/Vicent0205)
* Google Scholar: [profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
* X (Twitter): [@junteng88716710](https://twitter.com/junteng88716710)
