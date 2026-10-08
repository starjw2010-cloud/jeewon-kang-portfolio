# GS AI 앱 아키텍처 원본

2026-10-08 포트폴리오 작성자가 제공한 11개 PNG를 내용 변경 없이 보관했습니다. 저장소에서 연결하기 쉽도록 파일명만 영문으로 정리했습니다. 본문 설명은 [GS AI Intelligence Apps](../../case-studies/14-gs-ai-intelligence-prototypes.md)에 있습니다.

| 파일 | 담은 내용 | 읽는 범위 |
|---|---|---|
| [VOC 에이전트](voc-agent-demo.png) | 수집·분석·문서화 역할과 외부 API | 외부 API 기반 데모, 내부 시스템 연동은 향후 확장 |
| [VOC 서비스](voc-service-demo.png) | Slack·수집 일정·AI 추론·배포 구조 | 데모의 서비스 구성 |
| [Enterprise 확장](enterprise-extension-design.png) | 내부 시스템 연동·부서 배정·AI 모델 선택 | 후속 확장 설계 |
| [경쟁사 모니터링 에이전트](competitor-agent.png) | 뉴스 수집·경쟁사 구분·보고서 전달 | 뉴스 기반 프로토타입 |
| [경쟁사 모니터링 서비스](competitor-service.png) | 계열사별 경쟁사·뉴스 API·Slack 구성 | 원래 파일명의 ‘공시앱’과 달리 그림의 소스는 뉴스 API |
| [날씨 운영 서비스](weather-service.png) | 권역별 날씨·계열사 업무 검토·전달 | 운영 시사점 제안 구조 |
| [날씨 운영 에이전트](weather-agent.png) | 날씨에서 재고·판촉·수요·공정 검토로 이어지는 흐름 | 실측 예측 정확도나 운영 개선 수치를 뜻하지 않음 |
| [에너지 어시스턴트 에이전트](energy-assistant-agent.png) | 채널 맥락·Claude 분석·문서 생성 | 앱의 응답·보고 흐름 |
| [에너지 시장 인텔리전스](energy-market-agent.png) | 가격·환율·계열사 영향 검토 | 정보 수집·분석·보고 구조 |
| [에너지 어시스턴트 서비스](energy-assistant-service.png) | 질의응답·대화 맥락·Canvas 보고 | 앱의 서비스 구성 |
| [사업장 이동시간 조회](site-travel-agent.png) | 교통 API·경로·혼잡도·알림 | 조회·전달 앱 구성 |

그림은 프로젝트 설명 자료입니다. 도식에 적힌 정기 실행과 상시 운영 표현은 별도의 실운영 기록이나 가동률 검증을 대신하지 않습니다. 모델·공급사 표기는 자료 작성 당시의 구성 설명입니다.

[사례 본문](../../case-studies/14-gs-ai-intelligence-prototypes.md) · [포트폴리오](../../README.md)
