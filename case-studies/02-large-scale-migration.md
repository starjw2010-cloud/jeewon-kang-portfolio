# Case 02. Large-scale SaaS Migration

## Scope
- 7 Workspaces
- 198 Users
- 576 Channels in validation target
- 1,325,413 Messages
- 99.15% migration confirmed in sampled workspace
- 11,232 non-migrated records analyzed separately

## Work
- Migration strategy
- Export / Import
- Account merge
- Channel cleanup
- Weekend migration work
- Before/after validation
- Exception categorization

## Approach
Migration 완료 여부를 단순히 '작업 종료'로 판단하지 않고, 원본과 결과 데이터를 비교했습니다.

정상 이관된 데이터와 이관되지 않은 데이터를 분리하고, 잔여 건은 원인을 문서화했습니다.

## Lesson
Migration에서는 성공률만큼 **빠진 데이터가 무엇인지 설명할 수 있는 상태**가 중요합니다.
