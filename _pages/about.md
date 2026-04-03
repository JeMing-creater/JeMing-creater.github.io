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
I am Jiaming Liang. I am a first-year Ph.D student under the supervision of <a href='https://www2.scut.edu.cn/ft/2023/1201/c29779a527919/page.htm'> Prof. Hongmin Cai </a> at <a href='https://www.scut.edu.cn/new/'>South China University of Technology</a>. Before this, I completed my Master’s degree at <a href='https://www.gzhu.edu.cn/'>Guangzhou University</a>, and I had the honor of being mentored by <a href='https://people.ucas.ac.cn/~0058478'> Prof. Qiong Wang </a> and <a href='https://pangyan.me'> Assoc. Prof. Yan Pang </a> 

My research interests are primarily focused on medical image analysis and biomedical computing.

# 🔥 News
- *2026.3.29*: &nbsp;🎉🎉 A paper (Waveformer) has been accepted for <a href='https://pubmed.ncbi.nlm.nih.gov/41894215/'>IEEE Journal of Biomedical and Health Informatics (JBHI)</a>!
- *2025.11.11*: &nbsp;🎉🎉 A paper (MM-UNet) has been accepted for <a href='https://biod.whu.edu.cn/bibm2025/'>IEEE International Conference on Bioinformatics and Biomedicine (BIBM)</a>!
- *2025.08.25*: &nbsp;🎉🎉 A paper (Slim UNETRV2) has been accepted for <a href='https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=42'>IEEE Transactions on Medical Imaging</a>!


# 💫 Representative
<style>
.rep-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 18px;
  margin-top: 14px;
}

.rep-card {
  display: flex;
  align-items: stretch;
  min-height: 160px;
  text-decoration: none !important;
  border: 1px solid #e5e7eb;
  border-radius: 16px;
  overflow: hidden;
  background: #ffffff;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.06);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.rep-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.10);
}

/* 左侧文字：30% */
.rep-content {
  flex: 3;
  min-width: 0;
  padding: 16px 16px 16px 18px;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
}

/* 右侧图片：70% */
.rep-thumb {
  flex: 7;
  height: 160px;
  background: #f8fafc;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  padding: 10px;
  box-sizing: border-box;
}

.rep-thumb img {
  width: 100%;
  height: 100%;
  object-fit: contain;
  object-position: center;
  display: block;
}

/* 标题区域可滚动 */
.rep-title {
  width: 100%;
  max-height: 126px;
  overflow-y: auto;
  color: #111827;
  font-size: 0.98rem;
  font-weight: 700;
  line-height: 1.45;
  word-break: break-word;
  overflow-wrap: anywhere;
}

/* 手机端 */
@media (max-width: 640px) {
  .rep-grid {
    grid-template-columns: 1fr;
    gap: 14px;
  }

  .rep-card {
    min-height: 130px;
  }

  .rep-content {
    flex: 3;
    padding: 12px 12px 12px 14px;
  }

  .rep-thumb {
    flex: 7;
    height: 130px;
    padding: 8px;
  }

  .rep-title {
    font-size: 0.92rem;
    max-height: 104px;
    line-height: 1.4;
  }
}
</style>

<div class="rep-grid">

  <a class="rep-card" href="https://link.springer.com/chapter/10.1007/978-3-032-05141-7_27" target="_blank" rel="noopener noreferrer">
    <div class="rep-content">
      <div class="rep-title">
        Hwa-unetr: Hierarchical window aggregate unetr for 3d multimodal gastric lesion segmentation.
      </div>
    </div>
    <div class="rep-thumb">
      <img src="images/HWA.png" alt="HWA-UNETR">
    </div>
  </a>

  <a class="rep-card" href="https://ieeexplore.ieee.org/abstract/document/11138028/" target="_blank" rel="noopener noreferrer">
    <div class="rep-content">
      <div class="rep-title">
        Slim unetrv2: 3d image segmentation for resource-limited medical portable devices.
      </div>
    </div>
    <div class="rep-thumb">
      <img src="images/SlimV2.png" alt="Slim UNETRv2">
    </div>
  </a>

  <a class="rep-card" href="https://ieeexplore.ieee.org/abstract/document/11151753/" target="_blank" rel="noopener noreferrer">
    <div class="rep-content">
      <div class="rep-title">
        SegTom: a 3D volumetric medical image segmentation framework for thoracoabdominal multi-organ anatomical structures.
      </div>
    </div>
    <div class="rep-thumb">
      <img src="images/SegTom.png" alt="SegTom">
    </div>
  </a>

</div>

# 📝 Publications (by date)
- Liming Liang, Ting Kang, Yulin Li, **Jiaming Liang**, et al. "<font color= #699ce4>Waveformer: Dual-Branch Adaptive Network with Wavelet-Guided Cross-Context Decoding for Colorectal Polyp Segmentation.</font>" *IEEE journal of biomedical and health informatics*.

- Jiawen Liu, **Jiaming Liang (co-author)**, et al. "<font color= #699ce4>MM-UNet: Morph Mamba U-shaped Convolutional Networks for Retinal Vessel Segmentation.</font>" *IEEE International Conference on Bioinformatics and Biomedicine (BIBM)*.

- **Jiaming Liang**, et al. "<font color= #699ce4>Hwa-unetr: Hierarchical window aggregate unetr for 3d multimodal gastric lesion segmentation.</font>" *International Conference on Medical Image Computing and Computer-Assisted Intervention. Cham: Springer Nature Switzerland, 2025*.

- Yan Pang (Adviser), **Jiaming Liang**, et al. "<font color= #699ce4>Slim unetrv2: 3d image segmentation for resource-limited medical portable devices.</font>" *IEEE Transactions on Medical Imaging (2025)*.

- Yan Pang, Yunhao Li, **Jiaming Liang**, et al. "<font color= #699ce4>SegTom: a 3D volumetric medical image segmentation framework for thoracoabdominal multi-organ anatomical structures.</font>" *IEEE Journal of Biomedical and Health Informatics (2025)*.

- Yan Pang, Yunhao Li, Teng Huang, **Jiaming Liang**, et al. "<font color= #699ce4>Efficient breast lesion segmentation from ultrasound videos across multiple source-limited platforms.</font>" *IEEE Journal of Biomedical and Health Informatics (2025)*.

- Yan Pang, Yunhao Li, Teng Huang, **Jiaming Liang**, et al. "<font color= #699ce4>Online self-distillation and self-modeling for 3D brain tumor segmentation.</font>" *IEEE Journal of Biomedical and Health Informatics 29.12 (2025): 8965-8975*.

- **Jiaming Liang**, et al. "<font color= #699ce4>Comprehensive transformer integration network (ctin): Advancing endoscopic disease segmentation with hybrid transformer architecture.</font>" *Chinese Conference on Pattern Recognition and Computer Vision (PRCV). Singapore: Springer Nature Singapore, 2024**.

- Teng Huang, Yile Hong, Yan Pang, **Jiaming Liang**, et al. "<font color= #699ce4>AdaptFormer: An adaptive hierarchical semantic approach for change detection on remote sensing images.</font>" IEEE Transactions on Instrumentation and Measurement 73 (2024): 1-12*.

- Yan Pang (Adviser), **Jiaming Liang**, et al. "<font color= #699ce4>Slim UNETR: Scale hybrid transformers to efficient 3D medical image segmentation under limited computational resources.</font>" *IEEE transactions on medical imaging 43.3 (2023): 994-1005*.

- **Jiaming Liang**, et al. "<font color= #699ce4>GanNoise: Defending against black-box membership inference attacks by countering noise generation.</font>" *2023 International Conference on Data Security and Privacy Protection (DSPP). IEEE, 2023*.

- Bo Wei, Teng Huang, Xi Zhang, **Jiaming Liang**, et al. "<font color= #699ce4>CAM-PC: A novel method for camouflaging point clouds to counter adversarial deception in remote sensing.</font>" *IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing 17 (2023): 56-67*.

-  **Jiaming Liang**, et al. "<font color= #699ce4>Agilenet: A rapid and efficient breast lesion segmentation method for medical image analysis.</font>" *Chinese Conference on Pattern Recognition and Computer Vision (PRCV). Singapore: Springer Nature Singapore, 2023*.

- Teng Huang, Weiqing Kong, **Jiaming Liang**, et al. "<font color= #699ce4>Lightweight Multispectral Skeleton and Multi-stream Graph Attention Networks for Enhanced Action Prediction with Multiple Modalities.</font>" *Chinese Conference on Pattern Recognition and Computer Vision (PRCV). Singapore: Springer Nature Singapore, 2023*.

- Hongyang Yan, Anli Yan, Li Hu, **Jiaming Liang**, Haibo Hu. "<font color= #699ce4>MTL-leak: Privacy risk assessment in multi-task learning.</font>" *IEEE Transactions on Dependable and Secure Computing 21.1 (2023): 204-215*.




