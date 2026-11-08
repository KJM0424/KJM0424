<img src="https://capsule-render.vercel.app/api?type=waving&color=0:176B5B,100:2F8F7A&height=190&section=header&text=Jaemin%20Kim&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=AI%20%EA%B8%B0%EB%8A%A5%EC%9D%84%20%EC%84%9C%EB%B9%84%EC%8A%A4%EC%97%90%20%EB%B6%99%EC%9D%B4%EB%8A%94%20%EB%B0%B1%EC%97%94%EB%93%9C%C2%B7AI%20%EA%B0%9C%EB%B0%9C%EC%9E%90&descSize=18&descAlignY=60" width="100%" alt="Jaemin Kim" />

<p align="center">
  <a href="mailto:woals424@naver.com"><img src="https://img.shields.io/badge/woals424%40naver.com-176B5B?style=flat-square&logo=gmail&logoColor=white" alt="email"></a>
  <img src="https://img.shields.io/badge/Backend%20%2F%20AI%20Application-2F8F7A?style=flat-square" alt="role">
  <img src="https://img.shields.io/badge/SK%20AX%20SKALA%202%EA%B8%B0%20%EC%88%98%EB%A3%8C-555555?style=flat-square" alt="skala">
</p>

FastAPI로 AI 분석 서버를 만들고 Spring Boot 업무 서버와 비동기로 잇습니다. LangGraph 에이전트와 PyTorch 모델을 만들어 Docker와 AWS로 배포해 봤습니다. SK AX AI 개발자 과정(SKALA 2기, 908시간) 수료, 인하대학교 정보통신공학과 졸업.

## 주요 프로젝트

<table>
  <tr>
    <th width="26%">프로젝트</th>
    <th width="38%">무엇</th>
    <th>내 역할</th>
  </tr>
  <tr>
    <td>
      <b><a href="https://github.com/KJM0424/crewvoice-ai-server">CrewVoice</a></b><br>
      <sub>2025.11–12 · 6인 팀 · 현업 연계</sub><br>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">
      <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white">
      <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white">
    </td>
    <td>승무원 기내방송 음성을 6개 지표로 채점하고 GPT 피드백을 주는 AI 평가 서비스</td>
    <td><b>AI 분석 서버(FastAPI)</b>: API, 즉시 응답 후 분석하고 콜백하는 비동기 흐름, 멈춤 분석 모듈, 배포. Spring Boot 연동 참여</td>
  </tr>
  <tr>
    <td>
      <b><a href="https://github.com/KJM0424/gcn-lstm-log-anomaly-detection">GCN-LSTM 로그 이상탐지</a></b><br>
      <sub>2024.09–12 · 3인 졸업프로젝트</sub><br>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white">
      <img src="https://img.shields.io/badge/PyG-3C2179?style=flat-square">
    </td>
    <td>HDFS 로그 블록을 그래프로 바꿔 GCN과 LSTM을 결합한 2단계 이상탐지 모델. 공개 데이터 약 57만 블록</td>
    <td><b>모델 설계·실험·평가 공동</b>, 논문의 데이터·모델 장 집필</td>
  </tr>
  <tr>
    <td>
      <b><a href="https://github.com/KJM0424/regtech-agent">RegTech Agent</a></b><br>
      <sub>2025.10 · 팀 · 3일 MVP</sub><br>
      <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white">
      <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white">
    </td>
    <td>사업 정보로 적용 규제·체크리스트·리스크 보고서를 출처와 함께 만들어 메일로 보내는 9노드 에이전트</td>
    <td><b>모듈 분리와 병렬 분기</b>, 법령 PDF 벡터 검색 실험</td>
  </tr>
</table>

<details>
<summary><b>그 외 프로젝트와 과제</b></summary>
<br>

| 저장소 | 한 줄 | 시기 |
|---|---|---|
| [agentic-rag-startup-evaluator](https://github.com/Nangmanful/agentic-rag-startup-evaluator) | AI 스타트업 투자 평가 에이전트(5인 실습). **시장성 평가 에이전트 담당**: FAISS 검색, 질문 재작성, 웹 검색 보충 | 2025.10 |
| [travel-bill-wanted1](https://github.com/KJM0424/travel-bill-wanted1) | 여행 영수증을 AI로 읽어 사람별 송금액 계산, Streamlit 배포 (캠프 과제) | 2026.11 |
| [fastapi-auth-api](https://github.com/KJM0424/fastapi-auth-api) | 회원가입·로그인·JWT 재발급 API, ADR과 pytest (캠프 과제) | 2026.10 |
| [interview-coach](https://github.com/KJM0424/interview-coach) | 내 자료로 질문을 만들고 평가위원 4명이 채점하는 모의 면접 앱 (캠프 과제) | 2026.10 |
| [prompt](https://github.com/KJM0424/prompt) · [my-service](https://github.com/KJM0424/my-service) · [wanted_7](https://github.com/KJM0424/wanted_7) | 프롬프트 생성기, 출근길 도우미, 팀 실습 홈페이지 (캠프 과제) | 2026.10 |
| [jaemin-marketplace](https://github.com/KJM0424/jaemin-marketplace) | Claude Code 작업 규칙 플러그인 | 2026.10 |

</details>

## 기술 스택

<table>
  <tr>
    <td width="12%"><b>주력</b></td>
    <td><img src="https://skillicons.dev/icons?i=python,fastapi,pytorch,docker,aws,nginx,git&theme=light" height="36" alt="주력"><br><sub>Python · FastAPI · LangChain · LangGraph · OpenAI API · Azure Speech · PyTorch · FAISS · Docker · AWS</sub></td>
  </tr>
  <tr>
    <td><b>협업</b></td>
    <td><img src="https://skillicons.dev/icons?i=java,spring,postgres,githubactions,react&theme=light" height="36" alt="협업"><br><sub>Java · Spring Boot · JPA · PostgreSQL · GitHub Actions · React</sub></td>
  </tr>
  <tr>
    <td><b>실습</b></td>
    <td><img src="https://skillicons.dev/icons?i=kubernetes,jenkins,vue,mysql,sklearn&theme=light" height="36" alt="실습"><br><sub>Kubernetes · Jenkins · ArgoCD · MLflow · Vue.js · pgvector · scikit-learn</sub></td>
  </tr>
</table>

## 교육 · 활동 · 수상

| 시기 | 내용 |
|---|---|
| 2025.07–12 | **SK AX SKALA 2기 수료** (908시간) · 백엔드, LangChain·RAG, 클라우드 배포, 팀 프로젝트 3건 |
| 2024.08–2025.06 | **인하대 암호연구실 학부연구생** · BGV 동형암호 스킴과 modulus switching 구현, 랩미팅 발표 |
| 2023.10 | **GBIC 블록체인 해커톤 최우수상** (8팀 중) · 커피박 수거 보상 플랫폼 |
| 2023.12 | **프로보노 ICT 공모전 동상** · 고령 보행자 횡단보도 안전 시스템, 8개월 |
| 2023 | **정보통신공학과 학생회장 · 공과대학 학생회장 권한대행** · 총회·예산·감사, 16개 학과 축구 리그 |
| 2026.02 | **인하대학교 정보통신공학과 졸업** |

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2F8F7A,100:176B5B&height=90&section=footer" width="100%" alt="">
