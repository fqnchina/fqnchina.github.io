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

I am a Lead Researcher and team manager in the Imaging Algorithm Center of VIVO. Our group is the core algorithm team responsible for advancing the photographic quality in the flagship smartphones with the cutting-edge technologies (3D, AIGC, etc).

I was a Senior Researcher in the Visual Computing Center of Tencent AI Lab between 2021 to 2023.

I was a Postdoctoral Researcher in Stanford University supervised by <a href="https://geometry.stanford.edu/member/guibas/"> Prof. Leonidas Guibas</a> between 2019 to 2021.

I obtained my PhD degree in the  <a href="http://www.cs.sdu.edu.cn/">Computer Science and Technology School</a> of <a href="http://www.sdu.edu.cn/">Shandong University</a> at 2019. I was supervised by <a href="http://www.cs.sdu.edu.cn/~baoquan/"> Prof. Baoquan Chen</a>.

If you are interested in the internship in our group for either publishing academic papers or working on engineering projects, feel free to drop me an email.

My research focus lies in computer graphics, 3D vision, image processing, and human-computer interaction. My recent effort has been spent on pushing the limit of 3D vision and reinforcement learning technologies to implement an intelligent embodied agent in both forms of physical robots and digital humans. <strong>For the complete publication list, please refer to my <a href="https://scholar.google.co.uk/citations?user=2cY2zwUAAAAJ&hl=en">google scholar page</a>.

# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025 (Oral)</div><img src='./QingnanFan_files/cvpr_2025.gif' alt="sym" width="100%"></div></div>
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
- SLAM3R is a real-time dense scene reconstruction system that regresses 3D points from video frames using feed-forward neural networks, without explicitly estimating camera parameters.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGGRAPH Asia & TOG 2023</div><img src='./QingnanFan_files/siga_2023_activity_small.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Scene-aware Activity Program Generation with Language Guidance](./QingnanFan_files/cvpr_2025.pdf)

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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022 (Oral)</div><img src='./QingnanFan_files/cvpr22_adela.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[ADeLA: Automatic Dense Labeling with Attention for Viewpoint Shift in Semantic Segmentation](./QingnanFan_files/cvpr_2022_adela.pdf)

<a href="https://yanchaoyang.github.io/">Yanchao Yang*</a>, 
Hanxiang Ren*, 
<a href="https://hughw19.github.io/">He Wang</a>, 
<a href="https://cs.stanford.edu/people/bshen88/">Bokui Shen</a>, 
<strong>Qingnan Fan</strong>, 
<a href="https://www.youyizheng.net/">Youyi Zheng</a>, 
<a href="https://ckllab.stanford.edu/">C. Karen Liu</a>,
<a href="http://geometry.stanford.edu/member/guibas/index.html" target="_blank">Leonidas Guibas</a>.
  
<a href="https://arxiv.org/abs/2107.14285" target="_blank">arXiv</a>
/
<a href="./QingnanFan_files/cvpr_2022_adela.bib">bibtex</a>
- We describe a method to deal with performance drop in semantic segmentation caused by viewpoint changes within multi-camera systems, where temporally paired images are readily available, but the annotations may only be abundant for a few typical views.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2021 (Oral)</div><img src='./QingnanFan_files/iccv_2021_captra3.png' alt="sym" width="100%"></div></div>
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

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
