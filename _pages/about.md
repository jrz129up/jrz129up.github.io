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

<span style="font-size:17px;">我现在就读于中国人民大学农业与农村发展学院农村发展专业，师从[马九杰](http://www.sard.ruc.edu.cn/szll/zzjs/qzjs/299c34878e4d4d5d8b5878fdd743df0d.htm)教授</span>   
<br>
<br>
 <!-- 我已经发表 20+ 篇学术论文<a href='https://scholar.google.com/citations?user=WMkMTb4AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=引用"></a>。 -->

My research interests focus on the relationship between grassroots institutions and social development under the political context of socialism with Chinese characteristics, including:

Investigating the effectiveness of grassroots institutions in maximizing welfare or at least improving welfare:
Grassroots organizations and social welfare goals
Measurement of welfare
Causal mechanisms by which grassroots institutions impact welfare
External incentives and institutional changes in the context of institutional failure:
Heterogeneity of external incentives and optimal incentive combinations
How to transform external incentives into internal ones to achieve sustainable development
<br>
Currently, I am primarily exploring **"how to sustainably help communities form relatively effective informal institutions that contribute to welfare improvement."**
<br>
<br>
<span class='anchor' id='-xl'></span>

# 🎓 Education
- *2022.09 - 2025.06(expected)*, <a href="https://www.ruc.edu.cn/"><img class="svg" src="/images/Renmin_University_of_China_logo.svg" width="21pt"></a> Renmin University of China, School of Agricultural Economics and Rural Development, M.A., in Rural Development
- *2018.09 - 2022.06*, <a href="https://www.bjtu.edu.cn/"><img class="svg" src="/images/BJTU_emblem.svg" width="21pt"></a> Beijing Jiaotong University, School of Economics and Management, B.A., in Economics
<br>
<br>
<span class='anchor' id='-lw'></span>

# 📝 Publications

- 	JJ Jiao, QL Zhang, YY Wu, **Runze Jiang**, JE Wang. (2021). Change and Influencing Factors of China's Cross-regional Investment Network Structure. Progress in Geography. [[Website]](https://kns.cnki.net/kcms2/article/abstract?v=f1ZyUc11mdpYllT2xqHJRoxXcKTqVmXr4DtD6ltlH0CYLHwYvyjgm5ybiN0I3myBH_17MYu1KmSN1ftxJqErAFzasLI2IVRl5E5TScazfT91ACYsGHIvu6mYIRAMLyZ1H1MBs-DnPZzWetM5qrWazQ==&uniplatform=NZKPT&language=CHS)
<br>
- 	Chao Wang, **Runze Jiang** et al. (2020). Optimization Strategies for the Beijing Subway Fare System. China Transportation Review. [[Website]](https://kns.cnki.net/kcms2/article/abstract?v=f1ZyUc11mdrdk-T8GIsXuASAVU4iqRt6ZFgldxcDvkNnq-P4MpAAvTu-ilkeUUBW9tyJwd7-F03_h2QJeyfI7w57IX-5-dedSRwFEZknT9S4DpWXoLVtM6JNqpCfcCpEg3hhInWU56GEOwAOXae-1A==&uniplatform=NZKPT&language=CHS)

<br>

# Working Papers

- QL Zhang, **Runze Jiang**, JJ Jiao. Agglomeration and Dispersion Effects of High-speed Rail: A New Perspective of Intercity Labour Migration from China
  - **Conclusions**
    - HSR generates both AE and DE, with AE denominating DE
    - DE first occurs, followed by AE
    - Disparities of employment opportunities, wages, and environment have moderating impacts
  - **Data Sources and Research Methods**：The migration data comes from the 2017 China Migrants Dynamic Survey (CMDS), which includes spatial and temporal information on migration (recording past migration data each year)；constructs a balanced panel data set of 855,560 city pairs (293×292) based on 288 prefecture-level cities and 4 municipalities, covering 10 years from 2007 to 2016; A high-dimensional fixed effects model is used for regression analysis.
  - **Contribution**：Agglomeration effect (AE) induced by high-speed rail (HSR) is not well disentangled from dispersion effects (DE) in previous studies. By using a high-dimensional fixed effect model, this paper explicitly evaluates the impact of HSR’s AE and DE on migrant labourers at city-pair level. 

<br>
- **Runze Jiang**,Jiujie Ma.物质激励能促进规范违背吗？——来自全国治理积分制的证据
  - **研究结论**：物质激励并不利于人们违背无效规范，基层的组织能力才是主要因素
  - **数据来源与研究方法**：实地调研58个村庄收集质性资料，形成对积分制运行的基本了解，构建理论模型；利用Python与JS爬取为村平台数据，获取公共行为、基层组织等数据，并形成月度面板，进行回归分析
  - **研究贡献**
    - 从客体的角度说，当社会规范失效时采取物质激励促使人们违背无效规范的举措并不一定是有效的，补充了法律经济学中有关改变无效社会规范的研究
    - 从方法的角度说，在中国基层语境中证明了物质激励对动机挤出
    - 从主体的角度说，探讨了自治背景下基层组织，特别是拥有实权的党派组织，在公共产品生产中的重要作用
  - 未来拓展
    - 下一步研究将采用RCT，共分为四组，第一组是科斯组（市场化交易组），第二组是布鲁诺组（以公易公组），第三组是混合组，第四组是控制组
    - 第一组与第二组的差在本质上是在论证，公共领域内，到底是市场更优，还是确权前提下的集体主义制度更优；第三组是中国特色社会主义的一个写照
    - 通过对比不仅能证明公共行为领域内，到底是哪一种资源分配方式更优；往更宏观说，这是在论证不同制度的优劣之处
   
<br>
- **Runze Jiang**.浅尝辄止: 社会科学研究的数据处理手册
  - 写作本手册的初衷是陈述对计算机的简约理解，记录在社科研究中进行数据处理的过程，总结运用计算机处理数据的经验，在此基础上形成一般化的经验并成书推广；就算最终无法出版成书，本书也能成为小范围内（例如一个师门）数据处理的指导手册
  - 涉及领域包括基本的计算机科学（计算机组成原理，操作系统，数据结构与算法及计算机网络）；网络爬虫；数据清洗；计量经济学；机器学习。目前主要在撰写前两部分
  - 运用Python与JavaScript实现上述不同场景需求的具体代码

<span class='anchor' id='-ryjx'></span>

# 🏅 荣誉奖项
- *2023.06-2024.06*  &nbsp;&nbsp;中国人民大学农业与农村发展学院研究生会及学术部主席
- *2023.10*    &nbsp;&nbsp;中国人民大学农业与农村发展学院 二等学业奖学金
- *2022.10*    &nbsp;&nbsp;中国人民大学农业与农村发展学院 二等学业奖学金
- *2021.04*    &nbsp;&nbsp;第七届“中国外运杯”全国大学生物流设计大赛 全国二等奖
- *2021.04*    &nbsp;&nbsp;“正大杯”第十一届全国大学生市场调查与分析大赛 全国三等奖

<span class='anchor' id='-grjl'></span>

# 📄 CV

This is my [CV](/runze_jiang_cv.pdf)


