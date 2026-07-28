![header](https://capsule-render.vercel.app/api?text=%EC%98%A4%EB%8A%98%EB%8F%84_%ED%99%94%EC%9D%B4%ED%8C%85_%EB%84%98%EC%B9%98%EA%B2%8C_%F0%9F%9A%80&animation=fadeIn&type=Waving&color=gradient)

### 👋 안녕하세요! 백엔드 개발자 박준호입니다.

[![Hits](https://hits.sh/github.com/junho0831/junho0831.svg?style=flat-square&label=Views&color=555555&logo=github)](https://github.com/junho0831/junho0831)

운영 안정성과 데이터 정합성을 개선하는 3년+ 경력의 Java/Spring Boot 백엔드 개발자입니다.  
실제 운영 중 발생할 수 있는 검색 장애 대응, 중복 처리 방지, 인증 상태 관리, 배치 재실행 정합성 확보 등 문제 해결을 중심으로 개발하고 있습니다.

🌱 **현재 상태**: 백엔드 & 실시간 음성/미디어 인프라 개발  
📝 **기술 블로그**: [so-dak.com](https://so-dak.com)  
🌐 **서비스**: [voice-link.co.kr](https://voice-link.co.kr)  
📧 **이메일**: junho6667@gmail.com  
🐙 **GitHub**: [github.com/junho0831](https://github.com/junho0831)

---

## 🚀 기술 스택 (Tech Stack)

**Backend & Data**  
<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=Java&logoColor=white" /> 
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=Spring&logoColor=white" /> 
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white" /> 
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=PostgreSQL&logoColor=white" /> 
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white" /> 
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white" /> 
<img src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=Elasticsearch&logoColor=white" /> 

**Realtime & Media Infrastructure**  
<img src="https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=WebRTC&logoColor=white" /> 
<img src="https://img.shields.io/badge/LiveKit%20SFU-000000?style=for-the-badge&logo=LiveKit&logoColor=white" /> 
<img src="https://img.shields.io/badge/STUN%2FTURN-coturn-blue?style=for-the-badge" /> 
<img src="https://img.shields.io/badge/SSE%2FWebSocket-4A90E2?style=for-the-badge" /> 

**AI & Search**  
<img src="https://img.shields.io/badge/OpenAI%20API-412991?style=for-the-badge&logo=openai&logoColor=white" /> 
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" /> 
<img src="https://img.shields.io/badge/RAG-000000?style=for-the-badge" /> 

**DevOps & Automation**  
<img src="https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=Apache%20Airflow&logoColor=white" /> 
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" /> 
<img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" /> 
<img src="https://img.shields.io/badge/GitLab%20CI%2FCD-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" /> 

---

## 📌 주요 프로젝트 (Main Projects)

### 🎙️ VoiceLink 실시간 음성 통화 서비스 ([voice-link.co.kr](https://voice-link.co.kr))
- **기술 스택**: Spring Boot, LiveKit SFU, WebRTC, Redis, PostgreSQL, SSE, Docker, Nginx
- **핵심 역할 및 성과**:
  - Redis Lua Script, Transactional Outbox Pattern, `FOR UPDATE SKIP LOCKED`, `PESSIMISTIC_WRITE` 기반으로 실시간 동시 매칭 및 통화 세션 정합성 구현
  - LiveKit 미디어 서버 웹훅 및 Redis 기반 5초 단위 통화 품질 타임라인 저장/진단 서비스 설계
  - coturn TURN/TLS 최적화 및 Nginx 리버스 프록시 튜닝으로 모바일/방화벽 연결 실패 최소화

### 📝 So-Dak 기술 블로그 ([so-dak.com](https://so-dak.com))
- **기술 스택**: WordPress, Python Automation, AI Pipeline, Docker
- **설명**: 백엔드, WebRTC, 인프라 실무 노하우 및 운영 장애 대응 기술 포스팅 파이프라인 자동화 운영

---

# 🧩 경력 상세 (Experience)

## 🔹 엔셀 | 백엔드 개발자 (2025.01 ~ 현재)

### 1. Prism - Airflow 대용량 데이터 처리 자동화
* **주요 내용**: Java 배치를 Python/Airflow DAG로 이관하여 FTP 다운로드 -> 검증 -> 변환 -> DB 적재 -> 원본 삭제 단계를 Task 분리
* **기술적 성과**:
  * DB Commit 완료 후 원본 삭제 순서를 고정하여 데이터 유실 없는 재실행 안정성 확보
  * Unique Constraint 및 Upsert 적용으로 중복 적재 방지
  * `Chunk 조회 -> 파싱 -> Range Partition COPY` 방식으로 메모리 효율화

### 2. DataForge - Spring 검색 / 인증 / 관리 API
* **주요 내용**: Elasticsearch 장애 대응 DB Fallback 검색 조율 및 Redis TTL 토큰 관리
* **기술적 성과**:
  * ES 장애 시 사용자와 운영자에게 동일한 결과를 제공하는 DB Fallback 검색 알고리즘 구축
  * Refresh Token 저장·검증·회전을 Redis TTL 기반으로 일원화
  * Index 및 Unique Constraint 적용으로 신청·승인 중복 방지

### 3. SMIP - 공통 예외 처리 계층 구축 및 회귀 테스트
* **주요 내용**: API별 상이한 오류 응답을 공통 예외 처리 계층 및 표준 오류 포맷으로 통합
* **기술적 성과**:
  * 장애 분석 리드타임 **40분 → 12분** (70% 감소)
  * 동일 오류 재발률 **30% 감소**
  * JUnit5/Mockito 기반 회귀 테스트 체계 구축 및 Vue.js 공통 스토어 정리

---

## 🔹 헥토 | 백엔드 개발자 (2022.08 ~ 2024.07)

### 1. KMS - CI/CD 배포 자동화
* **기술 스택**: Spring Boot, GitLab CI/CD, Docker, Nginx
* **성과**: GitLab CI/CD 및 Docker 기반 배포 파이프라인 표준화로 릴리스 리드타임 **1시간 → 25분**, 배포 실패율 **5% → 0%** 달성

### 2. SmartQ - RAG 검색 API
* **기술 스택**: Spring Boot, OpenAI API, LangChain, RAG
* **성과**: LangChain + RAG 기반 맥락 검색 구축으로 검색 정확도 **60% → 80%**, 응답 대기 시간 **5분 → 1분** (주당 업무 12시간 절감)

### 3. 세이프캐시
* **성과**: 데이터 배치 자동화 및 Admin 기능 고도화로 정합성 이슈 **월 3건 → 0건** 달성

---

## 📫 사이드 프로젝트 및 링크

| 프로젝트 | 기술 스택 / 내용 | 링크 |
|----------|-------------------|------|
| **VoiceLink** | WebRTC, LiveKit, Redis Lua Script, Outbox Pattern | [voice-link.co.kr](https://voice-link.co.kr) |
| **So-Dak 기술 블로그** | 백엔드, WebRTC, 인프라 실무 기술 블로그 | [so-dak.com](https://so-dak.com) |
| **소모임 시스템** | OAuth 2.0 + JWT 인증, Spring Security 권한 관리 | [GitHub Link](https://github.com/junho0831/loopers-junho) |
| **GPT API 서비스** | OpenAI GPT 기반 비동기 API 서비스 개발 | [GitHub Link](https://github.com/KAN-JUNHO/fastApiProject2) |

---

✍️ **운영 안정성과 데이터 정합성을 꾸준히 개선하는 백엔드 개발자 박준호입니다.**
