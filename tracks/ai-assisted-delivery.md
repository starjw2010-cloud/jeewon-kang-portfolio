# AI-assisted Delivery

## Position

AI Coding Agent를 활용해 문제정의부터 구현 요청, 결과 검토와 다음 단계 판단까지 연결합니다.

제가 설명할 수 있는 역할은 다음과 같습니다.

- 문제와 요구사항 정의
- 작업 범위와 수용 기준 작성
- AI에게 작업 분해·수정 요청
- Repository 변경 반영
- 결과와 한계 확인
- Demo / Sandbox / Production 상태 구분

## Tools

- ChatGPT
- Claude
- Claude Code
- Codex

## Exposure

- Python / FastAPI
- Next.js / TypeScript
- Slack Bolt
- PostgreSQL / SQLite
- DuckDB / Parquet
- MCP
- RAG / Retrieval
- GitHub Actions
- Railway configuration

## Why This Matters

AI-assisted 개발의 장점은 구현 속도입니다. 반대로 코드가 빨리 만들어지는 만큼 사람이 요구사항, 테스트, 보안, 배포 범위를 더 명확히 관리해야 합니다.

따라서 다음을 분리합니다.

```text
What I asked for
What AI generated
What was tested
What was merged
What is still unverified
```

## Representative Case — GS AI Apps

시장·경쟁사와 고객 정보를 다루는 업무를 정하고 외부 API 수집, AI 분석, Slack 문서·알림으로 이어지는 프로토타입을 제작했습니다. 경쟁사 뉴스, 고객 VOC, 날씨 운영 시사점과 에너지 정보의 사용 흐름을 각각 구성했습니다.

자료 조사와 요구사항 정리에는 ChatGPT·Claude를 활용하고 앱 제작에는 AI 코딩 도구를 사용했습니다. 서비스 내부의 분석 모델과 기획·개발에 쓴 도구를 구분해 [GS 앱 상세 사례](../case-studies/14-gs-ai-intelligence-prototypes.md)에 정리했습니다. 완성된 프로토타입과 후속 기업 시스템 연동 설계의 범위도 함께 표시했습니다.

## Representative Case — SemiFlow

합성 제조 데이터 기반 운영 관제 프로젝트에서 사용자별 업무 질문, 데이터·권한 범위와 수용 기준을 정리했습니다. 기능 구현을 독립 검토·자동검증·변경 통합·실행 환경 확인으로 연결하는 관리 방식을 적용합니다.

[제품 판단과 AI Delivery 상세 사례](../public-projects/semiflow-deep-dive.md)에서 업무 문제, 근거 검색·답변 검증과 운영 전환 기준을 설명합니다. 본인 역할과 AI-assisted 코드 구현의 구분은 [근거 기준](../EVIDENCE.md)을 따릅니다.
