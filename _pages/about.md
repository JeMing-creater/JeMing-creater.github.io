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
  grid-template-columns: 1fr;
  gap: 18px;
  margin-top: 14px;
}

.rep-card {
  display: flex;
  align-items: stretch;
  min-height: 170px;
  border: 1px solid #e5e7eb;
  border-radius: 18px;
  overflow: hidden;
  background: #ffffff;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.06);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.rep-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.10);
}

/* 左侧文本区：30% */
.rep-content {
  flex: 3;
  min-width: 0;
  padding: 14px 12px 14px 16px;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
}

/* 文本内层：只允许纵向滚动 */
.rep-textbox {
  width: 100%;
  height: 100%;
  max-height: 140px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 10px;
  overflow-y: auto;
  overflow-x: hidden;
  min-width: 0;
}

/* 小铭牌行 */
.rep-badge-row {
  width: 100%;
  display: flex;
  justify-content: flex-start;
  align-items: center;
  flex: 0 0 auto;
  overflow: visible;
  min-width: 0;
}

/* 铭牌：始终完整露出，必要时缩小 */
.rep-badge {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: fit-content;
  max-width: 50%;
  min-width: 0;
  box-sizing: border-box;
  height: 20px;
  padding: 0 0.5em;
  border-radius: 999px;
  font-size: clamp(0.5rem, 0.9vw, 0.68rem);
  font-weight: 700;
  line-height: 1;
  letter-spacing: 0;
  color: #4b5563;
  text-decoration: none !important;
  border: 1px solid #d6d9de;
  background:
    linear-gradient(180deg, rgba(255,255,255,0.72) 0%, rgba(255,255,255,0.18) 35%, rgba(0,0,0,0.02) 100%),
    #eceff3;
  box-shadow:
    inset 0 1px 0 rgba(255,255,255,0.85),
    0 1px 2px rgba(0,0,0,0.05);
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  flex-shrink: 1;
}

/* 标题链接 */
.rep-title {
  display: block;
  width: 100%;
  min-width: 0;
  text-decoration: none !important;
  color: #111827;
  line-height: 1.08;
  overflow-x: hidden;
  overflow-y: visible;
}

/* 缩写：尽量不换行，自适应缩放 */
.rep-title-main {
  display: block;
  width: 100%;
  min-width: 0;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  font-size: clamp(0.95rem, 1.9vw, 1.28rem);
  font-weight: 800;
  letter-spacing: -0.01em;
  color: #111827;
}

/* 副标题：为缩写字号的一半 */
.rep-title-sub {
  display: block;
  margin-top: 6px;
  font-size: 0.5em;
  font-weight: 700;
  line-height: 1.35;
  color: #374151;
  word-break: break-word;
  overflow-wrap: anywhere;
  white-space: normal;
}

/* 右侧图片区：70% */
.rep-thumb-link {
  flex: 7;
  height: 170px;
  background: #f8fafc;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  padding: 10px;
  box-sizing: border-box;
  text-decoration: none !important;
}

.rep-thumb-link img {
  width: 100%;
  height: 100%;
  object-fit: contain;
  object-position: center;
  display: block;
  border: 0;
}

/* 手机端 */
@media (max-width: 640px) {
  .rep-grid {
    gap: 14px;
  }

  .rep-card {
    min-height: 140px;
  }

  .rep-content {
    flex: 3;
    padding: 12px 10px 12px 12px;
  }

  .rep-textbox {
    max-height: 114px;
    gap: 8px;
  }

  .rep-badge {
    max-width: 52%;
    height: 18px;
    padding: 0 0.42em;
    font-size: clamp(0.46rem, 1.8vw, 0.6rem);
  }

  .rep-title-main {
    font-size: clamp(0.84rem, 3vw, 1.02rem);
  }

  .rep-thumb-link {
    flex: 7;
    height: 140px;
    padding: 8px;
  }
}
</style>

<div class="rep-grid">

  <div class="rep-card">
    <div class="rep-content">
      <div class="rep-textbox">
        <div class="rep-badge-row">
          <a class="rep-badge" href="https://conferences.miccai.org/2025/en/default.asp" target="_blank" rel="noopener noreferrer">MICCAI</a>
        </div>
        <a class="rep-title" href="https://link.springer.com/chapter/10.1007/978-3-032-05141-7_27" target="_blank" rel="noopener noreferrer">
          <span class="rep-title-main">HWA-UNETR</span>
          <span class="rep-title-sub">Hierarchical Window Aggregate UNETR for 3D Multimodal Gastric Lesion Segmentation</span>
        </a>
      </div>
    </div>
    <a class="rep-thumb-link" href="https://link.springer.com/chapter/10.1007/978-3-032-05141-7_27" target="_blank" rel="noopener noreferrer">
      <img src="/images/HWA.png" alt="HWA-UNETR">
    </a>
  </div>

  <div class="rep-card">
    <div class="rep-content">
      <div class="rep-textbox">
        <div class="rep-badge-row">
          <a class="rep-badge" href="https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=42" target="_blank" rel="noopener noreferrer">TMI</a>
        </div>
        <a class="rep-title" href="https://ieeexplore.ieee.org/abstract/document/11138028/" target="_blank" rel="noopener noreferrer">
          <span class="rep-title-main">SlimUNETRv2</span>
          <span class="rep-title-sub">3D Image Segmentation for Resource-Limited Medical Portable Devices</span>
        </a>
      </div>
    </div>
    <a class="rep-thumb-link" href="https://ieeexplore.ieee.org/abstract/document/11138028/" target="_blank" rel="noopener noreferrer">
      <img src="/images/SlimV2.png" alt="SlimUNETRv2">
    </a>
  </div>

  <div class="rep-card">
    <div class="rep-content">
      <div class="rep-textbox">
        <div class="rep-badge-row">
          <a class="rep-badge" href="https://www.embs.org/jbhi/" target="_blank" rel="noopener noreferrer">JBHI</a>
        </div>
        <a class="rep-title" href="https://ieeexplore.ieee.org/abstract/document/11151753/" target="_blank" rel="noopener noreferrer">
          <span class="rep-title-main">SegTom</span>
          <span class="rep-title-sub">A 3D Volumetric Medical Image Segmentation Framework for Thoracoabdominal Multi-Organ Anatomical Structures</span>
        </a>
      </div>
    </div>
    <a class="rep-thumb-link" href="https://ieeexplore.ieee.org/abstract/document/11151753/" target="_blank" rel="noopener noreferrer">
      <img src="/images/SegTom.png" alt="SegTom">
    </a>
  </div>

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




