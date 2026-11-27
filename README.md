# 기술 스택 학습 로드맵 · 4~5시간 커리큘럼

**6단계 17개 기술**을 기술별 **4~5시간**으로 끊어 학습하는 로드맵입니다. **1단계는 Python & LangChain 최우선**으로 페이지 맨 위·로드맵 표 1~2번·첫 단계 칩에 배치했습니다. 각 세부 항목을 체크하면 진도율이 브라우저(`localStorage`)에 자동 저장됩니다.

- 라이브 페이지: https://wendy-park.github.io/tech-study-roadmap/
- 총 54개 학습 항목 · 총 예상 학습시간 약 77시간 · 무료 강의·교재 링크 36개

## 구성

| 단계 | 기술 |
| --- | --- |
| **1단계. 🔥 최우선 핵심** | **Python 3.11.9 · LangChain** |
| 2단계. 개발 환경 & 형상관리 | Visual Studio Code · GitLab/GitLab Issue/Notion |
| 3단계. 백엔드 & API 명세 | FastAPI 0.115.12 + Uvicorn · Swagger 5.32.1 |
| 4단계. 데이터베이스 & 스토리지 | DBeaver & Azure Database for MySQL · Azure Blob Storage · Redis · Azure Cosmos DB |
| 5단계. 프론트엔드 & API 연동 | TypeScript 5.2.2 · React.ts 18.2.0 · Axios 1.10.0 |
| 6단계. 컨테이너 · 배포 · 보안 · 로그 | Linux 기반 컨테이너 이미지 · GitLab CI/CD · SonarQube · Azure Log Analytics |

## 1단계 상세 (Python & LangChain)

### Python 3.11.9 — 실무·LangChain·FastAPI 연계 중심 5개 항목

| 시간 | 항목 |
| --- | --- |
| 0.5h | `venv` 가상환경 생성·활성화 · `pip install` · `requirements.txt` 버전 고정(`pip freeze`) |
| 1h | `.env`에 API 키 분리 · `python-dotenv` + `os.getenv` 로드 · `.gitignore` 처리 |
| 1h | 리스트/딕셔너리 컴프리헨션 · `json` 파싱(`loads`/`dumps`) · 파일 입출력 · `requests`/`httpx` 외부 API 호출 |
| 1h | Type Hints(`list`, `dict`, `Optional`, `Union`) · 클래스 & Pydantic(`BaseModel`) 데이터 모델링 |
| 1~1.5h | `async`/`await` 비동기 처리 · `try-except` 예외 처리 · `logging` 기초 |

### LangChain — 신규 추가 4개 항목

| 시간 | 항목 |
| --- | --- |
| 1.5h | 핵심 컴포넌트 & LCEL(`\|` 파이프 체인) — `ChatOpenAI`, `PromptTemplate`/`ChatPromptTemplate`, `OutputParser` |
| 1.5h | RAG 기초 — Document Loader(PDF/텍스트) → Text Splitter(청킹) → Embedding → VectorStore(FAISS/Chroma) → Retriever 연결 |
| 1h | 대화 이력(Memory / `ChatMessageHistory`) · Structured Output(JSON 구조화 출력·Pydantic 파서) |
| 1h | Tool/Function Calling & Agent 맛보기 · FastAPI 엔드포인트로 LangChain 체인 서빙(`/invoke`, 스트리밍) |

## 기능

- **전체 진도 대시보드** — 전체 진도율, 완료 항목/기술 수, 남은 예상 시간 (17개 기술 기준 자동 계산)
- **단계별 필터·네비게이션** — 상단 칩으로 단계 이동 및 필터링, 단계별 진도율 표시
- **전체 로드맵 표** — 17개 기술의 버전·목표 시간·항목 수·진도를 한눈에
- **항목별 체크리스트** — 기술별 시간 배분과 핵심 학습 항목, 기술별 완료율 실시간 갱신
- **바로 듣는 무료 강의** — 17개 기술마다 2~3개의 무료 강의·교재(유튜브·인프런 무료·MS Learn 무료·무료 웹 교재)를 플랫폼 배지와 함께 카드 안에 링크(새 탭으로 열림)
- **진도 초기화** 버튼, PC·모바일 반응형

## 기술별 무료 강의 링크

각 기술 카드 하단의 **바로 듣는 무료 강의** 영역에서 바로 열 수 있습니다. 17개 기술에 총 36개 링크를 넣었습니다.

| 기술 | 플랫폼 |
| --- | --- |
| Python | 유튜브(나도코딩 기본편 6시간) · 무료 교재(점프 투 파이썬, 위키독스) · 무료 교재(스쿨오브웹 비동기 입문) |
| LangChain | 무료 교재(테디노트 랭체인 한국어 튜토리얼, 위키독스) · 유튜브(테디노트 RAG 파이프라인) · 유튜브(조코딩 랭체인 AI 웹서비스) |
| Visual Studio Code | 유튜브(생활코딩) · MS Learn 무료(7분 공식 자습서) |
| GitLab · Issue · Notion | 인프런 무료(지옥에서 온 Git) · 유튜브(GitLab 3시간) |
| FastAPI + Uvicorn | 무료 교재(FastAPI 베이스캠프) · 유튜브(PyCon KR FastAPI Deep dive) |
| Swagger | 유튜브(Springdoc OpenAPI) · 무료 교재(스웨거로 테스트하기) |
| DBeaver & Azure MySQL | 유튜브(DBeaver 공식) · MS Learn 무료(유연한 서버 기능) |
| Azure Blob Storage | MS Learn 무료(구성 모듈 · Python 빠른 시작) |
| Redis | 유튜브(우아한레디스 · 쉬운코드 NoSQL) |
| Azure Cosmos DB | MS Learn 무료(기본 사항 · Python 빠른 시작) |
| TypeScript | 유튜브(3시간 완성 기초 · 얄팍한 코딩사전) |
| React.ts | 유튜브(ZeroCho TV 기본 강좌) · 생활코딩 React 입문수업 |
| Axios | 유튜브(라매개발자 fetch/axios · Traversy Crash Course) |
| Linux 컨테이너 이미지 | 유튜브(드림코딩 도커 정리 · 생활코딩 Docker 입구) |
| GitLab CI/CD | 유튜브(GitLab 공식 · freeCodeCamp 풀코스) |
| SonarQube | 유튜브(설치·스캔 실습 · 커버리지/품질 게이트) |
| Azure Log Analytics | MS Learn 무료(Log Analytics 자습서 · KQL 첫 쿼리) |

링크는 모두 무료로 볼 수 있는 강의·학습 자료이며, 인프런은 무료 표시가 확인된 강의만 넣었습니다. 새로 추가한 Python·LangChain 링크는 YouTube oEmbed 응답(제목·채널)과 페이지 본문 확인으로 실제 존재·무료 여부를 검증했습니다:

- 점프 투 파이썬 — 위키독스, 저자 박응용, 전 챕터 무료 공개(되새김 문제·코딩 면허 시험만 유료 e-book)
- 비동기 입문 (asyncio) — 스쿨오브웹 '모던 파이썬' 무료 웹 교재
- 테디노트 `<랭체인LangChain 노트>` — 위키독스 무료 전자책 (CC BY-NC-ND 2.0 KR)
- 테디노트 `#langchain 의 #RAG 파이프라인 이해해보기` — YouTube oEmbed 확인 (테디노트 TeddyNote)
- 조코딩 `랭체인으로 수익형 AI 웹서비스 만들기 with ChatGPT, LLaMA 2, RAG` — YouTube oEmbed 확인 (조코딩 JoCoding)

한국어 강의가 없는 항목(Azure 특화·SonarQube·GitLab·DBeaver 등)은 공식 영문 영상이나 MS Learn 한국어 모듈로 대체했습니다.

## 진도 저장 방식

- 저장 키: `tech-study-roadmap:v2` (기술이 17개로 늘고 Python 항목이 5개로 바뀌어 새 키를 사용)
- 이전 버전(`tech-study-roadmap:v1`)에 체크한 기록은 첫 방문 때 자동으로 승계됩니다. 항목 구성이 바뀐 Python만 제외하고 나머지 15개 기술의 체크는 그대로 유지됩니다.
- 진도 초기화를 누르면 v1·v2 기록을 함께 지웁니다.

## 사용

`index.html` 하나로 동작합니다. 저장소를 클론한 뒤 파일을 브라우저로 열거나, 위 라이브 페이지를 사용하세요. 진도는 브라우저마다 따로 저장되며 서버로 전송되지 않습니다.
