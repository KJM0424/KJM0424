# 김재민 · Jaemin Kim

AI 기능을 서비스에 붙이고, 내가 만든 측정이 맞는지 다시 잽니다.
백엔드·AI 애플리케이션 개발자. Python · FastAPI · LangGraph 주력, Spring Boot 협업 경험.

## 먼저 봐 주실 저장소 3개

| 저장소 | 무엇 | 내 역할 | 확인할 수 있는 것 |
|---|---|---|---|
| [crewvoice-ai-server](https://github.com/KJM0424/crewvoice-ai-server) | 승무원 기내방송을 6개 지표로 채점하는 AI 평가 서버. 6인 팀, 7주, 2025.11–12, 현업 담당자 연계 | 백엔드 2명 중 1명. FastAPI API와 비동기 분석 흐름, 멈춤(Pause) 분석 모듈, 분석 서버 배포. Spring Boot 비동기 연동 참여 | Spring Boot 요청에 즉시 응답하고 분석 뒤 콜백하는 흐름(`app/apis/router_springboot.py`), 표준 음성 baseline 생성기, 멈춤 분석 모듈. 알려진 문제와 수정 계획은 README에 정리 중 |
| [gcn-lstm-log-anomaly-detection](https://github.com/KJM0424/gcn-lstm-log-anomaly-detection) | HDFS 로그 블록을 그래프로 바꿔 GCN과 LSTM을 결합한 이상탐지. 3인 졸업프로젝트, 2024.09–12 | 모델 설계·실험·평가 공동 수행, 논문의 데이터·모델·대응 장 집필 | 로그를 그래프로 만드는 방법, GCN 임베딩을 LSTM에 넣는 2단계 학습 노트북. 보고했던 지표는 분할 문제로 재평가 중 |
| [regtech-agent](https://github.com/KJM0424/regtech-agent) | 중소기업 규제 분석 LangGraph 9노드 파이프라인. 팀 미니프로젝트, 3일, 2025.10 | 팀원 첫 버전의 모듈 분리와 병렬 분기 실험, 법령 PDF 벡터 검색 실험 | 9노드 구조와 검색 출처를 보고서까지 전달하는 흐름. 개인 재구현(v2) 예정 |

## 일하는 방식

- 역할 경계를 먼저 씁니다. 팀 프로젝트는 내 몫과 팀원 몫을 README에 나눠 적습니다.
- 코드를 빨리 만드는 일은 AI 도구에 맡기고, 무엇이 맞는 결과인지는 내가 정합니다. 틀린 답과 맞는 답 양쪽으로 확인합니다.
- 수치에는 측정 조건을 붙입니다. 측정하지 않은 수치는 쓰지 않습니다.

## 그 외 저장소

- 캠프 과제(AI 코딩 도구 주도로 제작): travel-bill-wanted1, fastapi-auth-api, interview-coach, prompt, my-service, wanted_7
- Claude Code 작업 규칙 플러그인: jaemin-marketplace

## 연락

woals424@naver.com
