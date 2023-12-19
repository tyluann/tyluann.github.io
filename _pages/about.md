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

I am a third-year Ph.D. candidate of [Computer Science & Engineering Department](https://engineering.buffalo.edu/computer-science-engineering.html), [University at Buffalo](https://www.buffalo.edu/), advised by [Prof. Junsong Yuan](https://cse.buffalo.edu/~jsyuan/). 
My research interest focuses 3D reconstruction.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

<span class='anchor' id='news'></span>

# 🔥 News
- *2023.02*: &nbsp;🎉🎉 Our paper "High Fidelity 3D Hand Shape Reconstruction via Scalable Graph Frequency Decomposition" is accept by CVPR 2023! Preprint paper and code will be released soon.
- *2022.05*: &nbsp;🎉🎉 I will join [Innopeak](https://www.innopeaktech.com/) as research intern this summer.


<span class='anchor' id='publications'></span>

# 📝 Selected Publications

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/papers/High-fidelity-hand.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
High Fidelity 3D Hand Shape Reconstruction\\ via Scalable Graph Frequency Decomposition
**Tianyu Luan**, Yuanhao Zhai, Jingjing Meng, Zhong Li, Zhang Chen, Yi Xu, and Junsong Yuan
[PDF]() [Code]() [Bibtex]() -->

<div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">ICCV 2023</div><img src='images/papers/ICCV23.png' alt="sym" width="100%"></div>
  </div>
  <div class='paper-box-text' markdown="1">
  **<font size=3><font face="Times New Roman">Towards Generic Image Manipulation Detection with Weakly-Supervised Self-Consistency Learning</font></font>**

  <font face="Times New Roman">Yuanhao Zhai, <b>Tianyu Luan</b>, David Doermann, and Junsong Yuan.</font>

  [\[PDF\]](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhai_Towards_Generic_Image_Manipulation_Detection_with_Weakly-Supervised_Self-Consistency_Learning_ICCV_2023_paper.pdf) [\[Code\]](https://github.com/yhZhai/WSCL) [\[Bibtex\]](https://scholar.googleusercontent.com/scholar.bib?q=info:n1I-9B1nxw0J:scholar.google.com/&output=citation&scisdr=ClH1ZfLwEJDI2yqqf20:AFWwaeYAAAAAZYGsZ23MpV74K1-ln4WldSPJdEU&scisig=AFWwaeYAAAAAZYGsZyBVVoSWge4K9uUtPSm74kk&scisf=4&ct=citation&cd=-1&hl=en&scfhb=1)
  </div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">CVPR 2023</div><img src='images/papers/High-fidelity-hand.png' alt="sym" width="100%"></div>
  </div>
  <div class='paper-box-text' markdown="1">
  **<font size=3><font face="Times New Roman">High Fidelity 3D Hand Shape Reconstruction via Scalable Graph Frequency Decomposition</font></font>**

  **<font face="Times New Roman">Tianyu Luan</font>**<font face="Times New Roman">, Yuanhao Zhai, Jingjing Meng, Zhong Li, Zhang Chen, Yi Xu, and Junsong Yuan.</font>

  [\[PDF\]](https://openaccess.thecvf.com/content/CVPR2023/papers/Luan_High_Fidelity_3D_Hand_Shape_Reconstruction_via_Scalable_Graph_Frequency_CVPR_2023_paper.pdf) [\[Code\]](https://github.com/tyluann/FreqHand) [\[Bibtex\]](https://scholar.googleusercontent.com/scholar.bib?q=info:TkgP5GwdpD8J:scholar.google.com/&output=citation&scisdr=ClH1ZfLwEJDI2yqtzQQ:AFWwaeYAAAAAZYGr1QQgNSRtQUCzXEw9aiMxx64&scisig=AFWwaeYAAAAAZYGr1bu_wiXZNRrtad3F4HTLLAI&scisf=4&ct=citation&cd=-1&hl=en&scfhb=1)
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">AAAI 2021</div><img src='images/papers/PC-HMR.png' alt="sym" width="100%"></div>
  </div>
  <div class='paper-box-text' markdown="1">
  **<font size=3><font face="Times New Roman">PC-HMR: Pose Calibration for 3D Human Mesh Recovery from 2D Images/Videos</font></font>**

  **<font face="Times New Roman">Tianyu Luan</font>**<font face="Times New Roman">, Yali Wang, Junhao Zhang, Zhe Wang, Zhipeng Zhou, and Yu Qiao.</font>

  [\[PDF\]](https://ojs.aaai.org/index.php/AAAI/article/view/16326/16133) [\[Bibtex\]](https://scholar.googleusercontent.com/scholar.bib?q=info:4lzK9xf0e78J:scholar.google.com/&output=citation&scisdr=CgXmzFsbELDBw5NYnoQ:AAGBfm0AAAAAZAxehoQ9-gBUIKEdmF-1x7XFYksbph3D&scisig=AAGBfm0AAAAAZAxehrPkVkmlqPB0eHbs7uUsJZ7eHaMi&scisf=4&ct=citation&cd=-1&hl=en)
  </div>
</div>


<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->


<span class='anchor' id='educations'></span>

# 📖 Educations
- *2021.08 - now*, Ph.D. in Computer Science, [University at Buffalo](https://www.buffalo.edu/), Buffalo, NY, United States
- *2014.09 - 2017.06*, M.Eng. in Electronical Engineering, [Tsinghua University](https://www.tsinghua.edu.cn/en/), Beijing, China
- *2009.08 - 2013.07*, B.S. in Applied Physics, [University of Science and Technology of China](https://en.ustc.edu.cn/), Hefei, Anhui, China


<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 



# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<span class='anchor' id='experiences'></span>

# 💻 Experiences
- *2023.05 - 2023.08*, Reseach Intern, [United Imaging Intelligence](https://usa.united-imaging.com/), Cambridge, MA, United States
- *2022.05 - 2022.08*, Reseach Intern, [InnoPeak Technology](https://www.innopeaktech.com/), Palo Alto, CA, United States
- *2019.07 - 2021.06*, Reseach Assistant, [Chinese Academy of Sciences](https://english.cas.cn/), Shenzhen, Guangdong, China
- *2017.05 - 2019.04*, Software Engineer, [HUAWEI](https://www.huawei.com/en/), Shenzhen, Guangdong, China