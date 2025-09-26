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

- **MLLM Training**: My research focuses on the training of advanced multimodal models, with a particular emphasis on super-high-resolution models such as [GeoLLaVA-8k](https://github.com/MiliLab/GeoLLaVA-8K)  (**NeurlPS 25 Spotlight**).

- **MLLM Evaluation**: I contribute to multiple research initiatives aimed at enhancing the evaluation processes for large-scale models. This includes projects such as [XLRS-Bench](https://xlrs-bench.github.io/home_page.html) (**CVPR 25 Highlight**), [OmniEarth-Bench](https://github.com/nanocm/OmniEarth-Bench).

- **Visual Foundation Model**: My research also focuses on the visual foundation models for remote sensing, such as [SelectiveMAE](https://github.com/MiliLab/SelectiveMAE) (**ICCV 25**) and [RoMA](https://github.com/MiliLab/RoMA) (**NeurlPS 25**).

- **Prompt Tuning of VLMs**: My work also includes the development of prompt tuning techniques for vision-language multimodal models, such as [LoL](https://ojs.aaai.org/index.php/AAAI/article/view/28343) (**AAAI 24**) and [RS-tuning](https://ieeexplore.ieee.org/abstract/document/10772151/) (**TGRS**).


<span class='anchor' id='-lwzl'></span>

# 🔥 News
- *2025.09:* 🎉Two papers are accepted by NeurlPS 2025, and GeoLLaVA-8K has been selected as **Spotlight**.

# 📝 Publications
### Conference
---
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurlPS 2025 Spotlight</div><img src='images/sensors2022.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	`Fengxiang Wang`, Rongbiao Wang, Gongzhe Qiu, Yu Hu, Yihua Kang. Mechanism of magnetic flux leakage detection method based on the slotted ferromagnetic lift-off layer. *Sensors*, 2022, 22(9): 3587. (JCR:Q2; IF:3.847)  
[[Github]](https://github.com/MiliLab/GeoLLaVA-8K) [[Arxiv]](https://arxiv.org/abs/2505.21375) [[Dataset]](https://huggingface.co/datasets/initiacms/GeoLLaVA-Data)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Sens. Actuators Phys. 2021</div><img src='images/sna2021.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	`Jian Tang`, Rongbiao Wang, Bocheng Liu, Yihua Kang. A novel magnetic flux leakage method based on the ferromagnetic lift-off layer with through groove. *Sensors and Actuators A: Physical*. 2021: 113091. (JCR:Q1; IF:4.291)  
[[网页]](https://dx.doi.org/10.1016/j.sna.2021.113091) [[预览]](https://github.com/tangjyan/tangjyan.github.io/blob/main/pdf/TangJ-2021-A%20novel%20magnetic%20flux%20leakage%20method%20based%20on%20the%20ferromagnetic%20lift-off%20layer.pdf) [[下载]](/pdf/TangJ-2021-A%20novel%20magnetic%20flux%20leakage%20method%20based%20on%20the%20ferromagnetic%20lift-off%20layer.pdf)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Int. J. Appl. Electrom. 2020</div><img src='images/ijaem2020.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	`Jian Tang`, Rongbiao Wang, Jikai Zhang, Yihua Kang. The influence of magnetic head’s pose on magnetic flux leakage detection. *International Journal of Applied Electromagnetics and Mechanics*. 2020, 64(1–4): 493–500. (JCR:Q4; IF:0.536)  
[[网页]](https://dx.doi.org/10.3233/JAE-209356) [[预览]](https://github.com/tangjyan/tangjyan.github.io/blob/main/pdf/TangJ-2020-The%20influence%20of%20magnetic%20head%E2%80%99s%20pose%20on%20magnetic%20flux%20leakage%20detection.pdf) [[下载]](/pdf/TangJ-2020-The%20influence%20of%20magnetic%20head%E2%80%99s%20pose%20on%20magnetic%20flux%20leakage%20detection.pdf)



### Journal
---

- 	`唐健`，王荣彪，康宜华. 大提离漏磁无损检测方法. *无损检测*. 2022,44(4): 67. (核心期刊)  
[[网页]](https://dx.doi.org/10.11973/wsjc202204000) [[预览]](https://github.com/tangjyan/tangjyan.github.io/blob/main/pdf/%E5%94%90%E5%81%A5-2022-%E5%A4%A7%E6%8F%90%E7%A6%BB%E6%BC%8F%E7%A3%81%E6%97%A0%E6%8D%9F%E6%A3%80%E6%B5%8B%E6%96%B9%E6%B3%95.pdf) [[下载]](/pdf/%E5%94%90%E5%81%A5-2022-%E5%A4%A7%E6%8F%90%E7%A6%BB%E6%BC%8F%E7%A3%81%E6%97%A0%E6%8D%9F%E6%A3%80%E6%B5%8B%E6%96%B9%E6%B3%95.pdf)  




<span class='anchor' id='-gzsx'></span>

# 💻 Work experience
- *2018.05 - 2020.02*, 重庆长江轴承股份有限公司, 重庆
- *2020.11.25 - 2020.12.02*, 湖北新冶钢有限公司, 湖北黄石
- *2017.6 - 2021.1*, 制造装备数字化国家工程研究中心, 湖北武汉








