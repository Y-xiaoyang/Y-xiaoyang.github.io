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
### Some works

<!-- 精美折叠论文卡片 -->
<div class="publication-card" style="display:flex; align-items:flex-start; margin-bottom:2em; border-radius:8px; box-shadow:0 2px 8px rgba(0,0,0,0.1); padding:1em; transition:all 0.3s;">

  <!-- 左侧图像 -->
  <div style="flex:0 0 150px; margin-right:1em;">
    <img src="images/FDPF.png" alt="Paper 1" style="width:150px; height:auto; object-fit:cover; border-radius:6px;">
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

<!-- 精美折叠论文卡片 -->
<div class="publication-card" style="display:flex; align-items:flex-start; margin-bottom:2em; border-radius:8px; box-shadow:0 2px 8px rgba(0,0,0,0.1); padding:1em; transition:all 0.3s;">

  <!-- 左侧图像 -->
  <div style="flex:0 0 150px; margin-right:1em;">
    <img src="images/FDPF.png" alt="Paper 1" style="width:150px; height:auto; object-fit:cover; border-radius:6px;">
  </div>

  <!-- 右侧信息 -->
  <div style="flex:1;">
    <h3 style="margin:0 0 0.3em 0;">Dual-Pathway Feature Separation and Gated Fusion Network for Infrared Small Target Detection</h3>
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
      Infrared small target detection (IRSTD) plays a vital role in infrared search and tracking (IRST), enabling intelligent systems to accurately detect dim and small targets within cluttered thermal environments. However, most existing deep learning approaches for IRSTD employ a unified-pathway architecture that conflates saliency and edge information within a shared representation space. This limitation causes feature entanglement, hindering the network’s capacity to accurately separate and represent global saliency and fine-grained edge contours. To overcome these challenges, we propose LoveNet, a dual-pathway network architecture that explicitly separates feature learning into two specialized branches. The first is a multiscale saliency learning branch designed to extract comprehensive structural and contrast information, capturing the global context of targets. The second is a fixed-scale edge learning branch aimed at preserving spatial details and enhancing the precision of edge contour delineation. To integrate the heterogeneous features extracted by two branches, a gated feature fusion mechanism is proposed to adaptively combine saliency and edge representations based on their spatial and semantic relevance. Furthermore, to provide robust and comprehensive supervision, a hybrid supervision strategy (HSS) is designed to guide the learning process of hierarchical feature representations. Experiments on the NUDT-SIRST, IRSTD-1k, and SIRST datasets demonstrate that LoveNet consistently achieves the best segmentation performance compared to the state-of-the-art methods, while maintaining a lightweight structure suitable for real-time applications.
    </div>
  </div>
</div>

<!-- 精美折叠论文卡片 -->
<div class="publication-card" style="display:flex; align-items:flex-start; margin-bottom:2em; border-radius:8px; box-shadow:0 2px 8px rgba(0,0,0,0.1); padding:1em; transition:all 0.3s;">

  <!-- 左侧图像 -->
  <div style="flex:0 0 150px; margin-right:1em;">
    <img src="images/FDPF.png" alt="Paper 1" style="width:150px; height:auto; object-fit:cover; border-radius:6px;">
  </div>

  <!-- 右侧信息 -->
  <div style="flex:1;">
    <h3 style="margin:0 0 0.3em 0;">Visual attention-guided multi-perspective learning and location-aware network for infrared small target detection</h3>
    <p style="margin:0.1em 0; font-size:0.9em; color:#555;">
      Xiaoyang Yuan, Coauthors.<br>
      <em>Pattern Recognition, 2025</em>
    </p>

    <!-- 摘要折叠按钮 -->
    <button class="abstract-toggle" style="margin-top:0.5em; font-size:0.85em; cursor:pointer; background-color:#f0f0f0; border:none; padding:0.4em 0.8em; border-radius:4px; transition:all 0.2s;">
      Show Abstract
    </button>

    <!-- 摘要内容 -->
    <div class="pub-abstract" style="margin-top:0.5em; font-size:0.9em; color:#333; max-height:0; overflow:hidden; transition:max-height 0.4s ease;">
      Infrared Small Target Detection (IRSTD) is crucial for Intelligent Systems within the field of Infrared Search and Tracking (IRST). However, existing methods face significant challenges, including the lack of texture structure across various target sizes, the absence of location awareness information, and the weak gray-scale energy distribution of targets, which hinder precise segmentation. To overcome these problems, we introduce the Visual Attention-Guided Multi-Perspective Learning and Location-Aware Network (ViAMLN), which is founded on the principle of multi-perspective feature coupling. ViAMLN is designed to mimic the human visual system by observing feature tensors from multiple perspectives (the front, side, and top views). The Residual Visual Attention Mechanism (RVAM) module is central to ViAMLN. By dynamically learning multi-perspective features, RVAM enhances location awareness capability and achieves comprehensive target characteristic representation. Furthermore, the Poly Kernel Visual Encoding (PKVE) module, incorporating the RVAM module, utilizes poly kernel parallel convolution to expand the receptive field, efficiently capturing shape, texture, and positional features across diverse target sizes. The Full-Scale Visual Decoding (FSVD) module aggregates full-scale feature tensors and then employs the RVAM module to refine feature representation and reduce false alarms by adaptively learning from cross-scale features. Experiments on the IRSTD-1k, NUDT-SIRST, and SIRST datasets demonstrate the superior performance of our method compared to state-of-the-art methods. These results validate the effectiveness of ViAMLN in enhancing segmentation accuracy and reducing false alarms.
    </div>
  </div>
</div>

<!-- 精美折叠论文卡片 -->
<div class="publication-card" style="display:flex; align-items:flex-start; margin-bottom:2em; border-radius:8px; box-shadow:0 2px 8px rgba(0,0,0,0.1); padding:1em; transition:all 0.3s;">

  <!-- 左侧图像 -->
  <div style="flex:0 0 150px; margin-right:1em;">
    <img src="images/FDPF.png" alt="Paper 1" style="width:150px; height:auto; object-fit:cover; border-radius:6px;">
  </div>

  <!-- 右侧信息 -->
  <div style="flex:1;">
    <h3 style="margin:0 0 0.3em 0;">MNHU-Net: A Multiscale Feature Fusion and Nested Structure-Based High-Order U-Net for Infrared Small Target Detection</h3>
    <p style="margin:0.1em 0; font-size:0.9em; color:#555;">
      Xiaoyang Yuan, Coauthors.<br>
      <em>IEEE Transactions on Aerospace and Electronic Systems, 2025</em>
    </p>

    <!-- 摘要折叠按钮 -->
    <button class="abstract-toggle" style="margin-top:0.5em; font-size:0.85em; cursor:pointer; background-color:#f0f0f0; border:none; padding:0.4em 0.8em; border-radius:4px; transition:all 0.2s;">
      Show Abstract
    </button>

    <!-- 摘要内容 -->
    <div class="pub-abstract" style="margin-top:0.5em; font-size:0.9em; color:#333; max-height:0; overflow:hidden; transition:max-height 0.4s ease;">
      Infrared small target detection (IRSTD) methods have been extensively investigated within the infrared search and tracking applications. U-shaped networks and their improved versions have significantly enhanced IRSTD segmentation performance in recent years. However, existing methods overlook the feature dilution and insufficient representation of long-range dependencies in feature maps, hindering the accurate segmentation of small targets obscured by background clutter. To handle this problem, we designed a multiscale feature fusion and nested structure-based high-order UNet (MNHU). Our approach utilizes a high-order UNet paradigm that progressively calibrates infrared feature maps, and integrates hierarchical features to enhance both small target and background texture extraction performance. High-order U-Net selectively integrates feature maps from highly correlated adjacent nodes. Subsequently, these encoding or decoding feature maps are progressively merged into a high-order fusion feature map, ensuring sufficient feature extraction and precise feature representation. We evaluate the proposed high-order UNet-based methods (MNHU-E, MNHU-D, and MNHU) on three public datasets. The results underscore our method's superior performance in target enhancement and texture awareness, outperforming state-of-the-art techniques in intersection over union, Dice similarity coefficient, precision, and sensitivity. MNHU exhibits robust segmentation capabilities and generalization, effectively achieving a balance between model complexity and performance, which highlights its suitability for practical applications.
    </div>
  </div>
</div>

<!-- 精美折叠论文卡片 -->
<div class="publication-card" style="display:flex; align-items:flex-start; margin-bottom:2em; border-radius:8px; box-shadow:0 2px 8px rgba(0,0,0,0.1); padding:1em; transition:all 0.3s;">

  <!-- 左侧图像 -->
  <div style="flex:0 0 150px; margin-right:1em;">
    <img src="images/FDPF.png" alt="Paper 1" style="width:150px; height:auto; object-fit:cover; border-radius:6px;">
  </div>

  <!-- 右侧信息 -->
  <div style="flex:1;">
    <h3 style="margin:0 0 0.3em 0;">IIMCNet: Intra- and Inter-Modality Correlation Network for Hybrid EEG-fNIRS Brain-Computer Interface</h3>
    <p style="margin:0.1em 0; font-size:0.9em; color:#555;">
      Xiaoyang Yuan, Coauthors.<br>
      <em>IEEE Journal of Biomedical and Health Informatics, 2025</em>
    </p>

    <!-- 摘要折叠按钮 -->
    <button class="abstract-toggle" style="margin-top:0.5em; font-size:0.85em; cursor:pointer; background-color:#f0f0f0; border:none; padding:0.4em 0.8em; border-radius:4px; transition:all 0.2s;">
      Show Abstract
    </button>

    <!-- 摘要内容 -->
    <div class="pub-abstract" style="margin-top:0.5em; font-size:0.9em; color:#333; max-height:0; overflow:hidden; transition:max-height 0.4s ease;">
      Hybrid Brain-Computer Interface (BCI) enhances accuracy and reliability by leveraging the complementary information provided by multi-modality signal fusion. EEG-fNIRS, a fusion of electroencephalogram (EEG) and functional near-infrared spectroscopy (fNIRS), have emerged as the suitable techniques for real-world BCI applications due to their portability and economic viability. Existing methods typically focus on the high-level feature representation with late-fusion or early-fusion strategies during the recognition tasks. However, they usually overlook the joint feature extraction of both intra-modality and inter-modality, which is crucial for optimizing BCI performance. In this study, we introduce an Intra- and Inter-modality Correlation Network (IIMCNet) to integrate both the inherent features derived from individual modalities: EEG, deoxygenated hemoglobin (HbR), and oxygenated hemoglobin (HbO), as well as the cross-modality features between EEG-HbR, EEG-HbO, and HbR-HbO data. The intra-modality correlation features are generated using a late fusion method (Intra-net), which combines the uni-modality features extracted by E-Net and f-Net. Concurrently, the inter-modality correlation features are extracted using an early fusion method (Inter-net). Inter-net is consist of three dilated convolution-based C-Nets that focus on neurovascular coupling across modalities. Finally, three intra-modality features, three inter-modality features, and the concatenate hybrid feature are fed into deep supervision module to enhance robustness and accuracy. Experiment results demonstrate the IIMCNet exhibits superior performance compared to methods that rely solely on either intra-modality or inter-modality correlation networks. Furthermore, IIMCNet outperforms other state-of-the-art methods in motor imagery and mental arithmetic tasks, respectively.
    </div>
  </div>
</div>
### Pub List

1. **Dual-Pathway Feature Separation and Gated Fusion Network for Infrared Small Target Detection**  
   Xiaoyang Yuan, Yan Zhang, Chunling Yang, Jiankai Zhu, Hanwen Zhang, Aishi Zhou  
   *IEEE Transactions on Geoscience and Remote Sensing, 2025*

2. **MNHU-Net: A Multi-Scale Feature Fusion and Nested Structure-Based High-Order U-Net for Infrared Small Target Detection**  
   Xiaoyang Yuan, Chunling Yang, Yu Chen, Yan Zhang  
   *IEEE Transactions on Aerospace and Electronic Systems, 2025*

3. **FDPF-Net: A full-scale dynamic pyramid fusion network for infrared small target detection**  
   Xiaoyang Yuan, Chunling Yang, Yu Chen, Yan Zhang, Anran Zhong, Qiyuan Zheng  
   *IEEE Transactions on Geoscience and Remote Sensing, 2025*

4. **Visual attention-guided multi-perspective learning and location-aware network for infrared small target detection**  
    Xiaoyang Yuan, Yan Zhang, Chunling Yang, Jiankai Zhu, Hanwen Zhang  
    *Pattern Recognition, 2025*

5. **IIMCNet: Intra-and Inter-Modality Correlation Network for Hybrid EEG-fNIRS Brain-Computer Interface**  
    Xiaoyang Yuan, Yan Zhang, Peter Rolfe  
    *IEEE Journal of Biomedical and Health Informatics, 2025*

6. **CSQNet: A Query-Driven Channel-Spatial Attention Network for Infrared Small Target Detection**  
   Xiaoyang Yuan, Yiding Wang, Chunling Yang, Yan Zhang, Mingwei Zhang  
   *IEEE Geoscience and Remote Sensing Letters, 2026*

7. **OASNet: Orthogonal Attention-Guided Spatial--Semantic Representation Learning Network for Infrared Small Target Detection**  
   Xiaoyang Yuan, Chunling Yang, Yuze Li, Yan Zhang  
   *IEEE Geoscience and Remote Sensing Letters, 2025*

8. **A novel command generation method for SSVEP-based BCI by introducing SSVEP blocking response**  
    Xiaoyang Yuan, Li Zhang, Qiang Sun, Xiangtian Lin, Changsheng Li  
    *Computers in Biology and Medicine, 2022*

9. **Enhancing detection of SSVEP-based BCIs via a novel CCA-based method**  
    Xiaoyang Yuan, Qiang Sun, Li Zhang, Haozhe Wang  
    *Biomedical Signal Processing and Control, 2022*

10. **TFST-Net: A Time-Frequency and Spatio-Temporal Attention Network for Hybrid EEG-fNIRS Brain-Computer Interfaces**  
   Xiaoyang Yuan, Yan Zhang  
   *2025 IEEE 20th Conference on Industrial Electronics and Applications (ICIEA)*

11. **Feature fusion improves brain-interface paradigm based on steady state visual evoked potential blocking response**  
    Xiangtian Lin, Li Zhang, Xiaoyang Yuan, Changsheng Li, Le He  
    *Journal of Radiation Research and Applied Sciences, 2024*

12. **A signal prediction-based method for motor imagery EEG classification**  
    Aishi Zhou, Li Zhang, Xiaoyang Yuan, Changsheng Li  
    *Biomedical Signal Processing and Control, 2023*

13. **TSFNet: Temporal-Spatial Fusion Network for Hybrid Brain-Computer Interface**  
   Yan Zhang, Bo Yin, Xiaoyang Yuan  
   *Sensors, 2025*

14. **Classifier Design for EEG-fNIRS Bimodal Brain-Computer Interface Technology**  
   Yan Zhang, Bo Yin, Xiaoyang Yuan, Hao Wang  
   *2025 IEEE 20th Conference on Industrial Electronics and Applications (ICIEA)*

15. **Improving SSVEP identification accuracy via generalized canonical correlation analysis**  
    Qiang Sun, Minyou Chen, Li Zhang, Xiaoyang Yuan, Changsheng Li  
    *2021 10th International IEEE/EMBS Conference on Neural Engineering (NER)*

16. **DHNet: Dual-Hierarchy Geometric Learning with Hyperbolic Embeddings for Few-Shot Point Cloud Classification**  
   Shuicai Luo, Xiaoyang Yuan, Can He, Jianshu Chao  
   *Available at SSRN 5481761*
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
