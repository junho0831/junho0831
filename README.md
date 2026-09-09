![header](https://capsule-render.vercel.app/api?text=PARK%20JUNHO&desc=Data%20%26%20Batch%20Backend%20Engineer&animation=fadeIn&type=Waving&color=gradient)

### 안녕하세요. 데이터 정합성과 배치 안정성을 숫자로 증명하는 Data/Batch Backend Engineer 박준호입니다.

[![Hits](https://hits.sh/github.com/junho0831/junho0831.svg?style=flat-square&label=Views&color=555555&logo=github)](https://github.com/junho0831/junho0831)

Java/Spring Boot 백엔드 엔지니어링 역량을 바탕으로 Python/Airflow 기반 대용량 로그 파싱, PostgreSQL 청크 파티션 적재, 고동시성 분산 락 제어 및 장애 복구 자동화 시스템을 구축하고 있습니다.  
약 **1,973만 건** 처리에서 청크 조회·파싱과 COPY 적재를 겹치는 파이프라인으로 처리 시간을 ![](https://img.shields.io/badge/30.6%25_단축-critical?style=flat-square) (`4,175초 → 2,896초`)했으며, 검색 장애 Fallback, Redis 원자적 선점(Lua Script), DB Outbox, 운영자 재처리 API 등 데이터 생성부터 장애 복구까지 이어지는 운영 흐름을 견고하게 설계해 왔습니다.

- **현재 직무**: 엔셀 백엔드 개발자 (Data/Batch Backend)
- **기술 블로그**: [so-dak.com](https://so-dak.com)
- **대표 서비스**: [voice-link.co.kr](https://voice-link.co.kr)
- **이메일**: junho6667@gmail.com
- **GitHub**: [github.com/junho0831](https://github.com/junho0831)

---

## 핵심 성과 매트릭스 (Key Performance Matrix)

| 프로젝트 / 영역 | 기존 (Before) | 개선 후 (After) | 핵심 기술 및 엔지니어링 해결 방식 |
| :--- | :---: | :---: | :--- |
| **대용량 파이프라인 (Prism)**<br>약 1,973만 건 처리 시간 | 4,175초 | ![](https://img.shields.io/badge/2,896초-30.6%25_단축-critical?style=flat-square) | PostgreSQL Range Partition 청크 COPY 스트리밍 및 파이프라인 오버랩 |
| **장애 분석 리드타임 (SMIP)**<br>장애 원인 규명 및 대응 | 40분 | ![](https://img.shields.io/badge/12분-70%25_단축-critical?style=flat-square) | 공통 예외 처리 계층(Global Exception Handler) 표준화 및 회귀 테스트 체계화 |
| **배포 리드타임 (KMS)**<br>빌드·테스트·배포 주기 | 1시간 | ![](https://img.shields.io/badge/25분-실패율_0%25-critical?style=flat-square) | GitLab CI/CD 및 Docker 빌드·배포 자동화 표준화 (58% 단축) |
| **사내 RAG 검색 (SmartQ)**<br>사내 지식 질의응답 | 60% / 5분 | ![](https://img.shields.io/badge/80%25_/_1분-정확도_+20%25p-critical?style=flat-square) | LangChain RAG 및 Contextual Chunking 기반 자동화 (주당 12시간 절감) |
| **데이터 정합성 (SafeCash)**<br>월간 데이터 불일치 이슈 | 월 3건 | ![](https://img.shields.io/badge/0건-100%25_제거-critical?style=flat-square) | 정기 배치 자동화 및 운영자 수동 DB 개입 없는 Admin 재처리 API 구축 |

---

## 기술 스택 (Tech Stack)

**Backend & Data**  
<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=Java&logoColor=white" /> 
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=Spring&logoColor=white" /> 
<img src="https://img.shields.io/badge/JPA%20%2F%20Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white" /> 
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white" /> 
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=PostgreSQL&logoColor=white" /> 
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white" /> 
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white" /> 
<img src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=Elasticsearch&logoColor=white" /> 

**Automation & DevOps**  
<img src="https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=Apache%20Airflow&logoColor=white" /> 
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" /> 
<img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" /> 
<img src="https://img.shields.io/badge/GitLab%20CI%2FCD-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" /> 

**Realtime & Media Infrastructure**  
<img src="https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=WebRTC&logoColor=white" /> 
<img src="https://img.shields.io/badge/LiveKit%20SFU-000000?style=for-the-badge&logo=LiveKit&logoColor=white" /> 
<img src="https://img.shields.io/badge/STUN%2FTURN-coturn-blue?style=for-the-badge" /> 
<img src="https://img.shields.io/badge/SSE%2FWebSocket-4A90E2?style=for-the-badge" /> 

**AI & Search**  
<img src="https://img.shields.io/badge/OpenAI%20API-412991?style=for-the-badge&logo=openai&logoColor=white" /> 
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" /> 
<img src="https://img.shields.io/badge/RAG-000000?style=for-the-badge" /> 

---

## 경력 상세 (Experience)

### 엔셀 | 백엔드 개발자 (2025.01 ~ 현재)

#### 1. Prism - Airflow 대용량 데이터 처리 자동화
- **기술 스택**: `Python` `Airflow` `PostgreSQL` `FTP`
- **핵심 역할 및 성과**:
  - 기존 Java 배치를 Python/Airflow DAG로 이관하며 `다운로드 ➔ 검증 ➔ 변환 ➔ 저장 ➔ 업로드 ➔ 원본 정리` 단계로 Task 분리
  - 업로드 성공 및 DB Commit 이후에만 원본 파일을 삭제하도록 순서를 고정하여 **장애 발생 시 데이터 유실 없는 재실행** 보장
  - `source_file` Unique Constraint와 UPSERT 적재 로직으로 **중복 적재 원천 차단**
  - PostgreSQL Range Partition에 청크별 COPY 적재 및 파이프라이닝을 적용하여 **약 1,973만 건 처리 시간 30.6% 단축** (`4,175초 ➔ 2,896초`)
  - DIE 수율·불량 유형 및 반도체 EUV Root Cause 빈도를 일별 요약 테이블에 멱등(Idempotent) 집계

#### 2. DataForge - Spring 검색 / 인증 / 관리 API
- **기술 스택**: `Java` `Spring Boot` `PostgreSQL` `Redis` `Elasticsearch` `JWT` `OAuth2`
- **핵심 역할 및 성과**:
  - Elasticsearch 장애 시 서비스 중단 없이 DB Fallback 검색으로 자동 전환 (동일 포맷 및 정렬 정책 일관화)
  - Refresh Token 저장·검증·회전·삭제를 **Redis TTL** 기준으로 단일화
  - 중복 신청·승인 방지를 위한 Unique Constraint 및 인덱스 복합 적용
  - 운영자가 직접 복구·조회·수정할 수 있는 **Admin 재처리 API** 구축

#### 3. SMIP - 공통 예외 처리 계층 구축 및 회귀 테스트
- **기술 스택**: `Java` `Spring Boot` `Vue.js` `JUnit5` `Mockito`
- **핵심 역할 및 성과**:
  - API별 상이했던 오류 응답 포맷을 공통 예외 처리 계층(Global Exception Handler)으로 표준화
  - 반복 발생하던 운영 장애 케이스를 JUnit5/Mockito 회귀 테스트로 코드화
  - **장애 분석 리드타임 70% 단축** (`40분 ➔ 12분`), **동일 오류 재발률 30% 감소**

---

### (주) 헥토 | AI개발팀 백엔드 개발자 (2023.10 ~ 2024.07)

#### 1. KMS - CI/CD 배포 자동화
- **기술 스택**: `Java` `Spring Boot` `GitLab CI/CD` `Docker` `Nginx`
- **핵심 역할 및 성과**:
  - GitLab CI/CD와 Docker 기반 빌드·테스트·배포 자동화 표준화 및 Nginx Staging 환경 구축
  - **릴리스 리드타임 58% 단축** (`1시간 ➔ 25분`), **배포 실패율 0% 달성** (`5% ➔ 0%`)

#### 2. SmartQ - 사내 지식 RAG 검색 API
- **기술 스택**: `Java` `Spring Boot` `OpenAI API` `LangChain` `FastAPI`
- **핵심 역할 및 성과**:
  - 키워드 일치 검색 한계를 해결하기 위해 LangChain 기반 사내 지식 RAG API 구축
  - **질의응답 정확도 80% 향상** (`60% ➔ 80%`), **답변 대기 시간 단축** (`5분 ➔ 1분`, 주당 12시간 절감)

---

### (주) 헥토이노베이션 | 마이데이터팀 사원 (2022.08 ~ 2023.10)

#### SafeCash - 정기 배치 및 Admin 재처리 API
- **기술 스택**: `Java` `Spring Boot` `MyBatis` `MySQL` `Crontab`
- **핵심 역할 및 성과**:
  - Crontab 기반 정기 배치 자동화 및 실행 이력/로그 추적 시스템 구축
  - 수동 DB 쿼리 방식을 운영자 Admin UI/API 재처리 방식으로 전환
  - **데이터 정합성 이슈 0건 달성** (`월 3건 ➔ 0건`)

---

## 대표 프로젝트 (Featured Project)

### VoiceLink - 실시간 음성 매칭·통화 서비스 ([voice-link.co.kr](https://voice-link.co.kr))
> 고동시성 분산 락, 이벤트 무결성, 실시간 미디어 인프라를 1인 전담 설계·개발·배포·운영한 프로덕션 프로젝트

- **기술 스택**: `Java` `Spring Boot` `Redis` `Lua Script` `DB Outbox` `Pub/Sub` `LiveKit SFU` `Docker` `Nginx` `WebRTC`
- **핵심 엔지니어링 문제 해결**:
  - **원자적 선점(Atomic Claim)**: Redis ZSET 대기열, Presence TTL, **Redis Lua Script** 기반으로 stale 결과 반환 및 중복 선점 원천 방지
  - **Cancel Marker 재검증**: 재매칭 직후 이전 결과가 반환되는 레이스 컨디션 방지 및 stale 결과 즉시 폐기
  - **DB Outbox + `FOR UPDATE SKIP LOCKED`**: Redis Pub/Sub 순단 시에도 매칭 이벤트가 유실되지 않도록 보장
  - **세션 직렬화**: LiveKit Webhook과 `/match/end` 처리를 DB 비관적 락(`PESSIMISTIC_WRITE`)으로 직렬화해 유령 세션 충돌 해결
  - **인프라 1인 운영**: Docker, Nginx 리버스 프록시/stream SNI, SSL 자동 갱신, coturn TURN 포트포워딩 구축

---

## 기술 블로그 대표 포스팅 ([so-dak.com](https://so-dak.com))

- WebRTC SFU와 STUN/TURN 서버 1인 구축 및 트래픽 분산 최적화기
- Redis Lua Script를 활용한 분산 환경 원자적 티켓팅/매칭 동시성 제어
- DB Outbox 패턴과 `FOR UPDATE SKIP LOCKED`로 분산 이벤트 유실 0% 달성하기
- 대용량 데이터 스트리밍과 PostgreSQL COPY 파이프라인 튜닝 실무

---

## Education & Awards

- **포스코 (POSTECH) AI / Big Data 아카데미** (2019.04 ~ 2019.06) — 최우수조 수상
- **공공빅데이터 교육** (2020.08 ~ 2020.09) — 우수상 수상
- **동명대학교 로봇시스템공학과** (2015.03 ~ 2019.03) — 학점 3.72 / 4.5, 도립진자 제어 시스템 설계 논문
- **대한적십자 헌혈은장** (120회 이상 헌혈)

---

## 링크 모음

| 서비스 / 링크 | 설명 | URL |
| :--- | :--- | :--- |
| **VoiceLink** | 실시간 음성 매칭 서비스 (실서비스 운영) | [voice-link.co.kr](https://voice-link.co.kr) |
| **So-Dak 블로그** | 백엔드 & 인프라 실무 트러블슈팅 기술 블로그 | [so-dak.com](https://so-dak.com) |
| **GitHub** | 전체 소스코드 및 활동 저장소 | [github.com/junho0831](https://github.com/junho0831) |

---

<div align="center">
  <b>데이터 정합성과 운영 복구력을 숫자로 증명하는 엔지니어 박준호입니다.</b>
</div>
