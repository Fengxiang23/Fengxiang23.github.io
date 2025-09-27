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

I am currently pursuing the Ph.D. degree with the College of Computer Science and Technology, National University of Defense Technology, under the supervisor of Prof. Wenjing Yang and Prof. Long Lan. I also collaborate with Prof. [[Jing Zhang]](https://scholar.google.com/citations?user=9jH5v74AAAAJ&hl=zh-CN) and Prof. [[Bo Du]](https://scholar.google.com/citations?user=Shy1gnMAAAAJ&hl=zh-CN) of Wuhan University in the remote sensing field. Any questions are welcome to contact me by wfx23@nudt.edu.cn.

MLLMs: I have carried out a series of works under the guidance of Professors [[Zhiyuan Liu]](https://scholar.google.com/citations?user=dT0v5u0AAAAJ&hl=en) and [[Maosong Sun]](https://scholar.google.com/citations?user=zIgT0HMAAAAJ&hl=en) from the THUNLP lab at Tsinghua University.

AI4S: my research has been conducted under the supervision of Professor [[Lei Bai]](https://scholar.google.com/citations?user=sakOO04AAAAJ&hl=en&oi=ao) and Dr. [[Wenlong Zhang]](https://scholar.google.com/citations?user=UnMImiUAAAAJ&hl=en) at Shanghai AI Lab.
 
<span class='anchor' id='-xl'></span>

# Research Highlights

- **MLLM Training**: My research focuses on the training of advanced multimodal models, with a particular emphasis on super-high-resolution models such as [GeoLLaVA-8k](https://github.com/MiliLab/GeoLLaVA-8K)  (**NeurlPS 25 Spotlight**).

- **MLLM Evaluation**: I contribute to multiple research initiatives aimed at enhancing the evaluation processes for large-scale models. This includes projects such as [XLRS-Bench](https://xlrs-bench.github.io/home_page.html) (**CVPR 25 Highlight**), [OmniEarth-Bench](https://github.com/nanocm/OmniEarth-Bench)(Arxiv), [SFE](https://github.com/PrismaX-Team/sfe)(**NeurlPS 25**).

- **Visual Foundation Model**: My research also focuses on the visual foundation models for remote sensing, such as [SelectiveMAE](https://github.com/MiliLab/SelectiveMAE) (**ICCV 25**) and [RoMA](https://github.com/MiliLab/RoMA) (**NeurlPS 25**).

- **Prompt Tuning of VLMs**: My work also includes the development of prompt tuning techniques for vision-language multimodal models, such as [LoL](https://ojs.aaai.org/index.php/AAAI/article/view/28343) (**AAAI 24**) and [RS-tuning](https://ieeexplore.ieee.org/abstract/document/10772151/) (**TGRS**).


<span class='anchor' id='-lwzl'></span>

# 🔥 News
- *2025.09:* 🎉Two papers are accepted by NeurlPS 2025, and GeoLLaVA-8K has been selected as **Spotlight**.

# 📝 Publications
### Conference

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025 Highlight</div><img src='images/xlrs-bench.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `Fengxiang Wang`, H. Wang, Z. Guo, D. Wang, Y. Wang,... Zhiyuan Liu & Maosong Sun. **XLRS-bench: Could your multimodal LLMs understand extremely large ultra-high-resolution remote sensing imagery?** *CVPR*, 2025. （CCF-A类会议, CVPR Highlight，前3%，共384篇）  
[[arXiv]](https://arxiv.org/abs/2503.23771) [[Dataset]](https://huggingface.co/datasets/initiacms/XLRS-Bench-lite) [[Code]](https://github.com/AI9Stars/XLRS-Bench)


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025 Spotlight</div><img src='images/geollava-8k.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `Fengxiang Wang`, M. Chen, Y. Li, D. Wang, H. Wang, ... Bo Du & Jing Zhang. **GeoLLaVA-8K: Scaling Remote-Sensing Multimodal Large Language Models to 8K Resolution.** *NeurIPS*, 2025. （CCF-A 类会议, NeurIPS Spotlight, 前3.1%, 共688篇）  
[[Github]](https://github.com/MiliLab/GeoLLaVA-8K) [[arXiv]](https://arxiv.org/abs/2505.21375) [[Dataset]](https://huggingface.co/datasets/initiacms/GeoLLaVA-Data)


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/roma.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `Fengxiang Wang`, H. Wang, Y. Wang, D. Wang, M. Chen, ... & J. Zhang. **RoMA: Scaling up mamba-based foundation models for remote sensing.** *NeurIPS*, 2025. （CCF-A 类会议）  
[[arXiv]](https://arxiv.org/abs/2503.10392) [[Code]](https://github.com/MiliLab/RoMA)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/selectivemae.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `Fengxiang Wang`, H. Wang, D. Wang, Z. Guo, Z. Zhong, ... & J. Zhang. **Harnessing massive satellite imagery with efficient masked image modeling.** *ICCV*, 2025. (CCF-A类会议)  
[[arXiv]](https://arxiv.org/abs/2406.11933) [[Code]](https://github.com/MiliLab/SelectiveMAE)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/aaai24.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `Fengxiang Wang`, W. Huang, S. Yang... & L. Lan. **Learning to learn better visual prompts.** *AAAI*, 2024. (CCF-A 类会议)  
[[Paper]](https://doi.org/10.1609/aaai.v38i6.28343) 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/omniearth.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `Fengxiang Wang`, M. Chen, X. He, Y. Zhang, F. Liu, ... & Lei Bai. **OmniEarth-Bench: Towards Holistic Evaluation of Earth's Six Spheres and Cross-Spheres Interactions with Multimodal Observational Earth Data.** *Arxiv*, 2025.  
[[arXiv]](https://arxiv.org/abs/2505.23522) [[Code]](https://github.com/nanocm/OmniEarth-Bench)

</div>
</div>


### Journal

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TGRS 2024</div><img src='images/tgrs24.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- L. Lan, `Fengxiang Wang*`, X. Zheng, Z. Wang, & X. Liu. **Efficient prompt tuning of large vision-language model for fine-grained ship classification.** *IEEE TGRS*, 2024. （SCI, 中科院一区Top，IF=8.6）  
[[arXiv]](https://arxiv.org/abs/2403.08271)


</div>
</div>


<span class='anchor' id='-gzsx'></span>

# 💻 Work experience
- *2023.11 - 2024.12*, working in THUNLP, guided by the Prof. Zhiyuan Liu and Prof. Maosong Sun.
- *2025.01 - 2025.10*, working in Shanghai AI Lab, AI for Science, guided by the Mentor Wenlong Zhang and Prof. Lei Bai.

















