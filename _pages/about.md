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


Hello, I’m Qihui Zhang (张祺珲), an undergraduate student at <a href='https://www.scu.edu.cn/'>Sichuan University</a>. My GPA is **3.91**/4.00, ranked **2% (5/210)** in the grade. I’m currently in my fourth year of undergraduate studies. I will begin my Master’s program at <a href = 'https://www.ece.pku.edu.cn/' >the School of Electronic and Computer Engineering, <img src="images/pku.png" style='width: 1.2em;'>Peking University</a> in September 2025.

My research interests include Human Alignment and Trustworthy AI. I have published 5 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=ZdgtY0EAAAAJ'> Google Scholar citations <strong><span id='total_cit'>300+</span></strong></a> ( <a href='https://scholar.google.com/citations?user=ZdgtY0EAAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FMask-Hui%2FMask-Hui.github.io%40google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).

Since August 2024, I have been interning as an algorithm engineer at the Visual Technology Lab in Alibaba <a href = 'https://damo.alibaba.com/'><img src="images/DAMO.png" style='height: 1.2em;'> DAMO Academy</a>, focusing on foundational intelligent technologies. I was a visiting student at <a href = 'https://www2.lehigh.edu/'>Lehigh University</a> from April 2023 to May 2024, where I worked under the guidance of <a href = 'https://lichao-sun.github.io/'>Prof. Lichao Sun</a>. Before this, I was under the mentorship of <a href = 'https://cs.scu.edu.cn/info/1359/16745.htm'>Prof. Yan Wang</a> at Sichuan University.

You can find out more about my publications at [Google Scholar](https://scholar.google.com/citations?user=ZdgtY0EAAAAJ), [Semantic Scholar](https://www.semanticscholar.org/author/Qihui-Zhang/46324457), and ResearchGate (coming soon).

# 🔥 News
- *2024.09.29:* &nbsp;🎉🎉 I will continue my research career and study at Peking University, See you in Shenzhen in 2025.09!
- *2024.09.25:* &nbsp;🎉🎉 HonestyLLM has been accepted by **NeurIPS** 2024! Congratulations to [Chujie](https://flossiee.github.io/)!
- *2024.07.04:* &nbsp;🎉🎉 Cliff has been accepted by **ECAI** 2024! Congratulations to Xiao!
- *2024.05.02:* &nbsp;🎉🎉 TrustLLM has been accepted by **ICML** 2024! Congratulations to [Yue](https://howiehwong.github.io/)!
- *2024.05.02:* &nbsp;🎉🎉 MLLM-as-a-Judge has been accepted by **ICML** 2024 **(Oral)**! Congratulations to [Dongping](https://dongping-chen.github.io/)! 
- *2024.03.14:* &nbsp;🎉🎉 Mixcase has been accepted by **NAACL** 2024 Findings! Congratulations to [Chujie](https://flossiee.github.io/), [Dongping](https://dongping-chen.github.io/)! 
- *2024.02.03:* &nbsp;🎉🎉 Our paper has been accepted by **ISBI** 2024!
- *2024.01.15:* &nbsp;🎉🎉 MetaTool has been accepted by **ICLR** 2024!


# 📝 Publications 

ICLR 2024 | ISBI 2024 | NAACL 2024 | ICML 2024 | ECAI 2024 | NeurIPS 2024

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/Honesty1_architecture.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[The Best of Both Worlds: Toward an Honest and Helpful Large Language Model](https://arxiv.org/pdf/2406.00380)

Chujie Gao \*, **Qihui Zhang** \*, Dongping Chen\*, Siyuan Wu\*, Yue Huang, Zhengyan Fu, Yao Wan, Xiangliang Zhang, Lichao Sun (*: equal contribution)

[**Dataset & Code**](https://github.com/Flossiee/HonestyLLM)

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

[**Code**](https://github.com/Dongping-Chen/MLLM-Judge) | [**Website**](https://mllm-judge.github.io/) | [**Data**](https://huggingface.co/datasets/shuaishuaicdp/MLLM-Judge)
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
    <div><div class="badge">Preprint</div>
      <img src='images/GUI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**GUI-World: A Dataset for GUI-oriented Multimodal LLM-based Agents** [[PDF]](https://arxiv.org/pdf/2406.10819) [[Github]](https://github.com/Dongping-Chen/GUI-World) [[Website]](https://gui-world.github.io)

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

-->

- [Triplet-constraint Transformer with Multi-scale Refinement for Dose Prediction in Radiotherapy](https://arxiv.org/pdf/2402.04566)
  Lu Wen \*, **Qihui Zhang** \*, Zhenghao Feng, Yuanyuan Xu, Xiao Chen, Jiliu Zhou, Yan Wang <strong>ISBI 2024 (*: equal contribution)


# 🎖 Honors and Awards
- *2021.10* National Scholarship.
- *2024.01* National College Computer Ability Challenge - **National First Prize**.
- *2024.07* Chinese Collegiate Computing Competition - **National Third Prize**.
- *2022.10* International "Internet +" College Student Innovation and Entrepreneurship Competition - **National Third Prize**.
- *2024.05* American College Mathematical Contest in Modeling - **International Honorable Mention**
- *2024.05* National LanQiao Cup Algorithm Competition (Python Group) **- Provincial First Prize**.
- *2022.10* National College Student Mathematical Modeling Competition **- Provincial First Prize**.
- *2023.10* Undergraduate Honours Bachelor's Degree Program.
- *2022.09* Sichuan Province Comprehensive Quality A-level Certificate.

# 📖 Educations
- *2020.09 - 2025.06 (now)*, BEng., Software Engineering, Sichuan University.

# 💻 Internships
- *2024.08 - 2024.12 (now)*, Visual Technology Lab in Alibaba <a href = 'https://damo.alibaba.com/'>DAMO Academy</a>, China.


# 💬 Services
- 2025.09, Reviewer for ICLR 2025


<!-- 
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

-->
