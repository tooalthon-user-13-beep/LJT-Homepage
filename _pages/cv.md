---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

**Junteng Liu**
Email: jliugi@connect.ust.hk | GitHub: [Vicent0205](https://github.com/Vicent0205) | [Google Scholar](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ)

**Education**
=======

* Ph.D. in Computer Science, Hong Kong University of Science and Technology (HKUST), 2024-Present
  * NLP Group, supervised by [Professor Junxian He](https://www.linkedin.com/in/junxianhe/)

* B.Eng. in Computer Science, Shanghai Jiao Tong University (SJTU), 2020-2024
  * Zhiyuan Honor Scholarship recipient

**Research Experience**
=======

* Research Intern, MINIMAX, *February 2025 - Present*

* Research Intern, Tencent WXG, *June 2024 - September 2024*
  * Advisor: Zifei Shan

* Research Intern, Shanghai AI Lab, *June 2023 - December 2023*
  * Advisor: Prof. Yu Cheng

**Publications**
=======

*Junteng Liu is the first author on the following publications:*

<ul>
  {% for post in site.publications reversed %}
    {% if post.authors contains 'Junteng Liu' %}
      <li>{% include archive-single-cv.html %}</li>
    {% endif %}
  {% endfor %}
</ul>

*Co-authored publications:*

<ul>
  {% for post in site.publications reversed %}
    {% if post.authors contains 'Liu,' and post.authors contains 'Junteng' != true %}
      {% unless post.authors contains 'Junteng' %}
        <li>{% include archive-single-cv.html %}</li>
      {% endunless %}
    {% endif %}
  {% endfor %}
</ul>

**Skills**
=======

* **Programming Languages**: Python, C++, Java
* **Deep Learning Frameworks**: PyTorch, TensorFlow
* **NLP**: LLM fine-tuning, RLHF, NER, summarization, translation
* **ML**: Supervised and unsupervised learning, reinforcement learning
* **Tools**: Git, Docker, LaTeX, Linux

**Research Interests**
=======

* Large Language Model Reasoning and Reinforcement Learning
* Hallucination in Vision-Language Models (VLM)
* LLM Truthfulness and Interpretability

**Service and Leadership**
=======

* Peer reviewer for ICML, NeurIPS, EMNLP, ACL, and AAAI conferences
* Teaching assistant for CS courses at HKUST and SJTU
* Campus ambassador for SJTU alumni activities

**Contact**
=======

* jliugi@connect.ust.hk
* [GitHub](https://github.com/Vicent0205)
* [Google Scholar](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ)
* [Twitter/X](https://twitter.com/junteng88716710)
