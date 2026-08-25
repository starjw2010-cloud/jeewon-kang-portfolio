# Case 06. AI-assisted Control Tower Sandbox

## Context
제조·운영 데이터를 다루는 AI Control Tower Sandbox입니다.

## Principle
LLM이 운영 데이터의 진실성을 결정하도록 하지 않고, deterministic data/evidence contract를 먼저 두는 방향을 검토했습니다.

## Repository Scope
- FastAPI
- Next.js
- PostgreSQL
- DuckDB
- Parquet
- Auth / RBAC / Audit
- GitHub Actions
- Test suite

## My Role
Codex task에서 요구사항·제약·수정 요청을 제시하고 AI-generated 변경을 owner Repository에 반영했습니다.

직접 수기 코딩 비율은 별도로 입증되지 않았으므로 직접 개발 프로젝트로 표현하지 않습니다.

## Lesson
AI-assisted 개발에서는 '얼마나 빨리 만들었는가'보다 **수용 기준, 검증 방법, 데이터 경계와 미구현 영역을 명확히 하는 것**이 중요했습니다.
