---
layout: single
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## 👋 About Me
<div style="text-align: justify;">
I am currently pursuing the Ph.D. degree in Electrical Engineering from Harbin Institute of Technology (HIT), Harbin, China.
My research focuses on infrared intelligent sensing and multimodal brain–computer interfaces, aiming to advance robust perception and efficient neural information decoding in complex environments. At the theoretical level, I focus on sparse image perception, time-series signal modeling, and the underlying mechanisms of thermal radiation theory, with applications in small target detection, image segmentation, and multimodal neural signal processing.
</div>
---

## 🔬 Research Interests

- Infrared small target detection
- Brain–computer interfaces (SSVEP, EEG-fNIRS)
- Multimodal signal analysis
- Intelligent perception and control systems

---

## 📄 Publications
### Journal Articles

- **OASNet: Orthogonal Attention-Guided Spatial–Semantic Representation Learning Network for Infrared Small Target Detection**  
## Publications

<div class="publication-card">
  <div style="display:flex; align-items:flex-start; margin-bottom:2em; border-radius:8px; box-shadow:0 2px 8px rgba(0,0,0,0.1); padding:1em;">
    <div style="flex:0 0 150px; margin-right:1em;">
      <img src="assets/images/paper1.png" alt="Paper 1" style="width:150px; height:auto; object-fit:cover; border-radius:6px;">
    </div>
    <div style="flex:1;">
      <h3>Paper Title Goes Here</h3>
      <p style="font-size:0.9em; color:#555;">Xiaoyang Yuan, Coauthors.<br><em>Journal / Conference Name, Year</em></p>
      <button class="abstract-toggle" style="margin-top:0.5em; font-size:0.85em; cursor:pointer; background-color:#f0f0f0; border:none; padding:0.4em 0.8em; border-radius:4px;">
        Show Abstract
      </button>
      <div class="pub-abstract" style="margin-top:0.5em; font-size:0.9em; color:#333; max-height:0; overflow:hidden; transition:max-height 0.4s ease;">
        Abstract goes here...
      </div>
    </div>
  </div>
</div>
<!-- 精美折叠论文卡片 -->
<div class="publication-card" style="display:flex; align-items:flex-start; margin-bottom:2em; border-radius:8px; box-shadow:0 2px 8px rgba(0,0,0,0.1); padding:1em; transition:all 0.3s;">

  <!-- 左侧图像 -->
  <div style="flex:0 0 150px; margin-right:1em;">
    <img src="assets/images/paper1.png" alt="Paper 1" style="width:150px; height:auto; object-fit:cover; border-radius:6px;">
  </div>

  <!-- 右侧信息 -->
  <div style="flex:1;">
    <h3 style="margin:0 0 0.3em 0;">FDPF-Net: A Full-Scale Dynamic Pyramid Fusion Network for Infrared Small Target Detection</h3>
    <p style="margin:0.1em 0; font-size:0.9em; color:#555;">
      Xiaoyang Yuan, Coauthors.<br>
      <em>IEEE Transactions on Geoscience and Remote Sensing, 2025</em>
    </p>

    <!-- 摘要折叠按钮 -->
    <button class="abstract-toggle" style="margin-top:0.5em; font-size:0.85em; cursor:pointer; background-color:#f0f0f0; border:none; padding:0.4em 0.8em; border-radius:4px; transition:all 0.2s;">
      Show Abstract
    </button>

    <!-- 摘要内容 -->
    <div class="pub-abstract" style="margin-top:0.5em; font-size:0.9em; color:#333; max-height:0; overflow:hidden; transition:max-height 0.4s ease;">
      Infrared small target detection (IRSTD) methods have been extensively researched for various military and civilian applications and have greatly developed with the progress of deep learning in recent years. However, the performance of IRSTD remains limited due to challenges such as weak detection capabilities for diverse target boundaries and the complex background clutter present in infrared images across different scenarios. To overcome these challenges, this article proposes a two-stage end-to-end full-scale dynamic pyramid fusion network (FDPF-Net). This network aims to refine small target boundary information and enhance both background consistency and the contrast between the target and its surroundings. The FDPF-Net introduces a feature extraction trunk subnetwork and a full-scale dynamic refinement subnetwork to extract and refine target and background information. Additionally, the proposed cross-layer scale-adaptive (CSA) module which is positioned between the trunk and the refinement subnetworks, adaptively integrates and optimizes the full-scale feature representation for boundary feature compensation. Finally, a feature pyramid fusion module is used to fuse and exploit the intrinsic information of small targets, avoiding feature dilution during the information passing process. Experimental results on three public datasets demonstrate that the proposed FDPF-Net outperforms other state-of-the-art (SOTA) methods in terms of intersection over union (IoU), dice similarity coefficient (DSC), Precision (Pre), and Sensitivity (Se) and also exhibits more robust segmentation performance. It also maintains a balance between segmentation performance and model complexity, indicating its significant potential for real-world IRSTD applications.
    </div>
  </div>
</div>
---

## 📝 Peer Review Activities

![Peer Review Record](images/peer review.png)

---
## 📬 Contact

- Email: Yuanxiaoyang1998@outlook.com  
- Google Scholar: https://scholar.google.com/citations?user=8DV7A_QAAAAJ  
- GitHub: https://github.com/Y-xiaoyang

  <script>
  document.querySelectorAll('.abstract-toggle').forEach(btn => {
    btn.addEventListener('click', () => {
      const abstractDiv = btn.nextElementSibling;
      if (abstractDiv.style.maxHeight && abstractDiv.style.maxHeight !== '0px') {
        abstractDiv.style.maxHeight = '0';
        btn.textContent = 'Show Abstract';
      } else {
        abstractDiv.style.maxHeight = abstractDiv.scrollHeight + 'px';
        btn.textContent = 'Hide Abstract';
      }
    });

    // Hover效果
    btn.addEventListener('mouseover', () => btn.style.backgroundColor='#e0e0e0');
    btn.addEventListener('mouseout', () => btn.style.backgroundColor='#f0f0f0');
  });
</script>
