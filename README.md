## 정세환 · AI Engineer

RAG · Agent · MCP · Evaluation

LLM은 읽고 판단하고 코드는 계산하도록 나눈 뒤, 그 구성이 맞는지 평가셋으로 확인합니다.

### 대표 프로젝트

| 프로젝트 | 내 역할 | 결과 |
|---|---|---|
| [triPilot 요식(Dining) 파트](https://github.com/hwansj/tripilot-dining) | 식당 판정 에이전트 설계·구현 — LLM은 조건 해석, 계산은 MCP 규칙 도구 | 검증용 333회 판정 정확도 98.5% (규칙만 79.3%) |
| [에코봇](https://github.com/hwansj/SKN32-3rd-3Team) · [4차](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN32-4th-3Team) | 분리배출 안내 RAG 챗봇의 검색 파이프라인·성능평가 | 통과율 1위 대신 환각률이 가장 낮은 하이브리드 검색(6%) 채택, R@5 0.607 → 0.730 |
| [Signal-T](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN32-2nd-1Team) | 팀장 · EDA · 다음 통신사 예측 모델 | 정확도 1위 대신 세 통신사를 고르게 맞히는 모델(macro F1) 선택, 강사 평가 95/100 |
| [Research Agent](https://github.com/hwansj/research_agent_fastapi_mysql) | 강의 실습 프로젝트에 MySQL 보고서 저장 도구 추가 | 기존 도구 호출 구조를 바꾸지 않고 MCP 도구로 연동 |

### 여러 프로젝트에서 지켜 온 기준

- 1등 수치보다 서비스 목적에 맞는 기준으로 고릅니다. (환각률, macro F1, 닫힌 식당 허용 0건)
- 우연히 좋아 보이는 결과는 거릅니다. (평가 데이터 분리·고정, 정답 교정, 순서를 바꿔 다시 채점)

### 연락처

asdffog0@naver.com
