# Public Projects

공개 코드와 공개 가능한 프로젝트 설명을 정리합니다. 고객 기밀과 비공개 업무 산출물은 포함하지 않습니다.

| Project | 목적 | 공개 범위 / 상태 |
|---|---|---|
| [CampusCase Desk MCP](#campuscase-desk-mcp) | 대학 업무 맥락을 검색하고 조회하는 MCP Demo | 공개 Repository / Synthetic Demo·PoC |
| [SemiFlow](#semiflow--operations-control-tower) | 제조 운영 위험을 근거와 함께 조사하고 보고하는 AI Sandbox | 공개 사례 설명 / 비공개 코드·개인 R&D |

## CampusCase Desk MCP

대학 업무 케이스, 태스크, 승인, 문서 맥락을 조회하는 **synthetic demo MCP server**입니다.

### Includes
- MCP tool interface
- keyword retrieval
- local TF-IDF/cosine retrieval
- RRF hybrid retrieval
- optional MariaDB backend
- integrity / smoke verification scripts

Repository:  
https://github.com/starjw2010-cloud/campuscasedesk-slack

**Status:** Synthetic Demo / PoC — 실제 대학 Production 시스템이 아닙니다.

---

## SemiFlow — Operations Control Tower

합성 제조사의 주문·생산·자재·출하 정보를 연결해 납기 위험을 조사하고, 근거를 보존한 AI 설명과 임원 보고서로 연결하는 **AI-assisted Sandbox**입니다.

### Includes
- 재현 가능한 규칙에 따른 운영 위험 계산
- 조직·주문 범위가 제한된 근거 검색과 읽기 전용 AI 조사
- 확인된 사실·AI 해석·미확인 정보의 구분
- 한국어 Web, 후속 질문, 임원 보고서 미리보기와 PDF 인쇄
- 인증·권한·감사 및 Backend·Web·데이터 통합 자동검증

문제정의, 수용 기준, 검증 범위와 운영 전 확인 과제를 중심으로 역할과 결과를 정리했습니다.

[Read Case Study](../case-studies/06-ai-assisted-control-tower.md)

**Status:** 개인 R&D / Synthetic Sandbox · 2026.10.07 점검 자료 기준. 코드는 비공개이며, 실제 고객의 유료 구축·운영 실적이나 측정된 업무 절감 효과를 뜻하지 않습니다. 현재 가동 상태와 상용 운영 준비도는 별도 확인 대상입니다.

---

## Other Work

다른 Prototype 상당수는 고객 대상 Demo 구조 또는 내부 업무 자산이 포함돼 있어 비공개로 유지하고 있습니다.

공개 Repo 수나 코드 양을 성과로 내세우기보다, 필요할 경우 면접에서 문제정의·아키텍처·검증 범위를 설명합니다.
