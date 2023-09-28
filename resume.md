---
title: "장동욱의 이력서"
layout: resume
---

# Dongwook Chang

Phone: +82 10 4055 8705  
Email: <dongwook.chan@gmail.com>  
GitHub: <https://github.com/dongwook-chan>  
Website: <https://dongwook-chan.github.io>  
LinkedIn: <https://www.linkedin.com/in/dongwook-chang-3ab763147>  


## Education

### **[Sogang Univ.](https://wwwe.sogang.ac.kr/wwwe/index_new.html)**

<span>2013.02&ndash;2020.02</span>

B.B.A. in Business Administration  
B.Eng. in Computer Science and Engineering  
GPA: 4.0/4.5 (Cum laude)

## Honors

### **[Dean's List](https://isbs.sogang.ac.kr/isbs/isbs03_3_1.html)**

Awarded to top 50 student in Sogang business school.

### **[Inbon Scholarship](http://www.sogang.ac.kr/bachelor/students/notice/notice08.html)**

Full scholarship awarded biannually to 1 student who is exceptionally promising and has excellent academic performance  

### **[Beta Gamma Sigma](https://www.betagammasigma.org/about/what-is-bgs)**

Accepted as a lifetime member of Beta Gamma Sigma for being top 10% of undergraduate students in a top 5% of business program accredited by [AACSB](https://www.betagammasigma.org/mainsitedev/about/affiliations/about-affiliations-aacsb?utm_source=Landing%20Page&utm_medium=Link&utm_campaign=BGS%20Branding&utm_content=AACSB)
<br>

## Activities

### **Startup club [Black Box](https://www.facebook.com/iblackbox/)**

<span>2013.03&ndash;2015.01</span>

**Vice president**  
    - 3rd place in annual startup competition at Sogang univ.  
    - Gave lectures on marketing, invited speakers to motivate members  
    - Designed startup curriculum and volunteered at mid-semester hackathon  
<br>

### **[Open Source Contribution Academy](https://www.contribution.ac)**
<span>2023.05&ndash;</span>

**Lead mentor for [python-mysql-replication](https://github.com/julien-duponchelle/python-mysql-replication)**  
    - Led team of 24 mentees to contribute to python-mysql-replication  
    - Gave lectures on the project and MySQL/MariaDB replication protocol
    - Fixed bugs, modernized repo and implemented feature requests  
<br>

## Work Experience

### **[ROKAF](https://www.airforce.mil.kr/user/indexSub.action?codyMenuSeq=56562&siteId=airforce-eng&menuUIType=top)**

<span>2015.02&ndash;2017.02</span>  
**Interpreter** at Republic Of Korea Air Force  
    - [17th MAGNUM](https://www.globalsecurity.org/military/facility/cheongju.htm): Interpreted for military officers and translated USAF technical order  
    - '15 [UFG](https://en.wikipedia.org/wiki/Ulchi-Freedom_Guardian): Translated documents for Computer Assisted eXercise  
    - '15 [CISM](https://www.milsport.one/cism/what-is-cism): Interpreted for Egyptian athletes  
    - F35 Augmentation TF: Translated manuals for Lockheed Martin information system  
<br>

### **[TmaxTibero](https://www.tmaxtibero.com/main.do)**

<span>2020.03&ndash;2020.06</span>

**Researcher** developed/designed parser/psm module for [Tibero](https://www.tmaxsoft.com/products/tibero/), enterprise RDBMS  
<br>
**[Tibero8] Implemented parser for `INSERT INTO SELECT`** <font size="2">C++, Flex & Bison</font>  
    - Analyzed syntax for `INSERT INTO SELECT` and added grammar rules  
<br>
**[Tibero6] Parsed `ORACLE JOIN(+)` predicates with multiple(>=3) tables** <font size="2">C</font>  
    - Redesigned data structure to hold multiple table references  
    - Constructed graphs to represent relationship between table references  
    - Raised semantic error for joins with any cycle  
    - Wrote unit tests for various graphs including multiple tree cases  
<br>
**[Tibero6] Patch & build maintenance** <font size="2">SVN</font>  
    - Created/merged/split patch to customize to fit consumer's needs  
<br>

### **[Kakao](https://www.kakaocorp.com/page/?lang=en)**

<span>2020.07&ndash;2022.06</span>

**Software Engineer** developed database replication([LOMIO](https://elseif.kakao.com/2020/session/99)) and database importation(DAVINCI, MIMEO) solutions  
<br>
**[LOMIO] Developed LOMIO, real-time [CDC](https://en.wikipedia.org/wiki/Change_data_capture) solution** <font size="2">Python, MySQL, Kafka</font>  
    - Improved auto-reconnect feature in case of failure  
    - Optimized event queue to maximize thruput  
    - Adopted Docker for efficient deployment  
    - Customer specific features to process data  
    - Maintained patch files  
<br>
**[LOMIO] MySQL library development** <font size="2">Python, MySQL</font>  
    - Analyzed MySQL source code and analyzed event packet to fix event parsing error  
    - Modified library for timezone awareness, data type conversion  
    - Added profiling and set session variables to minimize source overhead  
<br>
**[LOMIO] Refactored & switched to Go** <font size="2">Python, Go, MySQL, kafka</font>  
    - Improved functional cohesion for efficient maintenance  
    - Unified multiple repos to minimize code maintenance  
    - Decouple from MySQL client library to flexibly support other source RDBMSs  
    - Support postgresql as source  
<br>
**[DAVINCI] Developed large-file-to-RDBMS importation tool** <font size="2">Python, Flask, jQuery, MySQL, PostgreSQL</font>  
    - Developed SPA Web interface for file input, preview, column mapping etc.  
    - Utilized multithreading/multiprocessing to boost upload performance  
    - Set system/table-level attributes to optimize load performance  
<br>
**[MIMEO] Developed dump-file-to-kudu importation tool** <font size="2">Python, MySQL, Kudu</font>  
    - Dump on memory instead of disk to minimize disk IO cost  
    - Developed conversion from MySQL data types to Python and Kudu data types  
    - Adopted pyspark to utilize distributed processing on large dump files (>=100GB)  
<br>

### **Kakao**

<span>2022.06&ndash;</span>  
**Software Engineer** developed serving pipeline for vSLAM and [CMS](https://elseif.kakao.com/2020/session/95) for street view   
<br>
**[vSLAM] Served vSLAM model** <font size="2">Python, Flask</font>  
    - Designed feature storage  
    - Adopted queue to create pipeline for preprocessing and inference  
    - Adopted server-side session to store client-specific parameters  
    - Adopted Black code formatter  
<br>
**[CMS] Developed API and admin dashboard** <font size="2">Java, Spring, MySQL, PostgreSQL</font>  
    - Developed API for MySQL/PostgreSQL query  
    - Optimized queries  
<br> 
**[CMS] Image Extractor** <font size="2">Python</font>  
    - Maintained application to sample image from video  
    - Clustered and mapped coordinates to administrative district using PostGIS  
<br>
**Developed Chatbot** <font size="2">Python, Flask</font>  
    - Automated repetitive query requests  
<br>

## Open Source Contribution

### **[go-mysql](https://github.com/go-mysql-org/go-mysql)**

<span>2023.08&ndash;</span>

**A powerful mysql toolset with Go**  
    - Implemented visibility field in table map event for MySQL 8.0.23+  
<br>
### **[python-mysql-replication](https://github.com/noplay/python-mysql-replication)**

<span>2021.02&ndash;</span>

**Python implementation of MySQL replication protocol**  
    - Fixed features violating MySQL replication protocol  
    - Updated code to comply with latest protocol  
    - developed requested features & community support  
    - Top 2 active contributor & collaborator  
<br>
### **[kafka-python](https://github.com/dpkp/kafka-python)**

<span>2021.02</span>

**Python client for Apache Kafka**  
    - Fixed documentation on Kafka producer config  
<br>
### **[mysql-server](https://github.com/mysql/mysql-server)**

<span>2021.10</span>

**The world's most popular open source database**  
    - Updated outdated system variable list  
    - Updated and fixed MySQL Documentation  
<br>
## Certifications

### **Industrial Engineer Information Processing**

Credential ID: 16652006687Y
<br>

### **Oracle Certified Professional 11**

Credential ID: [254156974DBA11G](https://www.credly.com/badges/498fcbba-977d-4edb-a75f-8cf89feac25f/linked_in_profile)
<br>

## Online Judge

### **Baekjoon Online Judge**

**Rating: [Platinum V](https://solved.ac/en/profile/dongwook)**
<br>
