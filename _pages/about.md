---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am **Junteng Liu**, a first-year PhD candidate at the [HKUST NLP Group](https://hkust-nlp.github.io/), supervised by **Professor Junxian He**. I graduated from **Shanghai Jiao Tong University (SJTU)** in **June 2024**.

My research focuses on **natural language processing** and **machine learning**. I am particularly interested in:

- **LLM Reasoning and Reinforcement Learning**
- **Hallucination in Vision-Language Models (VLMs)**
- **LLM Truthfulness and Interpretability**

I enjoy studying how large language models reason, how to improve their reliability, and how to understand the internal representations behind their behaviors.

## Selected Publications

<ul>
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
</ul>

See the [publications page](/publications/) for the same mirrored publication list.
