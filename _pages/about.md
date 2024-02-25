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

I have got my master's degree at the Computer Vision Institute, Shenzhen University, under the supervision of Prof.[Feng Liu](https://scholar.google.com/citations?user=45uLWocAAAAJ) and Prof.[Linlin Shen](https://scholar.google.com/citations?user=AZ_y9HgAAAAJ). Besides, I was an intern at Jarvis Lab, Tencent. My major research interests include image & video generation and system security. 

# 🔥 News
- *2024.01*: &nbsp;🎉 I am invited as a reviewer for ECCV'2024!
- *2023.11*: &nbsp;🎉 I am invited as a reviewer for CVPR'2024!
- *2023.09*: &nbsp;🎉 Our paper (Dynamically Masked Discriminator for GANs) is accepted by **NeurIPS’2023**!
- *2023.07*: &nbsp;🎉 Our paper (BoxDiff: Text-to-Image Synthesis with Training-Free Box-Constrained Diffusion) is accepted by **ICCV’2023**!
- *2023.02*: &nbsp;🎉 Our paper (AdaptiveMix: Robust Feature Representation via Shrinking Feature Space.) is accepted by **CVPR’2023**!
- *2023.02*: &nbsp;🎉 Our paper (NewsNet: A Novel Dataset for Hierarchical Temporal Segmentation.) is accepted by **CVPR’2023**!
- *2022.09*: &nbsp; I am awarded the China National Scholarship.
- *2022.08*: &nbsp;🎉 Our paper (Decoupled Mixup for Out-of-Distribution Visual Recognition) is invited as a regular paper in the **ECCV'2022 Workshop**!
- *2022.08*: &nbsp; Our method (Decoupled Mixup) reaches to the 4th/40 in [Out-of-Distribution Visual Recognition ECCV'2022 NICO Challenge.](https://nicochallenge.com/)！
- *2022.07*: &nbsp;🎉 Our paper (Effective Presentation Attack Detection Driven by Face Related Task) is accepted by **ECCV’2022**! 
- *2022.06*: &nbsp;🎉 Our paper (A Multi-task Network with Weight Decay Skip Connection Training for Anomaly Detection in Retinal Fundus Images) is accepted by **MICCAI’2022**!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NIPS 2023</div><img src='images/dmd.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Dynamically Masked Discriminator for GANs.](https://arxiv.org/pdf/2306.07716.pdf) 

**Wentian Zhang**, Haozhe Liu, Bing Li, Jinheng Xie, Yawen Huang, Yuexiang Li, Yefeng Zheng, Bernard Ghanem

- In the GAN training, We observe that the discriminator model, trained on historically generated data, often slows down its adaptation to the changes in the new arrival generated data, which accordingly decreases the quality of generated results. We propose a new discriminator, which automatically detects its retardation and then dynamically masks its features, such that the discriminator can adaptively learn the temporally-vary distribution of generated data.
[**Code**](https://github.com/WentianZhang-ML/DyMD) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/adaptivemix.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[AdaptiveMix: Robust Feature Representation via Shrinking Feature Space.](https://openaccess.thecvf.com/content/CVPR2023/papers/Liu_AdaptiveMix_Improving_GAN_Training_via_Feature_Space_Shrinkage_CVPR_2023_paper.pdf) 

Haozhe Liu&#8224;, **Wentian Zhang**&#8224;, Bing Li, Haoqian Wu, Nanjun He, Yawen Huang, Yuexiang Li, Bernard Ghanem, Yefeng Zheng(**&#8224; Equal Contribution**)
 
- Training GANs is difficult since the training distribution is dynamic for the discriminator, leading to unstable image representation. We address the problem of training GANs from a novel perspective, i.e., robust image classification. We propose a simple yet effective module, namely AdaptivelyMix, for GANs, which shrinks the regions of training data in the image representation space of the discriminator. 
[**Code**](https://github.com/WentianZhang-ML/AdaptiveMix) 
</div>
</div>

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
  
**Wentian Zhang**;, Haozhe Liu;, Feng Liu, Raghavendra Ramachandra, Christoph Busch
  
- Unlike face PAD task, other face related tasks trained by huge amount of real faces (e.g. face recognition and attribute editing) can be effectively adopted into different application scenarios. Inspired by this, we propose to trade position of PAD and face related work in a face system and apply the free acquired prior knowledge from face related tasks to solve face PAD, so as to improve the generalization ability in detecting PAs. 
[**Code**](https://github.com/WentianZhang-ML/FRT-PAD)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2022</div><img src='images/wdmt.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Multi-task Network with Weight Decay Skip Connection Training for Anomaly Detection in Retinal Fundus Images](https://link.springer.com/chapter/10.1007/978-3-031-16434-7_63)

**Wentian Zhang**;, Xu Sun;, Yuexiang Li;, Haozhe Liu, Nanjun He, Feng Liu, Yefeng Zheng
  
- We propose a weight decay training strategy to progressively mute the skip connections of U-Net, which effectively adapts U-shape network to anomaly detection task. Furthermore, we formulate histograms of oriented gradients (HOG) prediction to encourage the framework to deeply exploit contextual information from fundus images. 
[**Code**](https://github.com/WentianZhang-ML/WDMT-Net)
</div>
</div>

### Selected Publication List

- **Zhang, W.**,Liu, H., Li, B., Xie, J., Huang, Y., Li, Y., Zheng, Y., & Ghanem, B. (2023). Dynamically Masked Discriminator for GANs. (NeurIPS'2023).
- **Zhang, W.**, Liu, H., Liu, F., Ramachandra, R., & Busch, C. (2022). Effective Presentation Attack Detection Driven by Face Related Task. (ECCV'2022). 
- **Zhang, W.**, Sun, X., Li, Y., Liu, H., He, N., Liu, F., & Zheng, Y. (2022). A Multi-task Network with Weight Decay Skip Connection Training for Anomaly Detection in Retinal Fundus Images. (MICCAI'2022).
- Liu, H.\*, **Zhang, W.**\*, Li, B., Wu, H., He, N., Huang, Y., Li, Y., Ghanem, B., & Zheng, Y. (2023). AdaptiveMix: Robust Feature Representation via Shrinking Feature Space. (CVPR'2023). (* Equal Contribution)
- Kong, Z.\*, **Zhang, W.**\*, Liu, F., Luo, W., Liu, H., Shen, L., Raghavendra, R. (2023). Taming Self-Supervised Learning for Presentation Attack Detection: De-Folding and De-Mixing. IEEE
T-NNLS (* Equal Contribution)
- Liu, H.\*, **Zhang, W.**\*, Xie J.\*, Wu, H., Li, B., Zhang, Z., Li, Y., Huang, Y., Ghanem, B., & Zheng, Y. (2022). Decoupled Mixup for Out-of-Distribution Visual Recognition. (ECCVW'2022). (* Equal Contribution)
- Wu, H., Chen, K., Liu, H., Zhuge, M., Li, B., Qiao, R., Shu, X., Gan, B., Xu, L., Ren, B., Xu, M., **Zhang, W.**, Ramachandra, R., Lin, C., & Ghanem, B. (2023) NewsNet: A Novel Dataset for Hierarchical Temporal Segmentation. (CVPR'2023).
- Xie, J., Li, Y., Huang, Y., Liu, H., **Zhang, W.**, Zheng, Y., & Shou, M. Z. (2023). BoxDiff: Text-to-Image Synthesis with Training-Free Box-Constrained Diffusion. (ICCV’2023).


# 🎖 Honors and Awards

- *2022* China National Scholarship (**Rate<0.02%**)
- *2021* Excellent Academic Scholarship, First Class
- *2020* Excellent Academic Scholarship, First Class 
- *2018* National University Big Data Application Innovation Competition, First Place

# 📖 Research Experience

### AI Initiative (KAUST) 
Visiting student supervised by [Dr. Bing Li](https://scholar.google.com/citations?user=xBiftlUAAAAJ). Closely cooperate with [Haozhe Liu](https://scholar.google.com/citations?user=QX51P54AAAAJ)

- Proposed an ownership protection method for generative models (diffusion models and GAN models).
- Proposed a dynamically masked discriminator for generative adversarial networks, which is accepted by **NeurIPS’2023**.
- Proposed a robust adversarial learning method by shrinking feature space in the training phase, which is accepted by **CVPR’2023**.
- Participated in establishing a novel dataset for hierarchical temporal segmentation, which is accepted by **CVPR’2023**.
 
### Jarvis Lab (Tencent) 
Internship supervised by Mentor: [Dr. Xu Sun](https://scholar.google.com/citations?user=c1PjjLMAAAAJ) & [Dr. Yuexiang Li](https://scholar.google.com/citations?user=WsKu4EMAAAAJ&hl=en) and Director: [Dr. Yefeng Zheng](https://scholar.google.com/citations?user=vAIECxgAAAAJ) 
  
- Proposed a weight decay strategy to progressively mute the skip connections of U-Net for anomaly detection task, which is accepted by **MICCAI'2022**.
- Participate to NICO Challenge (**ECCV'2022 Workshop**), our team reach to 5th/40 in both tracks at Phase I, and 4th in Track 2 at Final Phase. 

### Norwegian Biometrics Laboratory (NTNU)
Collaborating with [Prof. Raghavendra Ramachandra](https://scholar.google.com/citations?user=OIYIrmIAAAAJ)

- Proposed a face presentation attack detector based on the taskonomy features, which is accepted by **ECCV’2022**.

### Shenzhen Institute of Artificial Intelligence and Robotics for Society (CUHK)
Visiting student supervised by  [Prof. David Zhang](https://scholar.google.com/citations?&user=IOagLnEAAAAJ)

- Participated in collecting a multi-modal biometric dataset, which contains face, fingerprint and palmprint samples from 10k subjects.
- Proposed to apply a 3D convolution network to extract palmprint features which can be further encoded for recognition.

### Computer Vision Institute (Shenzhen University)
M.S. supervised by [Prof. Feng Liu](https://scholar.google.com/citations?hl=zh-CN&user=45uLWocAAAAJ) and [Prof. Linlin Shen](https://scholar.google.com/citations?user=AZ_y9HgAAAAJ)

- Proposed a uniform representation learning method for OCT-based Fingerprint anti-spoofing and Recognition, which is accepted by **Pattern Recognition**.
- Proposed a minutiae extraction model with a fusion-attention mechanism for multi-layered OCT fingerprints.
- Proposed to establish a one-class framework for OCT-based PAD. This work is accepted by **IEEE TIP**.

