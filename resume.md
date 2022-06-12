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

### **[Sogang Univ.](https://wwwe.sogang.ac.kr/wwwe/index_new.html)** <span>2013.02&ndash;2020.02</span>

B.B.A. Business Administration  
B.Eng. in Computer Science and Engineering  
GPA: 4.0/4.5 (cum laude)

## Honors
### **Dean's List**
Awarded to top 50 student in Sogang business school.

### **Inbon Scholarship**
Full scholarship awarded biannually to 1 student who is exceptionally promising and has excellent academic performance 

### **[Beta Gamma Sigma](https://www.betagammasigma.org/about/what-is-bgs)**
Accepted as a lifetime member of Beta Gamma Sigma for being top 10% of undergraduate students in a business school accredited by [AACSB](https://www.betagammasigma.org/mainsitedev/about/affiliations/about-affiliations-aacsb?utm_source=Landing%20Page&utm_medium=Link&utm_campaign=BGS%20Branding&utm_content=AACSB)
<br>
## Extracurricular Activities
### **[Startup club Black Box](https://www.facebook.com/iblackbox/)** <span>2013.03&ndash;2015.01</span>
**Vice president**    
    - 3rd place in annual startup competition at Sogang univ.    
    - Gave lectures on marketing, invited speakers to motivate members    
    - Designed startup curriculum and volunteered at mid-semester hackathon  
<br>
## Work Experience
### **[ROKAF](https://rokaf.airforce.mil.kr/airforce/398/subview.do)** <span>2015.02&ndash;2017.02</span>  
**Interpreter** at Republic Of Korea Air Force  
    - [17th MAGNUM](https://www.globalsecurity.org/military/facility/cheongju.htm): Interpreted for military officers and translated USAF technical order  
    - '15 [UFG](https://en.wikipedia.org/wiki/Ulchi-Freedom_Guardian): Translated documents for Computer Assisted eXercise  
    - '15 [CISM](https://en.wikipedia.org/wiki/Military_World_Games): Interpreted for Egyptian athletes   
    - F35 Augmentation TF: Translated manual for Lockheed Martin information system  
    - Safety Manual TF: Translated safety manual for hazardous chemicals  
<br>
### **[TmaxTibero](http://www.tmaxsoft.com/products/tibero/)** <span>2020.03&ndash;2020.06</span>
**Researcher** developing/designing parser/psm of Tibero, enterprise RDBMS  
<br>
**[Tibero8] Implemented parser for `INSERT INTO SELECT`** <font size="2">C++, Flex & Bison</font>  
    - Analyzed syntax for `INSERT INTO SELECT` and added parser rules and codes  
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
### **[Kakao](https://www.kakaocorp.com/page/?lang=en)** <span>2020.07&ndash;2022.06</span>
**Software Engineer** for database replication(LOMIO) and database importation(DAVINCI, MIMEO)  
<br>
**[LOMIO] Developed LOMIO, real-time CDC solution** <font size="2">Python, MySQL, Kafka</font>  
    - Improved auto-reconnect feature in case of failure    
    - Optimized event queue to maximize thruput  
    - Adopted Docker for efficient deployment  
    - Numerous customization logic to fit services' needs  
    - Maintained patch files  
<br>
**[LOMIO] MySQL library development** <font size="2">Python, MySQL</font>  
    - Analyzed MySQL source code and debugged event packet to fix event parsing error   
    - Customized library for timezone awareness, data type conversion  
    - Added profiling and set session variables to minimize source overhead    
<br>
**[LOMIO] Refactored & switched to Go** <font size="2">Go, Python, MySQL, kafka</font>  
    - Switch from temporal cohesion of customization logic to functional cohesion to minimize maintenance cost  
    - Unified multiple repos to minimize code update cost    
    - Decouple from MySQL client library to flexibly support other source RDBMSs  
    - Support postgresql as source (design for MongoDB and Hadoop is in progress)  
<br>
**[DAVINCI] Developed large-file-to-RDBMS importation tool**<br><font size="2">Python, Flask, jQuery, MySQL, PostgreSQL</font>  
    - Developed SPA Web interface for file input, preview, column mapping etc.    
    - Utilized multithreading/multiprocessing to boost upload performance   
    - Set system/table-level attributes to optimize load performance    
<br>
**[MIMEO] Developed dump-file-to-kudu importation tool** <font size="2">Python, MySQL, Kudu</font>  
    - Dump on memory instead of disk to minimize disk IO cost  
    - Developed conversion from MySQL data types to Python and Kudu data types    
    - Adopted pyspark to utilize distributed processing on large dump files (>=100GB)  
<br>
### **Kakao** <span>2022.06&ndash;</span>
**Back-end developer** for street view & indoor visual localization  
<br>
## Open Source Contribution

### **[python-mysql-replication](https://github.com/noplay/python-mysql-replication)** <span>2021.02&ndash;</span>
**Python implementation of MySQL replication protocol**  
    - Fixed features violating MySQL replication protocol  
    - Updated code to comply with latest protocol  
    - Community support  
    - Adding requested features  
<br>
### **[kafka-python](https://github.com/dpkp/kafka-python)** <span>2021.02</span>
**Python client for Apache Kafka**  
    - Fixed documentation on Kafka producer config  
<br>
### **[mysql-server](https://github.com/mysql/mysql-server)** <span>2021.10</span>
**(allegedly) The world's most popular open source database**  
    - Updated outdated system variable list  
    - Updated and fixed MySQL Documentation    
<br>
## Certifications
### **Industrial Engineer Information Processing**
Credential ID: 16652006687Y
<br>
### **[Oracle Certified Professional 11](https://www.credly.com/badges/498fcbba-977d-4edb-a75f-8cf89feac25f/linked_in_profile)**
Credential ID: 254156974DBA11G
<br>
## Online Judge
### **[Baekjoon Online Judge](https://www.acmicpc.net/)**
**Rating: [Platinum V](https://solved.ac/profile/dongwook)**
<br>