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

<!-- <!-- Hi! Here is Yuanjun Chai 柴源君 (sounds like Y-wen Joon, Ch-eye), aka Allen. I work at [VMware AI Lab](https://www.vmware.com/artificial-intelligence/ai-labs.html) <img src='./images/vmwarelogo.jpeg' style='width: 3.8em;'>, working on LLM and Multi-LLM.  -->

**I will go into UW-seattle as graduate student this Fall!**<br /> -->
<!-- Hi! Here is Yuanjun Chai 柴源君 (sounds like Y-wen Joon, Ch-eye), aka Allen. I work at [iFlyTek AI Lab](https://xinghuo.xfyun.cn/sparkapi) <img src='./images/iFlyTek_logo.jpeg' style='width: 3.8em;'>, working on LLM and Multi-LLM. -->

I graduated with highest honors from Xidian University, earning a bachelor's degree. My thesis about image inpainting received invaluable support by [Chao Dong](https://scholar.google.com/citations?user=OSDCB0UAAAAJ&hl=en&oi=ao) from SIAT-CAS <img src='./images/siat.jpeg' style='width: 1.6em;'>. Also, I am so lucky to have the privilege of collaborating with [Chao Dong](https://scholar.google.com/citations?user=OSDCB0UAAAAJ&hl=en&oi=ao) and [Yu Qiao](https://scholar.google.com/citations?hl=en&user=gFtI-8QAAAAJ) from CAS <img src='./images/cas.jpeg' style='width: 1.6em;'> working on image&video super-resolution, [Jason Cheung](https://www.ortho.hku.hk/biography/cheung-pui-yin-jason/) from HKU <img src='./images/hku.png' style='width: 1.6em;'> working on AI healthcare, [Yue Gao](https://www.gaoyue.org/) and [Eric Yi](https://scholar.google.com/citations?user=UyZL660AAAAJ&hl=en) from Tsinghua University <img src='./images/tsinghua.png' style='width: 1.6em;'> working on Embodied AI.<br />


Not only diving into research, I am also willing to empower new technologies into products to **make people's lives better**. Thus, I co-founded a start-up [INGREM inc](https://gazerecorder.com/gazepointer/), **to help high-paraplegia disabled people** using computer with precise eyes controling platform. Previously, I worked in [YeahMobi](https://en.yeahmobi.com/) -- affiliation of [Alibaba Group](https://www.alibabagroup.com/en-US) <img src='./images/Alibaba-Logo.png' style='width: 3.3em;'>, as a senior machine learning scientist (P8 expert). I was responsible for the all technical development of AIGC platform [Kreado AI](https://kreadoai.com/) <img src='./images/kreado_logo.png' style='width: 2.8em;'>, including AI Video Creation, AI model, custom clone service, and etc. 
<!-- <img src='./images/SparkLLM.png' style='width: 2.7em;'>, working on SparkLLM, RAG, agent and Multi-modal LLM. -->
Then, I am currently a machine learning engineer at VMware AI Lab <img src='./images/vmware.png' style='width: 2.3em;'>, working on LLM agent, RAG-based LLM and Multi-modal LLM.<br />

### Research Interests:

- **Generative AI**: LLM in education, RAG-based LLM, Multi-modal LLM, text-to-image, text-to-video
- **Virtual Avatar**: 2D&3D talking face generation, voice generation, custom character
- **AI in healthcare**: medical image, medical VLM
- **Computer Vision**: low-level vision, high-level vision
- **Embodied AI**: sim2real, multi-model perception

<!-- By the way, with strong research and industry experience, I decide to **seek for a PhD position**.  -->
By the way, I am so glad to collaborate with young researchers. Although pursuing academics is a tough journey, but we could overcome it together. Now I am holding multiple GPUs. If you are interested in my research, please directly contact me[yuanjunchai89@gmail.com](mailto:yuanjunchai89@gmail.com).


<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
<!-- - *2023.02*: &nbsp;🎉🎉 Thrilled to join iFlyTek AI Lab as MLE! We do some interesting projects on RAG-based LLM like [h2oGPT](https://github.com/h2oai/h2ogpt) (⭐️8k+). -->
- *2023.07*: &nbsp;🎉🎉 Thrilled to join VMware as MLE! We do some interesting projects on RAG-based LLM like [h2oGPT](https://github.com/h2oai/h2ogpt) (⭐️8k+).
- *2023.01*: &nbsp;🔥🔥 Our AIGC platform [Kreado AI](https://kreadoai.com/) has released to all over the world！
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

# 🖥️ Innovational Products
## 🧑‍🎨 AIGC (Generative Model)
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/kreado03.png' alt="sym" width="120%"></div></div>
<div class='paper-box-text' markdown="1">

[**Kreado AI: AIGC Platform for Marketing Content Generation**](https://kreadoai.com/)

**Yuanjun Chai** and YeahMobi.inc

- We propose a new AIGC platform for marketing content generation, named Kreado AI. Kreado AI is a hybrid worldwide AIGC platform that combines the strengths of so many AIGC functions:
  - Virtual Avatar (talking-face generation, speech synthesis, LLM)
  - AI model (text-to-image, LoRA, control net)
  - Custom clone serivces (image-to-video, voice clone)
  - Many AI tools and AI property
- Here I mainly focus on the Virtual Avatar and AI model algorithms improvement, as well as collaborate with system architect for entire architecture improvement. Users radiate to Europe, Africa, Southeast Asia, and the Americas, with quarterly revenue exceeding US$1 million.
</div>
</div>

## 🧙‍♂️ RAG-based LLM
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/h2oGPT.png' alt="sym" width="120%"></div></div>
<div class='paper-box-text' markdown="1">

[**h2o GPT: AIGC Platform for Marketing Content Generation**](https://tanzu.vmware.com/content/blog/vmware-greenplum-excels-as-genai-llm-data-platform)

**Yuanjun Chai**

[**Project**](https://gpt.h2o.ai/) \| [![](https://img.shields.io/github/stars/h2oai/h2ogpt?style=social&label=Code+Stars)](https://github.com/h2oai/h2ogpt) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We develop a new RAG-based LLM platform for AI cloud native and private AI. The platform could leverage diverse LLMs with extended dataset such as pdf, code base, dataset and internet links. Here I am responsible for all RAG-based LLM algorithm development, as well as industrial deployment. Functionality includes: 
  - QA and chat with extended dataset extraction
  - Content summarization
  - Content generation
  - AI agent
- Next step we would take research about Multi-modal LLM for AI cloud native.
</div>
</div>


## 👨‍⚕️ AI healthcare & Charity
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/eyes02.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Face Control: Fine Facial Control Platform for High-paraplegia Disabled People**](https://www.bilibili.com/video/BV1u34y1d7g3/?p=1&share_medium=iphone&share_plat=ios&share_session_id=FDFAD6F5-CCF8-47D9-B33E-DE9CB343384E&share_source=WEIXIN&share_tag=s_i&timestamp=1639402219&unique_k=OkjAetO)

**Yuanjun Chai**, Ingrem.inc

- I co-founded a start-up Ingrem, with other hardcore guys. We aim to build up a entire bed for living and playing of high-paraplegia disabled people. Here, I am responsible for the development of the software -- eyes&facial control platform. Based on computer vision algorithms, the system could help the diabled use their face details (such as eyebrow, eye, mouth, etc.) to control mouse and keyborad elaborately. Thus, our platform and our bed entirely enhance the accessibility of normal computer usage and social networks. We do believe tech
 make people's lives better, and we do it!
</div>
</div>

# 🎖 Honors and Awards
- *2022.04* Obtain a fully-funded PhD return offer from Li Ka Shing Faculty of Medicine, University of Hong Kong.
- *2019.06* Outstanding Undergraduate Student Award. 
- *2019.06* Outstanding Undergraduate Thesis Award (10/5000), Topic: Image Inpainting Based on Deep Learning. 
- *2018.08* Cambridge Summer AI Academic Programme Excellent Student – All A+ of Artificial Intelligence Classes.
- *2017.05* Golden Medal of National Computer Design Contest -- Birdsong Recognition with Machine Learning.

# 🎓 Educations
- *2015.08 - 2019.06*, Undergraduate, Xidian University. 
- *2018.08 - 2018.09*, Summer School, University of Cambridge (with Prof. Pietro Lio). 
- *2012.08 - 2015.06*, High School Affiliated to Northwestern University

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 🧑‍💻 Professional Experience
- *2023.07 - now*, Machine Learning Engineer, VMware AI Lab
- *2022.07 - 2023.07*, Senior Machine Learning Scientist, YeahMobi -- Alibaba Group.
- *2019.05 - 2022.07*, Research Assistant in Chinese Academy of Sciences, Tsinghua University and HKU (get return PhD offer). -->
# 🧑‍💻 Professional Experience
- *2023.07 - now*, Machine Learning Engineer, VMware AI Lab
<!-- - *2023.07 - now*, Machine Learning Engineer, iFlyTek -->
- *2022.07 - 2023.06*, Senior Machine Learning Scientist, YeahMobi -- Alibaba Group.
- *2019.05 - 2022.07*, Research Assistant in CAS, Tsinghua University and HKU (get return PhD offer).

# 🏃‍♂️ Hobbies
My hobbies include Fencing🤺, Basketball🏀, Swimming🏊, Guitar🎸 and Motorcycle🏍️. In the high school, I get my first gold medal in Fencing🤺 at the National Province Games🏅.

Besides, I have my lovely cat🐱: 
<br />
<img src='images/cat06.JPG' alt="sym02" width="25%"> <img src='images/cat10.jpg' alt="sym01" width="25%"> <img src='images/cat08.jpg' alt="sym03" width="25%">
