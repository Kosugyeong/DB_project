
# 교육 시설 운영 데이터 관리 DB 프로젝트
<br>

## ✏프로젝트 소개

 1. 교육 시설 운영 데이터를 설계하고, 교육 시설 운영하는데에 발생하는 모든 행동들에 대해 쿼리문을 작성하는 프로젝트입니다. 
 2. 체계적인 센터 운영을 위한 다양한 프로세스를 구성하였습니다.
 3. 교육생을 중심으로 한 다양한 데이터를 조회 및 수정할 수 있습니다.

<br>

## 개발환경


-	Platform : Windows 10
-	Oracle version : Oracle Database 11g
-	Developer tool : SQL Developer
- ERD tool : eXERD


<br>

## 구현 기능

### 관리자
1. 교사 계정 관리 및 개설 과정, 개설 과목에 사용하게 될 기초 정보를 등록 및 관리 
2. 여러 명의 교사와 교육생 정보를 등록 및 관리
3. 특정 개설 과정을 선택하는 경우 다양한 방식으로 조회 및 시스템 관리
4. 여러 개의 개설 과정과 과목을 등록 및 관리
5. 훈련비 측정 시스템을 관리
6. 전반적인 상담시스템을 등록 및 관리

### 교사
1. 자신의 강의 스케줄을 확인
2. 강의를 마친 과목에 대한 성적 처리를 위해서 배점 입출력
3. 강의를 마친 과목에 대한 성적 처리를 위해서 성적 입출력
4. 강의한 과정에 한해 선택하는 경우 모든 교육생의 출결을 조회
5. 교육생의 상담 내용 관리

### 교육생
1. 본인의 월 별 훈련비 조회 가능
2. 진행 과목에 대한 상담 조회 및 관리
3. 매일 근태 기록 및 현황 조회

<br>

## 담당 업무
|팀원|담당업무|
|------|-------------|
|**고수경**|**[관리자] 로그인 기능, 기초 정보 관리, 교사 계정 관리, 개설 과정 관리, 개설 과목 관리**|
|김영석|[관리자] 시험 관리 및 성적 조회|
|김은지|[교사] 과목상담 답변</br>[교육생] 과목상담 작성 및 조회 오류수정|
|백재민|[관리자] 교사 추천 도서 관리</br>[교사] 강의 스케줄 조회, 성적 입출력, 출결 관리 및 출결 조회, 추천도서 관리 기능 전체</br>[교육생] 성적 조회, 교사 추천도서 조회|
|박채은|[관리자] 수료 교육생 취업활동 관리, 협력기업관리, 개설 과정관리 수료날짜 지정, 출결 관리 및 출결 조회</br>[교사] 배점 입출력</br>[교육생] 수료 교육생 취업활동 조회, 협력기업 조회|
|황혜연|[교육생] 출결 관리 및 출결 조회, 훈련비 조회, 과목상담 작성 및 조회|

<br>

## 제작 후기
  - 설계를 아무리 꼼꼼하게 짰다고 해도 SQL구문 단계로 넘어가 쿼리문을 날려보았을 때 오류 혹은 의문을 가지게 되는 것을 겪어보고서, ERD 작성의 중요성을 느끼게 되었다.
  - 팀원들과의 원활한 소통과 협력 덕분에 모두의 의견이 전부 반영된 프로젝트로 완성이 되었다고 생각한다. 또한 ERD를 설계할 때와 순서도를 작성할 때 팀원들과 꾸준히 의견을 주고받으며 세세하게 짬으로 인해 ANSI-SQL과 PL/SQL을 작성할 때에큰 어려움이 없었다고 생각한다.
  - 모든 프로젝트를 진행하기 전 DB설계는 제일 기초가 되는 단계이므로 이 작업이 제일 중요한 단계라는 것을 깨달았다. 



