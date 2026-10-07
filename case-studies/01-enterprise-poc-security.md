# Case 01. Enterprise PoC — Security & Permission

**고객:** 대기업 · **기간:** 2026 · **상태:** PoC 수행, 계약 전환 및 최종 권한 재설계는 별도 확인 대상

## Situation
분산된 영업 자료와 보고 흐름을 Slack·Salesforce 기반으로 연결하는 PoC에서 현업 시나리오, SSO, 사용자 권한과 CRM 연동을 검토했습니다.

## My Role
현업·IT·보안 요구사항, Entra ID SSO와 Sales Elevate 검토를 조율했습니다. 보안 RFI 5개 영역을 정리하고 임원을 포함한 15명 대상 현장 데모와 Slackbot 업무 스킬 5종 기획을 담당했습니다.

## Issue
특정 기능이 여러 조직이 함께 사용하는 시스템에 데이터를 기록할 수 있는 권한 범위를 가진 상태를 확인했습니다.

## Action
1. 위험 가능성이 있는 기능을 우선 중단
2. 보안 담당자에게 상황 공유
3. Permission Set과 사용자 권한 확인
4. 원인 범위 축소
5. 관리자 작업이 필요한 부분을 후속 과제로 분리

## Result
PoC를 중단하지 않으면서 위험 기능의 사용을 제한하고 후속 조치 범위를 명확히 했습니다.

## Lesson
기능이 동작하는지보다 먼저, 어떤 계정이 어떤 데이터에 읽기·쓰기 권한을 갖는지 확인해야 합니다.

[같은 PoC의 사용·성과 점검](11-ai-adoption-review.md) · [Customer Success 트랙](../tracks/enterprise-customer-success.md) · [전체 포트폴리오](../README.md)
