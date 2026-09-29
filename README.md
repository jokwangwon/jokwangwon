# 조광원 / Kwang-Won Jo
### AI Backend / Backend Developer

AI 분석 결과를 실제 서비스 기능으로 연결하고, 운영 가능한 구조로 만드는 개발자입니다.

**1년 6개월 실무 경험 · 공공 AI 민원 분석 서비스 · On-Premise · KCI 제1저자 논문**

[Portfolio — gwangwon.dev](https://gwangwon.dev) · [Publication](https://doi.org/10.13067/JKIECS.2025.20.3.651)

## Experience

공공 AI 민원 분석 서비스 **민원e**에서 Python/FastAPI 기반 백엔드 개발을 경험했습니다.

- 유사 민원을 주제별로 사전 그룹화한 뒤 1024차원 임베딩과 DBSCAN으로 군집화하고, 대표 문서·Noise 처리와 일/주/월/연 스냅샷을 구현했습니다.
- 권한 Scope 기반 데이터 접근 제어, 주간 리포트 집계와 LLM 입력 구조, 챗봇 세션·메시지 API, 민원 필터링 preset을 담당했습니다.
- PostgreSQL, OpenSearch, Redis를 사용하는 백엔드와 온프레미스 환경 운영·장애 대응을 경험했습니다.

회사 코드는 공개하지 않습니다. 담당 범위와 기술 선택은 [포트폴리오의 민원e 사례](https://gwangwon.dev)에서 설명합니다.

## Selected Projects

| 프로젝트 | 문제와 구현 범위 | 현재 상태 |
| --- | --- | --- |
| [portfolio-blog](https://github.com/jokwangwon/portfolio-blog) | 포트폴리오와 기술 기록을 직접 운영합니다. Spring Boot·PostgreSQL API, Next.js 화면, 글 공개 범위·이미지 첨부·편집 충돌 처리와 배포 검증을 연결했습니다. | **Production / Deployed** — [서비스](https://gwangwon.dev) |
| [honcheon-server](https://github.com/jokwangwon/honcheon-server) | Minecraft 기반 무협 RPG 오픈월드 프로젝트입니다. 게임 규칙·세계 상태·저장 계층을 개발하고, AI-assisted world generation 결과를 인게임 검토와 자동화 도구로 반복 확인합니다. 전체 월드는 개발 중입니다. | **Active Development** |
| [AI_development_tool](https://github.com/jokwangwon/AI_development_tool) | AI가 생성한 코드를 검증 가능한 개발 프로세스 안에 넣는 도구입니다. 작업 승인·실행 기록·결과 검토와 테스트를 연결하며, 구현 범위와 실행 환경의 한계를 구분합니다. | **Experimental** |
| [Alert-log-project](https://github.com/jokwangwon/Alert-log-project) | Oracle 운영 로그 분석 프로젝트입니다. alert log를 파싱하고 규칙 사전으로 이벤트를 분류합니다. 로그에서 확인할 수 있는 사실과 알 수 없는 사실을 구분합니다. | **Experimental** |
| [ora-ppt-gen](https://github.com/jokwangwon/ora-ppt-gen) | Oracle 학습 HTML을 슬라이드 스펙으로 추출하고 PPTX로 변환합니다. 문서 동기화·검증·미리보기를 연결한 자동화 프로젝트입니다. | **Experimental** |

각 저장소 README에서 구현 근거, 실행 조건, 테스트와 현재 한계를 확인할 수 있습니다.

## Working with AI

개인 프로젝트에서 **AI-assisted development**를 사용합니다. AI agent를 코드 생성과 반복 작업에 활용하고, 요구사항 정의·설계 판단·코드 리뷰·테스트·검증은 개발자의 책임으로 둡니다.
검증 방법은 프로젝트별 test, lint, CI, manual review로 구분해 기록합니다.

## Technical Focus

| 영역 | 설명 가능한 경험 |
| --- | --- |
| Backend | Python, FastAPI, PostgreSQL, Redis, OpenSearch |
| AI Integration | LLM 연동, Embedding 기반 군집화, 분석 결과의 API·집계 기능 연결 |
| Infra / Ops | Docker, Linux, On-Premise |
| Research | CNN, dlib, Computer Vision, Behavior Recognition |

## Publication

**행동 레이블링 데이터셋을 활용한 CNN 및 dlib 기반 어린이 행동 유형 분류 시스템**

- **KCI 등재 학술지 · 제1저자**
- 조광원, 김동현, 박승민 — 한국전자통신학회 논문지, 2025, 20(3), 651–656
- CNN / dlib / Computer Vision / Behavior Recognition
- [DOI: 10.13067/JKIECS.2025.20.3.651](https://doi.org/10.13067/JKIECS.2025.20.3.651) · [KCI 공식 기록](https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART003221222)
