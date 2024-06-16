---
title: "장동욱의 이력서"
layout: resume
---

# Dongwook Chang

Phone: +82 10 4055 8705  
Email: <dongwook.chan@gmail.com>  
GitHub: <https://github.com/dongwook-chan>  
LinkedIn: <https://www.linkedin.com/in/dongwook-chang>  


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

Selected as the sole recipient of the full Scholarship among students for demonstrating exceptional vision.  

### **[Beta Gamma Sigma](https://www.betagammasigma.org/about/what-is-bgs)**

Accepted as a lifetime member for being top 10% of undergraduate students in a top 5% of business program accredited by [AACSB](https://www.betagammasigma.org/mainsitedev/about/affiliations/about-affiliations-aacsb?utm_source=Landing%20Page&utm_medium=Link&utm_campaign=BGS%20Branding&utm_content=AACSB)
<br>

## Activities

### **[Open Source Contribution Academy](https://www.contribution.ac)**
<span>2023.05&ndash;</span>

**Lead mentor for [python-mysql-replication](https://github.com/julien-duponchelle/python-mysql-replication)**  
    - Delivered lectures on MySQL replication protocol, guiding mentees' project contributions  
    - Secured 3rd place at the final presentation  
<br>

## Work
### **[Kakao](https://www.kakaocorp.com/page/?lang=en)** <span>2022.06&ndash;</span>
**Software Engineer** developed serving pipeline for SLAM and [CMS](https://elseif.kakao.com/2020/session/95) for street view
<br>  
**Served SLAM model** <font size="2">Python, Flask</font>  
    - Incorporated queue to create pipeline for preprocessing and inference  
    - Incorporated server-side session to store client-specific parameters  
<br>

**Developed API and admin dashboard** <font size="2">Java, Spring, MySQL, PostgreSQL</font>  
    - Developed APIs for MySQL/PostgreSQL query  
    - Optimized queries to reduce response time
<br>

**Image Extract Machine** <font size="2">Python</font>  
    - Maintained application to sample images from video  
    - Clustered and mapped coordinates to administrative district using PostGIS  
    - Dockerized and deployed on k8s
<br>

**Developed Chatbot** <font size="2">Python, Flask</font>  
    - Automated repetitive query requests  
<br>

**Developed library for object storage** <font size="2">Python</font>  
    - Wrapped REST API calls for object storage  
    - 40% faster than existing language-native interface  
<br>

### **Kakao** <span>2020.07&ndash;2022.06</span>

**Software Engineer** developed database replication([LOMIO](https://elseif.kakao.com/2020/session/99)) and database importation(DAVINCI, MIMEO) solutions
<br>  
**Developed LOMIO, real-time [CDC](https://en.wikipedia.org/wiki/Change_data_capture) solution** <font size="2">Python, Go, MySQL, Kafka</font>  
    - Analyzed MySQL source code and analyzed event packet to fix event parsing error  
    - Improved auto-reconnect feature in case of DB failure for better reliability  
    - Dockerized and utilized docker compose for efficient deployment  
    - Customer specific features to process data and maintained patch files  
    - Converted the source base to Go to improve performance (x2)  
    - Decoupled data processing from data access layer  
    - Add PostgreSQL as source DBMS  
  <br>
**[DAVINCI] Developed large-file-to-RDBMS importation tool** <font size="2">Python, Flask, jQuery, MySQL, PostgreSQL</font>  
    - Developed SPA Web interface for file input, preview, column mapping etc.  
    - Utilized multithreading/multiprocessing to boost upload performance  
<br>
**[MIMEO] Developed dump-file-to-kudu importation tool** <font size="2">Python, MySQL, Kudu</font>  
    - Dumped on memory instead to minimize disk IO cost  
    - Developed conversion from MySQL data types to Python and Kudu data types  
<br>

### **[TmaxTibero](https://www.tmaxtibero.com/main.do)** <span>2020.03&ndash;2020.06</span>

**Researcher** developed/designed parser/psm module for [Tibero](https://www.tmaxsoft.com/products/tibero/), enterprise RDBMS  
<br>
**Implemented `INSERT INTO SELECT` statement for Tibero8** <font size="2">C++, Flex & Bison</font>  
    - Implemented grammar rules, actions and data structures for the statement.  
<br>
**Implemented `ORACLE JOIN(+)` predicates with multiple(>=3) tables for Tibero6** <font size="2">C</font>   
    - Constructed graphs to represent relationship between table references  
    - Aided Samsung Electronics to migrate from Oracle to Tibero  
<br>
**Patch & build maintenance** <font size="2">SVN, emacs</font>  
    - Created/merged/split patch to customize to fit users' needs  
<br>

### **[ROKAF](https://www.airforce.mil.kr/user/indexSub.action?codyMenuSeq=56562&siteId=airforce-eng&menuUIType=top)** <span>2015.02&ndash;2017.02</span>  
**English Interpreter** at Republic of Korea Air Force  
    - [17th MAGNUM](https://www.globalsecurity.org/military/facility/cheongju.htm): Interpreted for military officers and translated USAF technical order  
    - '15 [UFG](https://en.wikipedia.org/wiki/Ulchi-Freedom_Guardian): Translated documents for Computer Assisted eXercise  
    - '15 [CISM](https://www.milsport.one/cism/what-is-cism): Interpreted for Egyptian athletes in an international sports event  
    - F-35 Operationalization TF: Translated Lockheed Martin information system manuals  
<br>

## Open Source
### **[MysqlCdc](https://github.com/rusuly/MySqlCdc)** <span>2023.12&ndash;</span>
**C# client for MySQL replication protocol**  
    - Implemented Rand_event [<font size="2">[PR]</font>](https://github.com/rusuly/MySqlCdc/pull/32)  
<br>

### **[go-mysql](https://github.com/go-mysql-org/go-mysql)** <span>2023.08&ndash;</span>

**Go client for MySQL replication protocol**  
    - Implemented visibility field in Table_map_event for MySQL 8.0.23+ [<font size="2">[PR]</font>](https://github.com/go-mysql-org/go-mysql/pull/813)  
<br>

### **[python-mysql-replication](https://github.com/noplay/python-mysql-replication)** <span>2021.02&ndash;</span>

**Python client for MySQL replication protocol**  
    - Minimized MySQL performance impact [<font size="2">[PR]</font>](https://github.com/julien-duponchelle/python-mysql-replication/pull/446) [<font size="2">[PR]</font>](https://github.com/julien-duponchelle/python-mysql-replication/pull/448) [<font size="2">[PR]</font>](https://github.com/julien-duponchelle/python-mysql-replication/pull/431)  
    - Improved protocol compliance [<font size="2">[PR]</font>](https://github.com/noplay/python-mysql-replication/pull/352) [<font size="2">[PR]</font>](https://github.com/noplay/python-mysql-replication/pull/355) [<font size="2">[PR]</font>](https://github.com/noplay/python-mysql-replication/pull/360) [<font size="2">[PR]</font>](https://github.com/noplay/python-mysql-replication/pull/361) [<font size="2">[PR]</font>](https://github.com/julien-duponchelle/python-mysql-replication/pull/446)  
    - Fixed bugs [<font size="2">[PR]</font>](https://github.com/noplay/python-mysql-replication/pull/369) [<font size="2">[PR]</font>](https://github.com/noplay/python-mysql-replication/pull/397)  
    - Implemented feature requests [<font size="2">[PR]</font>](https://github.com/noplay/python-mysql-replication/pull/351) [<font size="2">[PR]</font>](https://github.com/noplay/python-mysql-replication/pull/357)  
    - Maintainer and top 3 contributor  
<br>

### **[mysql-server](https://github.com/mysql/mysql-server)** <span>2021.10&ndash;</span>

**RDBMS**  
    - Identified and documented undocumented SQL modes [<font size="2">[bug]</font>](https://bugs.mysql.com/bug.php?id=105144)  
    - Corrected the formula for the length of null-bitmask field in the documentation [<font size="2">[bug]</font>](https://bugs.mysql.com/bug.php?id=105297)  
    - Identified and documented undocumented system variables [<font size="2">[bug]</font>](https://bugs.mysql.com/bug.php?id=105300)  
<br>

## Certifications

### **Deep Learning for Data Analysis and Image Processing**

Credential ID: 2023-공개SW-심화-9호
<br>

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
