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

Hi, I am currently a graduate student in the Institute of Computational Linguistics at <img class="intro-logo" style="width: 19px; padding-bottom: 5px;" src="/images/pku.png"> Peking University, advised by [Prof. Baobao Chang](https://scholar.google.com/citations?user=LaKNyhQAAAAJ). Before that, I earned my bachelor’s degree from <img class="intro-logo" style="width: 19px; padding-bottom: 5px;" src="/images/tju.png"> Tianjin University. I have had the privilege of collaborating with [Prof. Minjia Zhang](https://minjiazhang.github.io/) at the University of Illinois Urbana-Champaign, [Prof. Junjie Hu](https://junjiehu.github.io/) at the University of Wisconsin–Madison, and [Prof. Maosong Sun](https://scholar.google.com/citations?user=zIgT0HMAAAAJ) at Tsinghua University. I have also engaged in research projects supported by <img class="intro-logo" style="width: 19px; padding-bottom: 5px;" src="/images/Microsoft.png"> Microsoft Research Asia, gaining exposure to both academic and industrial AI research settings.

I am fortunate to have collaborated with researchers at <img class="intro-logo" style="width: 19px; padding-bottom: 5px;" src="/images/pku.png"> PKU, <img class="intro-logo" style="width: 19px; padding-bottom: 5px;" src="/images/uiuc.png"> UIUC, <img class="intro-logo" style="width: 19px; padding-bottom: 5px;" src="/images/wisc.png">Wisc, <img class="intro-logo" style="width: 19px; padding-bottom: 5px;" src="/images/thu.png"> THU, and <img class="intro-logo" style="width: 19px; padding-bottom: 5px;" src="/images/Microsoft.png"> Microsoft Research Asia.
[**Resume**](<PLACEHOLDER_RESUME_LINK>) [**Google Scholar**](https://scholar.google.com/citations?&user=skIXywUAAAAJ)

My research interests revolve around **Foundation Language Models**, **Multimodal Learning**, and **Data-centric AI**:

* **Data-centric Approaches**: Constructing and curating synthetic and structured data to enhance foundation model capabilities while reducing training costs.
* **Multimodal Integration**: Improving vision-language models through multimodal instruction tuning, alignment strategies, and reducing hallucinations.
<!-- * **Efficiency & Scalability**: Exploring techniques like cross-lingual distillation and selective data training to achieve improved performance with reduced resources, particularly for low-resource languages and long-context understanding. -->

<!-- **<font color="red">I am currently seeking Ph.D. positions for Fall 2025. If you know of any opportunities that align with my research interests, please feel free to reach out to me at <font color="blue">[📧]</font>. I would love to discuss potential collaborations or positions. Thank you!</font>**
 -->
My research interest includes neural machine translation and computer vision. I have published 8 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=skIXywUAAAAJ'>google scholar citations <a href='https://scholar.google.com/citations?user=skIXywUAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.


# 🔥 News
- *2024.09*: &nbsp;🎉🎉 Our paper, “UltraEdit: Instruction-based Fine-Grained Image Editing at Scale”, has been accepted by NeurIPS 2024!  

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='images/mmicl.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MMICL: Empowering vision-language model with multi-modal in-context learning](https://arxiv.org/abs/2309.07915)

**Haozhe Zhao**, Zefan Cai, Shuzheng Si, Xiaojian Ma, Kaikai An, Liang Chen, Zixuan Liu, Sheng Wang, Wenjuan Han, Baobao Chang

[**[paper]**](https://arxiv.org/pdf/2309.0791) [**[code]**](https://github.com/HaozheZhao/MIC) 
- The Twelfth International Conference on Learning Representations(ICLR), 2024.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/UltraEdit.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[UltraEdit: Instruction-based Fine-Grained Image Editing at Scale](https://arxiv.org/abs/2407.05282)

**Haozhe Zhao**, Xiaojian Ma, Liang Chen, Shuzheng Si, Rujie Wu, Kaikai An, Peiyu Yu, Minjia Zhang, Qing Li, Baobao Chang

[**[paper]**](https://arxiv.org/pdf/2407.05282) [**[code]**](https://ultra-editing.github.io/) 
- The Thirty-Eighth Annual Conference on Neural Information Processing Systems(NeurIPS), 2024.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NAACL 2024</div><img src='images/alsace.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Mitigating Language-Level Performance Disparity in mPLMs via Teacher Language Selection and Cross-lingual Self-Distillation](https://aclanthology.org/2024.naacl-long.160/)

**Haozhe Zhao**, Zefan Cai, Shuzheng Si, Liang Chen, Yufeng He, Kaikai An, Baobao Chang

[**[paper]**](https://aclanthology.org/2024.naacl-long.160/) [**[code]**](https://github.com/HaozheZhao/ALSACE) 
- 2024 Annual Conference of the North American Chapter of the Association for Computational Linguistics(NAACL), 2024.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024, Oral</div><img src='images/fastv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An image is worth 1/2 tokens after layer 2: Plug-and-play inference acceleration for large vision-language models](https://arxiv.org/abs/2403.06764)

Liang Chen, **Haozhe Zhao**, Tianyu Liu, Shuai Bai, Junyang Lin, Chang Zhou, Baobao Chang

[**[paper]**](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/10478.pdf) [**[code]**](https://github.com/pkunlp-icler/FastV) 
- The 18th European Conference on Computer Vision(ECCV), 2024, **Oral**.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">preprint</div><img src='images/lacing.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Looking Beyond Text: Reducing Language bias in Large Vision-Language Models via Multimodal Dual-Attention and Soft-Image Guidance](https://arxiv.org/abs/2411.14279)

**Haozhe Zhao**, Shuzheng Si, Liang Chen, Yichi Zhang, Maosong Sun, Mingjia Zhang, Baobao Chang

[**[paper]**](https://arxiv.org/pdf/2411.14279) [**[code]**](https://github.com/HaozheZhao/LACING) 
- The Twelfth International Conference on Learning Representations(ICLR), 2024.
</div>
</div>

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
 -->
# 📖 Educations
- *2022.09 - 2025.06 (Expected)*, M.S. in Software Engineering, Peking University. 
- *2018.09 - 2022.06*, Bachelor in Software Engineering, Tianjin University. 


<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
 -->
