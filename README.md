# 김상준 · Backend Developer

장애를 재현하고 계측해 원인까지 추적하고, 그 과정을 문서로 남기는 백엔드 개발자입니다.
명지대학교 융합소프트웨어학부 응용소프트웨어학과 (2027. 02 졸업예정).

**주력**: Java · Spring Boot · PostgreSQL · Redis · Python(FastAPI) · gRPC

## 대표 프로젝트

- **[planMate](https://www.planmate.site)** — 여러 사람이 동시에 편집하는 실시간 협업 여행 플래너 웹사이트 (4인 팀, PM · 백엔드). 2026 관광데이터 활용 공모전 제출
  - **메인 서버([Backend-v2](https://github.com/cow-planmate/Backend-v2))** — DB 스키마·엔티티·JWT 인증 설계, 소셜 로그인·일정·협업 권한·체크리스트 API 구현 (커밋 131/195, 테스트 메서드 713/786, DB 마이그레이션 14/18)
  - **AI 일정 챗봇 서버([planmate-ai](https://github.com/cow-planmate/planmate-ai))** — FastAPI + Gemini로 8개 유형 43개 시나리오에 답하는 챗봇 구현, 대화 결과를 실제 일정에 반영하는 기능 연동 (커밋 27/32)
  - **성능·구조 개선** — 외부 API 호출 한도 초과 원인을 계측으로 찾아 AI 일정 생성 21~55초 → 17~23초, 길찾기 결과 DB 캐싱으로 279ms → 28ms, 메인 서버 지역 도메인·DB 변경을 AI 서버가 재배포 없이 반영하도록 gRPC 동기화
  - **운영 모니터링 대시보드([planmate-monitor](https://github.com/cow-planmate/planmate-monitor))** — Go · React로 응답시간·에러율·JVM 메모리·GC 지표를 보는 API 11개·화면 4개 (1인 개발)
- **[SharedSync](https://github.com/Shared-Sync/SharedSync)** — 팀 실시간 동기화 프레임워크에 PR 5건 머지. "지운 일정이 다시 나타난다"는 보고를 서버 2대 재현으로 추적해 동기화 버그 16건을 수정하고, 여러 연산을 한 번에 되돌리는 Undo 기능 추가

📧 tedtidsjsj@gmail.com
