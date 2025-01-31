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

I currently serve as the Technical Director at MEGVII Research. My research and project interests include Machine Learning, Computer Vision, and Computer Graphics, among others. Recently, I have been primarily focusing on Diffusion models with applications in Computer Vision.

I received my Master degree at Information and Communication Engineering in University of Electronic Science and Technology of China (UESTC), supervised by [Prof. Yiming Pi](https://www.researchgate.net/scientific-contributions/Yiming-Pi-13739828) and [Prof. Zongjie Cao](https://www.researchgate.net/scientific-contributions/Zongjie-Cao-33269443), in 2019. I obtained my Bachelor degree at Electronic Information Engineering in University of South China (USC) in 2015. During in internship, I was luckily mentored by [Dr. Zhanghui Kuang](https://scholar.google.com/citations?hl=zh-CN&user=z4wkHDgAAAAJ) at SenseTime and [Prof. Shuaicheng Liu](http://www.liushuaicheng.org/), [Dr. Jue Wang](https://juewang725.github.io/) at MEGVII Research. 




# 🔥 News
- *2024.12*: &nbsp;🎉🎉 Two papers are accepted by the Association for the Advancement of Artificial Intelligence (**AAAI 2025**).
- *2024.07*: &nbsp;🎉🎉 One paper is accepted by the ACM International Conference on Multimedia (**MM2024**).
- *2024.04*  &nbsp;🎉🎉 We win 2nd place in the NTIRE 2024 BracketIRE Challenge (**Runner up**).
- *2023.12*: &nbsp;🎉🎉 One paper is accepted by Elsevier Pattern Recognition (**PR2023**).
- *2023.07*: &nbsp;🎉🎉 One paper is accepted by the IEEE Conference on International Conference on Computer Vision(**ICCV2023**).
- *2023.06*: &nbsp;🎉🎉 One paper is accepted by the IEEE Conference on Computer Vision and Pattern Recognition Workshop (**CVPRW2023**).
- *2023.06*: &nbsp;🎉🎉 We win 2nd place in the NTIRE 2023 Shadow Removal Challenge (**2st place on perceptual scores**).
- *2022.06*: &nbsp;🎉🎉 We win 1st place in the NTIRE 2022 Efficient Super-Resolution Challenge (**Winner**).
- *2023.02*: &nbsp;🎉🎉 We win 2nd place in the MIPI 2022 RGBW Joint Fusion and Denoise Challenge (**Runner up**).
- *2022.12*: &nbsp;🎉🎉 One paper is accepted by the IEEE on Transaction on Image Processing(**TIP2022**). 
<!--- *2021.12*: &nbsp;🎉🎉 One paper is accepted by the AAAI Conference on Artificial Intelligence (AAAI 2022). -->
 

# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><img src='images/500x300.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf), **Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

**CVPR, 2022** \| [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

<!-- ###################################################### -->

<div class='paper-box'><div class='paper-box-image'><img src='images/meflut.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**MEFLUT: Unsupervised Learning 1D Lookup Tables for Multi-exposure Image Fusion**  
<u>Ting Jiang</u>, Chuan Wang, Xinpeng Li, Ru Li, Haoqiang Fan, Shuaicheng Liu

**<font color = "#224B8D">International Conference on Computer Vision （ICCV） 2023</font>** \| [Paper](https://arxiv.org/pdf/2309.11847.pdf) \| [Code](https://github.com/Hedlen/MEFLUT) <strong><span class='show_paper_citations' data='3WQTKocAAAAJ:WF5omc3nYNoC'></span></strong>
- This work introduce MEFLUT that learns 1D LUTs for the task of MEF. It show that the fusion weights can be encoded into the LUTs successfully. Once learned, MEFLUT can be easily deployed with high efficiency, so that a 4K image runs in less than 4ms on a PC GPU. 
- This is the first time to demonstrate the benefits of LUTs for MEF. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/sam_iqa.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**SAM-IQA: Can Segment Anything Boost Image Quality Assessment?**  
Xinpeng Li, <u>Ting Jiang</u>, Haoqiang Fan, Shuaicheng Liu

**<font color = "#224B8D">ArXiv 2023</font>** \| [Paper](https://arxiv.org/pdf/2307.04455.pdf)\| [Code](https://github.com/Hedlen/SAM-IQA)  <strong><span class='show_paper_citations' data='3WQTKocAAAAJ:WF5omc3nYNoC'></span></strong>
- This work first introduce the SAM encoder as a feature extractor in IQA and demonstrate its strong generalization ability in this domain
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/real_noise.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Realistic Noise Synthesis with Diffusion Models**  
Qi Wu, Mingyan Han, <u>Ting Jiang</u>, Haoqiang Fan, Bing Zeng, Shuaicheng Liu

**<font color = "#224B8D">ArXiv 2023</font>** \| [Paper](https://arxiv.org/pdf/2305.14022.pdf)  <strong><span class='show_paper_citations' data='3WQTKocAAAAJ:WF5omc3nYNoC'></span></strong>
- This work first propose a real noise data synthesis approach
based on the diffusion model.
- A camera setting embedding approach is designed that
can better control the distribution and level of generated noise.
</div>
</div>

<!-- ###################################################### -->

<div class='paper-box'><div class='paper-box-image'><img src='images/ntire_sr.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**DIPNet: Efficiency Distillation and Iterative Pruning for Image Super-Resolution**  
Lei Yu, Xinpeng Li, Youwei Li, <u>Ting Jiang</u>, Qi Wu, Haoqiang Fan, Shuaicheng Liu

**<font color = "#224B8D">IEEE Conference on Computer Vision and Pattern Recognition Workshop (CVPRW) 2023</font>** \| [Paper](https://openaccess.thecvf.com/content/CVPR2023W/NTIRE/papers/Yu_DIPNet_Efficiency_Distillation_and_Iterative_Pruning_for_Image_Super-Resolution_CVPRW_2023_paper.pdf) \| [Code](https://github.com/xiumu00/DIPNet) <strong><span class='show_paper_citations' data='3WQTKocAAAAJ:WF5omc3nYNoC'></span></strong>
- <span style="color:red">**Winner method**</span> of the NTIRE Super-Resolution Challenge 2023.
- This work propose the use of enhanced HR images to improve the learning ability of lightweight networks.
- A novel multi-stage lightweight training strategy combining distillation, progressive learning, and pruning is proposed.
</div>
</div>

<!-- ###################################################### -->

<div class='paper-box'><div class='paper-box-image'><img src='images/tip_pruning.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Efficient Neural Architecture Search via firefly optimization for SAR ship detection**  
Jielei Wang, Zongyong Cui, <u>Ting Jiang</u>, Changjie Cao, Zongjie Cao

**<font color = "#224B8D">IEEE Transactions on Image Processing (TIP) 2022</font>** \| [Paper](https://ieeexplore.ieee.org/abstract/document/9999699/) <strong><span class='show_paper_citations' data='3WQTKocAAAAJ:WF5omc3nYNoC'></span></strong>
- A set of lightweight detection networks for SAR ship target detection are proposed. 
</div>
</div>

<!-- ###################################################### -->

<div class='paper-box'><div class='paper-box-image'><img src='images/ntire_hdr.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**ADNet: Attention-guided Deformable Convolutional Network for High Dynamic Range Imaging**  
Zhen Liu, Wenjie Lin, Xinpeng Li, <u>Ting Jiang</u>, Mingyan Han, Qing Rao, Haoqiang Fan, Jian Sun, Shuaicheng Liu

**<font color = "#224B8D">IEEE Conference on Computer Vision and Pattern Recognition Workshop (CVPRW) 2021</font>** \| [Paper](https://openaccess.thecvf.com/content/CVPR2021W/NTIRE/papers/Liu_ADNet_Attention-Guided_Deformable_Convolutional_Network_for_High_Dynamic_Range_Imaging_CVPRW_2021_paper.pdf) \| [Code](https://github.com/liuzhen03/ADNet) \| [Video: [Youtube](https://www.youtube.com/watch?v=M0X-BXe3UqM&t=2s), [Bilibili](https://www.bilibili.com/video/BV19h411a78M/)] <strong><span class='show_paper_citations' data='3WQTKocAAAAJ:WF5omc3nYNoC'></span></strong>
- This work proposes a novel dual-branch pipeline for multiframe HDR imaging of dynamic scenes.
<!-- - A deep constrained least square filtering module is applied in the feature space to generate clean features based on the estimated kernel. -->
</div>
</div>

<!-- ###################################################### -->

<div class='paper-box'><div class='paper-box-image'><img src='images/nc_pruning.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Filter pruning with a feature map entropy importance criterion for convolution neural networks compressing**  
Jielei Wang, <u>Ting Jiang</u>, Zongyong Cui, Zongjie Cao

**<font color = "#224B8D">Neuro Computing 2021</font>** \| [Paper](https://www.sciencedirect.com/science/article/abs/pii/S092523122101078X) <strong><span class='show_paper_citations' data='3WQTKocAAAAJ:eQOLeE2rZwMC'></span></strong>
- A novel structured pruning method for Convolutional Neural Networks (CNN) compression is proposed, where filter-level redundant weights are pruned according to entropy importance criteria (termed FPEI).
<!-- - We introduce a latent vector that can represent the high-dimensional action and be optimized in an Actor-Critic RL framework. -->
</div>
</div>

<!-- ###################################################### -->

- **A Knowledge Distillation Method Based on IQE Attention Mechanism for Target Recognition in Sar Imagery**  
Jielei Wang, <u>Ting Jiang</u>, Zongyong Cui, Zongjie Cao, Changjie Cao 
***<font color = "#224B8D">International Geoscience and Remote Sensing Symposium (IGRASS) 2022 Oral</font>*** \| [[Paper](https://ieeexplore.ieee.org/abstract/document/9883376/)]

- **Data augmentation with Gabor filter in deep convolutional neural networks for SAR target recognition**  
<u>Ting Jiang</u>, Zongyong Cui, Zhi Zhou, Zongjie Cao 
***<font color = "#224B8D">International Geoscience and Remote Sensing Symposium (IGRASS) 2022</font>*** \| [[Paper](https://ieeexplore.ieee.org/abstract/document/8518792/)]

- **Adaptive Weighted Multi-Task Sparse Representation Classification in SAR Image Recognition**  
Zhi Zhou, Zongjie Cao, Yiming Pi, <u>Ting Jiang</u>  
***<font color = "#224B8D">International Geoscience and Remote Sensing Symposium (IGRASS) 2018</font>*** \| [[Paper](https://sci-hub.se/10.1109/igarss.2018.8519004)]

# 🧵 Projects
<div class='paper-box'><div class='paper-box-image'><video src='images/DMS_phone_demo.mp4' controls="" width="33%"></video><video src='images/DMS_smoke_demo1.mp4' controls="" width="33%"></video><video src='images/DMS_smoke_demo2.mp4' controls="" width="33%"></video></div>
<div class='paper-box-text' markdown="1">

**Driver Monitor System**  
- Dec. 2018 - Jul. 2019, Major Membor
- Responsible for designing a light-weighted end-to-end network running on an onboard chip to detect smoking, phoning, and drinking in driving. 
- I participated in the overall pipeline of algorithm development, including data collection, data cleaning, algorithm development, etc.
</div>
</div>

<!-- ###################################################### -->

<div class='paper-box'><div class='paper-box-image'><img src='images/hdr_full.png' alt="sym" width="110%"></div>
<div class='paper-box-text' markdown="1">

**High Dynamic Range Image (HDRI)**  
- Jul. 2019 - Present, Algorithm Leader
- Responsible for HDRI projects, including YUV and RAW domains. Compared with ordinary images, HDRI can provide more dynamic range and image details, which can better reflect the visual effects in the real environment of people.
</div>
</div>

<!-- ###################################################### -->

<div class='paper-box'><div class='paper-box-image'><img src='images/cjyj_full.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Super Night View**  
- Jul. 2019 - Present, Algorithm Leader
- Responsible for Super night view projects, including YUV and RAW domains. In hand-held super night scene, improve night scene brightness, clarity, noise, dynamic range and other performance.
</div>
</div>

<!-- ###################################################### -->

<div class='paper-box'><div class='paper-box-image'><img src='images/dzjz.png' alt="sym" width="100%"><img src='images/szjz.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Multi-frame or Single-frame Denoising**  
- Oct. 2021 - Present, Algorithm Leader
- Responsible for image and video denoising projects, including YUV and RAW domains. In extreme scenarios, the noise is improved, and it is suitable for various mobile devices, such as mobile phones, vehicles, drones, robots, etc. 
</div>
</div>

<!-- ###################################################### -->

<div class='paper-box'><div class='paper-box-image'><img src='images/sr.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Super Resolution (SR)**  
- Jul. 2022 - Present, Algorithm Leader
- Responsible for image and video SR projects, including YUV and RAW domains. The recovery effect of details in the smart phone super resolution project is better than that of the competitor.
</div>
</div>

<!-- ###################################################### -->

<div class='paper-box'><div class='paper-box-image'><img src='images/b.png' alt="sym" width="33%"><img src='images/b1.png' alt="sym" width="33%"><img src='images/b2.png' alt="sym" width="33%"></div>
<div class='paper-box-text' markdown="1">

**Portrait Beauty**  
- Jul. 2019 - Nov. 2019, Algorithm Leader
- Responsible for leading Portrait beauty projects. As a team leader, I led team members in developing a novel beautifying algorithm capable of adaptive face area adjustment to achieve effective portrait enhancement. This algorithm was successfully applied to products and widely adopted.
- 
</div>
</div>

<!-- ###################################################### -->
<div class='paper-box'><div class='paper-box-image'><img src='images/gjjc.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Object Detection**  
- Jul. 2021 - Mar. 2022, Algorithm Leader
- Responsible for Object Detection projects. It mainly involves the detection of ghosts existing in the project to achieve precise positioning.
</div>
</div>

<!-- ###################################################### -->
<div class='paper-box'><div class='paper-box-image'><img src='images/inpainting.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Intelligent Erase**  
- Sep. 2021 - Mar. 2022, Algorithm Leader
- Responsible for Intelligent Erase projects. The recovery effect of details in the smart erasing project is better than that of competing models.
</div>
</div>

<!-- ###################################################### -->


# 🎖 Honors and Awards
- *2023* **2nd** place in NTIRE Image Shadow Removal Challenge (2st place on perceptual scores)
- *2023*, **Winner Award** in NTIRE 2023 Efficient Super-resolution Challenge
- *2022*, *2023*, **Runner up Award** in MIPI RGBW Joint Fusion and Denoise Challenge
- *2021*, **Winner Award** in NTIRE 2021 High Dynamic Range Challenge (Multiple Frames)
- *2021*, **MegTeam Award** in MEGVII Research
- *2021*, *2023*, **Excellent Team Award** in MEGVII Research
- *2019* **Outstanding Graduates**, University of Electronic Science and Technology of China (UESTC)
- *2015* **Outstanding Graduates**, University of South China (USC) 
- *2014* **The First Prize Scholarship**, University of South China (USC)
- *2013* **National Scholarship**, China


# 📖 Educations
- *2016.09 - 2019.06*, Master, University of Electronic Science and Technology of China (UESTC). 
- *2011.09 - 2015.06*, Undergraduate, University of South China (USC).

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💬 Teaching 
- *2023.01 - 2018-04*, Teaching Assistant in the course *Statistical Machine Learning*, at Uppsala University
- *2018.10 - 2018-12*, Teaching Assistant in the course *Foundations of Computer Science*, at Chengdu University of Information Technology -->

# 📫 Academic Services
### Journal Reviewer 
- IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI) 2024
- IEEE Transactions on Image Processing (TIP) 2023
- IEEE Transactions on Circuits and Systems for Video Technology (TCSVT) 2023

### Conference Reviewer
- IEEE Conference on International Conference on Computer Vision (ICCV) 2023

# 💻 Experience
- *2021.03 - present*, Technical Director, at [Megvii Technology](https://megvii.com/), China.
- *2019.03 - 2021.03*, Research Assistant, at [Megvii Technology](https://megvii.com/), China.
- *2018.11 - 2019.03*, Research Intern, at [Megvii Technology](https://megvii.com/), China.
- *2018.05 - 2020.11*, Research Intern, at [SenseTime Technology](https://www.sensetime.com/), China.
- *2017.05 - 2018.05*, Research Assistant, at [University of Electronic Science and Technology of China (UESTC)](https://en.uestc.edu.cn/), China.
