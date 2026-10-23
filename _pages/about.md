---
permalink: /
title: "Zhiyuan Zhang (Holly)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

👋 Hi! I am a Ph.D. student in **Computer Science** at the **University of California, Los Angeles (UCLA)**, advised by [Prof. Jiaqi Ma](https://mobility-lab.seas.ucla.edu/about/) and [Prof. Yuan Tian](https://www.ytian.info/). Before UCLA, I obtained B.Sc. degree at [The Hong Kong Polytechnic University](https://www.polyu.edu.hk/).

My research focuses on **privacy-preserving large language models**, especially **differentially private retrieval-augmented generation (RAG)**, and on **human mobility modeling** from GPS trajectories with LLMs. I have also worked on **diffusion transformers** for synthetic trajectory generation.

<!-- # 🔥 News
{: .section-header #news}

{% include news.html %} -->

# 📝 Publications
{: .section-header #publications}

<!-- <p class="section-note">* equal contribution. See also my <a href="{{ site.author.googlescholar }}">Google Scholar</a> profile.</p> -->

{% assign selected_pubs = site.publications | where: "selected", true | sort: "date" | reverse %}
{% for post in selected_pubs %}
  {% include publication-card.html %}
{% endfor %}

# 🎓 Education
{: .section-header #education}

- **[University of California, Los Angeles (UCLA)](https://www.ucla.edu/)**<br>Ph.D. in Computer Science
- **[The Hong Kong Polytechnic University](https://www.polyu.edu.hk/)**<br>B.Sc. (Hons) Scheme in Computing
- **[Chalmers University of Technology](https://www.chalmers.se/en/)**, Sweden<br>Exchange
- **[University of Cambridge](https://www.cam.ac.uk/)**, United Kingdom<br>Summer School
{: .edu-list}

# 🏆 Honors and Awards
{: .section-header #honors}

- **2026** UCLA Doctoral Travel Grant
- **2024** Adlerbert Foreign Student Hospitality Foundation Scholarship, Chalmers University of Technology
- **2023/24** Wong Tit-shing Student Exchange Scholarship, HK PolyU
- **2023** Best GBA Solution, [Cathay Hackathon 2023]({{ base_path }}/portfolio/portfolio-1/)
- **2022/23** Dean's Honours List of Outstanding Students, HK PolyU
{: .dated-list}


# 💻 Teaching
{: .section-header #teach}

- **2026** TA of CEE 181/281 Traffic Engineering Systems, UCLA
- **2023** Volunteer Teacher of Heartfire, HK PolyU

<!-- # 🎶 Miscellaneous
- I am a musical enthusiast. I can sing all 46 songs of Broadway show Hamilton.  -->

<!-- {: .dated-list .skills-list} -->
<!-- # 💻 Skills
{: .section-header #skills}

- **Programming** Python, C++, Java, SQL, R, JavaScript, C
- **ML / AI** Transformers, Diffusion Models, Diffusion Transformers (DiT), Neural Operators, PyTorch, TensorFlow
- **LLM & Retrieval** Retrieval-Augmented Generation (RAG), Dense Passage Retrieval (DPR), LLM Evaluation
- **Deployment** 4-bit Quantization (Hugging Face), ONNX, TensorRT
{: .dated-list .skills-list} -->

<p class="last-updated">Last updated: {{ site.time | date: "%B %Y" }}</p>
