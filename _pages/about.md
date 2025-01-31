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

# 😊 About Me
<span class='anchor' id='about-me'></span>
I am Jiaming Liang. I am currently working as a research assistant at SCUT and will further my studies here as a first-year PhD student under the supervision of <a href='https://www2.scut.edu.cn/ft/2023/1201/c29779a527919/page.htm'> Prof. Hongmin Cai </a>. Before this, I completed my Master’s degree at Guangzhou University, and I had the honor of being mentored by <a href='https://people.ucas.ac.cn/~0058478'> Prof. Qiong Wang </a> and <a href='https://pangyan.me'> Assoc. Prof. Yan Pang </a> 

My research interests are primarily focused on medical image processing and biomedical computing.


# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PRCV 2024</div><img src='images/CTIN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Comprehensive Transformer Integration Network (CTIN): Advancing Endoscopic Disease Segmentation with Hybrid Transformer Architecture](https://link.springer.com/chapter/10.1007/978-981-97-8499-8_15)

<a href='https://jeming-creater.github.io/'><strong>Jiaming Liang</strong></a>, Mingdu Zhang, Caiyan Tan, Teng Huang, Xi Zhang, Zheng Zhang\*, Shegan Gao, Qian Sheng\*, Yan Pang\*

[**Conference paper (CCF-C)**](https://cvpr.thecvf.com/Conferences/2024)<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- CTIN, leveraging Transformer's strengths and introducing a Global Local Fusion Extractor module, enhances the precision of endoscopic image segmentation by preserving boundary details and accurately localizing objects, thus demonstrating superior performance and robustness in challenging scenarios. This approach addresses the limitations of existing models in capturing complex boundaries and small objects, achieving state-of-the-art results on various metrics. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PRCV 2024</div><img src='images/LMS-GAT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Lightweight Multispectral Skeleton and Multi-stream Graph Attention Networks for Enhanced Action Prediction with Multiple Modalities](https://link.springer.com/chapter/10.1007/978-981-99-8429-9_6)

Teng Huang\*, Weiqing Kong, <a href='https://jeming-creater.github.io/'><strong>Jiaming Liang</strong></a>, Ziyu Ding, Hui Li, Xi Zhang\*
[**Conference paper (CCF-C)**](https://cvpr.thecvf.com/Conferences/2024)<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- LMS-GAT introduces a novel approach to human action recognition by facilitating information exchange through node concentration and diffusion across structural and temporal dimensions, selectively suppressing and reinstating structural node representations for specific actions ,and utilizing hierarchical shifted temporal windows to assess temporal information. This method effectively addresses dynamic changes during action transitions, outperforming state-of-the-art methods in prediction accuracy on the NTU RGB+D 60 and 120 datasets, thus highlighting its improved efficacy in capturing and recognizing human actions.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIM 2024</div><img src='images/AdaptFormer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AdaptFormer: An Adaptive Hierarchical Semantic Approach for Change Detection on Remote Sensing Images](https://ieeexplore.ieee.org/document/10497147)

Teng Huang, Yile Hong, Yan Pang, <a href='https://jeming-creater.github.io/'><strong>Jiaming Liang</strong></a>, Jie Hong, Lin Huang, Yuan Zhang, Yan Jia, Patrizia Savi

[**Project**](https://github.com/aigzhusmart/AdaptFormer) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>   [**Journal (JCR Q1, IF 5.6)**](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=19)<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- AdaptFormer is designed to adaptively interpret hierarchical semantics in remote sensing change detection, employing tailored strategies across three semantic depths to enhance the identification of environmental changes, from straightforward operations for shallow semantics to cascaded depthwise attention for in-depth semantics. This approach enables AdaptFormer to surpass leading benchmarks, achieving exceptional F1 and IoU scores of 92.65% and 86.31% on the LEVIR-CD dataset, and 97.59% and 95.29% on the DSIFN-CD dataset, respectively. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PRCV 2023</div><img src='images/LMS-GAT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AgileNet: A Rapid and Efficient Breast Lesion Segmentation Method for Medical Image Analysis](https://link.springer.com/chapter/10.1007/978-981-99-8469-5_33)

<a href='https://jeming-creater.github.io/'><strong>Jiaming Liang</strong></a>, Teng Huang\*, Dan Li, Ziyu Ding, Yunhao Li, Lin Huang, Qiong Wang, Xi Zhang\*
[**Conference paper (CCF-C)**](https://cvpr.thecvf.com/Conferences/2023)<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- AgileNet is an efficient lesion segmentation model that balances accuracy and efficiency by combining the strengths of convolutional neural networks and transformers, utilizing an Agile block for cost-effective information exchange that incorporates both global and local contexts. Demonstrating superior performance in terms of accuracy, model size, and throughput on resource-constrained devices, AgileNet offers a promising solution for accurate and efficient medical image segmentation in such settings.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMI 2023</div><img src='images/SlimUNETR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Slim UNETR: Scale Hybrid Transformers to Efficient 3D Medical Image Segmentation Under Limited Computational Resources](https://ieeexplore.ieee.org/abstract/document/10288609/)

Yan Pang (Adviser), <a href='https://jeming-creater.github.io/'><strong>Jiaming Liang</strong></a>, Teng Huang\*, Hao Chen, Yunhao Li, Dan Li, Lin Huang, Qiong Wang\*

[**Project**](https://github.com/aigzhusmart/Slim-UNETR) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>   [**Journal (JCR Q1, IF 10.6)**](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp/?punumber=42)<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- SlimUNETR is a lightweight 3D medical image segmentation model that achieves state-of-the-art performance on the BraTS2021 and other 3D lesion segmentation datasets, while also seeing a significant reduction in the number of parameters and floating-point computations. 
</div>
</div>


# 📖 Educations
- *2021.09 - 2024.06*, Guangzhou University, Master of Computer Science. 
- *2017.09 - 2021.06*, Foshan University, Bachelor of Computer Science. 

