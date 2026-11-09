## 정세환 · AI Engineer

RAG · Agent · MCP · Evaluation

LLM은 읽고 판단하고 코드는 계산하도록 나눈 뒤, 그 구성이 맞는지 평가셋으로 확인합니다.

### 프로젝트

| | 프로젝트 | 내 역할 | 결과 |
|---|---|---|---|
| 01 | [triPilot · 멀티에이전트 여행 기획·지속 관리 시스템](https://github.com/hwansj/tripilot-dining) | Dining 에이전트 설계·구현 — LLM은 조건 해석, 계산·조회는 MCP 도구(규칙 6·조회 3) | 검증 일정 40개 · 확인 항목 111개 × 3회 판정 정확도 98.5% (규칙 기반 79.3%) |
| 02 | [에코봇 분리배출 안내 RAG 챗봇](https://github.com/hwansj/SKN32-3rd-3Team) · [4차](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN32-4th-3Team) | 검색 파이프라인 구현 · 성능평가 | 평가셋 정답 오류 13건 교정 후 비교, 환각률이 가장 낮은 하이브리드 검색(6%) 채택, Recall@5 0.607 → 0.730 |
| 03 | 소형 LLM 미세조정 · 서빙 실습 | 교재 기반 개인 실습 — RunPod GPU에서 Qwen2.5-0.5B QLoRA SFT · DPO, FastAPI 서빙 | DPO 평가 점수의 길이 편향을 찾아 토큰당 평균 로그 확률로 수정 |
| 04 | [Research Agent DB 연동](https://github.com/hwansj/research_agent_fastapi_mysql) | 강의 실습 확장 — MySQL 보고서 저장 MCP 도구 · 'DB에 저장' 버튼 | 기존 도구 호출 엔드포인트를 재사용해 다른 기능의 호출 구조 유지 |

그 외: [Signal-T 통신사 이탈 예측](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN32-2nd-1Team) — 팀장 · EDA · 다음 통신사 예측 모델

### 여러 프로젝트에서 지켜 온 기준

- 1등 수치보다 서비스 목적에 맞는 기준으로 고릅니다. (환각률, macro F1, 닫힌 식당 허용 0건)
- 우연히 좋아 보이는 결과는 거릅니다. (평가 데이터 분리·고정, 정답 교정, 순서를 바꿔 다시 채점)

### 연락처

asdffog0@naver.com
