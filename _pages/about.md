---
permalink: /
title: ""
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

# 🙋‍♂️ <font color="#4A708B">个人简介</font>
李政霖，博士，副教授，博士生导师。本硕毕业于大连理工大学，博士毕业于英国谢菲尔德大学。上海市海外高层次人才，主持国家自然科学基金青年、启明星培育等多项纵向课题、以第一及通讯作者在重要学术期刊和国际会议上发表多篇论文，其中包括 IEEE Trans. on Industrial Informatics，IEEE Trans. on Intelligent Transportation Systems，IJCAI等。中国人工智能学会智能机器人专委会委员、Cyborg and Bionic Systems期刊（IF 10.5）青年编委。

<span class='anchor' id='pub'></span>

# 📝 <font color="#4A708B">主要研究领域</font>

## 1. **自动驾驶/机器人感知及端到端系统**：包括多传感器融合感知、协同感知、端到端自动驾驶、占用网格估计、水面无人艇感知等；

### 1. 视觉-毫米波雷达水面融合感知

<div class='paper-box'><div class='paper-box-image'><div><img src='images/img1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
*Target Detection for USVs by Radar-vision Fusion with Swag-robust Distance-aware Probabilistic Multi-modal Data Association，IEEE Sensors Journal，2024*
- 减弱水面反射、平台晃动、逆光或阴雨的影响
- 在复杂场景下具有可靠检测性能
</div>
</div>

### test
<div>
  
  <!-- 图1和视频1并排 -->
  <div style="display: flex; justify-content: space-between;">
    <img src="images/img1.jpg" alt="视觉-雷达融合感知示意图" width="49%">
    <video controls width="49%"><source src="images/video1.mp4" type="video/mp4"></video>
  </div>
  
  <!-- 图2单独一行 -->
  <div>
    <img src="images/img2.jpg" alt="长图示例" width="100%">
  </div>
</div>

### test 2
<div class='paper-box'>
  <video controls width="100%">
    <source src='images/output_2.mp4' type="video/mp4">
  </video>
</div>


## 2. **机器人训练数据生成与增强**：包括新视角图像合成、多模态数据生成、数据增强、风格迁移等；

<div class='paper-box'>
  <h3>3D目标检测的分割视角位置编码</h3>
  <div style="display: flex; justify-content: space-between; margin-bottom: 10px;">
    <figure style="text-align: center; margin: 0 5px;">
      <img src="images/img5.jpg" alt="图像5" width="100%">
      <figcaption>图5: 描述内容</figcaption>
    </figure>
    <figure style="text-align: center; margin: 0 5px;">
      <img src="images/img6.jpg" alt="图像6" width="100%">
      <figcaption>图6: 描述内容</figcaption>
    </figure>
  </div>
  <div style="display: flex; justify-content: space-between; margin-bottom: 10px;">
    <figure style="text-align:intrepreter: center; margin: 0 5px;">
      <img src="images/img7.jpg" alt="图像7" width="100%">
      <figcaption>图7: 描述内容</figcaption>
    </figure>
    <figure style="text-align: center; margin: 0 5px;">
      <img src="images/img8.jpg" alt="图像8" width="100%">
      <figcaption>图8: 描述内容</figcaption>
    </figure>
    <figure style="text-align: center; margin: 0 5px;">
      <img src="images/img9.jpg" alt="图像9" width="100%">
      <figcaption>图9: 描述内容</figcaption>
    </figure>
  </div>
  <p>将全局空间进行多层级分割，与虚拟视角空间对齐并进行位置编码，以低计算量实现全局注意力</p>
  <p style="font-size: smaller; margin-top: 10px;">DVPE: divided view position embedding for multi-view 3D object detection，IJCAI 2024（CCF A）</p>
</div>

## 3. **机器学习与计算机视觉**：包括信息融合、深度学习的不确定性量化与分析、大模型微调、增量学习/终身学习等。

<span class='anchor' id='publication'></span>

# 📝 <font color="#4A708B">代表性成果</font>
1. Zhenglin Li, Wenbo Zheng, Le Yang, Liyan Ma, Yang Zhou, Yan Peng. MonoAux: Fully Exploiting Auxiliary Information and Uncertainty for Monocular 3D Object Detection. Cyborg and Bionic Systems, 2024, 5: 0097.
2. Jiasen Wang, Zhenglin Li, Ke Sun, Xianyuan Liu, Yang Zhou. DVPE: Divided View Position Embedding for Multi-View 3D Object Detection. In Proceedings of the Thirty-Third International Joint Conference on Artificial Intelligence, pp. 6877-6885. 2024.
3. Zhenglin Li, Tianxin Yuan, Liyan Ma, Yang Zhou, Yan Peng. Target Detection for USVs by Radar-vision Fusion with Swag-robust Distance-aware Probabilistic Multi-modal Data Association, IEEE Sensors Journal, 2024, 5: 20177 – 20187.
4. Zhenglin Li, Lyudmila S. Mihaylova, Olga Isupova, and Lucile Rossi. "Autonomous flame detection in videos with a Dirichlet process Gaussian mixture color model." IEEE Transactions on Industrial Informatics, 2017, vol. 14, no. 3: 1146-1154.
5. Xiang Liu, Zhenglin Li, Yang Zhou, Yan Peng, Jun Luo. Camera–Radar Fusion with Modality Interaction and Radar Gaussian Expansion for 3D Object Detection. Cyborg and Bionic Systems, 2024, 5: 0079.
6. Zhenglin Li, Lyudmila Mihaylova, and Le Yang. "A deep learning framework for autonomous flame detection." Neurocomputing, 2021, 448 : 205-216.
7. Chuan Lin, Guangjie Han, Qiuzi Tao, Li Liu, Syed Bilal Hussain Shah, Tongwei Zhang. Underwater Equipotential Line Tracking Based on Self-Attention Embedded Multiagent Reinforcement Learning Toward AUV-Based ITS. IEEE Transactions on Intelligent Transportation Systems, 2023, 24(8): 8580–8591.
8. Ke Sun, Zhenglin Li. Sparse Data Injection Attacks on Smart Grid: An Information-Theoretic Approach. IEEE Sensors Journal, 2022, 22(14): 14553–14562.
9. Zhenglin Li, Mahnaz Arvaneh, Heather E. Elphick, Ruth N. Kingshott, Lyudmila S. Mihaylova. A Dirichlet Process Mixture Model for Autonomous Sleep Apnea Detection Using Oxygen Saturation Data. 2020 IEEE 23rd International Conference on Information Fusion (FUSION), 2020, pp. 1–8.
10. Wenbo Zheng, Zhenglin Li, Wenbo Xie, Songyi Zhong, Tianxin Yuan, Yan Peng. SCON: Semantic Cross-Modal Data Association Offset Estimation Network for Radar-Vision Feature Fusion. 2024 IEEE International Conference on Unmanned Systems (ICUS), 2024, pp. 1516–1520.


<span class='anchor' id='project'></span>

# 📝 <font color="#4A708B">科研项目（主持与在研项目）</font>
1. **军委科技委“XXXXXX”项目子课题**，XX环境理解与XX安全控制技术研究，主持，505万元
2. **国家自然科学基金青年项目**，面向未知多变场景的视觉自主火灾监测，30万元，负责人
3. **上海市启明星培育（扬帆专项）**，基于无人艇的海洋温盐场重构及传感器部署智能规划，20万元，负责人

# 📝 <font color="#4A708B">联系方式</font>

- **邮箱**：[zhenglin_li@shu.edu.cn](mailto:zhenglin_li@shu.edu.cn)
- **地址**：上海市，上海大学未来技术学院/人工智能研究院
<span class='anchor' id='CV'></span>
