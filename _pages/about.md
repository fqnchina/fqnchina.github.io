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

I am a Lead Researcher and Team Manager in the vivo BlueImage Lab. Our group is the core algorithm team responsible for advancing the photographic quality in the flagship smartphones with the cutting-edge technologies (3D, AIGC, etc).

I was a Senior Researcher in the Visual Computing Center of Tencent AI Lab between 2021 to 2023.

I was a Postdoctoral Researcher in Stanford University supervised by <a href="https://geometry.stanford.edu/member/guibas/"> Prof. Leonidas Guibas</a> between 2019 to 2021.

I obtained my PhD degree in the  <a href="http://www.cs.sdu.edu.cn/">Computer Science and Technology School</a> of <a href="http://www.sdu.edu.cn/">Shandong University</a> at 2019. I was supervised by <a href="http://www.cs.sdu.edu.cn/~baoquan/"> Prof. Baoquan Chen</a>.

My research focus lies in computational photography, 3D vision, Embodied AI.  I have published 40+ papers <a href='https://scholar.google.com/citations?user=2cY2zwUAAAAJ&hl=en'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FFqnchina%2Ffqnchina.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> at the top international conferences such as SIGGRAPH, CVPR, ICCV, including 10+ oral papers.

👩‍🎓🧑‍🎓 <span style="color:blue">**Internship at VIVO.** If you are interested in the research internship on computational photography, 3DV and Embodied AI, feel free to drop me an email.</span>

# 🔥 Tech Transfer

VIVO X200 series: <a href="https://www.dxomark.com/putting-the-vivo-x200-pro-to-the-test-in-china/">Telephoto enhancement via high-fidelity one-step diffusion​</a>

VIVO X300 series: 
- <a href="https://www.dxomark.com/vivo-x300-pro-camera-test//">Text image (Chinese/English) enhancement via diffusion prior​</a>
- <a href="https://www.dxomark.com/vivo-x300-pro-camera-test//">Landmark image enhancement via reference-guided diffusion​</a>
- <a href="https://www.dxomark.com/vivo-x300-pro-camera-test//">Lens bokeh distillation via one-step diffusion</a>

# 📝 Selected Publications 
**Equal contribution**$^\star$

## 🧑‍🎨 Computational photography

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026 </div><img src='./QingnanFan_files/iclr_2026.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[LiveMoments: Reselected Key Photo Restoration in Live Photos via Reference-guided Diffusion](./QingnanFan_files/iclr_2026.pdf)

Clara Xue, Zizheng Yan, Zhenning Shi, Yuhang Yu, Jingyu Zhuang, Qi Zhang, Jinwei Chen, <strong>Qingnan Fan</strong>.

- The first to address the problem of reselected key photo restoration in Live Photos.
- LiveMoments significantly improves perceptual quality and fidelity over existing solutions, including the recent flagships from vivo and iPhone.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025 </div><img src='./QingnanFan_files/iccv_2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[BokehDiff: Neural Lens Blur with One-Step Diffusion](./QingnanFan_files/iccv_2025.pdf)

Chengxuan Zhu, <strong>Qingnan Fan</strong>, Qi Zhang, Jinwei Chen, Huaqi Zhang, Chao Xu, Boxin Shi.
  
<a href="https://arxiv.org/abs/2507.18060" target="_blank">arXiv</a>
/
<a href="https://github.com/FreeButUselessSoul/bokehdiff" target="_blank">codes</a>
/
press: <a href="https://www.youtube.com/watch?v=kay87MWCY9U" target="_blank">Droider</a>

- The first neural lens blur rendering pipeline based on pretrained diffusion priors.
- A diffusion framework with only one inference step that achieves outstanding quality compared with previous methods, especially in regions where depth prediction fails.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025 </div><img src='./QingnanFan_files/cvpr_2025_tsd.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[TSD-SR: One-Step Diffusion with Target Score Distillation for Real-World Image Super-Resolution](./QingnanFan_files/cvpr_2025_tsd.pdf)

Linwei Dong*, <strong>Qingnan Fan*</strong>, Yihong Guo, Zhonghao Wang, Qi Zhang, Jinwei Chen, Yawei Luo, Changqing Zou.
  
<a href="https://arxiv.org/abs/2411.18263" target="_blank">arXiv</a>
/
<a href="https://github.com/Microtreei/TSD-SR" target="_blank">codes</a>

- The first image super-resolution work that leverages the pretrained diffusion transformer (DIT) prior, specifically Stable Diffusion 3.
- TSD-SR has superior restoration results (most of the metrics perform the best) and the fastest inference speed (e.g. 40 times faster than SeeSR) compared to the past Real-ISR approaches based on pre-trained diffusion priors.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025 </div><img src='./QingnanFan_files/nips_2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Text-Aware Real-World Image Super-Resolution via Diffusion Model with Joint Segmentation Decoders](./QingnanFan_files/nips_2025.pdf)

Qiming Hu, Linlong Fan, Yiyan Luo, Yuhang Yu, Xiaojie Guo, <strong>Qingnan Fan</strong>.
  
<a href="https://arxiv.org/abs/2506.04641" target="_blank">arXiv</a>
/
<a href="https://github.com/mingcv/TADiSR" target="_blank">codes</a>

- The first full-image text super-resolution work utilizing the diffusion priors.
- A novel diffusion-based SR framework, which integrates text-aware attention and joint segmentation decoders to recover not only natural details but also the structural fidelity of text regions in degraded real-world images.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MM 2025 (Oral) </div><img src='./QingnanFan_files/mm_2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[AuthFace: Towards Authentic Blind Face Restoration with Face-oriented Generative Diffusion Prior](./QingnanFan_files/mm_2025.pdf)

Guoqiang Liang, <strong>Qingnan Fan</strong>, Bingtao Fu, Jinwei Chen, Hong Gu, Lin Wang.

<a href="https://arxiv.org/abs/2410.09864" target="_blank">arXiv</a>
/
<a href="https://github.com/EthanLiang99/AuthFace" target="_blank">codes</a>

- Pioneering a new approach by enhancing the generative capabilities of pretrained T2I models for authentic face restoration, moving beyond traditional model design.
- A novel framework, namely AuthFace that achieves highly authentic face restoration results by exploring a face-oriented generative diffusion prior.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2021 </div><img src='./QingnanFan_files/tpami21_thumbnail.gif'  alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[A General Decoupled Learning Framework for Parameterized Image Operators](./QingnanFan_files/tpami_2021.pdf)

<strong>Qingnan Fan*</strong>, 
<a href="http://www.dongdongchen.bid/">Dongdong Chen*</a>, 
<a href="http://www.lyuan.org/">Lu Yuan</a>,
<a href="https://www.microsoft.com/en-us/research/people/ganghua/">Gang Hua</a>, 
<a href="http://staff.ustc.edu.cn/~ynh/">Nenghai Yu</a>, 
<a href="http://www.cs.sdu.edu.cn/~baoquan/">Baoquan Chen</a>.

<a href="https://arxiv.org/abs/1907.05852">arXiv</a>
/ 
<a href="https://github.com/fqnchina/DecoupleLearning">codes</a>
/
<a href="./QingnanFan_files/tpami_2021.bib">bibtex</a>
- A journal extension of our ECCV 2018 paper. We further propose a cheap parameter-tuning version of the decouple learning framework that enables real-time alternation between different image operators.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGGRAPH Asia & TOG 2018 </div><img src='./QingnanFan_files/siga18_thumbnail.png'  alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Image Smoothing via Unsupervised Learning](./QingnanFan_files/siggraph_asia_2018.pdf)

<strong>Qingnan Fan</strong>, 
<a href="http://jlyang.org/">Jiaolong Yang</a>, 
<a href="http://www.davidwipf.com/">David Wipf</a>, <a href="http://www.cs.sdu.edu.cn/~baoquan/">Baoquan Chen</a>,
<a href="https://www.microsoft.com/en-us/research/people/xtong/">Xin Tong</a>.

<a href="https://arxiv.org/abs/1811.02804">arXiv</a>
/ 
<a href="https://github.com/fqnchina/ImageSmoothing">codes</a>
/ 
<a href="https://www.dropbox.com/s/p3ql7etstto1g4e/siggraph_asia_2018_supp.pdf?dl=0">supp file</a>
/
<a href="./QingnanFan_files/siga_2018.bib">bibtex</a>
- Treat deep learning as an optimization tool to minimize the proposed image smoothing objective function in an unsupervised manner. Multiple different smoothing effects can be easily learned by adaptively changing the proposed objective function.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2018 (Oral) </div><img src='./QingnanFan_files/cvpr18_thumbnail_v2.png'  alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Revisiting Deep Intrinsic Image Decompositions](./QingnanFan_files/cvpr_2018.pdf)

<strong>Qingnan Fan</strong>, 
<a href="http://jlyang.org/">Jiaolong Yang</a>, 
<a href="https://www.microsoft.com/en-us/research/people/ganghua/">Gang Hua</a>, 
<a href="http://www.cs.sdu.edu.cn/~baoquan/">Baoquan Chen</a>,
<a href="http://www.davidwipf.com/">David Wipf</a>.

<a href="https://arxiv.org/abs/1701.02965">arXiv</a>
/ 
<a href="https://github.com/fqnchina/IntrinsicImage">codes</a>
/
<a href="./QingnanFan_files/cvpr_2018_v4_JL.pptx">slides</a>
/ <a href="./QingnanFan_files/cvpr_2018_supp.pdf">supp file</a> /
<a href="./QingnanFan_files/cvpr_2018_poster.pdf">poster</a>
/ 
<a href="./QingnanFan_files/cvpr_2018.bib">bibtex</a>
- The first demonstration of a single basic deep architecture capable of achieving state-of-the-art results when applied to each of the major intrinsic benchmarks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2018 (Oral) </div><img src='./QingnanFan_files/iccv17_thumbnail.png'  alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[A Generic Deep Architecture for Single Image Reflection Removal and Image Smoothing](./QingnanFan_files/iccv_2017.pdf)

<strong>Qingnan Fan</strong>, 
<a href="http://jlyang.org/">Jiaolong Yang</a>, 
<a href="https://www.microsoft.com/en-us/research/people/ganghua/">Gang Hua</a>, 
<a href="http://www.cs.sdu.edu.cn/~baoquan/">Baoquan Chen</a>,
<a href="http://www.davidwipf.com/">David Wipf</a>.

<a href="https://arxiv.org/abs/1708.03474">arXiv</a>
/ 
<a href="https://github.com/fqnchina/CEILNet">codes</a>
/ 
<a href="./QingnanFan_files/iccv_2017_supp.pdf">supp file</a>
/ 
<a href="./QingnanFan_files/iccv_2017_poster.pdf">poster</a>
/ 
<a href="./QingnanFan_files/iccv_2017.bib">bibtex</a>
- An advanced deep architecture for low-level vision tasks; A novel reflection image synthesis approach which enables outstanding generalization ability to real images with trained newtork.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGGRAPH Asia & TOG 2015 </div><img src='./QingnanFan_files/siga_2015.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[JumpCut: Non-Successive Mask Transfer and Interpolation for Video Cutout](https://www.dropbox.com/s/q2xvrag0g5l8wii/%5B2015%5D%5Bsiggraph_asia%5DJumpCut%20Non-Successive%20Mask%20Transfer%20and%20Interpolation%20for%20Video%20Cutout.pdf?dl=0)

<strong>Qingnan Fan</strong>,
<a href="http://vr.sdu.edu.cn/~zf/">Fan Zhong</a>,
<a href="http://www.cs.huji.ac.il/~danix/">Dani Lischinski</a>,
<a href="http://www.math.tau.ac.il/~dcor/">Daniel Cohen-Or</a>,
<a href="http://www.cs.sdu.edu.cn/~baoquan/">Baoquan Chen</a>.

<a href="https://github.com/sduirc/JumpCut">codes</a>
/ 
<a href="https://www.dropbox.com/scl/fi/jr84cmwryf50vnb61wb6e/siga_2015.pptx?dl=0&rlkey=9jn17dt75d0g2bi23wlax5hb6">slides</a>
/ 
<a href="https://www.youtube.com/watch?v=drqnwDg0JFM&t=77s">video</a>
/ 
<a href="https://www.dropbox.com/s/4b76crsifryn6rq/siga_2015_supp.rar?dl=0">supp file</a>
/ 
<a href="https://www.dropbox.com/s/v0v3pkrhz1vizyt/VideoSeg_dataset.rar?dl=0">dataset</a>
/ 
<a href="./QingnanFan_files/siga_2015.bib">bibtex</a>
- An interactive real-time video segmentation algorithm. Significantly improve the video cutout accuracy and efficiency.
</div>
</div>

## 📚 Embodied AI

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025 (Highlight)</div><img src='./QingnanFan_files/cvpr_2025.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[SLAM3R: Real-Time Dense Scene Reconstruction from Monocular RGB Videos](./QingnanFan_files/cvpr_2025.pdf)

Yuzheng Liu*,
<a href="https://scholar.google.com/citations?user=vtZMhssAAAAJ&hl=en/">Siyan Dong*</a>, 
<a href="https://ffrivera0.github.io/">Shuzhe Wang</a>, 
<a href="https://yd-yin.github.io/">Yingda Yin</a>, 
<a href="https://yanchaoyang.github.io/">Yanchao Yang</a>, 
<strong>Qingnan Fan</strong>, 
<a href="https://cfcs.pku.edu.cn/baoquan/">Baoquan Chen</a>.
  
<a href="https://arxiv.org/abs/2412.09401" target="_blank">arXiv</a>
/
<a href="https://www.youtube.com/watch?v=V1SHYkCTqHc" target="_blank">video</a>
/
<a href="https://github.com/PKU-VCL-3DV/SLAM3R/" target="_blank">codes</a>

- **Award**: China3DV 2025, Top1 paper.
- SLAM3R is a real-time dense scene reconstruction system that regresses 3D points from video frames using feed-forward neural networks, without explicitly estimating camera parameters.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='./QingnanFan_files/cvpr_2025_reloc3r.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Reloc3r: Large-Scale Training of Relative Camera Pose Regression for Generalizable, Fast, and Accurate Visual Localization](./QingnanFan_files/cvpr_2025_reloc3r.pdf)

<a href="https://siyandong.github.io/">Siyan Dong*</a>,
<a href="https://ffrivera0.github.io/">Shuzhe Wang*</a>,
<a href="http://b1ueber2y.me/">Shaohui Liu</a>,
<a href="">Lulu Cai</a>,
<strong>Qingnan Fan</strong>, 
<a href="https://users.aalto.fi/~kannalj1/">Juho Kannala</a>,
<a href="https://yanchaoyang.github.io/">Yanchao Yang</a>.
 
<a href="https://arxiv.org/abs/2412.08376" target="_blank">arXiv</a>
/
<a href="https://www.youtube.com/watch?v=uHcEZRPOE5s" target="_blank">video</a>
/
<a href="https://huggingface.co/spaces/siyan824/reloc3r-512_relpose" target="_blank">demo (online)</a>
/
<a href="https://github.com/ffrivera0/reloc3r" target="_blank">codes</a>

- Reloc3r is a simple yet effective camera pose estimation framework that combines a pre-trained two-view relative camera pose regression network with a multi-view motion averaging module.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGGRAPH Asia & TOG 2023</div><img src='./QingnanFan_files/siga_2023_activity_small.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Scene-aware Activity Program Generation with Language Guidance](./QingnanFan_files/sigatog_2023.pdf)

Zejia Su,
<strong>Qingnan Fan</strong>, 
<a href="https://xuelin-chen.github.io/">Xuelin Chen</a>, 
<a href="https://people.scs.carleton.ca/~olivervankaick/">Oliver van Kaick</a>, 
<a href="https://vcc.tech/~huihuang">Hui Huang</a>, 
<a href="https://csse.szu.edu.cn/staff/ruizhenhu/">Ruizhen Hu</a>.
  
<a href="https://toddbear.github.io/LangGuidedProg/" target="_blank">project page</a>
/
<a href="./QingnanFan_files/tog_2023_supp.pdf" target="_blank">supp file</a>
/
<a href="./QingnanFan_files/tog_2023.bib">bibtex</a>
- We address the problem of scene-aware activity program generation, which requires decomposing a given activity task into instructions that can be sequentially performed within a target scene to complete the activity.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGGRAPH Asia 2023</div><img src='./QingnanFan_files/siga_2023_ease.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[C·ASE: Learning Conditional Adversarial Skill Embeddings for Physics-based Characters](./QingnanFan_files/siga_2023.pdf)

<a href="https://frank-zy-dou.github.io/">Zhiyang Dou</a>,
<a href="https://xuelin-chen.github.io/">Xuelin Chen</a>, 
<strong>Qingnan Fan</strong>, 
<a href="https://homepages.inf.ed.ac.uk/tkomura/">Taku Komura</a>, 
<a href="https://engineering.tamu.edu/cse/profiles/Wang-Wenping.html">Wenping Wang</a>.
  
<a href="http://arxiv.org/abs/2309.11351" target="_blank">arXiv</a>
/
<a href="https://frank-zy-dou.github.io/projects/CASE/index.html" target="_blank">project page</a>
/
<a href="https://youtu.be/Cgq6JbQ1VW4" target="_blank">video</a>
/
<a href="./QingnanFan_files/siga_2023.bib">bibtex</a>
- We present C·ASE, an efficient and effective framework that learns conditional Adversarial Skill Embeddings for Elite physics-based characters.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2023</div><img src='./QingnanFan_files/iclr_2023.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[DualAfford: Learning Collaborative Visual Affordance for Dual-gripper Object Manipulation](./QingnanFan_files/iclr_2023.pdf)
  
<a href="https://www.researchgate.net/profile/Yan-Zhao-182" target="_blank">Yan Zhao*</a>,
<a href="https://warshallrho.github.io/" target="_blank">Ruihai Wu*</a>,
Zhehuan Chen,
Yourong Zhang,
<strong>Qingnan Fan</strong>, 
<a href="https://cs.stanford.edu/~kaichun/">Kaichun Mo</a>, 
<a href="https://zsdonghao.github.io/" target='_blank'>Hao Dong</a>.
  
<a href="https://arxiv.org/abs/2207.01971" target="_blank">arXiv</a>
/
<a href="https://hyperplane-lab.github.io/DualAfford/" target="_blank">project page</a>
/
<a href="https://www.youtube.com/watch?v=3NsnIIrgv0w" target="_blank">video</a>
/
<a href="./QingnanFan_files/iclr-2023.bib">bibtex</a>
- We propose a novel learning framework, DualAfford, to learn collaborative affordance for dual-gripper manipulation tasks. The core design of the approach is to reduce the quadratic problem for two grippers into two disentangled yet interconnected subtasks for efficient learning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='./QingnanFan_files/cvpr_2023.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[3D-Aware Object Goal Navigation via Simultaneous Exploration and Identification](./QingnanFan_files/cvpr_2023.pdf)
  
<a href="https://jzhzhang.github.io/">Jiazhao Zhang*</a>, 
<a href="https://liudai-homepage.github.io/">Liu Dai*</a>, 
<a href="https://mfp0610.github.io/">Fanpeng Meng</a>, 
<strong>Qingnan Fan</strong>, 
<a href="https://xuelin-chen.github.io/">Xuelin Chen</a>, 
<a href="https://kevinkaixu.net/">Kai Xu</a>, 
<a href="https://hughw19.github.io/">He Wang</a>.
  
<a href="https://arxiv.org/abs/2212.00338" target="_blank">arXiv</a>
/
<a href="https://pku-epic.github.io/3D-Aware-ObjectNav/" target="_blank">project page</a>
/
<a href="./QingnanFan_files/cvpr_2023.bib">bibtex</a>
- We propose a framework for the challenging 3D-aware Object goal navigation task based on two straightforward sub-policies. The two sub-polices, namely corner-guided exploration policy and category-aware identification policy, simultaneously perform by utilizing online fused 3D points as observation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2022</div><img src='./QingnanFan_files/vat_mart.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[VAT-Mart: Learning Visual Action Trajectory Proposals for Manipulating 3D ARTiculated Objects](./QingnanFan_files/iclr_2022.pdf)
  
<a href="https://warshallrho.github.io/" target="_blank">Ruihai Wu*</a>,
<a href="https://www.researchgate.net/profile/Yan-Zhao-182" target="_blank">Yan Zhao*</a>,
<a href="https://cs.stanford.edu/~kaichun/">Kaichun Mo*</a>, 
<a href="https://guozz.cn/" target='_blank'>Zizheng Guo</a>,
<a href="https://github.com/galaxy-qazzz" target='_blank'>Yian Wang</a>,
<a href="https://tianhaowuhz.github.io/" target="_blank">Tianhao Wu</a>,
<strong>Qingnan Fan</strong>, 
<a href="https://xuelin-chen.github.io/" target='_blank'>Xuelin Chen</a>,
<a href="http://geometry.stanford.edu/member/guibas/index.html" target="_blank">Leonidas Guibas</a>,
<a href="https://zsdonghao.github.io/" target='_blank'>Hao Dong</a>.
  
<a href="https://arxiv.org/abs/2106.14440" target="_blank">arXiv</a>
/
<a href="https://hyperplane-lab.github.io/vat-mart" target="_blank">project page</a>
/
<a href="https://github.com/warshallrho/VAT-Mart" target="_blank">codes</a>
/
<a href="https://www.youtube.com/watch?v=HjhsLKf1eQY" target="_blank">video</a>
/
<a href="./QingnanFan_files/iclr-2022.bib">bibtex</a>
- **Award**: WAIC 2025, Young Outstanding Paper Award
- We design an interaction-for-perception framework, VAT-MART, to learn actionable visual representations for more effective manipulation of 3D articulated objects.
</div>
</div>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022 (Oral)</div><img src='./QingnanFan_files/cvpr22_adela_v2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[ADeLA: Automatic Dense Labeling with Attention for Viewpoint Shift in Semantic Segmentation](./QingnanFan_files/cvpr_2022_adela.pdf)
  
<a href="https://yanchaoyang.github.io/">Yanchao Yang* </a>, 
Hanxiang Ren*,
<a href="https://hughw19.github.io/">He Wang</a>,  
<a href="https://cs.stanford.edu/people/bshen88/">Bokui Shen</a>, 
<strong>Qingnan Fan</strong>, 
<a href="https://www.youyizheng.net/">Youyi Zheng</a>, 
<a href="https://ckllab.stanford.edu/">C. Karen Liu</a>,
<a href="http://geometry.stanford.edu/member/guibas/index.html" target="_blank">Leonidas Guibas</a>.
  
<a href="https://arxiv.org/abs/2107.14285" target="_blank">arXiv</a>
/
<a href="https://github.com/ReNginx/ADeLA" target="_blank">codes</a>
/
<a href="./QingnanFan_files/cvpr_2022_adela.bib">bibtex</a>
- We describe a method to deal with performance drop in semantic segmentation caused by viewpoint changes within multi-camera systems, where temporally paired images are readily available, but the annotations may only be abundant for a few typical views.
</div>
</div> -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='./QingnanFan_files/eccv_2022_AdaAfford.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[AdaAfford: Learning to Adapt Manipulation Affordance for 3D Articulated Objects via Few-shot Interactions](./QingnanFan_files/eccv_2022_AdaAfford.pdf)
  
<a href="https://github.com/galaxy-qazzz">Yian Wang*</a>, 
<a href="https://warshallrho.github.io/" target="_blank">Ruihai Wu*</a>,
<a href="https://cs.stanford.edu/~kaichun/">Kaichun Mo*</a>, 
Jiaqi Ke,
<strong>Qingnan Fan</strong>, 
<a href="http://geometry.stanford.edu/member/guibas/index.html" target="_blank">Leonidas Guibas</a>,
<a href="https://zsdonghao.github.io/" target='_blank'>Hao Dong</a>.
  
<a href="https://arxiv.org/abs/2112.00246" target="_blank">arXiv</a>
/
<a href="https://hyperplane-lab.github.io/AdaAfford/" target="_blank">project page</a>
/
<a href="https://github.com/wangyian-me/AdaAffordCode/" target="_blank">codes</a>
/
<a href="https://www.youtube.com/watch?v=Qaq0YkpNxe4">video</a>
/
<a href="./QingnanFan_files/eccv_2022_AdaAfford.bib">bibtex</a>
- In this paper, we propose a novel framework, named AdaAfford, that learns to perform very few test-time interactions for quickly adapting the affordance priors to more accurate instance-specific posteriors.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='./QingnanFan_files/eccv_2022_localization.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Towards Accurate Active Camera Localization](./QingnanFan_files/eccv_2022_localization.pdf)
  
Qihang Fang*, 
<a href="https://yd-yin.github.io/">Yingda Yin*</a>, 
<strong>Qingnan Fan</strong>, 
<a href="https://fxia22.github.io/">Fei Xia</a>,
<a href="https://scholar.google.com/citations?user=vtZMhssAAAAJ&hl=en/">Siyan Dong</a>, 
Sheng Wang,
<a href="https://juewang725.github.io/">Jue Wang</a>,
<a href="http://geometry.stanford.edu/member/guibas/index.html" target="_blank">Leonidas Guibas</a>,
<a href="https://cfcs.pku.edu.cn/baoquan/">Baoquan Chen</a>.
  
<a href="https://arxiv.org/abs/2012.04263" target="_blank">arXiv</a>
/
<a href="https://github.com/qhFang/AccurateACL" target="_blank">codes</a>
/
<a href="https://www.youtube.com/watch?v=pDMoZ6pjkkQ">video</a>
/
<a href="./QingnanFan_files/eccv_2022_localization_supp.pdf">supp file</a>
/
<a href="./QingnanFan_files/eccv_2022_localization.bib">bibtex</a>
- In this work, we explicitly model the camera and scene uncertainty components to solve the problem of active camera localization by reinforcement learning. Our algorithm improves over the state-of-the-art Markov Localization based approaches by a large margin on the fine-scale camera pose accuracy.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='./QingnanFan_files/cvpr22_mapping.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Multi-Robot Active Mapping via Neural Bipartite Graph Matching](./QingnanFan_files/cvpr_2022_mapping.pdf)
  
Kai Ye*, 
<a href="https://scholar.google.com/citations?user=vtZMhssAAAAJ&hl=en/">Siyan Dong*</a>, 
<strong>Qingnan Fan</strong>, 
<a href="https://hughw19.github.io/">He Wang</a>, 
<a href="https://ericyi.github.io/">Li Yi</a>, 
<a href="https://fxia22.github.io/">Fei Xia</a>,
<a href="https://juewang725.github.io/">Jue Wang</a>,
<a href="https://cfcs.pku.edu.cn/baoquan/">Baoquan Chen</a>.
  
<a href="https://arxiv.org/abs/2203.16319" target="_blank">arXiv</a>
/
<a href="https://github.com/siyandong/NeuralCoMapping" target="_blank">codes</a>
/
<a href="https://www.youtube.com/watch?v=M7LRzWDG6mk" target="_blank">video</a>
/
<a href="./QingnanFan_files/cvpr_2022_mapping_supp.pdf">supp file</a>
/
<a href="./QingnanFan_files/cvpr_2022_mapping_poster.pdf">poster</a>
/
<a href="./QingnanFan_files/cvpr_2022_mapping.bib">bibtex</a>
- We propose a novel multi-robot active mapping algorithm by reducing the problem to bipartite graph matching, solved by the proposed multiplex graph neural network (mGNN) via reinforcement learning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2021 (Oral)</div><img src='./QingnanFan_files/iccv_2021_captra3.gif' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">
[CAPTRA: CAtegory-level Pose Tracking for Rigid and Articulated Objects from Point Clouds](./QingnanFan_files/iccv_2021_captra.pdf)

Yijia Weng*, 
<a href="https://hughw19.github.io/">He Wang*</a>, 
Qiang Zhou,
<a href="https://yzqin.github.io/">Yuzhe Qin</a>, 
<a href="https://geometry.stanford.edu/person.php?id=duanyq19">Yueqi Duan</a>, 
<strong>Qingnan Fan</strong>, 
<a href="https://cfcs.pku.edu.cn/baoquan/">Baoquan Chen</a>,
<a href="http://ai.ucsd.edu/~haosu/">Hao Su</a>,
<a href="https://geometry.stanford.edu/member/guibas/index.html">Leonidas Guibas</a>.

<a href="https://arxiv.org/abs/2104.03437">arXiv</a>
/
<a href="https://yijiaweng.github.io/CAPTRA/" target="_blank">project page</a>
/
<a href="https://github.com/HalfSummer11/CAPTRA">codes</a>
/
<a href="https://www.youtube.com/watch?v=JFPcOHCH2O0">video</a>
/
<a href="./QingnanFan_files/iccv_2021_captra.bib">bibtex</a>
- For the first time, we propose a unified framework that can handle 9-DoF pose tracking for novel rigid object instances as well as per-part pose tracking for 3D articulated objects.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2021 (Oral)</div><img src='./QingnanFan_files/cvpr21_localization_thumbnail_v2.png'  alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Robust Neural Routing Through Space Partitions for Camera Relocalization in Dynamic Indoor Environments](./QingnanFan_files/cvpr_2021_localization.pdf)

<a href="https://scholar.google.com/citations?user=vtZMhssAAAAJ&hl=en/">Siyan Dong*</a>, 
<strong>Qingnan Fan*</strong>, 
<a href="https://hughw19.github.io/">He Wang</a>, 
Ji Shi,
<a href="https://ericyi.github.io/">Li Yi</a>, 
<a href="https://www.cs.princeton.edu/~funk/">Thomas Funkhouser</a>,
<a href="https://cfcs.pku.edu.cn/baoquan/">Baoquan Chen</a>,
<a href="https://geometry.stanford.edu/member/guibas/index.html">Leonidas Guibas</a>.

<a href="https://arxiv.org/abs/2012.04746">arXiv</a>
/
<a href="https://github.com/siyandong/NeuralRouting">codes</a>
/
<a href="https://www.youtube.com/watch?v=_1eInWKbuVA" target="_blank">video</a>
/
<a href="./QingnanFan_files/cvpr_2021_localization.bib">bibtex</a>
- A novel outlier-aware neural tree to tackle the camera localization challenges in dynamic indoor environments. It achieves the best performance in the RIO-10 benchmark.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2020</div><img src='./QingnanFan_files/nips_2020_v2.gif'  alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Generative 3D Part Assembly via Dynamic Graph Learning](./QingnanFan_files/nips_2020_part_assembly.pdf)

Jialei Huang*,
<a href="https://championchess.github.io/">Guanqi Zhan*</a>, 
<strong>Qingnan Fan</strong>, 
<a href="https://cs.stanford.edu/~kaichun/">Kaichun Mo</a>, 
<a href="https://linsats.github.io/">Lin Shao</a>,
<a href="https://cfcs.pku.edu.cn/baoquan/">Baoquan Chen</a>, 
<a href="https://geometry.stanford.edu/member/guibas/index.html">Leonidas Guibas</a>, 
<a href="https://zsdonghao.github.io/">Hao Dong</a>.

<a href="https://arxiv.org/abs/2006.07793">arXiv</a>
/ 
<a href="https://hyperplane-lab.github.io/Generative-3D-Part-Assembly/">project page</a>
/ 
<a href="https://github.com/Championchess/Generative-3D-Part-Assembly">codes</a>
/ 
<a href="./QingnanFan_files/nips_2020_part_assembly.bib">bibtex</a>
/ 
press (<a href="https://mp.weixin.qq.com/s?__biz=MzA3MzI4MjgzMw==&mid=2650799676&idx=4&sn=1d2c6761bd3892686aacfc5d5dc1c14c&chksm=871a3a42b06db35402bc4e3ed6334f99b0e408ccf9ea30a072ec8bbd4d510e2a35887b563408&scene=0&xtrack=1&key=b21c8bfc2e98d5d832fabcf5a6128c64545a73289c8282c226af065f0e8e665138087c317b186eaebc3355bd9f2e7898b264453a14bd40dffbbb6fef2ef4abeec2a55a98cd3059f89720fff44355005b3bd6c07b912f9076963bed81b37c096beb0b826a868249f36912f97e3e7aaddf2db31632acfed190f0cc958aac41e3d8&ascene=1&uin=NDE4NjY0ODU1&devicetype=Windows+10+x64&version=6300002f&lang=zh_CN&exportkey=AWEFijHWuK4REu4n0VpJCOc%3D&pass_ticket=%2FxhWQurVrRrCi87xYVsAtep82meBarP1vauCZheyCMo17a9a4Hpo24ulX3EPdonG&wx_header=0">机器之心</a>,<a href="https://mp.weixin.qq.com/s?__biz=MzA5ODEzMjIyMA==&mid=2247547123&idx=4&sn=dea62a5edc7a65687d08872ce7ebb5ac&chksm=90943160a7e3b876a68ad4b69af47d5b57e40d50d5ba0034db79e2801dc6d6531eacee36e635&mpshare=1&scene=1&srcid=1017FVRyXZjpjkBieLaw7eQX&sharer_sharetime=1602869239113&sharer_shareid=49c5a30c6732bec1bffca4ce2cfd738b&key=905d9831417cd6b735a634c11fe9e11a86e7bec0fce71b3b6a37c07ef6c6049aea49aff5f0223327ab828a3657dbcd0fb4b9aad0c19b9ee4dedc401426ecd5fc0a44f846a5fb951c4039c3b26e3184934d8810e75e3a13d21762ae46ec85e060c0e769031a118bb4fcaf7d0d6d6c8944979019e20273ca05103f170d592abb78&ascene=1&uin=NDE4NjY0ODU1&devicetype=Windows+10+x64&version=6300002f&lang=zh_CN&exportkey=AYpfmqiYvoArYHlAv2MUXGs%3D&pass_ticket=%2FxhWQurVrRrCi87xYVsAtep82meBarP1vauCZheyCMo17a9a4Hpo24ulX3EPdonG&wx_header=0">AI科技评论</a>)
- A dynamic graph learning algorithm for autonomous part assembly. It learns to reason an assembly-oriented dynamically-evolved relation graph, which indicates the assembly process which is guided by the major parts (chair leg&seat).
</div>
</div>


<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGGRAPH & TOG 2014 </div><img src='./QingnanFan_files/a97-lu.gif' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">
[Build-to-Last: Strength to Weight 3D Printed Objects](https://www.dropbox.com/s/f84dqmtht41k8vv/a97-lu.pdf?dl=0)

<a href="http://vr.sdu.edu.cn/~lulin/">Lin Lu</a>,
<a href="http://www.cs.bgu.ac.il/~asharf/">Andrei Sharf</a>,
Haisen Zhao, Yuan Wei,
<strong>Qingnan Fan</strong>, Xuelin Chen,
<a href="http://www.animlife.com/">Yann Savoye</a>,
<a href="http://www.cs.sdu.edu.cn/zh/60">Changhe Tu</a>,
<a href="http://www.math.tau.ac.il/~dcor/">Daniel Cohen-Or</a>,
<a href="http://www.cs.sdu.edu.cn/~baoquan/">Baoquan Chen</a>.

<a href="https://www.youtube.com/watch?v=V5IrPSvcm_8&t=5s">video</a>
/ 
<a href="./QingnanFan_files/sig_2014.bib">bibtex</a>
- Reduce the material cost and weight of a given object while providing a durable printed model that is resistant to impact and external forces.
</div>
</div> -->

# 🎖 Honors and Awards       
- *2022*, Tencent Outstanding Contributor
- *2020*, CCF Doctorial Dissertation Award Nominee (CCF 优博提名)
- *2018*, Academic Star Nominee of Shandong University (10/20000)
- *2015*, Presidential Scholarship of Shandong University (35/20000) (Highest honor for students in SDU, only 35 elected among around 20000 candidates)

# 📖 Educations
- *2019.09 - 2021.03*, PostDoc, Stanford University
- *2014.09 - 2019.06*, Ph.D., Shandong University
- *2010.09 - 2014.06*, Undergraduate, Shandong University

# 💬 Invited Talks      
- *2022.04*, Active 3D scene understanding and its applications, “三维视觉与智能图形”前沿论坛, 图图名师讲堂
- *2021.10*, Visual Localization, Embodied AI Workshop, Valse
- *2019.01*, Deep Learning in Computational Photography, USC ICT/UW Reality Lab/Berkeley/Stanford/Google/MSR
- *2018.12*, Deep Learning for Single Image Artifact Removal, ACCV Tutorial
- *2018.12*, Image Smoothing via Unsupervised Learning, GAMES Webinar
- *2018.08*, Discovering Unsupervised Learning in Image Processing, CIA, Cambridge University

# 💻 Internships and Visiting students
- *2018.04 - 2019.08*, Beijing Film Academy, China.
- *2018.08 - 2018.10*, University of Cambridge, UK.
- *2016.09 - 2018.03*, Microsoft Research Asia, China.
- *2015.04 - 2015.05*, Tel Aviv University, Israel.
- *2014.10 - 2014.11*, The Hebrew University of Jerusalem, Israel.
