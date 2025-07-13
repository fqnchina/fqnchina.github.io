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

My research focus lies in computer graphics, 3D vision, image processing, and human-computer interaction.  I have published about 40 papers at the top international conferences. <strong>For the complete publication list, please refer to my <a href="https://scholar.google.co.uk/citations?user=2cY2zwUAAAAJ&hl=en">google scholar page</a>.
<!-- <a href='https://scholar.google.com/citations?user=2cY2zwUAAAAJ&hl=en'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> --> 

👩‍🎓🧑‍🎓 <span style="color:blue">**Internship at VIVO.** If you are interested in the research internship in our group on computational photography, 3DV and embodied ai, feel free to drop me an email.</span>

# 🔥 Tech Transfer
VIVO X200 series: <a href="https://www.vivo.com.cn/brand/news/detail?id=1273&type=0">Telephoto Image Enhancement​</a>

# 📝 Selected Publications 
**Equal contribution**$^\star$

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
- SLAM3R is a real-time dense scene reconstruction system that regresses 3D points from video frames using feed-forward neural networks, without explicitly estimating camera parameters.
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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022 (Oral)</div><img src='./QingnanFan_files/cvpr22_adela_v2.png' alt="sym" width="100%"></div></div>
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
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2021 (Oral)</div><img src='./QingnanFan_files/iccv_2021_captra3.gif' alt="sym" width="100%"></div></div>
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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGGRAPH & TOG 2014 </div><img src='./QingnanFan_files/a97-lu.gif' alt="sym" width="100%"></div></div>
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
</div>

# 🎖 Honors and Awards       
- *2022* Tencent Outstanding Contributor. 
- *2020* CCF Doctorial Dissertation Award Nominee (CCF 优博提名)
- *2018* Academic Star Nominee of Shandong University (10/20000)
- *2015* Presidential Scholarship of Shandong University (35/20000) (Highest honor for students in SDU, only 35 elected among around 20000 candidates)

# 📖 Educations
- *2019 - 2021*, PostDoc, Stanford University
- *2014 - 2019*, Ph.D., Shandong University.
- *2010 - 2014*, Undergraduate, Shandong University. 

# 💬 Invited Talks      
- *2022.04*, Active 3D scene understanding and its applications, “三维视觉与智能图形”前沿论坛, 图图名师讲堂
- *2021.10*, Visual Localization, Embodied AI Workshop, Valse
- *2019.01*, Deep Learning in Computational Photography, USC ICT/UW Reality Lab/Berkeley/Stanford/Google/MSR
- *2018.12*, Deep Learning for Single Image Artifact Removal, ACCV Tutorial
- *2018.12*, Image Smoothing via Unsupervised Learning, GAMES Webinar
- *2018.08*, Discovering Unsupervised Learning in Image Processing, CIA, Cambridge University

# 💻 Internships/Visiting students
- *2018 - 2019*, Beijing Film Academy, China.
- *2018*, University of Cambridge, UK.
- *2016-2018*, Microsoft Research Asia, China.
- *2015*, Tel Aviv University, Israel.
- *2014*, The Hebrew University of Jerusalem, Israel.
