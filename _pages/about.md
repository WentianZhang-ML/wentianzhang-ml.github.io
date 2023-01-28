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

I am studying for my master's degree at the Computer Vision Institute, Shenzhen University, under the supervision of Prof.[Feng Liu](https://scholar.google.com/citations?user=45uLWocAAAAJ) and Prof.[Linlin Shen](https://scholar.google.com/citations?user=AZ_y9HgAAAAJ). Besides, I am an intern at Jarvis Lab, Tencent. My major research interests include Unsupervised Learning, Anomaly Detection and Pattern Recognition. 


# 🔥 News
- *2022.09*: &nbsp; I am awarded the China National Scholarship.
- *2022.08*: &nbsp;🎉 Our paper (Decoupled Mixup for Out-of-Distribution Visual Recognition) is invited as a regular paper in the **ECCV'2022 Workshop**!
- *2022.08*: &nbsp; Our method (Decoupled Mixup) reaches to the 4th/40 in [Out-of-Distribution Visual Recognition ECCV'2022 NICO Challenge.](https://nicochallenge.com/)！
- *2022.07*: &nbsp;🎉 Our paper (Effective Presentation Attack Detection Driven by Face Related Task) is accepted by **ECCV’2022**! 
- *2022.06*: &nbsp;🎉 Our paper (A Multi-task Network with Weight Decay Skip Connection Training for Anomaly Detection in Retinal Fundus Images) is accepted by **MICCAI’2022**!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCVW 2022</div><img src='images/decouple.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Decoupled Mixup for Out-of-Distribution Visual Recognition.](https://arxiv.org/pdf/2210.14783.pdf) 

Haozhe Liu&#8224;, **Wentian Zhang**&#8224;, Jinheng Xie&#8224;, Haoqian Wu, Bing Li, Ziqi Zhang, Yuexiang Li, Yawen Huang, Bernard Ghanem, Yefeng Zheng(**&#8224; Equal Contribution**)
 
- We propose a novel ”Decoupled-Mixup” method to train CNN models for OOD visual recognition. Different from previous work combining pairs of images homogeneously, our method decouples each image into discriminative and noise-prone regions, and then heterogeneously combine these regions of image pairs to train CNN models. 
[**Code**](https://github.com/HaozheLiu-ST/NICOChallenge-OOD-Classification) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/frt-pad.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Effective Presentation Attack Detection Driven by Face Related Task](https://link.springer.com/chapter/10.1007/978-3-031-20065-6_24)
  
**Wentian Zhang**&#8224;, Haozhe Liu&#8224;, Feng Liu, Raghavendra Ramachandra, Christoph Busch (**&#8224; Equal Contribution**)
  
- Unlike face PAD task, other face related tasks trained by huge amount of real faces (e.g. face recognition and attribute editing) can be effectively adopted into different application scenarios. Inspired by this, we propose to trade position of PAD and face related work in a face system and apply the free acquired prior knowledge from face related tasks to solve face PAD, so as to improve the generalization ability in detecting PAs. 
[**Code**](https://github.com/WentianZhang-ML/FRT-PAD)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2022</div><img src='images/wdmt.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Multi-task Network with Weight Decay Skip Connection Training for Anomaly Detection in Retinal Fundus Images](https://link.springer.com/chapter/10.1007/978-3-031-16434-7_63)

**Wentian Zhang**&#8224;, Xu Sun&#8224;, Yuexiang Li&#8224;, Haozhe Liu, Nanjun He, Feng Liu, Yefeng Zheng  (**&#8224; Equal Contribution**)
  
- We propose a weight decay training strategy to progressively mute the skip connections of U-Net, which effectively adapts U-shape network to anomaly detection task. Furthermore, we formulate histograms of oriented gradients (HOG) prediction to encourage the framework to deeply exploit contextual information from fundus images. 
[**Code**](https://github.com/WentianZhang-ML/WDMT-Net)
</div>
</div>

### Selected Publication List

- **Zhang, W.**, Liu, H., Liu, F., Ramachandra, R., & Busch, C. (2022). Effective Presentation Attack Detection Driven by Face Related Task. European Conference on Computer Vision (ECCV). 
- **Zhang, W.**, Liu, H., Liu, F., & Ramachandra, R. (2022). A Uniform Representation Learning Method for OCT-based Fingerprint Presentation Attack Detection and Reconstruction. arXiv preprint arXiv:2209.12208.
- **Zhang, W.**, Sun, X., Li, Y., Liu, H., He, N., Liu, F., & Zheng, Y. (2022). A Multi-task Network with Weight Decay Skip Connection Training for Anomaly Detection in Retinal Fundus Images. In International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI). 
- Liu, H., **Zhang, W.**, Xie J., Wu, H., Li, B., Zhang, Z., Li, Y., Huang, Y., Ghanem, B., & Zheng, Y. (2022). Decoupled Mixup for Out-of-Distribution Visual Recognition. European Conference on Computer Vision Workshop (ECCVW)
- Liu, F., Zeng, W., **Zhang, W.**, Wang, L., Cheng, J., & Lai, Z. (2022). Multi-layered Minutiae Extraction based on Fusion-Attention for OCT Fingerprints. IEEE Transactions on Biometrics, Behavior, and Identity Science (TBIOM).
- Liu, F., Liu, G., **Zhang, W.**, Wang, L., & Shen, L. (2022). A Novel High-Resolution Fingerprint Representation Method. IEEE Transactions on Biometrics, Behavior, and Identity Science (TBIOM).
- Liu, F., Liu, H., **Zhang, W.**, Liu, G., & Shen, L. (2021). One-class fingerprint presentation attack detection using auto-encoder network. IEEE Transactions on Image Processing.

# 🎖 Honors and Awards

- *2022* China National Scholarship (**Rate<0.02%**)
- *2021* Excellent Academic Scholarship, First Class
- *2020* Excellent Academic Scholarship, First Class 
- *2018* National University Big Data Application Innovation Competition in Northwest, First Place

# 📖 Research Experience

### Jarvis Lab (Tencent) 
Internship supervised by Mentor: [Dr. Xu Sun](https://scholar.google.com/citations?user=c1PjjLMAAAAJ) & [Dr. Yuexiang Li](https://scholar.google.com/citations?user=WsKu4EMAAAAJ&hl=en) and Director: [Dr. Yefeng Zheng](https://scholar.google.com/citations?user=vAIECxgAAAAJ) 
  
- Proposed Dynamic Feature Aggregation to improve the robustness against adversarial attacks.
- Participate to NICO Challenge (**ECCV'2022 Workshop**), our team reach to 5th/40 in both tracks at Phase I, and 4th in Track 2 at Final Phase. 
- Proposed a weight decay strategy to progressively mute the skip connections of U-Net for anomaly detection task, which is accepted by **MICCAI'2022**.

### The Chinese University of Hong Kong, Shenzhen
Visiting student supervised by  [Prof. David Zhang](https://scholar.google.com/citations?&user=IOagLnEAAAAJ)

- Designed a method to extract the arc length of the palm, which can effectively locate the ROI of principle lines. 
- Proposed to apply a 3D convolution network to extract palmprint features which can be further encoded for recognition.


### Computer Vision Insitute (SZU)
M.S. supervised by [Prof. Feng Liu](https://scholar.google.com/citations?hl=zh-CN&user=45uLWocAAAAJ) and [Prof. Linlin Shen](https://scholar.google.com/citations?user=AZ_y9HgAAAAJ)

- Proposed a face presentation attack detector based on the taskonomy features, which is accepted by **ECCV'2022**.
- Collected a famous presentation attack dataset based on OCT and **for the first time** established a one-class framework for OCT based PAD. This work is accepted by **IEEE TIP**

