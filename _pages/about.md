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

<!-- I am a third-year Ph.D. candidate of [Computer Science & Engineering Department](https://engineering.buffalo.edu/computer-science-engineering.html), [University at Buffalo](https://www.buffalo.edu/), advised by [Prof. Junsong Yuan](https://cse.buffalo.edu/~jsyuan/). 
My research interest focuses 3D reconstruction. -->

# 🧑 Short Bio
Tianyu Luan is a final-year Ph.D. candidate of [Computer Science & Engineering Department](https://engineering.buffalo.edu/computer-science-engineering.html), [State University of New York at Buffalo](https://www.buffalo.edu/), Buffalo NY, United States, advised by [Prof. Junsong Yuan](https://cse.buffalo.edu/~jsyuan/). He received his B.S. degree in Applied Physics at [University of Science and Technology of China](https://en.ustc.edu.cn/), Hefei Anhui, China in 2013, and his M.Eng. degree in Electronical and Telecommunication Engineering at [Tsinghua University](https://www.tsinghua.edu.cn/en/), Beijing, China in 2017. His research interest lies in [3D shape detail measurement, reconstruction, and generation](pdfs/Dissertation_proposal.pdf). 

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

<span class='anchor' id='news'></span>

# 🔥 News
- <p style="color: red;">I'm currently looking for a postdoc position in computer vision/generative AI related areas starting from 2025 summer. If you're interested, please drop me a message/email at any time!</p>
- *2024.07*: &nbsp;🎉🎉 2 papers accepted by ECCV 2024, including 1 first author paper!
- *2024.05*: &nbsp;🎉🎉 1 paper accepted by ICML 2024!
- *2024.03*: &nbsp;🎉🎉 I will join [Pixocial](https://pixocial.com/) as a research intern this summer!
- *2024.02*: &nbsp;🎉🎉 3 papers accepted by CVPR 2024, including 1 first author paper!
- *2024.02*: &nbsp;🎉🎉 I will join [UII America](https://www.uii-ai.com/) as research intern this spring for the 2nd time!
- *2023.07*: &nbsp;🎉🎉 1 paper accepted by ICCV 2023!
- *2023.05*: &nbsp;🎉🎉 I will join [UII America](https://www.uii-ai.com/) as research intern this summer!
- *2023.02*: &nbsp;🎉🎉 1 first author paper accepted by CVPR 2023!
- *2022.05*: &nbsp;🎉🎉 I will join [OPPO US Research Center](https://www.innopeaktech.com/) as research intern this summer.


<span class='anchor' id='publications'></span>

# 📝 Selected Publications

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/papers/High-fidelity-hand.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
High Fidelity 3D Hand Shape Reconstruction\\ via Scalable Graph Frequency Decomposition
**Tianyu Luan**, Yuanhao Zhai, Jingjing Meng, Zhong Li, Zhang Chen, Yi Xu, and Junsong Yuan
[PDF]() [Code]() [Bibtex]() -->

<div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">ECCV 2024</div><img src='images/papers/ECCV24_PartBody.png' alt="sym" width="100%"></div>
  </div>
  <div class='paper-box-text' markdown="1">
  **<font size=3><font face="Times New Roman">Divide and Fuse: Body Part Mesh Recovery from Partially Visible Human Images</font></font>**

  <font face="Times New Roman"><b>Tianyu Luan</b>, Zhongpai Gao, Luyuan Xie, Abhishek Sharma, Hao Ding, Benjamin Planche, Meng Zheng, Ange Lou, Terrence Chen, Junsong Yuan, and Ziyan Wu. </font>
  <font face="Times New Roman"><em>ECCV'2024</em></font>

  [\[PDF (Coming Soon)\]]() [\[Bibtex (Coming Soon)\]](bibtex/ECCV24_PartBody.html) [\[Project (Coming Soon)\]](https://bit.ly/DaF) 
  </div>
</div>



<div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">ICML 2024</div><img src='images/papers/ICML24_FL.png' alt="sym" width="100%"></div>
  </div>
  <div class='paper-box-text' markdown="1">
  **<font size=3><font face="Times New Roman">MH-pFLID: Model Heterogeneous Personalized Federated Learning via Injection and Distillation for Medical Data Analysis</font></font>**

  <font face="Times New Roman">Luyuan Xie, Manqing Lin, <b>Tianyu Luan<sup>✉</sup></b>, Cong Li, Yuejian Fang, Qingni Shen, and Zhonghai Wu. </font>
  <font face="Times New Roman"><em>ICML'2024</em></font>

  [\[PDF\]](https://arxiv.org/pdf/2405.06822) [\[Bibtex\]](bibtex/ICML24_FL.html) [\[Project (Coming Soon)\]]()  [\[Code (Coming Soon)\]]() <!-- [\[Bibtex\]]() -->
  </div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">CVPR 2024</div><img src='images/papers/CVPR24_metric.png' alt="sym" width="100%"></div>
  </div>
  <div class='paper-box-text' markdown="1">
  **<font size=3><font face="Times New Roman">Spectrum AUC Difference (SAUCD): Human-aligned 3D Shape Evaluation</font></font>**

  <font face="Times New Roman"><b>Tianyu Luan</b>, Zhong Li, Lele Chen, Xuan Gong, Lichang Chen, Yi Xu, and Junsong Yuan. </font>
  <font face="Times New Roman"><em>CVPR'2024</em></font>

  [\[PDF\]](https://arxiv.org/pdf/2403.01619) [\[Bibtex\]](bibtex/CVPR24_metric.html) [\[Project\]](https://bit.ly/saucd)  [\[Code\]](https://github.com/tyluann/SAUCD) <!-- [\[Bibtex\]]() -->
  </div>
</div>

<!-- <div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">CVPR 2024</div><img src='images/papers/CVPR24_PC.png' alt="sym" width="100%"></div>
  </div>
  <div class='paper-box-text' markdown="1">
  **<font size=3><font face="Times New Roman">FSC: Few-point Shape Completion</font></font>**

  <font face="Times New Roman">Xianzu Wu*, Xianfeng Wu*, <b>Tianyu Luan</b>, Yajing Bai, Zhongyuan Lai, and Junsong Yuan.</font>

  <font face="Times New Roman"><em>CVPR'2024</em></font>

  [\[PDF\]](https://arxiv.org/pdf/2403.07359) [\[Bibtex\]](bibtex/CVPR24_PC.html) [\[Project (Coming Soon)\]]() [\[Code (Coming Soon)\]]()
  </div>
</div>  -->

<!-- <div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">CVPR 2024</div><img src='images/papers/CVPR24_nerf.gif' alt="sym" width="100%"></div>
  </div>
  <div class='paper-box-text' markdown="1">
  **<font size=3><font face="Times New Roman">DaReNeRF: Direction-aware Representation for Dynamic Scenes</font></font>**

  <font face="Times New Roman">Ange Lou, Benjamin Planche, Zhongpai Gao, Yamin Li, <b>Tianyu Luan</b>, Hao Ding, Terrence Chen, Jack Noble, and Ziyan Wu.</font>

  <font face="Times New Roman"><em>CVPR'2024</em></font>

  [\[PDF\]](https://arxiv.org/pdf/2403.02265) [\[Bibtex\]](bibtex/CVPR24_nerf.html) [\[Project (Coming Soon)\]]() [\[Code (Coming Soon)\]]()
  </div>
</div> -->


<!-- <div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">ICCV 2023</div><img src='images/papers/ICCV23.png' alt="sym" width="100%"></div>
  </div>
  <div class='paper-box-text' markdown="1">
  **<font size=3><font face="Times New Roman">Towards Generic Image Manipulation Detection with Weakly-Supervised Self-Consistency Learning</font></font>**

  <font face="Times New Roman">Yuanhao Zhai, <b>Tianyu Luan</b>, David Doermann, and Junsong Yuan. <em>ICCV'2023</em></font>

  [\[PDF\]](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhai_Towards_Generic_Image_Manipulation_Detection_with_Weakly-Supervised_Self-Consistency_Learning_ICCV_2023_paper.pdf) [\[Code\]](https://github.com/yhZhai/WSCL) [\[Bibtex\]](bibtex/ICCV23_mani.html)[\[Demo\]](https://huggingface.co/spaces/yhzhai/WSCL)
  </div>
</div> -->


<div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">CVPR 2023</div><img src='images/papers/High-fidelity-hand.png' alt="sym" width="100%"></div>
  </div>
  <div class='paper-box-text' markdown="1">
  **<font size=3><font face="Times New Roman">High Fidelity 3D Hand Shape Reconstruction via Scalable Graph Frequency Decomposition</font></font>**

  **<font face="Times New Roman">Tianyu Luan</font>**<font face="Times New Roman">, Yuanhao Zhai, Jingjing Meng, Zhong Li, Zhang Chen, Yi Xu, and Junsong Yuan. <em>CVPR'2023</em></font>

  [\[PDF\]](https://openaccess.thecvf.com/content/CVPR2023/papers/Luan_High_Fidelity_3D_Hand_Shape_Reconstruction_via_Scalable_Graph_Frequency_CVPR_2023_paper.pdf) [\[Code\]](https://github.com/tyluann/FreqHand) [\[Bibtex\]](bibtex/CVPR23_hand.html)
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">AAAI 2021</div><img src='images/papers/PC-HMR.png' alt="sym" width="100%"></div>
  </div>
  <div class='paper-box-text' markdown="1">
  **<font size=3><font face="Times New Roman">PC-HMR: Pose Calibration for 3D Human Mesh Recovery from 2D Images/Videos</font></font>**

  **<font face="Times New Roman">Tianyu Luan*</font>**<font face="Times New Roman">, Yali Wang*, Junhao Zhang*, Zhe Wang, Zhipeng Zhou, and Yu Qiao. <em>AAAI'2021</em></font>

  [\[PDF\]](https://ojs.aaai.org/index.php/AAAI/article/view/16326/16133) [\[Bibtex\]](bibtex/AAAI2021_pchmr.html)
  </div>
</div>


<span class='anchor' id='teaching'></span>

# 👨‍🏫 Teaching
- *21 Fall*, Teaching Assistant, Computer Vision and Image Processing (CSE 573), University at Buffalo.
- *22 Spring*, Teaching Assistant, Computer Vision and Image Processing (CSE 573), University at Buffalo.
- *22 Fall*, Teaching Assistant, Computer Vision and Image Processing (CSE 573), University at Buffalo.

<span class='anchor' id='service'></span>

# 👨‍🎓 Service
- *Conference Reviews:* CVPR'23'24, ICCV'23, ECCV'24, ACM MM'24.
- *Joural Reviews:* TPAMI, MVA.
  
<span class='anchor' id='experiences'></span>

# 💻 Experiences
- *2024.06 - present*, Reseach Intern, [Pixocial](https://pixocial.com/), Bellevue, WA, United States. <br> Working with [Dr. Haoxiang Li](https://resume.haoxiang.org/).
- *2024.02 - 2024.05*, Reseach Intern, [United Imaging Intelligence](https://usa.united-imaging.com/), Burlington, MA, United States. <br> Worked with [Dr. Zhongpai Gao](https://sites.google.com/site/gaozhongpai) and [Dr. Ziyan Wu](http://wuziyan.com/).
- *2023.05 - 2023.08*, Reseach Intern, [United Imaging Intelligence](https://usa.united-imaging.com/), Cambridge, MA, United States. <br> Worked with [Dr. Zhongpai Gao](https://sites.google.com/site/gaozhongpai) and [Dr. Ziyan Wu](http://wuziyan.com/).
- *2022.05 - 2022.08*, Reseach Intern, [OPPO US Research Center](https://www.innopeaktech.com/), Palo Alto, CA, United States. <br> Worked with [Dr. Zhong Li](https://sites.google.com/site/lizhong19900216) and [Dr. Yi Xu](https://www.linkedin.com/in/yi-xu-42654823/).
- *2019.07 - 2021.06*, Reseach Assistant, [Chinese Academy of Sciences](https://english.cas.cn/), Shenzhen, Guangdong, China. <br> Worked with [Prof. Yali Wang](https://scholar.google.com/citations?user=hD948dkAAAAJ&hl=zh-CN) and [Prof. Yu Qiao](https://scholar.google.com/citations?user=gFtI-8QAAAAJ&hl=en).
- *2017.05 - 2019.04*, Software Engineer, [HUAWEI](https://www.huawei.com/en/), Shenzhen, Guangdong, China.

<span class='anchor' id='educations'></span>

# 📖 Educations
- *2021.08 - present*, Ph.D. candidate in Computer Science, [University at Buffalo](https://www.buffalo.edu/), Buffalo, NY, United States
- *2014.09 - 2017.06*, M.Eng. in Electronical Engineering, [Tsinghua University](https://www.tsinghua.edu.cn/en/), Beijing, China
- *2009.08 - 2013.07*, B.S. in Applied Physics, [University of Science and Technology of China](https://en.ustc.edu.cn/), Hefei, Anhui, China