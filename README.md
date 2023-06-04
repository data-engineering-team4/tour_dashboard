# ✈️ 국내 여행 어디로 갈까?
### 공공 데이터 포털의 tour API를 활용한 국내 관광 정보 시각화 대시보드
<br>

## ✔️ 프로젝트 개요
### 목적
공공 데이터 포털의 관광 관련 api, KOSIS 국가 통계 포털의 범죄 데이터를 활용해 편의 시설, 행사 정보, 많이 가는 지역, 범죄가 많이 발생하는 지역 등 국내 관광의 다양한 정보를 시각화하여 제공한다.
<br>

### 개발 기간
- 23.05.29 ~ 23.06.02
<br>

### 팀원 소개 및 역할
|  이름  | 역할 | GitHub | 
| :---: | :---: | :--- |
| 김승언 | AWS 환경 세팅, 데이터 적재, 시각화 및 대시보드 | [@SikHyeya](https://github.com/SikHyeya) |
| 김선호 | DB 모델링, 데이터 적재, 시각화 및 대시보드 | [@sunhokim1457](https://github.com/sunhokim1457) |
| 김지석 | DB 모델링, 데이터 적재, 시각화 및 대시보드 | [@plays0708](https://github.com/plays0708) |
| 송지혜 | DB 모델링, 데이터 적재, 시각화 및 대시보드 | [@ssongjj](https://github.com/ssongjj) |
<br>

## ⚒️ Tech Stack
| Field | Stack |
|:---:|:---:|
| Data | <img src="https://img.shields.io/badge/amazonaws-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"><img src="https://img.shields.io/badge/googlecolab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white"><img src="https://img.shields.io/badge/postgresql-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"> ||
| Language | <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"> ||
| Dashboard | <img src="https://img.shields.io/badge/tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white"> ||
| Tools | <img src="https://img.shields.io/badge/trello-0052CC?style=for-the-badge&logo=trello&logoColor=white"><img src="https://img.shields.io/badge/slack-4A154B?style=for-the-badge&logo=slack&logoColor=white"><img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"> ||
<br>

## 🧩 ERD
![erd](https://github.com/data-engineering-team4/tour_dashboard/assets/123959802/62256e26-2257-46c3-af71-1e02846b00b1)
<br>

## 🗾 대시보드 구성
![국내 시설 및 행사 현황 대시보드](https://github.com/data-engineering-team4/tour_dashboard/assets/123959802/1782ede4-1c56-4968-92cd-fa5e55e583e1)
![월별 관광객 대시보드](https://github.com/data-engineering-team4/tour_dashboard/assets/123959802/e91c1b3e-6846-4452-8ac3-06b44230ae2a)
![관광객 대비 인프라 대시보드](https://github.com/data-engineering-team4/tour_dashboard/assets/123959802/9c076365-b78a-4411-a250-dbd3f6ad7952)
![범죄율 대시보드](https://github.com/data-engineering-team4/tour_dashboard/assets/123959802/d4f461de-f650-44fc-9298-f956280fafc9)
<br>

## 🫕 API Source
- [한국관광공사_관광빅데이터 정보 서비스_GW](https://www.data.go.kr/tcs/dss/selectApiDataDetailView.do?publicDataPk=15101972)
- [한국관광공사_국문 관광정보 서비스_GW](https://www.data.go.kr/iim/api/selectAPIAcountView.do)
- [범죄의 검거 상황(총괄)](https://kosis.kr/statHtml/statHtml.do?orgId=135&tblId=DT_135N_1A001A&vw_cd=MT_ZTITLE&list_id=135_001_001_001_001&scrId=&seqNo=&lang_mode=ko&obj_var_id=&itm_id=&conn_path=MT_ZTITLE&path=%252FstatisticsList%252FstatisticsListIndex.do)
