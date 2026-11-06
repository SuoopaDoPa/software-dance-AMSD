# 소프트웨어 댄스 (Software Dance)

> **AMSD** — AI-MCP-based Software Dance
>
> 용어 창시: **박정진 (Park JungJin)**, 2026년 11월 6일
> First coined by Park JungJin, November 6, 2026

---

## 왜 이 용어가 필요한가

대중의 AI 활용 인식은 두 갈래에 멈춰 있다. **바이브 코딩** — 개발자가 AI로 코드를 만드는 것. **사무 자동화** — 사무직이 AI로 메일·보고서·반복 업무를 줄이는 것. 그 사이에 거대한 공백이 있다: **전문 소프트웨어로 일하는 실무자들**이다. 설계자, 제조·품질 담당자, 영상 편집자, 건축가 — 이들의 업무는 코딩도 아니고 문서 작업도 아니다.

이들 중 상당수가 AI를 업무에 쓰고 싶어 하지만, 자기 일에 들어맞는 활용 모델이 없어서 시도 앞에서 주춤한다. AI가 자기 분야의 전문 소프트웨어를 직접 다룰 수 있다는 것, 그리고 여러 도구를 거쳐 결과물을 끝까지 끌고 갈 수 있다는 것 — 이 방식 자체를 모르기 때문이다.

소프트웨어 댄스는 그 공백을 메우기 위한 용어이며, 하는 일은 두 가지다. **새로운 길을 개척하는 행위에 정의를 주는 것**, 그리고 **시도를 주저하는 실무자에게 따라 할 수 있는 모델을 제시하는 것**. 이름이 생기면 그 행위는 논의할 수 있는 것이 되고, 모델이 생기면 따라 할 수 있는 것이 된다.

**Why this term exists.** Public understanding of applied AI has stalled at two models: *vibe coding* (developers making software with AI) and *office automation* (clerical work made faster). Between them lies a vast gap — practitioners who work through professional software: designers, manufacturing and QC engineers, video editors, architects. Many of them want to use AI at work but freeze at the attempt, because no usage model fits their job. Software Dance fills that gap by doing two things: it gives a *definition* to the act of pioneering a new path, and it hands hesitant practitioners a *model* they can follow. A name makes the act discussable; a model makes it repeatable.

## 정의

**소프트웨어 댄스(Software Dance)** 는 AI가 MCP(Model Context Protocol)를 통해 각 도메인에 전문화된 소프트웨어들을 넘나들며, 하나의 목표를 향해 작업물의 완성도를 높여가는 작업 방식이다.

모델링은 CAD로, 애니메이션은 3D 그래픽 도구로, 문서는 워드프로세서로 — 원래 여러 직업(도메인)의 사람들이 핸드오프하며 수행하던 작업을, 하나의 AI가 **맥락을 유지한 채** 전문 도구만 갈아타며 수행한다.

**Software Dance** is a way of working in which an AI, via MCP (Model Context Protocol), moves across domain-specialized software tools — CAD for modeling, 3D graphics tools for animation, word processors for documentation — carrying a single goal and full context, raising the quality of one deliverable through each tool. Work that used to be handed off between people of different professions is performed by one AI that keeps the context and only switches instruments.

## 성립 조건

소프트웨어 댄스는 다음 두 조건 위에서 성립한다.

1. **불균등한 숙련도의 사용자** — 사용자는 여러 전문 소프트웨어를 다룰 수 있으나, 자신의 전문 도메인 밖에서는 활용도가 떨어진다. AI는 이 숙련도 격차를 메우고, 사용자는 각 단계의 결과를 판단한다. 완전 초보는 AI의 작업을 검증할 수 없고, 전 분야 전문가는 애초에 AI가 필요 없다 — 춤추는 주체는 AI 단독이 아니라 **사용자-AI 쌍**이다.
2. **단일 맥락 안의 작업물** — 작업물과 그 맥락(치수, 설계 의도, 제약 조건)은 하나의 AI 세션과 사용자 사이에서 소실 없이 흐르며, 각 단계에서 해당 도메인의 전문 소프트웨어로 가공된다. 사람 간 핸드오프에서는 파일만 넘어가고 의도는 넘어가지 않지만, 소프트웨어 댄스에서는 의도가 살아 있는 채로 다음 도구에 도달한다.

**Preconditions.** Software Dance holds under two conditions: (1) a user with *uneven proficiency* — able to operate multiple professional tools, but far less fluent outside their own domain; the AI fills the proficiency gap while the user judges each stage's output, so the dancing subject is the user-AI pair, not the AI alone. (2) the *work-in-progress stays in a single context* — the deliverable and its context (dimensions, design intent, constraints) flow losslessly between one AI session and the user, processed at each stage by that domain's professional software; the intent that is lost in human-to-human handoffs arrives alive at the next tool.

## 왜 "댄스"인가

기존 용어들은 이 방식을 담지 못한다.

| 기존 용어 | 한계 |
|---|---|
| 파이프라인 (pipeline) | 일방향 직선. 되돌아가거나 순서를 바꾸는 유연함이 없다 |
| 오케스트레이션 (orchestration) | AI 에이전트끼리의 분업. 산출물의 품질 상한이 모델 능력에 묶인다 |
| 툴체인 (toolchain) | 개발 도구 중심의 기계적 연결 |
| 라운드트리핑 (round-tripping) | 두 도구 사이의 왕복에 한정 |

소프트웨어 댄스는 다르다. 필요하면 되돌아가고, 순서를 바꾸고, 각 도메인에서 수십 년 쌓인 **진짜 전문 도구의 엔진**을 빌린다. 파트너(도구)를 바꿔가며 추지만, 춤추는 주체와 음악(목표·맥락)은 하나로 이어진다. 그래서 춤이다.

핵심 차별점 세 가지:

1. **AI 안에 갇히지 않는다** — 멀티 에이전트 오케스트레이션은 LLM 여러 개의 역할 분담이지만, 소프트웨어 댄스는 CAD의 파라메트릭 커널, 렌더 엔진, 조판 엔진 같은 실제 전문 엔진을 사용한다.
2. **각 단계가 검증 가능하다** — 전문 소프트웨어의 산출물은 검증 가능한 포맷이다. STEP 파일의 지오메트리는 수학적으로 정의되고, 간섭 체크와 질량 계산이 도구 안에서 돌아간다. LLM이 텍스트로 생성하는 "대략 이런 형상"과는 신뢰 수준이 다르다.
3. **핸드오프 손실이 사라진다** — 사람 간 핸드오프마다 발생하던 의도 전달 손실과 대기 시간이, 한 AI가 맥락을 유지하므로 사라진다.

## 용어의 유래

처음에는 **툴댄스(Tool Dance)** 로 지으려 했다. 그러나 CNC 5축 가공 분야에서 공구가 틸팅·회전하며 움직이는 것을 이미 툴댄스라 부르고 있었다. 용어 충돌을 피하면서 오히려 더 정확한 이름에 도착했다 — 이 방식의 핵심은 범용 '툴'이 아니라 각 도메인의 전문 '소프트웨어'를 거친다는 것이기 때문이다.

## 약어: AMSD

**AMSD** = **A**I-**M**CP-based **S**oftware **D**ance

해시태그, 저장소명, 검색 키워드로 사용한다. 본문과 대화에서는 "소프트웨어 댄스"로 부른다.

## 실천 사례

창시자가 이 용어를 만들기 전부터 실제로 수행해 온 방식이다. 한 예로, 화장품 용기 리디자인 제안 한 건을 다음의 흐름으로 완결했다:

실측·3D 스캔 데이터 기반 AI 역설계 → Fusion 360 모델링 (MCP) → 레진 3D 프린터 출력으로 기구 검증 → AI로 설계치수 정형화 → STEP·CAD 도면 문서화 → 워킹 목업 제작 → 고객사 제안 → 특허 선행조사(KIPRIS·해외 특허/실용신안/디자인) → 특허 출원용 모델링·도면 제작

설계자, 시제품 기사, 문서 담당자, 특허 조사원 — 원래 네 사람의 일을, 하나의 AI와 전문 소프트웨어들로 한 흐름 안에서 수행했다.

## 댄스에서 안무로 — 자동화로의 이행

소프트웨어 댄스는 종착점이 아니라 **선행 단계**다.

처음 추는 춤은 즉흥이다. 순서를 바꾸고, 되돌아가고, 경로를 몸으로 탐색한다. 그러나 같은 춤을 반복하면 스텝이 정형화된다 — **안무(choreography)** 가 된다. 안무가 확정된 흐름은 더 이상 사용자가 매번 출 필요가 없으며, 고정된 자동화 워크플로우로 응고될 수 있다.

무엇을 자동화해야 하는지를 미리 아는 사람은 없다. 춤을 춰본 사람만이 안무를 쓸 수 있다. 소프트웨어 댄스는 **자동화할 흐름을 발견하는 과정 그 자체**이며, 기존 자동화 담론이 비워 두었던 "자동화 대상의 발견" 단계에 이름을 준다.

댄스는 자동화에 흡수되어 사라지지 않는다. 정형화된 흐름을 자동화에 넘겨주고, 사용자-AI 쌍은 다음 미탐색 문제로 옮겨간다. 댄스는 언제나 최전선의 활동이다.

경계도 분명하다. 모든 댄스가 안무가 되는 것은 아니다 — 반복되는 흐름만 자동화할 가치가 있고, 1회성 작업은 댄스로 완결된다.

**From dance to choreography.** Software Dance is not an endpoint but a precursor stage. The first dance is improvisation — reordering, backtracking, exploring the path. Repeated, the steps crystallize into choreography, and a settled choreography can harden into a fixed automated workflow. No one knows in advance what to automate; only those who have danced can write the choreography. Software Dance is thus the discovery process for automation itself — and it never disappears: it hands the settled flow to automation and moves on, with the user-AI pair, to the next unexplored problem. Not every dance becomes choreography — only recurring flows earn automation; one-off work completes as a dance.

## 라이선스

이 문서는 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.ko)을 따른다. 용어는 자유롭게 사용하되, 개념의 출처를 표기해 주기 바란다: **"소프트웨어 댄스(Software Dance), 박정진, 2026"**
