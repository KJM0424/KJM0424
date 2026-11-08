<img src="https://capsule-render.vercel.app/api?type=waving&color=0:176B5B,100:2F8F7A&height=190&section=header&text=Jaemin%20Kim&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=AI%20%EA%B8%B0%EB%8A%A5%EC%9D%84%20%EC%84%9C%EB%B9%84%EC%8A%A4%EC%97%90%20%EB%B6%99%EC%9D%B4%EB%8A%94%20%EB%B0%B1%EC%97%94%EB%93%9C%C2%B7AI%20%EA%B0%9C%EB%B0%9C%EC%9E%90&descSize=18&descAlignY=60" width="100%" alt="Jaemin Kim" />

<p align="center">
  <a href="mailto:woals424@naver.com"><img src="https://img.shields.io/badge/woals424%40naver.com-176B5B?style=flat-square&logo=gmail&logoColor=white" alt="email"></a>
  <img src="https://img.shields.io/badge/Backend%20%2F%20AI%20Application-2F8F7A?style=flat-square" alt="role">
  <img src="https://img.shields.io/badge/SK%20AX%20SKALA%202%EA%B8%B0%20%EC%88%98%EB%A3%8C-555555?style=flat-square" alt="skala">
</p>

## 소개

Python과 FastAPI로 AI 분석 서버를 만들고 Spring Boot 업무 서버와 비동기로 잇는 일을 해 봤습니다. LangGraph로 멀티에이전트 파이프라인을, PyTorch로 그래프 신경망 모델을 만들었고, Docker와 AWS로 배포까지 해 봤습니다. SK AX의 5개월 AI 개발자 과정(SKALA 2기, 908시간)을 수료했고, 인하대학교 정보통신공학과를 졸업했습니다.

## 주요 프로젝트

<table>
  <tr>
    <th width="34%">프로젝트</th>
    <th>내용과 내 역할</th>
    <th width="22%">기술</th>
  </tr>
  <tr>
    <td>
      <b><a href="https://github.com/KJM0424/crewvoice-ai-server">CrewVoice</a></b><br>
      승무원 기내방송 AI 평가 서비스<br>
      <sub>2025.11 – 12 · 6인 팀 · SK AX 과정 최종 · 현업 연계</sub>
    </td>
    <td>
      기내방송 음성을 발음·억양·강세·멈춤·톤·속도 6개 지표로 채점하고 GPT 피드백을 주는 서비스.<br>
      <b>백엔드 2명 중 1명.</b> FastAPI 분석 서버의 API와 비동기 분석 흐름(즉시 응답 → 분석 → 콜백, 실패와 시간초과도 콜백), 멈춤(Pause) 분석 모듈, 표준 음성 32트랙 baseline 생성기, 분석 서버 배포. Spring Boot 비동기 연동 참여.
    </td>
    <td>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">
      <img src="https://img.shields.io/badge/Azure%20Speech-0078D4?style=flat-square&logo=microsoftazure&logoColor=white">
      <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white">
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
      <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white">
    </td>
  </tr>
  <tr>
    <td>
      <b><a href="https://github.com/KJM0424/gcn-lstm-log-anomaly-detection">GCN-LSTM 로그 이상탐지</a></b><br>
      분산 시스템 로그에서 장애 징후 탐지<br>
      <sub>2024.09 – 12 · 3인 졸업프로젝트</sub>
    </td>
    <td>
      HDFS 로그 블록을 그래프(이벤트 노드, 전이 엣지)로 바꿔 GCN 노드 임베딩을 순서대로 LSTM에 넣는 2단계 모델. 공개 데이터셋 약 57만 블록.<br>
      <b>모델 설계·실험·평가 공동 수행</b>, 논문의 데이터·모델·대응 장 집필, 주제발표 시스템 설계 파트.
    </td>
    <td>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white">
      <img src="https://img.shields.io/badge/PyTorch%20Geometric-3C2179?style=flat-square">
      <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white">
    </td>
  </tr>
  <tr>
    <td>
      <b><a href="https://github.com/KJM0424/regtech-agent">RegTech Agent</a></b><br>
      중소기업 규제 분석 멀티에이전트<br>
      <sub>2025.10 · 팀 미니프로젝트 · 3일 MVP</sub>
    </td>
    <td>
      사업 정보를 넣으면 적용 규제, 체크리스트, 리스크 평가를 출처와 함께 PDF 보고서로 만들어 메일로 보내는 LangGraph 9노드 파이프라인.<br>
      <b>첫 버전의 모듈 분리와 병렬 분기 실험</b>, 법령 PDF 벡터 검색 실험.
    </td>
    <td>
      <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white">
      <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white">
      <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white">
    </td>
  </tr>
</table>

<details>
<summary><b>그 외 프로젝트와 과제</b></summary>
<br>

| 저장소 | 내용 | 시기 |
|---|---|---|
| [agentic-rag-startup-evaluator](https://github.com/Nangmanful/agentic-rag-startup-evaluator) | AI 스타트업 투자 평가 멀티에이전트. 5인 팀 실습, **시장성 평가 에이전트 담당**(FAISS 검색, 질문 재작성, 웹 검색 보충) | 2025.10 |
| [travel-bill-wanted1](https://github.com/KJM0424/travel-bill-wanted1) | 여행 영수증을 AI로 읽어 사람별 송금액을 계산하는 Streamlit 앱. 캠프 과제, 배포 | 2026.11 |
| [fastapi-auth-api](https://github.com/KJM0424/fastapi-auth-api) | FastAPI 회원가입·로그인·JWT 재발급 API. 캠프 과제 | 2026.10 |
| [interview-coach](https://github.com/KJM0424/interview-coach) | 내 자료와 공고로 질문을 만들고 평가위원 4명이 채점하는 모의 면접 앱. 캠프 과제 | 2026.10 |
| [prompt](https://github.com/KJM0424/prompt) · [my-service](https://github.com/KJM0424/my-service) · [wanted_7](https://github.com/KJM0424/wanted_7) | 프롬프트 생성기, 공공 API 출근길 도우미, 팀 실습 홈페이지. 캠프 과제 | 2026.10 |
| [jaemin-marketplace](https://github.com/KJM0424/jaemin-marketplace) | Claude Code 작업 규칙 플러그인(코드 규칙, 문서 규칙, AI 활용 기록) | 2026.10 |

</details>

## 기술 스택

<table>
  <tr>
    <td><b>주력</b><br><sub>프로젝트에서 구현</sub></td>
    <td>
      <img src="https://skillicons.dev/icons?i=python,fastapi,pytorch,docker,aws,nginx,git&theme=light" alt="주력" height="40"><br>
      <sub>Python · FastAPI · Pydantic · LangChain · LangGraph · OpenAI API · Azure Speech · PyTorch · PyTorch Geometric · FAISS · Docker · nginx · AWS EC2/S3</sub>
    </td>
  </tr>
  <tr>
    <td><b>협업</b><br><sub>팀 프로젝트에서 함께 사용</sub></td>
    <td>
      <img src="https://skillicons.dev/icons?i=java,spring,postgres,githubactions,react&theme=light" alt="협업" height="40"><br>
      <sub>Java · Spring Boot 3 · JPA · PostgreSQL · GitHub Actions · GHCR · React</sub>
    </td>
  </tr>
  <tr>
    <td><b>실습</b><br><sub>과정에서 다룸</sub></td>
    <td>
      <img src="https://skillicons.dev/icons?i=kubernetes,jenkins,vue,mysql,sklearn&theme=light" alt="실습" height="40"><br>
      <sub>Kubernetes · Jenkins · ArgoCD · MLflow · Vue.js · pgvector · scikit-learn · XGBoost</sub>
    </td>
  </tr>
</table>

## 교육 · 활동 · 수상

| 시기 | 내용 |
|---|---|
| 2025.07 – 12 | **SK AX SKALA 2기 수료** (908시간). Spring Boot·FastAPI 백엔드, LangChain·LangGraph·RAG, Docker·클라우드 배포, 팀 프로젝트 3건 |
| 2024.08 – 2025.06 | **인하대학교 암호연구실 학부연구생**. BGV 동형암호 논문을 읽고 암호화 스킴과 modulus switching을 구현해 랩미팅 발표 |
| 2023.10 | **GBIC 블록체인 해커톤 2023 최우수상** (8팀 중). 커피박 수거 보상 플랫폼, 4인 팀 |
| 2023.12 | **프로보노 ICT 공모전 동상**. 고령 보행자 횡단보도 안전 시스템, 8개월, 임베디드 통신 코드 |
| 2023 | **정보통신공학과 학생회장 · 공과대학 학생회장 권한대행**. 총회·예산·정기감사 완료, 16개 학과 축구 리그 운영 |
| 2019 – 2026 | **인하대학교 정보통신공학과 졸업** (2026.02) |

## 일하는 방식

- 팀 프로젝트는 내 몫과 팀원 몫을 README에 나눠 적습니다.
- 코드를 빨리 만드는 일은 AI 도구에 맡기고, 무엇이 맞는 결과인지는 직접 정하고 확인합니다.
- 수치에는 측정 조건을 붙입니다.

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KJM0424&layout=compact&hide=html,css,jupyter%20notebook&langs_count=6&theme=default&hide_border=true&title_color=176B5B&text_color=333333" alt="Top languages" height="150">
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2F8F7A,100:176B5B&height=90&section=footer" width="100%" alt="">
