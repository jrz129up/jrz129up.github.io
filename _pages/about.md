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

<span style="font-size:17px;">I am presently pursuing a master degree in Rural Development at the School of Agricultural Economics and Rural Development, Renmin University of China, under the supervision of [Professor Jiujie Ma](http://www.sard.ruc.edu.cn/szll/zzjs/qzjs/299c34878e4d4d5d8b5878fdd743df0d.htm)</span>   
<br>
<br>
 <!-- 我已经发表 20+ 篇学术论文<a href='https://scholar.google.com/citations?user=WMkMTb4AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=引用"></a>。 -->

My research interests focus on the relationship between grassroots institutions and social development under the political context of socialism with Chinese characteristics, including:

- Investigating the effectiveness of grassroots institutions in maximizing welfare or at least improving welfare:
  - Grassroots organizations and social welfare goals
  - Measurement of welfare
  - Causal mechanisms by which grassroots institutions impact welfare
- External incentives and institutional changes in the context of institutional failure:
  - Heterogeneity of external incentives and optimal incentive combinations
  - How to transform external incentives into internal ones to achieve sustainable development
<br>
Currently, I am primarily exploring **"how to sustainably help communities form relatively effective informal institutions that contribute to welfare improvement."**
<br>
<br>
<span class='anchor' id='-xl'></span>

# 🎓 Education
- *2022.09 - 2025.06(expected)*, <a href="https://www.ruc.edu.cn/"><img class="svg" src="/Renmin_University_of_China_logo.svg" width="21pt"></a> Renmin University of China, School of Agricultural Economics and Rural Development, M.A., in Rural Development
- *2018.09 - 2022.06*, <a href="https://www.bjtu.edu.cn/"><img class="svg" src="/BJTU_emblem.svg" width="21pt"></a> Beijing Jiaotong University, School of Economics and Management, B.A., in Economics
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
  - **Data Sources and Research Methods**：The migration data comes from the 2017 China Migrants Dynamic Survey (CMDS), which includes spatial and temporal information on migration (recording past migration data each year)；constructs a balanced panel data set of 855,560 city pairs (293×292) based on 288 prefecture-level cities and 4 municipalities, covering 10 years from 2007 to 2016; a high-dimensional fixed effects model is used for regression analysis.
  - **Contributions**：Agglomeration effect (AE) induced by high-speed rail (HSR) is not well disentangled from dispersion effects (DE) in previous studies. By using a high-dimensional fixed effect model, this paper explicitly evaluates the impact of HSR’s AE and DE on migrant labourers at city-pair level. 

<br>
- **Runze Jiang**,Jiujie Ma. Can Tangible Incentives Promote Norm Violations? Evidence from China's National Point System for Governance 
  - **Conclusions**：Material incentives do not necessarily encourage people to violate ineffective norms; the organizational capacity at the grassroots level is the primary factor. 
  - **Data Sources and Research Methods**
    - Through field research in 58 villages, qualitative data was collected to understand the basic operation of the point system and to construct a theoretical model
    - Data on public behavior and grassroots organizations was obtained using Python and JavaScript to scrape the WeVillage platform, forming a monthly panel for regression analysis
  - **Contributions**
    - From an objective perspective, this paper adds to the literature in law and economics by showing that using tangible incentives to encourage people to violate ineffective social norms may not be effective
    - From the perspective of the method, this paper demonstrates the motivational crowding-out effect within the context of China's grassroots governance
    - From the perspective of the subject, this paper explores the significant role of grassroots organizations, particularly authoritative party organizations, in influencing public behavior through tangible incentives
  - **Research Agenda**
    - The next phase of the study will employ a Randomized Controlled Trial (RCT), dividing subjects into four groups: the Coase Group (market), the Bruno Group (public-to-public exchange), the Mixed Group, and the Control Group
    - The fundamental difference between the first and second groups is to argue whether the market or a collectivist system under property rights is superior in the public domain; the Mixed Group reflects the characteristics of socialism with Chinese characteristics
    - This comparison will not only demonstrate which resource allocation method is superior in the field of public behavior but also, on a more macro level, argue the merits and drawbacks of different systems
   
<br>
- **Runze Jiang**.A Taste: A No-frills Data Processing Manual for Social Science Research
  - The initial intent behind writing this manual is to provide a simplified understanding of computers, document the data processing procedures in social science research, and summarize experiences in using computers for data processing; based on these foundations, the aim is to generalize these experiences into a book for broader dissemination; even if it does not get published, it will serve as a data processing guide within a smaller scope (e.g., a research group)
  - The manual covers areas including basic computer science (computer organization, operating systems, data structures and algorithms, and computer networks), web scraping, data cleaning, econometrics, and machine learning; the primary focus is currently on the first two sections
  - It includes specific code implementations using Python and JavaScript to address the needs of various scenarios

<span class='anchor' id='-ryjx'></span>

# 🏅 Honors and Rewards
- *2023.06-2024.06*  &nbsp;&nbsp;School of Agricultural Economics and Rural Development, Renmin University of China &nbsp;&nbsp;President of the Graduate Student Union and Academic Department
- *2023.10*    &nbsp;&nbsp;School of Agricultural Economics and Rural Development, Renmin University of China &nbsp;&nbsp; Second-Class Academic Scholarship
- *2022.10*    &nbsp;&nbsp;School of Agricultural Economics and Rural Development, Renmin University of China &nbsp;&nbsp; Second-Class Academic Scholarship
- *2021.04*    &nbsp;&nbsp;7th China National Logistics Design Competition &nbsp;&nbsp; National Second Prize
- *2021.04*    &nbsp;&nbsp;11th "Zhengda Cup" National College Student Market Survey and Analysis Competition   &nbsp;&nbsp; National Third Prize

<span class='anchor' id='-grjl'></span>

# 📄 CV

This is my [CV](/runze_jiang_cv.pdf)


