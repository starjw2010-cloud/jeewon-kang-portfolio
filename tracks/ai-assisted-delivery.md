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

## Representative Case — SemiFlow

합성 제조 데이터 기반 운영 관제 프로젝트에서 사용자별 업무 질문, 데이터·권한 범위와 수용 기준을 정리했습니다. 기능 구현을 독립 검토·자동검증·변경 통합·실행 환경 확인으로 연결하는 관리 방식을 적용합니다.

[제품 판단과 AI Delivery 상세 사례](../public-projects/semiflow-deep-dive.md)에서 업무 문제, 근거 검색·답변 검증과 운영 전환 기준을 설명합니다. 본인 역할과 AI-assisted 코드 구현의 구분은 [근거 기준](../EVIDENCE.md)을 따릅니다.
