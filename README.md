<div align="center">

<img src="https://img.shields.io/badge/🐾_PETHOTEL-FF6B6B?style=for-the-badge&logoColor=white" height="50"/>

# 🐕 PETHOTEL — 반려견 호텔 예약·관리 플랫폼
> 반려견과 함께하는 특별한 순간을 위한 스마트 호텔 예약 서비스 🏨🐶

[![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)](https://reactjs.org/)
[![Spring Boot](https://img.shields.io/badge/SpringBoot-6DB33F?style=flat-square&logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)](https://www.java.com/)

</div>

---

## 📌 프로젝트 개요

| 항목 | 내용 |
|------|------|
| 📅 개발 기간 | 2026.01.26 ~ 2026.02.12 |
| 👥 팀 구성 | 3인 팀 프로젝트 |
| 🔗 GitHub | [MSA15_3-2 Repository](https://github.com/wjsgnlrkd9822-design/MSA15_3-2.git) |
| 💡 주요 기능 | 객실 예약, 관리자 페이지, 회원 관리, 카카오페이 결제, AI 챗봇 상담 |
| 📊 PPT 링크 | (https://docs.google.com/presentation/d/1Y5Kkb03I9_-gr9pW9zMr2519DH7mtc0N/edit?slide=id.p1#slide=id.p1) |
| 🎬 시연 영상 | https://www.youtube.com/watch?v=3yj7KpHMMHw |

---

## 🛠 기술 스택

### Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

### Backend
![Spring Boot](https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/SpringSecurity-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-BF0000?style=for-the-badge)
![Apache Tomcat](https://img.shields.io/badge/Tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black)

### Database
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

---

## 👥 팀원 및 역할 분담

| 팀원 | 역할 | 주요 기능 |
|------|------|-----------|
| 전휘강 | 🎨 UI/UX · 예약 시스템 · AI 기능 | 메인 페이지, 예약 페이지, 예약 상세 페이지, CCTV 모달, AI 챗봇 |
| 나승현 | 🛡 인증 · 결제 · 마이페이지 | 로그인/회원가입, 카카오페이 결제, 마이페이지 |
| 유지상 | 📋 공지사항 · 관리자 시스템 | 공지사항 페이지, 관리자 페이지 전체 |

---

## ✨ 기능 상세

### 🎨 전휘강 — 메인 페이지 · 예약 · AI 기능

#### 🏠 메인 페이지
- 서비스 소개 카드 렌더링 및 예약 페이지 이동 연결
- **공지사항 모달** — 최신 공지 팝업 표시
- **실시간 CCTV 모달** — 실시간 모니터링 화면 모달 UI
- **AI 챗봇 모달** — OpenAI 기반 실시간 상담 챗봇 연동

#### 📅 예약 페이지
- 날짜 · 견종 · 가격 필터 기반 객실 검색 기능
- 중복 예약 방지 로직 적용
- 예약 상태 실시간 반영

#### 📋 예약 상세 페이지
- 예약 내역 상세 조회 UI
- 상태 관리 및 데이터 연동 처리

#### 🏨 소개 페이지
- 서비스 · 시설 · 팀 정보를 카드형 UI로 구성
- 예약 페이지로 자연스럽게 연결되는 CTA 흐름 설계

---

### 🛡 나승현 — 인증 · 결제 · 마이페이지

#### 🔐 로그인 / 회원가입 페이지
- 일반 로그인 및 소셜 로그인 (카카오 / 네이버 OAuth2)
- Spring Security 기반 인증 처리
- JWT 토큰 발급 및 필터 적용

#### 💳 카카오페이 결제 시스템
- 카카오페이 API 연동 결제 흐름 구현
- 결제 성공 / 실패 / 취소 / 환불 처리
- 쿠폰 할인 적용 기능

#### 👤 마이페이지
- 회원 정보 조회 및 수정
- 반려견 등록 · 수정 · 삭제 (건강 증명서 파일 업로드 포함)
- 예약 내역 조회 및 상태 관리

---

### 📋 유지상 — 공지사항 · 관리자 시스템

#### 📢 공지사항 페이지
- 공지사항 목록 조회 및 상세 페이지 구성
- 페이지네이션 처리

#### 🛠 관리자 페이지
- 전체 예약 관리 (조회 · 수정 · 취소)
- 회원 관리 (목록 조회 · 권한 설정 · 활성화/비활성화)
- 객실 관리 (등록 · 수정 · 삭제)
- 트레이너 관리
- 반려견 현황 및 펫 상태 관리
- 서비스 항목 관리
