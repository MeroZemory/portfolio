# 김지오 (Jio Kim)

**게임 보안 팀 리드 & 백엔드 개발자**

- **Email:** merozemory@gmail.com
- **LinkedIn:** [linkedin.com/in/jio-kim-a63389321](https://www.linkedin.com/in/jio-kim-a63389321)

---

## 소개

6년간 게임 보안 분야에서 안티치트 팀을 리딩하며 보안 전략 수립과 치팅 탐지 R&D를 총괄했습니다. 보안 솔루션 개발뿐 아니라 Node.js/TypeScript 기반의 백엔드 시스템 개발 및 운영 대시보드 유지보수 경험을 보유하고 있습니다. PyTorch 기반 시계열 AI 모델을 도입하여 탐지를 고도화했으며, Jenkins/TeamCity CI/CD 파이프라인 최적화를 통해 DevOps 환경을 개선해 왔습니다.

---

## 기술

### 핵심 역량
- 위협 및 취약점 관리
- 리버스 엔지니어링
- 어셈블리 언어

### 프로그래밍 언어
| 분류 | 기술 |
|------|------|
| **주력** | C/C++, TypeScript, Python, C# |
| **보조** | Lua, Java, Assembly |

### 기술 스택
| 분류 | 기술 |
|------|------|
| **보안** | 리버스 엔지니어링, 안티치트 개발, 취약점 분석 (웹/앱/게임), 패킷 분석 (Wireshark, Fiddler) |
| **백엔드** | Node.js, Express, TypeScript, ASP.NET Core MVC, FastAPI, GraphQL, Discord.js, RESTful API |
| **프론트엔드** | React, Flutter |
| **AI/ML** | PyTorch (시계열 모델), LangChain, RAG, FAISS |
| **데이터베이스** | MySQL, PostgreSQL, MongoDB, Neo4j, Redis |
| **DevOps** | Jenkins, TeamCity, Git, Docker |
| **데스크톱** | WPF, Electron |

---

## 경력

### 크립텍트 (Cryptect)
**게임보안팀** | 2019.08 – 2025.07 (6년)

#### 게임보안팀 리드 (2021.08 – 2025.07)
- 게임 보안 전략 수립 및 치팅 탐지 R&D 총괄
- 안티치트 솔루션 (CheatBlocker) 개발 및 유지보수 (클라이언트/서버/웹)
- PyTorch 기반 키스트로크 시계열 모델 개발 (치팅 탐지)
- Node.js/Express/TypeScript 기반 백엔드 시스템 및 운영 대시보드 유지보수
- Jenkins/TeamCity CI/CD 파이프라인 자동화 및 코드 사이닝 통합
- WPF/Electron 기반 데스크톱 도구 유지보수

#### 분석팀 / 리버스 엔지니어 (2019.08 – 2021.08)
- 게임 보안 솔루션 유지보수 (클라이언트/서버/웹)
- 치트 분석 및 대응
- 보안 기술 연구 개발

---

### 라인플러스 (LINE Plus Corp)
**GrayLab (Product Security)** | 2019.04 – 2019.06 (3개월, 인턴)

- 보안 취약점 분석 (외부 보안 솔루션, 모바일 앱, 웹)

---

## 프로젝트

### 업무 프로젝트

#### AI 기반 하드웨어 매크로 탐지 시스템
> PyTorch + LSTM 기반 시계열 분석으로 하드웨어 매크로 탐지

- **배경:** 기존 시그니처 방식으로는 탐지 불가능한 하드웨어 매크로 사용 유저 증가
- **해결책:** 유저의 입력 타이밍을 시계열 데이터로 분석하여 기계적 패턴 학습 및 탐지
- **기술 스택:** PyTorch, LSTM
- **성과:** 내부 검증 결과 유의미한 F1-Score 달성, 실제 제재 프로세스에 도입

#### 통합 보안 운영 플랫폼 유지보수 및 개선
> 실시간 보안 위협 시각화 및 원클릭 제재 시스템

- **배경:** 기존 보안 운영 플랫폼의 기능 부족 및 성능 이슈
- **작업 내용:** 신규 기능 추가, 성능 최적화, 버그 수정
- **기술 스택:** Node.js, Express, TypeScript, React, ASP.NET Core
- **성과:** 플랫폼 안정성 및 운영 효율성 향상

### 개인 프로젝트

#### Auto-Trader - AI 기반 알고리즘 트레이딩 플랫폼
> 딥러닝 기반 프로덕션급 알고리즘 트레이딩 시스템

- **개요:** 6개의 AI 모델(Transformer, MLP, SSM, GNN, Multimodal), 실시간 데이터 파이프라인, 고성능 백테스팅 엔진을 통합한 트레이딩 플랫폼
- **기술 스택:** FastAPI, React, PyTorch, PostgreSQL, Redis, WebSocket
- **핵심 구현:**
  - Kronos: Decoder-only Transformer 기반 주가 예측 (BSQ 토큰화로 22M+ 벡터 → 4,096 클러스터)
  - TimeMixer/TimeMachine: ICLR 2025 SOTA MLP 및 Mamba SSM 기반 시계열 모델
  - MambaLLM: 멀티모달 모델 (가격 + 뉴스 텍스트 Cross-Attention 융합)
  - 이벤트 기반 백테스팅 엔진: 17+ 트레이딩 전략, Sharpe Ratio/Max Drawdown 자동 분석
  - 실시간 데이터 파이프라인: KIS WebSocket, Redis Pub/Sub, 마이크로초 지연 브로드캐스트

#### Codex Mobile - AI 코드 실행 모바일 플랫폼
> Codex Core를 모바일에서 제어하는 크로스 플랫폼 실시간 애플리케이션

- **개요:** 모바일에서 원격 서버의 Codex Core에 명령을 전달하고, SSE 기반 실시간 로그 스트리밍으로 결과를 확인하는 풀스택 시스템
- **기술 스택:** Flutter, FastAPI, Docker
- **핵심 구현:**
  - SSE 기반 실시간 로그 스트리밍 (<100ms 지연)
  - 에이전트 풀 관리: 레퍼런스 카운팅 기반 수명 관리, graceful shutdown
  - 오프라인 명령 큐잉 및 재연결 시 자동 동기화
  - Feature-First 모듈 아키텍처: Clean Architecture 기반 레이어 분리

#### PlayDex - AI 게임 지식 어시스턴트
> RAG 기반 게임 데이터 AI 챗봇 서비스

- **개요:** 게임 데이터를 기반으로 한 RAG(Retrieval-Augmented Generation) 기반 AI 챗봇. 공식 데이터와 AI 추론을 결합하여 신뢰도 높은 답변 제공
- **기술 스택:** FastAPI, React, LangChain, FAISS, Neo4j, OpenAI API, Docker
- **핵심 구현:**
  - 하이브리드 검색 시스템 (FAISS Vector + BM25 + BGE-M3 Reranking)
  - HyQE (Hypothetical Question Embeddings): 문서 인덱싱 시 가상 질문 생성으로 검색 recall 향상
  - Neuro-Symbolic RAG: RAG + Function Calling + Graph DB 결합
  - Chain-of-Thought 기반 Fine-tuning 데이터셋 생성 파이프라인
  - 증분 인덱싱 시스템 (MD5 해시 기반 변경 감지)
  - SSE 기반 실시간 스트리밍 채팅

#### 온톨로지 파이프라인 - 디지털 트윈 지식 그래프 플랫폼
> Palantir Foundry 스타일의 시맨틱 지식 그래프 데이터 파이프라인

- **개요:** 비정형 데이터를 구조화된 온톨로지로 변환하는 데이터 파이프라인. LLM 기반 자연어 쿼리, 자동 사실 추출, 그래프 데이터베이스 통합
- **기술 스택:** FastAPI, React, Neo4j, GraphQL, OpenAI API, RDF/SHACL, LinkML
- **핵심 구현:**
  - 7단계 데이터 파이프라인 (Bronze → Silver → Gold)
  - NL2Cypher: 자연어 → Neo4j Cypher 쿼리 변환 (12가지 Intent 분류)
  - LLM 기반 사실 추출 및 데이터 품질 검증
  - 증거 중심 아키텍처: 모든 사실의 출처 및 데이터 계보 추적
  - SHACL 검증 및 LinkML 기반 온톨로지 스키마 관리

#### Jouriva - AI 여행 일정 자동 생성 플랫폼
> LLM 기반 개인화 여행 일정 자동 생성 및 검증 시스템

- **개요:** 사용자의 여행 조건을 입력받아 AI가 최적화된 일정을 생성하고, 자동 검증 파이프라인을 통해 품질을 보장하는 풀스택 웹 애플리케이션
- **기술 스택:** FastAPI, React, TypeScript, PostgreSQL, OpenAI API, Leaflet
- **핵심 구현:**
  - 멀티 스테이지 LLM 파이프라인: 생성 → 검증 → 피드백 루프 → 웹 번들 생성
  - 자동 검증 시스템: 안전성, 일정 밀도, 교통 연계성 다차원 검사
  - 체크포인트 복구 시스템: LLM 실패 시 중간 상태 저장 및 비용 최적화
  - Git 스타일 버전 관리: 일정 버전 브랜칭 및 스냅샷
  - SSE 기반 실시간 파이프라인 진행 상황 스트리밍

#### Dayfolio - 기업용 근태·연차 관리 시스템
> Next.js 15 기반 근태관리 및 연차관리 웹 애플리케이션

- **개요:** 복잡한 비즈니스 로직(연차 자동 부여, 타임존 기반 출퇴근 관리)을 처리하며, JWT 기반 인증과 역할 기반 접근 제어를 구현한 풀스택 시스템
- **기술 스택:** Next.js 15, React 19, TypeScript, PostgreSQL, Docker
- **핵심 구현:**
  - 비트마스크 기반 연차 충돌 감지: 중복 신청 방지, 반차/반반차 조합 허용
  - 트랜잭션 기반 출퇴근 처리: 미퇴근 기록 자동 상태 변경
  - JWT 인증 + HTTP-only 쿠키 (XSS 방지), 역할 기반 접근 제어
  - 11개 전략적 DB 인덱스 설계, 슬로우 쿼리 로깅 (500ms 기준)
  - Docker 멀티 스테이지 빌드: 개발/QA/프로덕션 분리

#### Stick-it - 디지털 포스트잇 노트 서비스
> 태블릿 드로잉 앱 + 실시간 디스플레이 + 관리자 콘솔을 연결하는 풀스택 실시간 애플리케이션

- **개요:** 태블릿에서 이미지 기반 노트를 생성하고, WebSocket을 통해 실시간으로 공개 디스플레이에 표시하며, 관리자 콘솔에서 관리할 수 있는 시스템
- **기술 스택:** Flutter, React, FastAPI, PostgreSQL, WebSocket, Docker
- **핵심 구현:**
  - WebSocket 기반 실시간 노트 브로드캐스팅 (asyncio Lock 동시성 제어)
  - 오프라인 우선 아키텍처: 네트워크 미연결 시 로컬 저장 후 자동 동기화
  - Clean Architecture 적용 (Flutter 3-layer 분리)
  - TanStack React Query 기반 서버 상태 관리

#### AI 기반 YouTube 영상 분석 플랫폼
> LLM을 활용한 YouTube 영상 분석 및 요약 웹 애플리케이션

- **개요:** LLM을 활용하여 YouTube 영상을 분석, 전사 및 요약
- **기술 스택:** Next.js, React, Node.js, Express, Socket.io, MongoDB, OpenAI API
- **핵심 구현:**
  - 대용량 오디오 자동 분할 및 병렬 처리
  - Socket.io를 통한 실시간 진행 상황 스트리밍
  - 서버 사이드 캐싱으로 응답 시간 최적화
  - 멀티 AI 모델 아키텍처 구현

#### YAWAWE-Clipper - 소셜 미디어 클리핑 관리 봇
> Discord 기반 멀티 플랫폼 콘텐츠 클리핑 팀 관리 도구

- **개요:** Instagram, TikTok, YouTube 플랫폼의 계정 인증, 클립 조회수 추적, 성과 기반 정산을 자동화하는 Discord 봇
- **기술 스택:** TypeScript, Node.js, Discord.js, MongoDB, Docker
- **핵심 구현:**
  - 멀티 플랫폼 계정 인증 시스템 (고유 코드 기반 자동 검증)
  - Instagram GraphQL API 역엔지니어링 기반 스크래퍼 (2025 최신)
  - 계층적 권한 시스템 (Bot Owner → Server Admin → Clipping Admin → Clipper)
  - 동시성 제어를 위한 Review Lock 시스템
  - 자동 수익 정산 및 조회수 추적

---

## 학력

### 중앙대학교
- **학위:** 학사
- **전공:** 자연과학대학 생명과학부 생명과학전공
- **기간:** 2012.02 – 2020.08

### 세종과학고등학교
- **기간:** 2009.03 – 2012.02

---

## 자격 및 교육

| 자격/수료 | 기관 | 취득일 |
|----------|------|--------|
| 정보처리기사 | 한국산업인력공단 | 2017.05 |
| BEST OF THE BEST 7기 (취약점 분석 트랙) | 한국정보기술연구원 (KITRI) | 2018.07 – 2019.03 |
| 리버스엔지니어링 & 악성코드 분석 과정 | 오픈시큐어랩 | 2016.11 – 2017.03 |

---

## 언어

| 언어 | 수준 |
|------|------|
| 한국어 | 원어민 |
| 영어 | 업무 가능 수준 |
