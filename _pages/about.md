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

I am **Qihui Zhang (张祺珲)**, a first-year Master's student at the <a href='https://www.ece.pku.edu.cn/'>School of Electronic and Computer Engineering</a>, <a href='https://english.pku.edu.cn/'><img src="images/pku.png" style='width: 1.2em; vertical-align: sub;'> Peking University</a>, advised by <a href='https://yuanli2333.github.io/'>Prof. Li Yuan</a>. You can reach me via email at `qhzhang25@stu.pku.edu.cn`. Previously, I was a Research Intern at Alibaba <a href='https://damo.alibaba.com/'><img src="images/DAMO.png" style='height: 1.2em; vertical-align: sub;'> DAMO Academy</a>, mentored by <a href='https://ybsong00.github.io'>Dr. Yibing Song</a>. 

My research focuses on building **Capable and Trustworthy AGI**, with specific interests in **Human Alignment**, **Multi-modal Learning**, and **Model Safety**. I have published 10+ papers at top-tier conferences (CVPR, ICML, NeurIPS, ICLR, AAAI), with **1,500+ citations** (<a href='https://scholar.google.com/citations?user=ZdgtY0EAAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FMask-Hui%2FMask-Hui.github.io%40google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations" style="vertical-align: middle;"></a>). I am also a recipient of the **National Scholarship** (Top 0.2%, twice) and winner of multiple national coding competitions. For more details on my publication, please visit my profiles on [Google Scholar](https://scholar.google.com/citations?user=ZdgtY0EAAAAJ), [Semantic Scholar](https://www.semanticscholar.org/author/Qihui-Zhang/46324457), and [ResearchGate](https://www.researchgate.net/profile/Qihui-Zhang-13/research).






<span class='anchor' id='news'></span>
# 🔥 News
- *2025.10.21:* &nbsp;🎉🎉 TrustAGI has been accepted by **ICLR** 2026!
- *2025.10.21:* &nbsp;🎉🎉 AsFT has been accepted by **AAAI** 2026 **(Oral)**!
- *2025.10.21:* &nbsp;🎉🎉 We have published a technical report on UniWorld-V2 (Edit-R1)!
- *2025.09.15:* &nbsp;🎉🎉 CoT-lized Diffusion have been accepted by **NeurIPS** 2025!
- *2025.02.27:* &nbsp;🎉🎉 UPME have been accepted by **CVPR** 2025!
- *2025.01.23:* &nbsp;🎉🎉 Three papers have been accepted by **ICLR** 2025!

<details>
<summary>Old News</summary>
<ul>
  <li>2024.09.29: &nbsp;🎉🎉 I will continue my research career and study at <strong>Peking University</strong>!</li>
  <li>2024.09.25: &nbsp;🎉🎉 HonestLLM has been accepted by <strong>NeurIPS</strong> 2024! Congratulations to <a href="https://flossiee.github.io/">Chujie</a>!</li>
  <li>2024.08.25: &nbsp;🎉🎉 I have started my internship in <strong>Alibaba DAMO Academy</strong>!</li>
  <li>2024.07.04: &nbsp;🎉🎉 Cliff has been accepted by <strong>ECAI</strong> 2024! Congratulations to <a href="https://scholar.google.com/citations?user=kFWimw4AAAAJ">Xiao</a>!</li>
  <li>2024.05.02: &nbsp;🎉🎉 TrustLLM has been accepted by <strong>ICML</strong> 2024! Congratulations to <a href="https://howiehwong.github.io/">Yue</a>!</li>
  <li>2024.05.02: &nbsp;🎉🎉 MLLM-as-a-Judge has been accepted by <strong>ICML</strong> 2024 <strong>(Oral)</strong>! Congratulations to <a href="https://dongping-chen.github.io/">Dongping</a>! </li>
  <li>2024.03.14: &nbsp;🎉🎉 Mixtext has been accepted by <strong>NAACL</strong> 2024 Findings! Congratulations to <a href="https://flossiee.github.io/">Chujie</a>, <a href="https://dongping-chen.github.io/">Dongping</a>! </li>
</ul>
</details>




<span class='anchor' id='publications'></span>
# 📝 Publications 

| CVPR 2025  | NAACL 2024 | NeurIPS 2025 |AAAI 2026 * 2| NeurIPS 2024 | ICLR 2026 |
| ICLR 2025 * 3 | ICML 2024 * 2 | ICLR 2024 | ECAI 2024 | ISBI 2024 | 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/UPME_pipeline-CR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[UPME: An Unsupervised Peer Review Framework for Multimodal Large Language Model Evaluation](https://arxiv.org/pdf/2503.14941)

**Qihui Zhang** \*, Munan Ning \*, Zheyuan Liu, Yanbo Wang, Jiayi Ye, Yue Huang, Shuo Yang, Xiao Chen, Yibing Song, Li Yuan. (*: equal contribution)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026 Oral</div><img src='images/ASFT_pipeline.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AsFT: Anchoring Safety During LLM Fine-Tuning Within Narrow Safety Basin](https://arxiv.org/abs/2506.08473)

Shuo Yang \*, **Qihui Zhang** \*, Yuyang Liu, Yue Huang, Xiaojun Jia, Kunpeng Ning, Jiayu Yao, Jigang Wang, Hailiang Dai, Yibing Song, Li Yuan (*: equal contribution)

[**Code**](https://github.com/PKU-YuanGroup/AsFT)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/Honesty1_architecture.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HonestLLM: Toward an Honest and Helpful Large Language Model](https://arxiv.org/pdf/2406.00380)

Chujie Gao \*, **Qihui Zhang** \*, Dongping Chen\*, Siyuan Wu\*, Yue Huang, Zhengyan Fu, Yao Wan, Xiangliang Zhang, Lichao Sun (*: equal contribution)

[**Dataset & Code**](https://github.com/Flossiee/HonestyLLM)

</div>
</div>





<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Technical Report</div><img src='images/Edit-R1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Uniworld-V2: Reinforce Image Editing with Diffusion Negative-aware Finetuning and MLLM Implicit Feedback](https://arxiv.org/abs/2510.16888)

Zongjian Li \*, Zheyuan Liu \*, **Qihui Zhang** \*, Bin Lin \*, Shenghai Yuan, Zhiyuan Yan, Yang Ye, Wangbo Yu, Yuwei Niu, Li Yuan (*: equal contribution)

[**Model Weights**](https://huggingface.co/collections/chestnutlzj/edit-r1-68dc3ecce74f5d37314d59f4) | [**Code**](https://github.com/PKU-YuanGroup/UniWorld-V2)

</div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">NAACL 2024 Findings</div>
      <img src='images/MixSet_generation.png' alt="sym" width="100%">
    </div>
  </div>
  
<div class='paper-box-text' markdown="1">

[LLM-as-a-Coauthor: Can Mixed Human-Written and Machine-Generated Text Be Detected?](https://arxiv.org/pdf/2401.05952.pdf)

**Qihui Zhang** \*, Chujie Gao \*, Dongping Chen \*, Yue Huang, Yao Wan, Lichao Sun (*: equal contribution)

[**Dataset & Code**](https://github.com/Dongping-Chen/MixSet) | [**Website**](https://llm-coauthor.github.io/)
</div>

</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2024</div><img src='images/trustllm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TrustLLM: Trustworthiness in Large Language Models](https://arxiv.org/pdf/2401.05561.pdf)

Yue Huang \*, Lichao Sun \*, Haoran Wang \*, Siyuan Wu \*, **Qihui Zhang** \*, Chujie Gao \*, Yixin Huang, Wenhan Lyu, Yixuan Zhang, Xiner Li, Zhengliang Liu, Yixin Liu, Yijue Wang, Zhikun Zhang, Bhavya Kailkhura, Caiming Xiong, et al. (*: major contribution)

[**Toolkit & Code**](https://github.com/HowieHwong/TrustLLM) | [**Website**](https://trustllmbenchmark.github.io/TrustLLM-Website/)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2024 (Oral)</div><img src='images/mllm-judgev2.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MLLM-as-a-Judge: Assessing Multimodal LLM-as-a-Judge with Vision-Language Benchmark](https://arxiv.org/abs/2402.04788)

Dongping Chen \*, Ruoxi Chen \*, Shilin Zhang \*, Yinuo Liu \*, Yaochen Wang \*, Huichi Zhou \*, **Qihui Zhang** \*, Pan Zhou, Yao Wan, Lichao Sun (*: equal contribution)

[**Code**](https://github.com/Dongping-Chen/MLLM-Judge) | [**Website**](https://mllm-judge.github.io/) | [**Dataset**](https://huggingface.co/datasets/shuaishuaicdp/MLLM-Judge)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/Pipeline_shuo_v2_page-0001.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CoT-lized Diffusion: Let's Reinforce T2I Generation Step-by-step](https://arxiv.org/abs/2507.04451)

Zheyuan Liu, Munan Ning, **Qihui Zhang**, Shuo Yang, Zhongrui Wang, Yiwei Yang, Xianzhe Xu, Yibing Song, Weihua Chen, Fan Wang, Li Yuan

</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICLR 2024</div>
      <img src='images/metatool_00.png' alt="sym" width="100%">
    </div>
  </div>
<div class='paper-box-text' markdown="1">


[MetaTool Benchmark for Large Language Models: Deciding Whether to Use Tools and Which to Use](https://arxiv.org/pdf/2310.03128.pdf)

Yue Huang, Jiawen Shi, Yuan Li, Chenrui Fan, Siyuan Wu, **Qihui Zhang**, Yixin Liu, Pan Zhou, Yao Wan, Neil Zhenqiang Gong, Lichao Sun

</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">ICLR 2025</div>
      <img src='images/llm-judge-bias.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Justice or Prejudice? Quantifying Biases in LLM-as-a-Judge](https://arxiv.org/abs/2410.02736)

Jiayi Ye, Yanbo Wang, Yue Huang, Dongping Chen, **Qihui Zhang**, Pin-Yu Chen, Nitesh V. Chawla, Xiangliang Zhang 

[![Website Visits](https://img.shields.io/badge/Github-Website-blue?style=flat&logo=github&logoColor=white)](https://llm-judge-bias.github.io/)
[![Paper](https://img.shields.io/badge/Paper-PDF-blue)](https://arxiv.org/pdf/2410.02736)

</div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">ICLR 2025</div>
      <img src='images/datagen.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DataGen: Unified Synthetic Dataset Generation via Large Language Models](https://arxiv.org/pdf/2406.18966)

Siyuan Wu, Yue Huang, Chujie Gao, Dongping Chen, **Qihui Zhang**, Yao Wan, Tianyi Zhou, Xiangliang Zhang, Jianfeng Gao, Chaowei Xiao, Lichao Sun.
</div>
</div>




<div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">ICLR 2025</div>
      <img src='images/GUI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GUI-World: A Dataset for GUI-oriented Multimodal LLM-based Agents](https://arxiv.org/pdf/2406.10819) [[Github]](https://github.com/Dongping-Chen/GUI-World) [[Website]](https://gui-world.github.io)

Dongping Chen \*, Yue Huang \*, Siyuan Wu, Jingyu Tang, Liuyi Chen, Yilin Bai, Zhigang He, Chenlong Wang, Huichi Zhou, Yiqiang Li, Tianshuo Zhou, Yue Yu, Chujie Gao, **Qihui Zhang**, Yi Gui, Zhen Li, Yao Wan†, Pan Zhou†, Jianfeng Gao, Lichao Sun

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECAI 2024</div><img src='images/ECAI-pipeline.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Cliff: Leveraging Ambiguous Samples for Enhanced Test-Time Adaptation](https://ebooks.iospress.nl/volumearticle/69639)

Xiao Chen \*, **Qihui Zhang** \*, Yan Wang (*: equal contribution)

</div>
</div>


<!-- 
[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>



- [Unigen: A unified framework for textual dataset generation using large language models](https://arxiv.org/pdf/2406.18966)
  Siyuan Wu, Yue Huang, Chujie Gao, Dongping Chen, **Qihui Zhang**, Yao Wan, Tianyi Zhou, Xiangliang Zhang, Jianfeng Gao, Chaowei Xiao, Lichao Sun. <strong>ICLR 2025


- [Justice or Prejudice? Quantifying Biases in LLM-as-a-Judge](https://arxiv.org/pdf/2410.02736)
  Jiayi Ye, Yanbo Wang, Yue Huang, Dongping Chen, **Qihui Zhang**, Nuno Moniz, Tian Gao, Werner Geyer, Chao Huang, Pin-Yu Chen, Nitesh V Chawla, Xiangliang Zhang. <strong>ICLR 2025
-->

- [Triplet-constraint Transformer with Multi-scale Refinement for Dose Prediction in Radiotherapy](https://arxiv.org/pdf/2402.04566)
  Lu Wen \*, **Qihui Zhang** \*, Zhenghao Feng, Yuanyuan Xu, Xiao Chen, Jiliu Zhou, Yan Wang <strong>ISBI 2024 (*: equal contribution)



<span class='anchor' id='honors'></span>
# 🎖 Honors and Awards

- *2024.10* National Scholarship.
- *2024.01* National College Computer Ability Challenge - **National First Prize**.
- *2024.07* Chinese Collegiate Computing Competition - **National Third Prize**.
- *2022.10* International "Internet +" College Student Innovation and Entrepreneurship Competition - **National Third Prize**.
- *2024.05* American College Mathematical Contest in Modeling - **International Honorable Mention**
- *2024.05* National LanQiao Cup Algorithm Competition (Python Group) **- Provincial First Prize**.
- *2022.10* National College Student Mathematical Modeling Competition **- Provincial First Prize**.
- *2023.10* Undergraduate Honours Bachelor's Degree Program.
- *2022.09* Provincial Comprehensive Quality A-level Certificate.
- *2021.10* National Scholarship.


<span class='anchor' id='education'></span>
# 📖 Education
<!-- 
# - *2020.09 - 2025.06 (now)*, BEng., Software Engineering, Sichuan University.

-->
- 2025.09 - 2028.06 (expected), MSc., Computer Science and Technology, Peking University.

# 💻 Internships
- *2024.08 - now*, Visual Technology Lab in Alibaba <a href = 'https://damo.alibaba.com/'>DAMO Academy</a>, China.


# 💬 Services
- Conference Reviewer for ICLR 2025, ICML 2025, ACL 2025, NeurIPS 2025
- Journal Reviewer for ACM Transactions on Information Systems

<!-- 
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

-->

<a href="https://mapmyvisitors.com/web/1by88"  title="Visit tracker"><img src="https://mapmyvisitors.com/map.png?d=2oex5D8qKbBfWJUKlE7fKLMjNMnbSwuTVbAniKBUy8w&cl=ffffff" /></a>
