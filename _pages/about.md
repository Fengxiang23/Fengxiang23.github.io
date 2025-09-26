---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently pursuing the Ph.D. degree with the College of Computer Science and Technology, National University of Defense Technology, under the supervisor of Prof. Wenjing Yang and Prof. Long Lan. I also collaborate with [[Jing Zhang]](https://scholar.google.com/citations?user=9jH5v74AAAAJ&hl=zh-CN) and [[Bo Du]](https://scholar.google.com/citations?user=Shy1gnMAAAAJ&hl=zh-CN) in the remote sensing field. Any questions are welcome to contact me by wfx23@nudt.edu.cn.
 <a href='https://scholar.google.com/citations?user=WMkMTb4AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=引用"></a>。

<span class='anchor' id='-xl'></span>

# Research Highlights

- Multimodal Model Training: My research focuses on the training of advanced multimodal models, with a particular emphasis on high-resolution models such as SliME and omni-MLLMs, including the VITA series (Vita, Vita 1.5), general MLLMs including Long Vita, Kwai Keye-VL, Kwai Keye-VL 1.5, and Agentic MLLMs such as Thyme: Think Beyond Images projects.

- Model Evaluation: I contribute to multiple research initiatives aimed at enhancing the evaluation processes for large-scale models. This includes projects such as [[XLRS-Bench]](https://xlrs-bench.github.io/home_page.html) (CVPR 25 Highlight), [[OmniEarth-Bench]](https://github.com/nanocm/OmniEarth-Bench) (arXiv).

- Post-Training and Alignment for Multimodal Models: My work also includes the development of post-training techniques for multimodal models, such as MM-RLHF (ICML 25) and DAMO (ICML 25), along with R1-Reward and surveys of MLLM Alignment. These projects examine how to optimize model behavior after initial training to adapt to specific tasks and ensure responsible AI deployment.

- Applications of MLLMs: My research extends to applications of MLLMs in practical domains, including time-series data (ICML 2024), education (AAAI 25 AI Innovation in Application Award), and detection of low-quality short video (KDD 2025).


<span class='anchor' id='-lwzl'></span>


# 📝 Publications
### Conference
---
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurlPS 2025 Spotlight</div><img src='images/sensors2022.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

# 📝 Publications
### Conference & Journal
---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025 Highlights</div><img src='images/xlrs-bench.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `Fengxiang Wang`, H. Wang, Z. Guo, D. Wang, Y. Wang, M. Chen, ... & M. Sun. **XLRS-bench: Could your multimodal LLMs understand extremely large ultra-high-resolution remote sensing imagery?** *CVPR*, 2025. （CCF-A类会议, CVPR Highlights，前2.8%，共384篇）  
[[arXiv]](https://arxiv.org/abs/2503.23771) [[Dataset]](https://huggingface.co/datasets/initiacms/XLRS-Bench-lite) [[Code]](https://github.com/AI9Stars/XLRS-Bench)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/selectivemae.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `Fengxiang Wang`, H. Wang, D. Wang, Z. Guo, Z. Zhong, L. Lan, ... & J. Zhang. **Harnessing massive satellite imagery with efficient masked image modeling.** *ICCV*, 2025. (CCF-A类会议)  
[[arXiv]](https://arxiv.org/abs/2406.11933) [[Code]](https://github.com/MiliLab/SelectiveMAE)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/aaai24.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `Fengxiang Wang`, W. Huang, S. Yang, Q. Fan, & L. Lan. **Learning to learn better visual prompts.** *AAAI*, 2024. (CCF-A 类会议)  
[[Paper]](https://doi.org/10.1609/aaai.v38i6.28343) 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/geollava.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `Fengxiang Wang`, M. Chen, Y. Li, D. Wang, H. Wang, Z. Guo, ... & J. Zhang. **GeoLLaVA-8K: Scaling Remote-Sensing Multimodal Large Language Models to 8K Resolution.** *NeurIPS*, 2025. （CCF-A 类会议）  
[[Github]](https://github.com/MiliLab/GeoLLaVA-8K) [[arXiv]](https://arxiv.org/abs/2505.21375) [[Dataset]](https://huggingface.co/datasets/initiacms/GeoLLaVA-Data)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/roma.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `Fengxiang Wang`, H. Wang, Y. Wang, D. Wang, M. Chen, H. Zhao, ... & J. Zhang. **Roma: Scaling up mamba-based foundation models for remote sensing.** *NeurIPS*, 2025. （CCF-A 类会议）  
[[arXiv]](https://arxiv.org/abs/2503.10392) [[Code]](https://github.com/MiliLab/RoMA)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/omnibench.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `Fengxiang Wang`, M. Chen, X. He, Y. Zhang, F. Liu, Z. Guo, ... & L. Bai. **OmniEarth-Bench: Towards Holistic Evaluation of Earth'**
[[arXiv]](https://arxiv.org/abs/2505.23522) [[Code]](https://github.com/nanocm/OmniEarth-Bench)



### Journal
---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TGRS 2024</div><img src='images/tgrs24.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- L. Lan, `Fengxiang Wang*`, X. Zheng, Z. Wang, & X. Liu. **Efficient prompt tuning of large vision-language model for fine-grained ship classification.** *IEEE TGRS*, 2024. （中科院一区Top SCI，IF=8.6, 共同一作兼独立通讯）  
[[arXiv]](https://arxiv.org/abs/2403.08271)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">GISci 2024</div><img src='images/gis24.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `Fengxiang Wang`, D. Yu, L. Huang, Y. Zhang, Y. Chen, & Z. Wang. **Fine-grained ship image classification and detection based on a vision transformer and multi-grain feature vector FPN model.** *Geo-spatial Information Science*, 1–22, 2024. （中科院二区 SCI，IF=5.5, 国产期刊，李德仁院士为主编）  
[[Paper]](https://doi.org/10.1080/10095020.2024.2331552) 





<span class='anchor' id='-gzsx'></span>

# 💻 Work experience
- *2018.05 - 2020.02*, 重庆长江轴承股份有限公司, 重庆
- *2020.11.25 - 2020.12.02*, 湖北新冶钢有限公司, 湖北黄石
- *2017.6 - 2021.1*, 制造装备数字化国家工程研究中心, 湖北武汉



