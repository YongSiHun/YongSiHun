# 👋 Backend Developer / DevOps Engineer

컨테이너 및 서버리스, DevOps를 기반으로  
**서비스 설계부터 배포, 운영까지 End-to-End로 구축하는 개발자입니다.**

- GCP / Cloudflare 기반 서버리스 아키텍처 설계 경험
- Docker & CI/CD 기반 자동화된 배포 환경 구축
- nginx 기반 웹 서버 라우팅 / TypeScript (Express, NestJS) 기반 애플리케이션 서버 개발
- Bash 스크립트 기반 테스트 자동화


---

![header](https://capsule-render.vercel.app/api?type=soft&color=ffca1a&height=50&section=header&text=Key%20Experience&fontSize=30)

## 🚀 Key Experience

### 1. [기능 추가가 두려운 코드 베이스를 고친 이야기](https://2mukee.tistory.com/1131)

**문제**
- 모든 UI의 레이아웃이 한 코드 파일에서 관리되고 있었다.
- 비즈니스 로직 코드와 UI 코드가 얽혀있었다.
- 단독 함수가 되어야하는 유틸리티 함수끼리 서로 호출하여 비즈니스 로직 함수처럼 작동하고 있었다.
- 아토믹 패턴을 애매하게 사용하여 파일과 모듈의 구조가 불명확 했다.
- 책임이 뒤섞여있어서 코드 수정 시 사이드 이펙트가 많이 발생했다.
- API 호출과 DB 쿼리 로직이 섞여있는 등 끔찍한 모습이 보였다.
- 데이터 가공 로직이 비즈니스 로직과 결합되어 있어서 코드 재활용을 할 수 없었다.
- 파일명, 함수명, 변수명에 대한 컨벤션이 지켜지지 않았다.

**해결**
- [코드 구조 리팩토링 (아토믹 패턴에서 feature based 구조로 변경)](https://github.com/KNUT-Capstone-Design-team-1/wip-application-v2/issues/125)
- [파일명 규칙 및 코드 컨벤션 확립 (워크 플로우 확립)](https://github.com/KNUT-Capstone-Design-team-1/wip-document/blob/main/workflow/pages/%EC%BD%94%EB%93%9C_%EC%BB%A8%EB%B2%A4%EC%85%98.md)
- [expo migration](https://github.com/KNUT-Capstone-Design-team-1/wip-application-v2/issues/70)
- 유지보수에 방해가 되던 라이브러리 대체 (`realm > expo-sqlite` 등)
- [워크로드 분리 (서버리스 API를 특성에 맞게 분리)](https://github.com/KNUT-Capstone-Design-team-1/wip-document/blob/main/diagram/%EC%8B%9C%EC%8A%A4%ED%85%9C_%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98.md)
- [로깅 기능 도입](https://github.com/KNUT-Capstone-Design-team-1/wip-application-v2/issues/91)
- 클라이언트 테스트 도입
- [스크린 플로우 개선(스크린 플로우 다이어그램 작성하여 화면 설계)](https://github.com/KNUT-Capstone-Design-team-1/wip-document/blob/main/diagram/features/%EC%95%8C%EC%95%BD_%EC%8B%9D%EB%B3%84_%EA%B2%80%EC%83%89_%EC%8A%A4%ED%81%AC%EB%A6%B0_%ED%94%8C%EB%A1%9C%EC%9A%B0_%EB%8B%A4%EC%9D%B4%EC%96%B4%EA%B7%B8%EB%9E%A8.md)
- [추상화 수준 통일](https://github.com/KNUT-Capstone-Design-team-1/wip-document/blob/main/development/%EC%B6%94%EC%83%81%ED%99%94.md)

**결과**
- 각 기능 간 종속성이 사라져, 코드 변경 간 사이드 이펙트가 현저히 줄어듦
- 워크로드 분리를 통해 서버리스 API 호출 비용과 배포 비용 절감
- 기능 별로 로직이 분리되어 새로운 기능 추가가 용이해짐
- 정교한 문서화를 통해 팀원 간 소통 오류가 개선됨


---

![header](https://capsule-render.vercel.app/api?type=soft&color=ffca1a&height=50&section=header&text=Project&fontSize=30)

## 🚀 Projects

### 1. 이게뭐약 (~2026)
🔗 https://github.com/KNUT-Capstone-Design-team-1  

- AI 기반 알약 검색 애플리케이션
- [시스템 아키텍처](https://github.com/KNUT-Capstone-Design-team-1/wip-document/blob/main/diagram/%EC%8B%9C%EC%8A%A4%ED%85%9C_%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98.md)

**Role**
- 팀장 / PM / DevOps / Backend

**Key Contributions**
- Docker 기반 서버 컨테이너화
- GitHub Actions 기반 CI/CD 구축
- 서버리스 아키텍처 설계 (Google Cloud Platform / Cloudflare)
- Cloudflare R2 스토리지 연동
- 서비스 전체 리팩토링

**Repositories**
- [application](https://github.com/KNUT-Capstone-Design-team-1/wip-application-v2)
- [serverless](https://github.com/KNUT-Capstone-Design-team-1/wip-serverless)
- [resource-deployer](http://github.com/KNUT-Capstone-Design-team-1)
- [infra](https://github.com/KNUT-Capstone-Design-team-1/wip-infra)
- [client](https://github.com/KNUT-Capstone-Design-team-1/wip-client)
- 외 다수


---

### 2. 모해묵지 (~2021)
🔗 https://github.com/KNUT-Mohaemookji  

- 자취생 요리 추천 웹 서비스  

**Role**
- 팀장 / Backend (Express)

**Key Contributions**
- Jenkins 기반 CI/CD 구축

**Repository**
- [backend](https://github.com/KNUT-Mohaemookji/mohaemookji-backend)


---

### 3. 헤르메스 (~2020)
🔗 https://github.com/HermesProj-KNUT  

- 청각 장애인을 위한 실시간 통역 서비스  

**Role**
- 팀장 / React Native / Embedded (Python)

**Key Contributions**
- Firebase 기반 채팅 서버 구축
- Google Speech-to-Text 연동

**Repositories**
- [Hub](https://github.com/HermesProj-KNUT/Hermes_Hub)
- [App](https://github.com/HermesProj-KNUT/Hermes_App)


---

![header](https://capsule-render.vercel.app/api?type=soft&color=ffca1a&height=50&section=header&text=Skill&fontSize=30)

## 🛠 Tech Stack

### 💻 Programming
- JavaScript / TypeScript  
  → Express / NestJS

### ⚙️ DevOps
- Docker (Compose / Swarm)
- CI/CD (GitHub Actions / GitLab CI / Jenkins)

### ☁️ Cloud
- Google Cloud Platform (Cloud Functions / Cloud Run / Firebase / Firestore)
- Cloudflare (R2 / Workers / D1)
- AWS (EC2 / Route53)
- OpenStack (API)

### 🗄 Database
- MySQL (MariaDB), MongoDB

### 🌐 Network
- Nginx


---

![header](https://capsule-render.vercel.app/api?type=soft&color=ffca1a&height=50&section=header&text=Certification&fontSize=30)

## 📜 Certification
- 정보처리기사
- 리눅스 마스터 1급
- 네트워크 관리사 2급
- PC 정비사 1급
- 정보기기 운용 기능사
- 컴퓨터 활용 2급
- 빅데이터 실무 활용 능력 1급


---

![header](https://capsule-render.vercel.app/api?type=soft&color=ffca1a&height=50&section=header&text=Links&fontSize=30)

## 🔗 Links
- Blog: https://2mukee.tistory.com  
- Community: https://cafe.naver.com/bagsingood1537
