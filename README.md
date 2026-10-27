# 제주 스마트 버스 — Codex 새 개발

확정 PRD에서 새로 개발하기 위한 문서 저장소입니다. 현재 앱 코드·의존성·Vercel 연결은 없습니다. 기존 S4han/jeju-smart-bus와 운영 배포는 보존합니다.

- [PRD](docs/제주_스마트_버스_PRD_v1.0.md)
- [개발 규칙](AGENTS.md)
- [단계별 계획과 FR/AC 추적표](IMPLEMENTATION_PLAN.md)
- [첫 작업](tasks/TASK-001.md)
- [검증 기록 규칙](docs/verification/README.md)

MVP: FR-001~018, FR-020. FR-019는 후속 버전. 월 외부 과금 0원·개인정보 보호·API 실호출 검증은 필수이며 현재 모든 게이트는 미검증입니다.

## Codex 시작 프롬프트

이 저장소의 AGENTS.md, docs/제주_스마트_버스_PRD_v1.0.md, IMPLEMENTATION_PLAN.md를 읽고 tasks/TASK-001.md만 수행하세요. PRD를 변경하지 말고 개인정보 PRIV-001~004, 월 0원 비용 및 GATE-06, API 실호출 계획을 먼저 문서화하세요. 이번 작업은 문서 조사·설계만 수행하며 앱 코드·의존성·배포를 만들거나 외부 버스 API를 호출하지 마세요. 사용자 확정·AI 제안·미결정을 구분하고 필요한 결정만 묶어 제시하세요. 기존 S4han/jeju-smart-bus와 Vercel은 변경하지 마세요. 결과·검증 상태·보류 사항을 보고하고 TASK-002로 자동 진행하지 마세요.
