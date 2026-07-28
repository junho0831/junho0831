![header](https://capsule-render.vercel.app/api?text=오늘도_화이팅_넘치게_🚀&animation=fadeIn&type=Waving&color=gradient)

### 👋 안녕하세요! 백엔드 개발자 박준호입니다.

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://github.com/junho0831/junho0831)](https://github.com/junho0831/junho0831)

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=junho0831&show_icons=true&theme=radical" alt="junho0831 github stats" />
</p>

🌱 **현재 상태**: 백엔드 & 실시간 음성/미디어 인프라 개발  
📝 **기술 블로그**: [so-dak.com](https://so-dak.com)  
📧 **이메일**: junho6667@gmail.com  
🐙 **GitHub**: [github.com/junho0831](https://github.com/junho0831)

---

## 🚀 기술 스택 (Tech Stack)

**Backend & Infrastructure**  
<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=Java&logoColor=white" /> 
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=Spring&logoColor=white" /> 
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white" /> 
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white" /> 
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=PostgreSQL&logoColor=white" /> 
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white" /> 

**Realtime & Media Systems**  
<img src="https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=WebRTC&logoColor=white" /> 
<img src="https://img.shields.io/badge/LiveKit%20SFU-000000?style=for-the-badge&logo=LiveKit&logoColor=white" /> 
<img src="https://img.shields.io/badge/STUN%2FTURN-coturn-blue?style=for-the-badge" /> 
<img src="https://img.shields.io/badge/SSE%2FWebSocket-4A90E2?style=for-the-badge" /> 

**Frontend & Mobile**  
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black" /> 
<img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=Vue.js&logoColor=white" /> 
<img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=Flutter&logoColor=white" /> 

**DevOps & Tools**  
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" /> 
<img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" /> 
<img src="https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" /> 
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" /> 

---

## 📌 주요 프로젝트 (Main Projects)

### 🎙️ Voice-Link 실시간 음성 통화 서비스
- **기술 스택**: Spring Boot, LiveKit SFU, WebRTC, Redis (분산 락 & 타임라인), SSE, PostgreSQL, Nginx
- **설명**: 1:1 실시간 음성 통화 및 다자간 미디어 스트리밍 플랫폼 개발
- **핵심 역할**:
  - LiveKit 미디어 서버 웹훅 처리 및 Redis 기반 5초 단위 통화 품질 타임라인 저장/진단 서비스 구축
  - Redis 분산 락(Redisson) 기반 동시 통화 매칭 경쟁 조건(Race Condition) 방지 및 SSE 상태 실시간 전파
  - WebRTC NAT 우회를 위한 coturn/TURN/TLS 서버 최적화 및 네트워크 트러블슈팅

### 📝 So-Dak 기술 블로그 ([so-dak.com](https://so-dak.com))
- **기술 스택**: WordPress, Python Automation, AI Pipeline, Docker
- **설명**: 실무 백엔드, WebRTC, 인프라 최적화 경험 공유를 위한 기술 블로그 운영 및 포스팅 파이프라인 구축

---

## 🥾 현재 하는 일
- Voice-Link 실시간 음성 서비스 및 백엔드 인프라 고도화
- 기존 레거시 시스템 유지보수 및 신규 API 연동 개발
- 기술 블로그 ([so-dak.com](https://so-dak.com)) 운영 및 기술 지식 공유
- 백준 알고리즘 풀이 (골드 진행 중) → [바로가기](https://www.acmicpc.net/user/junho7778)

---

# 🔭 경력 요약  

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

# 🧩 경력 상세 (문제 · 원인 · 해결 · 성과)

## 🔹 엔셀 | SMIP 유지보수 (2025.01 ~ 현재)
- **[문제]**: API마다 예외 처리 방식이 달라 장애 원인 분석 시간 증가 / Vue.js 상태 분산
- **[해결]**: 공통 예외 처리 계층 구축 + 데이터 검증 정책 확립 / MVVM 패턴 및 공통 스토어 도입
- **[성과]**: 장애 분석 리드타임 **40분 → 12분** (70% 감소) / 동일 오류 재발률 **30% 감소**

## 🔹 투바 | ERP 유지보수 (2024.07 ~ 2024.12)
- **[문제]**: 레거시 PHP 구조로 확장성 저하 / 대용량 업로드 시 파일-DB 정합성 이슈
- **[해결]**: Java RESTful API로 재구축 / AtomicInteger 고유 ID + `@Transactional` 파일 정리 구조 적용
- **[성과]**: 업로드 실패율 **18% → 0%** / 운영팀 장애 문의 **월 20건 → 10건**

## 🔹 헥토 | KMS 시스템 (2024.03 ~ 2024.07)
- **[문제]**: 수동 배포로 인한 리드타임 증가 / HashMap 기반 비정형 데이터 명세 불일치
- **[해결]**: GitLab CI/CD + Docker 자동화 구축 / Nginx Reverse Proxy Staging 환경 표준화
- **[성과]**: 릴리스 리드타임 **1시간 → 25분** / 배포 실패율 **5% → 0%**

## 🔹 헥토 | 스마트큐(인터뷰 시스템) (2023.10 ~ 2024.07)
- **[문제]**: 단순 키워드 검색 방식으로 원하는 자료 검색 비효율 / 상담 처리 지연
- **[해결]**: LangChain + RAG 기반 맥락 검색 및 백그라운드 비동기 응답 처리 구축
- **[성과]**: 검색 정확도 **60% → 80%** / 응답 대기 시간 **5분 → 1분** / 주당 업무 시간 **12시간 절감**

## 🔹 헥토이노베이션 | 세이프캐시 (2022.08 ~ 2023.09)
- **[해결 & 성과]**: 배치 자동화 및 Admin 기능 고도화 → 데이터 정합성 이슈 **월 3건 → 0건**

---

## 📫 사이드 프로젝트 및 링크

| 프로젝트 | 내용 | 링크 |
|----------|------|------|
| **Voice-Link 음성 통화** | WebRTC, LiveKit, Redis 분산 락, SSE 기반 음성 통화 플랫폼 | - |
| **So-Dak 기술 블로그** | 백엔드, WebRTC, 인프라 실무 기술 블로그 | [so-dak.com](https://so-dak.com) |
| **소모임 시스템 개발** | OAuth 2.0 + JWT 인증, Spring Security 권한 관리 | [GitHub Link](https://github.com/junho0831/loopers-junho) |
| **알고리즘 스터디** | 알고리즘 풀이 및 코드 리뷰 흐름 운영 | [GitHub Link](https://github.com/junho0831/junho-algo-java) |
| **GPT 프로젝트** | OpenAI GPT 기반 API 서비스 개발 | [GitHub Link](https://github.com/KAN-JUNHO/fastApiProject2) |

---

✍️ **꾸준히 학습하고 실무 가치를 창출하는 백엔드 개발자 박준호입니다.**
