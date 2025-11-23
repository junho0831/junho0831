![header](https://capsule-render.vercel.app/api?text=오늘도_화이팅_넘치게&animation=fadeIn&type=Waving&color=gradient)

### 👋 안녕하세요! 백엔드 개발자 박준호입니다.

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://github.com/junho0831/junho0831)](https://github.com/junho0831/junho0831)

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=junho0831&show_icons=true&theme=radical)

🌱 **현재 상태**: 백엔드 개발  
📧 **이메일**: junho6667@gmail.com  
🐙 **GitHub**: [github.com/junho0831](https://github.com/junho0831)

---

## 🚀 좋아하는 기술

**백엔드**  
<img src="https://img.shields.io/badge/Java-green?style=for-the-badge&logo=Java&logoColor=007396" /> 
<img src="https://img.shields.io/badge/Spring Boot-green?style=for-the-badge&logo=Spring&logoColor=6DB33F" /> 
<img src="https://img.shields.io/badge/Python-blueviolet?style=for-the-badge&logo=Python&logoColor=ffdd54" /> 
<img src="https://img.shields.io/badge/MySQL-blue?style=for-the-badge&logo=MySQL&logoColor=white" /> 
<img src="https://img.shields.io/badge/Redis-red?style=for-the-badge&logo=Redis&logoColor=white" /> 

**프론트엔드**  
<img src="https://img.shields.io/badge/JavaScript-yellow?style=for-the-badge&logo=JavaScript&logoColor=F7DF1E" /> 
<img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=Vue.js&logoColor=white" /> 

**데브옵스 및 기타**  
<img src="https://img.shields.io/badge/GitLab-orange?style=for-the-badge&logo=gitlab" /> 
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" /> 
<img src="https://img.shields.io/badge/CI/CD-lightgrey?style=for-the-badge&logo=GitHubActions&logoColor=black" /> 
<img src="https://img.shields.io/badge/Langchain-lightgrey?style=for-the-badge&logo=Langchain&logoColor=blue" /> 
<img src="https://img.shields.io/badge/Streamlit-orange?style=for-the-badge&logo=Streamlit&logoColor=white" /> 

---

## 🥾 현재 하는 일
- 기존 레거시 시스템 유지보수 및 신규 API 연동 개발
- Vue.js 기반 UI 기능 개선
- 백준 알고리즘 풀이 (골드 진행 중) → [바로가기](https://www.acmicpc.net/user/junho7778)

---

# 🔭 경력 요약  
*(README 상단에는 요약, 아래에는 상세 버전)*

### 엔셀 (2025.01 ~ 현재) — 백엔드 개발자
- Spring Boot 기반 API 유지보수 및 신규 기능 개발
- Vue.js 기반 UI 개선 및 상태 관리 구조 정리

### 투바 (2024.07 ~ 2024.12) — ERP 유지보수
- 파일 업로드 고도화(50MB×10개 안정성 확보)
- PHP → Java 마이그레이션

### 헥토 (2023.10 ~ 2024.07)
- KMS(지식관리시스템) 신규 API 개발
- 스마트큐 AI 인터뷰 시스템 개발(LangChain·RAG)

### 헥토이노베이션 (2022.08 ~ 2023.09)
- LG PASS MONEY API 개발
- 배치 자동화 및 운영 안정화

---

# 🧩 경력 상세(문제 · 원인 · 해결 · 성과)

## 🔹 엔셀 | SMIP 유지보수 (2025.01 ~ 현재)

### [문제]
- API마다 예외 처리 방식이 달라 장애 원인 분석 시간이 증가  
- Vue.js 상태가 화면 단위로 흩어져 복잡도 상승

### [해결]
- 공통 예외 처리 계층 구축 + 데이터 검증 정책 확립  
- MVVM 패턴 적용 및 공통 스토어 도입

### [성과]
- 장애 분석 리드타임 **40분 → 12분**  
- 동일 오류 재발률 **30% 감소**

---

## 🔹 투바 | ERP 유지보수 (2024.07 ~ 2024.12)

### [문제]
- PHP 기반 레거시 구조로 협업·확장 어려움  
- 대용량 업로드 시 파일/DB 정합성 이슈 발생

### [해결]
- Java 기반 API로 재구축, REST 표준화  
- AtomicInteger 고유 ID + @Transactional 파일 정리 구조 적용

### [성과]
- 업로드 실패율 **18% → 0%**  
- 운영팀 장애 문의 **월 20건 → 10건**

---

## 🔹 헥토 | KMS 시스템 (2024.03 ~ 2024.07)

### [문제]
- 수동 배포로 리드타임 증가  
- HashMap 기반 비정형 데이터로 명세 불일치

### [해결]
- GitLab CI/CD + Docker 자동화 구축  
- Nginx Reverse Proxy 기반 Staging 환경 표준화

### [성과]
- 릴리스 리드타임 **1시간 → 25분**  
- 배포 실패율 **5% → 0%**

---

## 🔹 헥토 | 스마트큐(인터뷰 시스템) (2023.10 ~ 2024.07)

### [문제]
- 키워드 검색 방식으로 원하는 인터뷰 자료 찾기 어려움  
- 반복 상담 처리 비효율

### [해결]
- LangChain + RAG 기반 맥락 검색 구축  
- 응답 생성 비동기화(Background Worker)

### [성과]
- 검색 정확도 **60% → 80%**  
- 응답 대기 시간 **5분 → 1분**  
- 상담팀 업무 **주당 12시간 절감**

---

## 🔹 헥토이노베이션 | 세이프캐시 (2022.08 ~ 2023.09)

### [해결 & 성과]
- 배치 자동화 및 Admin 기능 고도화 → 데이터 정합성 이슈 **월 3건 → 0건**

---

## 📫 사이드 프로젝트

| 프로젝트 | 내용 | 링크 |
|----------|------|------|
| **소모임 시스템 개발** | OAuth 2.0 + JWT 인증, Spring Security 권한 관리 | https://github.com/junho0831/loopers-junho |
| **알고리즘 스터디** | 알고리즘 풀이 및 코드 리뷰 흐름 운영 | https://github.com/junho0831/junho-algo-java |
| **GPT 프로젝트** | OpenAI GPT 기반 API 서비스 개발 | https://github.com/KAN-JUNHO/fastApiProject2 |

---

✍️ **꾸준히 학습하며 성장하는 백엔드 개발자 박준호입니다.**
