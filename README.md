## 👨‍💻 김준환 | Backend Engineer

문제를 기능이 아니라 **서비스·운영 관점**에서 정의하고,
**정합성·성능·확장성**을 기준으로 의사결정하는 백엔드 개발자입니다.

---

## 🛠 기술 스택

### 언어 · 프레임워크

<p>
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=spring&logoColor=white" />
</p>

### 인프라 · 데이터

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
</p>

---

## 📌 프로젝트

### 전국 IT 동아리 모음 사이트 (TECA)

**전국 IT 동아리 정보 통합 서비스**
`2024.04 ~ 진행 중`

* 전국 대학 IT 동아리 정보를 한 곳에서 제공하는 서비스 개발
* Cloudflare Workers 기반 **서버리스 백엔드 설계 및 운영**
* 봇(User-Agent)과 일반 사용자를 구분하는 **SEO 대응 렌더링 전략** 적용
* 검색 엔진 노출 최적화를 위한 **동적 메타 태그 생성**
* 트래픽 증가 시에도 서버 증설 없이 대응 가능한 구조 설계
* **한 달 기준 10,000건 이상의 요청, MAU 1,200명 달성** (2026.01.15 기준)

---

### 하루멍록 (Harumeonglog)

**반려동물 루틴 관리 + 커뮤니티 서비스**
`2025.01 ~ 진행 중`

* Spring Boot 기반 백엔드 서버 설계 및 구현
* 게시판 / 알림 도메인 담당
* **비동기 기반 알림 처리**로 FCM 알림 지연
  → 최대 10초 → **1초 미만**으로 개선
* Redis 캐시 및 인덱스 최적화로
  **API 지연시간 1983ms → 47ms 개선**
* 좋아요·차단·신고에 **복합 유니크 키** 적용
  → 중복 요청 완전 차단
* **증분 쿼리**로 좋아요·차단 카운트 동시성 문제 해결
* N+1 문제 해결 (Fetch Join, Batch Size 튜닝)
* AWS EB(EC2) / RDS / S3 기반 배포 및 운영
  → **무중단 배포로 다운타임 제거**
---

### Simple-RAG

**문서 기반 질의응답 시스템 (개인 프로젝트)**
`2025.08`

* RAG 구조 설계 및 구현
* SHA-256 기반 문서 **중복 제거 + 스트리밍 해시 처리**
* PostgreSQL + pgvector 테이블 분리 설계
  → 임베딩 크기 확장 대비
* 테스트를 위한 Fake S3 유틸 구현
* InputStream으로 OOM 방지

---

### 세금 챗봇 (Tax Chatbot)

**문서 기반 세무 질의응답 챗봇**
`2025.07 ~ 2025.08`

* RAG 기반 세금 Q&A 챗봇 설계 및 구현
* LangChain, LangSmith 활용
* 검색 정확도 향상을 위한 Retriever 튜닝
* Few-shot Prompt 설계 및 대화 히스토리 유지
* LangSmith 평가 기능을 활용한 응답 품질 비교 실험

---

### QAStudio

**AI 기반 QA 자동화 플랫폼**
`2024.12 ~ 2025.02`

* 백엔드 팀 리드
* OAuth 로그인, 스레드 처리 구조 개선
* GitHub Actions + Docker 기반 CI/CD 파이프라인 구축
* 브랜치 전략, PR 템플릿, 코드 컨벤션 정립
* 헬스체크 기반 배포 안정성 강화

---

### AvAb

**레크리에이션 추천 서비스**
`2023.12 ~ 진행 중`

* 레크리에이션 활동 추천을 위한 **추천 서비스 백엔드 설계 및 구현**
* 플로우 추천 기능 구현
* 스프링 시큐리티 기반 인증 인가 구현

---

## 🧑‍🏫 활동

### UMC (University MakeUs Challenge)

`2023.03 ~ 2025.08`

* 중앙 서버 팀 리드 & 상명대학교 회장
* 전국 30개 대학 800명 이상 대상 **DB / AWS 워크북 배포**
* 교내 학생들을 대상으로 DB / Spring / AWS / 네트워크를 주제로 매주 세미나 진행
* 커리큘럼 및 실습 워크북 직접 제작
* 해커톤·세미나·네트워킹 행사 기획 및 운영

### 멋쟁이 사자처럼 대학

`2025.03 ~ 2026.01`

* 교내 백엔드 파트장
* 학생들을 대상으로 세미나 진행

### 이니로 (교내 IT 동아리)

`2024.03 ~ 2025.08`

* 교내 프로그래밍 경진대회 (수뭉컵 개최)
 * 인프라 구축 및 문제 출제 담당

---

### 해커톤 & 대외 활동

* INHA SW NET-Zero 해커톤 **대상 / 특별상** (2024)
* Nerdinary 해커톤 **우수상** (2024)
* 농심 NDS AWS 직무캠프 **우수상** (2024)
* 교내 프로그래밍 대회 (수뭉컵) 개최
  → 인프라 구축 및 문제 출제 (2024 - 2025)

---

## ✍️ Blog

기술 블로그: https://student-developer-story.tistory.com

---

## 🏆 알고리즘

* BOJ / solved.ac
  [https://solved.ac/musoyou10](https://solved.ac/musoyou10)

---
