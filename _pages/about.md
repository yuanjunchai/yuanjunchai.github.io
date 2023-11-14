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

Hi! Here is Yuanjun Chai (Y-wen Joon, Ch-eye), aka Allen. I work at [VMware AI Lab](https://www.vmware.com/artificial-intelligence/ai-labs.html) <img src='./images/vmwarelogo.jpeg' style='width: 3.3em;'>, working on AI for cloud native group.


I graduated with highest honors from Xidian University, earning a bachelor's degree. My thesis about inpainting received invaluable support by [Chao Dong](https://scholar.google.com/citations?user=OSDCB0UAAAAJ&hl=en&oi=ao) from SIAT-CAS <img src='./images/siat.jpeg' style='width: 1.6em;'>. Also, I had the privilege of collaborating with [Chao Dong](https://scholar.google.com/citations?user=OSDCB0UAAAAJ&hl=en&oi=ao) and [Yu Qiao](https://scholar.google.com/citations?hl=en&user=gFtI-8QAAAAJ) from Chinese Academcy of Sciences <img src='./images/cas.jpeg' style='width: 1.6em;'> working on image&video super-resolution, [Jason Cheung](https://www.ortho.hku.hk/biography/cheung-pui-yin-jason/) from HKU <img src='./images/hku.png' style='width: 1.6em;'> working on AI healthcare, [Yue Gao](https://www.gaoyue.org/) and [Eric Yi](https://scholar.google.com/citations?user=UyZL660AAAAJ&hl=en) from Tsinghua University <img src='./images/tsinghua.png' style='width: 1.6em;'> working on Embodied AI.


Not only diving into research, I am also willing to empower new technologies into products to **make people's lives better**. Thus, I co-founded a start-up [INGREM inc](https://gazerecorder.com/gazepointer/), **to help high-paraplegia disabled people** using computer with precise eyes controling platform. Previously, I worked in [YeahMobi](https://en.yeahmobi.com/) -- affiliation of [Alibaba Group](https://www.alibabagroup.com/en-US) <img src='./images/Alibaba-Logo.png' style='width: 3.3em;'>, as a senior machine learning scientist (P8 expert). I was responsible for the all technical development of AIGC platform [Kreado AI](https://kreadoai.com/) <img src='./images/kreado_logo.png' style='width: 2.8em;'>, including AI Video Creation, AI model, custom clone service, and etc. Then, I am currently a senior machine learning engineer at VMware AI Lab <img src='./images/vmware.png' style='width: 2.3em;'>, working on RAG-based LLM (Retrieval Augmented Generation) and Multi-modal LLM.

### Research Interests:

- **AIGC (AI Generative Content)**: RAG-based LLM, Multi-modal LLM, text-to-image, text-to-video
- **Virtual Avatar**: 2D&3D talking face generation, voice clone, custom character
- **AI in healthcare**: medical image, medical LLM
- **Computer Vision**: low-level vision, high-level vision
- **Embodied AI**: sim2real, multi-model perception

Above things are my research interests. If you are interested in any of these topics and would like to academic collaborations, please feel free to contact me at [yuanjunchai89@gmail.com](mailto:yuanjunchai89@gmail.com).

By the way, with strong research and industry experience, I decide to **seek for a PhD position NOW**. Although PhD is a tough journey, but I could overcome it with responsibility, active feedback, and all great supervisors&collaborators. If you are interested in my research and applications, please directly contact me.


<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2023.07*: &nbsp;🎉🎉 Thrilled to join VMware AI Lab as MLE! We do some interesting projects on RAG-based LLM like [h2oGPT](https://github.com/h2oai/h2ogpt) (⭐️8k+).
- *2023.04*: &nbsp;🔥🔥 Our AIGC platform [Kreado AI](https://kreadoai.com/) has released to all over the world！
- *2022.04*: &nbsp;👏👏 Glad to obtain fully-funded PhD offer from University of HongKong (HKU)!
- *2021.09*: &nbsp;🥰🥰 Our eyes control platform has helped high-paraplegia disabled people more than 300!
- *2021.08*: &nbsp;🎉🎉 Our [IKC](https://github.com/yuanjunchai/IKC) -- CVPR project about real-world super-resolution get more than ⭐️200+.

# 📝 Publications 
## 👁️ Computer Vision
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR</div><img src='images/ikc_arch02.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**IKC: Blind Super-Resolution With Iterative Kernel Correction**](https://arxiv.org/pdf/1904.03377.pdf)

Jinjin Gu, Hannan Lu, Wangmeng Zuo, Chao Dong

[**Project**](https://www.jasongt.com/projectpages/IKC.html) \| [![](https://img.shields.io/github/stars/yuanjunchai/IKC?style=social&label=Code+Stars)](https://github.com/yuanjunchai/IKC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose an Iterative Kernel Correction (IKC) method for blur kernel estimation in blind SR problem, where the blur kernels are unknown. We draw the observation that kernel mismatch could bring regular artifacts (either over-sharpening or over-smoothing), which can be applied to correct inaccurate blur kernels. Thus we introduce an iterative correction scheme – IKC that achieves better results than direct kernel estimation. We further propose an effective SR network architecture using spatial feature transform (SFT) layers to handle multiple blur kernels, named SFTMD.
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🖥️ Innovation Bridge
## 🧑‍🎨 AIGC (Generative Model)
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/kreado03.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Kreado AI: AIGC Platform for Marketing Content Generation**](https://kreadoai.com/)

YeahMobi.inc

<!-- [**Project**](https://www.jasongt.com/projectpages/IKC.html) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- We propose a new AIGC platform for marketing content generation, named Kreado AI. Kreado AI is a hybrid worldwide AIGC platform that combines the strengths of Virtual Avatar (talking-face generation, voice clone, LLM), AI model (text-to-image, LoRA, control net), many AI tools and AI property. Here I mainly focus on the Virtual Avatar and AI model algorithms improvement, as well as collaborate with system architect for entire architecture improvement. Users radiate to Europe, Africa, Southeast Asia, and the Americas, with quarterly revenue exceeding US$1 million.
</div>
</div>

## 🧙‍♂️ RAG-based LLM
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/h2oGPT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**h2o GPT: AIGC Platform for Marketing Content Generation**](https://gpt.h2o.ai/)

VMware.inc

<!-- [**Project**](https://www.jasongt.com/projectpages/IKC.html) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- We propose a new AIGC platform for marketing content generation, named Kreado AI. Kreado AI is a hybrid worldwide AIGC platform that combines the strengths of Virtual Avatar (talking-face generation, voice clone, LLM), AI model (text-to-image, LoRA, control net), many AI tools and AI property. Here I mainly focus on the Virtual Avatar and AI model algorithms improvement, as well as collaborate with system architect for entire architecture improvement. Users radiate to Europe, Africa, Southeast Asia, and the Americas, with quarterly revenue exceeding US$1 million.
</div>
</div>


## 👨‍⚕️ AI healthcare & Charity
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/kreado02.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Kreado AI: AIGC Platform for Marketing Content Generation**](https://kreadoai.com/)

YeahMobi.inc

<!-- [**Project**](https://www.jasongt.com/projectpages/IKC.html) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- We propose a new AIGC platform for marketing content generation, named Kreado AI. Kreado AI is a hybrid worldwide AIGC platform that combines the strengths of Virtual Avatar (talking-face generation, voice clone, LLM), AI model (text-to-image, LoRA, control net), many AI tools and AI property. Here I mainly focus on the Virtual Avatar and AI model algorithms improvement, as well as collaborate with system architect for entire architecture improvement. Users radiate to Europe, Africa, Southeast Asia, and the Americas, with quarterly revenue exceeding US$1 million.
</div>
</div>

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 🎓 Educations
- *2015.08 - 2019.06*, Undergraduate, Xidian University. 
- *2018.08 - 2018.09*, Summer school, University of Cambridge. 
- *2012.08 - 2015.06*, High School Affiliated to Northwestern University

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 🧑‍💻 Professional Experience
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.

# 🏃‍♂️ Hobbies
My hobbies include Fencing🤺, Basketball🏀, Swimming🏊, Guitar🎸 and Motorcycle🏍️. In the high school, I get my first gold medal in Fencing🤺 at the National Games🏅.

Besides, I have my lovely cat🐱 -- DotDot: <img src='images/500x300.png' alt="sym" width="30%">