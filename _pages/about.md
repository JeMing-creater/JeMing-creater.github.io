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
- *2025.01.18*: &nbsp;🎉🎉 A paper (MOD) is accepted by IEEE Journal of Biomedicaland Health Informatics!
- *2025.01.11*: &nbsp;🎉🎉 A paper (BaS) is accepted by IEEE Journal of Biomedicaland Health Informatics! 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JBHI 2025</div><img src='images/MOD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

🎉New!!!🎉[Online Self-distillation and Self-modeling for 3D Brain Tumor Segmentation]()

Yan Pang, Yunhao Li, Teng Huang\*, <a href='https://jeming-creater.github.io/'><strong>Jiaming Liang</strong></a>, Zhen Wang, Changyu Dong, Dongyang Kuang, Ying Hu, Hao Chen, Tim Lei, Qiong Wang\*

[**Project**](https://github.com/aigzhusmart/MOD) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>&nbsp; &nbsp; [**Journal (JCR Q1, IF 7.7)**](https://www.embs.org/jbhi/)<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- MOD is a plug-and-play component designed to enhance supervised learning models for brain tumor segmentation in data-scarce environments by integrating an Online Tokenizer and a Dense Predictor. These elements facilitate efficient representation learning through self-distillation and self-modeling on masked patches, promoting swift convergence. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JBHI 2025</div><img src='images/BaS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

🎉New!!!🎉[Efficient Breast Lesion Segmentation from Ultrasound Videos Across Multiple Source-limited Platforms]()

Yan Pang, Yunhao Li, Teng Huang\*, <a href='https://jeming-creater.github.io/'><strong>Jiaming Liang</strong></a>, Ziyu Ding, Hao Chen, Baoliang Zhao, Ying Hu, Zheng Zhang, Qiong Wang\*

[**Project**](https://github.com/aigzhusmart/BaS) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>&nbsp; &nbsp; [**Journal (JCR Q1, IF 7.7)**](https://www.embs.org/jbhi/)<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- BaS is an innovative, on-device breast lesion segmentation model designed for medical videos, integrating Stem module and BaSBlock to refine representations through inter- and intra-frame analysis, thus balancing segmentation performance and inference speed. This model surpasses existing top-performing models in efficiency and prediction accuracy on resource-limited devices by offering two versions, BaS-S for enhanced segmentation accuracy and BaS-L for faster inference times. 
</div>
</div>


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

[**Project**](https://github.com/aigzhusmart/AdaptFormer) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>&nbsp; &nbsp; [**Journal (JCR Q1, IF 5.6)**](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=19)<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- AdaptFormer is designed to adaptively interpret hierarchical semantics in remote sensing change detection, employing tailored strategies across three semantic depths to enhance the identification of environmental changes, from straightforward operations for shallow semantics to cascaded depthwise attention for in-depth semantics. This approach enables AdaptFormer to surpass leading benchmarks, achieving exceptional F1 and IoU scores of 92.65% and 86.31% on the LEVIR-CD dataset, and 97.59% and 95.29% on the DSIFN-CD dataset, respectively. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PRCV 2023</div><img src='images/AgileNet.png' alt="sym" width="100%"></div></div>
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

[**Project**](https://github.com/aigzhusmart/Slim-UNETR) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>&nbsp; &nbsp; [**Journal (JCR Q1, IF 10.6)**](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp/?punumber=42)<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- SlimUNETR is a lightweight 3D medical image segmentation model that achieves state-of-the-art performance on the BraTS2021 and other 3D lesion segmentation datasets, while also seeing a significant reduction in the number of parameters and floating-point computations. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">DDSP 2023</div><img src='images/GanNoise.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GanNoise: Defending against  black-box membership inference attacks by countering noise generation](https://ieeexplore.ieee.org/document/10405019)

<a href='https://jeming-creater.github.io/'><strong>Jiaming Liang</strong></a>, Teng Huang\*, Zidan Luo, Dan Li, Yunhao Li, Ziyu Ding

[**Conference paper (EI)**](https://dspp2023.xidian.edu.cn/)<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- GanNoise is a novel training framework designed to preserve privacy in deep learning models by generating noise that adds randomness to private data during training, thereby preventing excessive memorization of the actual training data while maintaining classification accuracy. This approach effectively defends against membership inference attacks without compromising model performance, outperforming existing advanced MIA defense solutions in terms of efficiency across various datasets.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JST-AEORS 2023</div><img src='images/Cam.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Cam-PC: A Novel Method for Camouflaging Point Clouds to Counter Adversarial Deception in Remote Sensing](https://ieeexplore.ieee.org/document/10285331)

Bo Wei, Teng Huang\*, Xi Zhang,  <a href='https://jeming-creater.github.io/'><strong>Jiaming Liang</strong></a>, Yunhao Li, Ziyu Ding, Cong Cao, Dan Li, Yongfeng Chen, Huagang Xiong, Feng Jiang, Xiqiu Zhang\*

[**Journal (JCR Q2, IF 4.7)**](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=4609443)<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- This article explores the increased privacy risks associated with multi-task learning (MTL) compared to traditional single-task learning, through the design of model extraction attacks (MEA) and membership inference attacks (MIA) in MTL. Evaluations across six MTL model architectures and two popular MTL datasets reveal that both the number of tasks and the complexity of training data significantly influence attack performance, demonstrating that MTL is more vulnerable to these attacks than single-task learning. This highlights the need for enhanced privacy measures in MTL frameworks.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TDSC 2022</div><img src='images/MTL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MTL-Leak: Privacy Risk Assessment in Multi-Task Learning](https://ieeexplore.ieee.org/document/10050399)

Hongyang Yan, Anli Yan, Li Hu,  <a href='https://jeming-creater.github.io/'><strong>Jiaming Liang</strong></a>, Haibo Hu\*

[**Journal (JCR Q2, IF 7.0)**](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=8858)<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- Multi-task learning (MTL) supports simultaneous training over multiple related tasks and learns the shared representation. While improving the generalization ability of training on a single task, MTL has higher privacy risk than traditional single-task learning because more sensitive information is extracted and learned in a correlated manner. Unfortunately, very few works have attempted to address the privacy risks posed by MTL. In this article, we first investigate such risk by designing model extraction attack (MEA) and membership inference attack (MIA) in MTL. Then we evaluate the privacy risks on six MTL model architectures and two popular MTL datasets, whose results show that both the number of tasks and the complexity of training data play an important role in the attack performance. Our investigation shows that MTL is more vulnerable than traditional single-task learning under both attacks.
</div>
</div>

# 📖 Educations
- *2021.09 - 2024.06*, Guangzhou University, Master of Computer Science. 
- *2017.09 - 2021.06*, Foshan University, Bachelor of Computer Science. 

