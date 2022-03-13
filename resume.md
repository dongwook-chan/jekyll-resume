---
title: "장동욱의 이력서"
layout: resume
---

# 장동욱

> 데이터 플랫폼 개발자입니다. RDBMS의 parser 및 replication 모듈에 관심이 많아 끊임없이 연구하고 개발합니다.

## 연락처
+82 10 4055 8705  
dongwook.chan@gmail.com

## 학력

### **서강대학교** <span>2013.02&ndash;2020.02</span>

**전공:** 경영학, 컴퓨터공학  
**성적:** 4.0/4.5  

## 수상

### **Dean's List**
경영학부 성적 우수자로 선정

### **인본장학금**
비전이 촉망되는 경영학부 학생 1명에게 격년으로 지급되는 전액 장학금

### **[Beta Gamma Sigma](https://www.betagammasigma.org/about/what-is-bgs)**
AACSB 인증 경영대학을 상위 10%의 성적으로 졸업한 평생 회원

## 교외활동

### **[창업동아리 BLACK BOX](https://www.facebook.com/iblackbox/)** <span>2013.03&ndash;2015.01</span>
**교육부장 및 부회장 역임**    
    - 제 3회 서강대학교 창업경진대회 우수상  
    - 학생 창업을 위한 마케팅 강의, 초청 강사 초빙  
    - 대구경북창업아카데미 커리큘럼 설계 및 해커톤 진행  
<br>
## 경력
### **[대한민국 공군](https://rokaf.airforce.mil.kr/airforce/398/subview.do)** <span>2015.02&ndash;2017.02</span>  
**어학병 복무**  
    - 한미공동탄약관리반 배치: 미군 통역 및 기술도서 번역  
    - 한미연합훈련 UFG 파견: Computer Assisted eXercise 자료 번역 및 통역  
    - 세계군인체육대회 파견: 선수단 통역 및 매니지먼트  
    - F35전력화 TF 파견: 록히드 마틴社의 정보체계 매뉴얼 번역  
<br>
### **[Alda Linguo](https://www.crunchbase.com/organization/aldalinguo)** <span>2019.12&ndash;2020.02</span>
**영미권 사용자를 위한 한국어 학습 데이터 수집 담당**  
    - base64로 암호화된 웹 검색 결과를 복호화하여 크롤링  
    - json 형식으로 수집한 데이터를 xlsx로 변환하여 리포팅  
<br>
### **[티맥스티베로](https://www.tmaxdata.com/product/productView.do?prod_cd=tibero&detail_gubun=prod_main)** <span>2020.03&ndash;2020.06</span>
RDBMS Tibero를 설계, 개발 및 유지보수    
<br>
**[Tibero8] `INSERT INTO SELECT` 구현** <font size="2">C++, Flex & Bison</font>  
    - `INSERT INTO SELECT` 구문 syntax spec 분석 및 Bison 구현  
    - Tibero6의 로직을 참고하여 Tibero8에 C++로 구현  
<br>
**[Tibero6] 복수 테이블이 명시된 `ORACLE JOIN` 구현** <font size="2">C</font>  
    - 조건절 자료구조 재설계: 복수 테이블을 가리킬 수 있도록  
    - 테이블 간의 관계를 graph로 구현  
    - cycle detection에서 tree가 아니라고 판별될 경우 semantic error raise  
    - graph의 다양한 형태에 따라 unit test 작성 (multiple tree case 포함)  
<br>
**[Tibero6] 패치 관리** <font size="2">SVN</font>  
    - 사이트별 커스터마이징을 위한 패치 생성  
    - 신규 패치 생성 및 기존 패치 merge/split  
<br>
**각종 유틸리티 학습 및 공유** <font size="2">C, C++</font>  
<br>
### **[카카오](https://www.kakaocorp.com/page/)** <span>2020.07&ndash;현재</span>
실시간 CDC (데이터 복제) 솔루션 **LOMIO**, 대용량 파일 적재 솔루션 **DA-VINCI** 개발 및 운영   
<br>
**[LOMIO] LOMIO 운영 / 서비스별 커스터마이징** <font size="2">Python, MySQL, Kafka</font>  
    - 카카오 4개 법인, 20여 개 서비스에 LOMIO 적용  
    - 카카오커머스 BI의 NiFi->LOMIO 전환 전담  
    - 카카오커머스 주문 API 및 ERP의 LOMIO 적용 전담 ('22 04월 서비스 투입 예정)  
    - 서비스별 요구사항 개발 (데이터 가공/변환, 컴플라이언스 로직, thruput 최적화)  
    - 서비스별 라이브러리 커스터마이징을 위한 패치 관리 전담  
<br>
**[LOMIO] LOMIO 개발** <font size="2">Python, MySQL, kafka</font>  
전사 실시간 CDC(데이터 복제) 솔루션  
    - 무중단/무손실/무중복 복제를 위한 DB 연결/재연결 기능 개발  
    - thruput 개선을 위한 최적화  
    - 도커 전환  
    - 테스트 환경 구축 및 unit test 작성 중  
<br>
**[LOMIO] 라이브러리 개발** <font size="2">Python, MySQL</font>  
전사 실시간 CDC(데이터 복제) 솔루션  
    - MySQL 소스코드 분석 및 binlog event 디버깅 통해 저수준 버그 해결  
    - python-mysql-replication의 replication protocol 미준수 항목 교정  
    - 타임존 인식, 데이터 소싱 프로파일링, 복제 세션 및 복제 쿼리 최적화를 위한 라이브러리 개발  
<br>
**[LOMIO] 소스코드 통합 및 타 저장소로의 확장** <font size="2">Python, MySQL, kafka</font>  
    - 산재한 저장소를 통합하여 유지보수 비용 최소화  
    - DB와의 결합도를 낮추기 위한 리팩토링  
    - PostgreSQL 지원을 위한 개발 / MongoDB 및 Hadoop 지원 검토 중  
<br>
**[DA-VINCI] 개발 및 운영** <font size="2">Python, Flask, JavaScript, MySQL, PostgreSQL</font>  
전사 대용량 파일 적재 솔루션 (file to RDBMS)  
    - 개발 배경: 인증 모듈 사용 및 작업 로깅으로 컴플라이언스 이슈 해결  
    - csv, xlsx 파일 업로드를 위한 web interface 구현 (SPA)  
    - 업로드 속도 향상을 위해 멀티스레드/멀티프로세스 업로드/적재  
    - 적재 최적화를 위한 RDBMS 시스템 변수 설정  
<br>
**초기적재 솔루션 개발 중** <font size="2">Python, MySQL, Kudu</font>  
<br>
## 오픈소스 기여

### **[python-mysql-replication](https://github.com/noplay/python-mysql-replication)** <span>2021.02&ndash;현재</span>
**MySQL replication protocol의 Python client**  
    - protocol에 위배된 코드 교정  
    - 최신 protocol 반영하여 코드 갱신  
    - 커뮤니티 서포트: 질의응답, 요청 기능 추가  
    - 기여 순위 6위  

### **[kafka-python](https://github.com/dpkp/kafka-python)** <span>2021.02</span>
**Kafka의 Python client**  
    - Kafka producer config의 잘못된 서술 교정  

### **[mysql-server](https://github.com/mysql/mysql-server)** <span>2021.09&ndash;현재</span>
**오픈소스 RDBMS**  
    - 미갱신된 system variable list 갱신  
    - MySQL Documentation의 잘못된 서술 교정 및 최신 코드에 맞게 갱신  
<br>
## 자격증
### **정보처리산업기사**
일련번호: 16652006687Y
<br>
### **[Oracle Certified Professional 11](https://www.credly.com/badges/498fcbba-977d-4edb-a75f-8cf89feac25f/linked_in_profile)**
일련번호: 254156974DBA11G
<br>
## 온라인 저지
### **[백준 온라인 저지](https://www.acmicpc.net/)**
**[Gold I 등급](https://solved.ac/profile/dongwook)**
<br>
## 각종 링크
### **[GitHub](https://github.com/dongwook-chan)**
### **[LinkedIn](https://www.linkedin.com/in/dongwook-chang-3ab763147/)**
### **[기술 블로그](https://dongwook-chan.github.io/)**
