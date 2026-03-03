<!-- 헤더 -->
<h1 align="center">안녕하세요, 한정훈 입니다 👋</h1>
<p align="center">
 SW 개발자를 희망합니다.<br/>
  Java · JSP/Servlet · Spring Boot · Oracle/MariaDB · MyBatis/JPA · FastAPI · WebSocket · MediaPipe · Redis · AWS
</p>

<p align="center">
  <a href="https://github.com/pobiq?tab=followers"><img src="https://img.shields.io/github/followers/pobiq?style=flat&logo=github" /></a>
  <img src="https://komarev.com/ghpvc/?username=pobiq&style=flat" />
</p>

---

## 소개
- **Hoops** – 농구 매칭/커뮤니티 백엔드 (Spring Boot + JWT + Redis + MariaDB + WebSocket/SSE)
- **BabyHands** – 웹캠 기반 수어 학습 (Jsp/Servlet + FastAPI + Oracle)
- **GenieGoods** - 사용자 맞춤 반려동물 굿즈 시안 자동 생성 및 주문 웹 서비스 (React + Spring Boot + Yolo11 + NanoBanana)

---

## 🔗 대표 레포지토리
- 🔹 [hoops-project/backend](https://github.com/hoops-project/backend) – Spring Boot 기반 농구 매칭/커뮤니티 백엔드
- 🔹 [babyhands-web](https://github.com/pobiq/babyhands-web) – JSP/Servlet + Oracle + MyBatis
- 🔹 [babyhands-python](https://github.com/pobiq/babyhands-python) – FastAPI + MediaPipe/LSTM
- 🔹 [geniegoods/frontend](https://github.com/pobiq/geniegood-frontend) – React 기반 반려동물 굿즈 시안 웹서비스 프론트엔드
- 🔹 [geniegoods/backend](https://github.com/pobiq/geniegoods-backend) – Spring boot 기반 반려동물 굿즈 시안 웹서비스 엔드
- 🔹 [geniegoods/yolo11](https://github.com/pobiq/geniegood-yolo11) – 반려동물 굿즈 시안 웹서비스 Yolo11 모델
- 🔹 [geniegoods/nanobanana](https://github.com/pobiq/geniegoods-nanobanana) – 반려동물 굿즈 시안 웹서비스 나노바나나 API 호출

---

## 🚀 하이라이트 프로젝트

| 프로젝트 | 주요 스택 | 어떤 걸 만들었나요 |
|---|---|---|
| **Hoops Backend** | Spring Boot 3, Spring Security, JWT, JPA, MariaDB, Redis, STOMP WebSocket, SSE, OAuth2, Swagger, AWS | 경기 개설/참가, 채팅, 친구/평가/신고, 알림, 관리자 기능 |
| **BabyHands (Web)** | Java, JSP/Servlet, MyBatis, Oracle, Tomcat | 수어 학습/테스트, 진행률·랭킹, OAuth, 마이페이지 |
| **BabyHands (AI)** | FastAPI, MediaPipe, OpenCV, WebSocket | 실시간 제스처 예측, REST/WS 연동 |
| **GenieGoods (Front)** | React, JavaScript, TailwindCSS, ReactRouter, TanStack Query, Zustand | SPA 구조 설계, Rest API 연동, 결제 API 연동, 카카오 우편번호 API 연동, Zustand로 상태 관리, TanStack Query와 Axios로 백엔드와 비동기 통신 |
| **GenieGoods (Back)** | Spring Boot 4, Spring Security, JWT, JPA, MySQL, OAuth2, Swagger, Spring Batch | JWT Token 발급, 소셜 로그인 기능, Object Storage에 이미지 저장, 다운로드, 인증/인가 구조 설계, API 명세서|
| **GenieGoods (AI)** | FastAPI, OpenCV, Yolo11, NanoBanana | Docker-Compose 기반 모델 컨테이너화, Spring Boot와 연동, 에러시 재생성 로직 추가 |
---

### Hoops – 개요
- 경기 생성/참가(3:3, 5:5), 참가자 승인·강퇴, 전용 그룹채팅
- 친구/초대, 매너 포인트 평가, 신고/블랙리스트, 각종 알림
- 인증/보안: Spring Security + JWT, 실시간: STOMP(WebSocket) / SSE, 캐시·토큰: Redis

### BabyHands – 개요
- 실시간 웹캠 제스처 → **FastAPI** 모델 예측 → **JSP UI** 업데이트  
- **정확도 ≥ 60%** 시 학습 성공 처리 및 `SL_LEARN` 반영  
- 도넛형 진행률, 랭킹 상위 5 + 무한 스크롤, 지난 학습 결과/평균


### 기술 스택
<p align="left">
  <img src="https://img.shields.io/badge/Java-007396?logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?logo=springsecurity&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Tomcat-F8DC75?logo=apachetomcat&logoColor=black" />
  <img src="https://img.shields.io/badge/Oracle-F80000?logo=oracle&logoColor=white" />
  <img src="https://img.shields.io/badge/MariaDB-003545?logo=mariadb&logoColor=white" />
  <img src="https://img.shields.io/badge/MyBatis-BA2F2F" />
  <img src="https://img.shields.io/badge/JPA%2FHibernate-59666C?logo=hibernate&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/WebSocket-STOMP-000000" />
  <img src="https://img.shields.io/badge/SSE-Server--Sent--Events-000000" />
  <img src="https://img.shields.io/badge/OAuth2-Authorization-000000" />
  <img src="https://img.shields.io/badge/JWT-Token-000000" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/MediaPipe-1A73E8" />
  <img src="https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/Swagger-85EA2D?logo=swagger&logoColor=black" />
  <img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?logo=figma&logoColor=white" />
</p>


<p align="center"> <img src="https://github-readme-stats.vercel.app/api?username=pobiq&show_icons=true&hide_border=true" height="150" /> <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pobiq&layout=compact&hide_border=true" height="150" /> <br/> <img src="https://github-readme-streak-stats.herokuapp.com/?user=pobiq&hide_border=true" height="150"/> </p> ```
