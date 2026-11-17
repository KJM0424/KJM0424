<img src="https://capsule-render.vercel.app/api?type=waving&color=0:176B5B,100:2F8F7A&height=190&section=header&text=Jaemin%20Kim&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=LLM%20%EC%97%90%EC%9D%B4%EC%A0%84%ED%8A%B8%EC%99%80%20FastAPI%20%EC%84%9C%EB%B2%84%EB%A5%BC%20%EB%A7%8C%EB%93%9C%EB%8A%94%20AI%20%EC%97%94%EC%A7%80%EB%8B%88%EC%96%B4&descSize=18&descAlignY=60" width="100%" alt="Jaemin Kim" />

<p align="center">
  <a href="mailto:woals424@naver.com"><img src="https://img.shields.io/badge/woals424%40naver.com-176B5B?style=flat-square&logo=gmail&logoColor=white" alt="email"></a>
  <img src="https://img.shields.io/badge/AI%20Engineer-2F8F7A?style=flat-square" alt="role">
  <img src="https://img.shields.io/badge/SK%20AX%20SKALA%202%EA%B8%B0%20%EC%88%98%EB%A3%8C-555555?style=flat-square" alt="skala">
</p>

LangGraph로 검색 결과를 평가해 재검색하는 에이전트를 만들었고, FastAPI 분석 서버를 Spring Boot 업무 서버와 비동기로 이어 Docker와 AWS EC2로 배포했습니다. SK AX AI 개발자 과정(SKALA 2기, 908시간) 수료, 인하대학교 정보통신공학과 졸업.

## 주요 프로젝트

<table>
  <tr>
    <th width="26%">프로젝트</th>
    <th width="38%">무엇</th>
    <th>내 역할</th>
  </tr>
  <tr>
    <td>
      <b>CrewVoice</b><br>
      <sub>2025.11–12 · 6인 팀 · SK AX 최종 프로젝트</sub><br>
      <sub><a href="https://github.com/Gongjoong-Jebi-Club/CrewVoice-BE-FastApi">FastAPI 분석 서버</a> · <a href="https://github.com/Gongjoong-Jebi-Club/CrewVoice-BE-SpringBoot">Spring 서버</a></sub><br>
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
    <td><b>모델 설계·실험·평가 공동</b>, 시스템 설계 파트 발표, 학과 결과 논문 공저</td>
  </tr>
  <tr>
    <td>
      <b><a href="https://github.com/KJM0424/regtech-agent">RegTech Agent</a></b><br>
      <sub>2025.10 · 3인 팀 · 3일</sub><br>
      <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white">
      <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white">
    </td>
    <td>사업 정보로 적용 규제·체크리스트·리스크 보고서를 출처와 함께 만들어 메일로 보내는 9노드 에이전트</td>
    <td><b>검색·분류·리스크 평가 단계 구현</b>: 검색 결과에 출처 ID를 붙여 분류와 보고서까지 전달. 서비스 기획 초안, 법령 API·판례 출처 조사</td>
  </tr>
</table>

<details>
<summary><b>그 외</b></summary>
<br>

| 저장소 | 한 줄 | 시기 |
|---|---|---|
| [jaemin-marketplace](https://github.com/KJM0424/jaemin-marketplace) | Claude Code 작업 규칙 플러그인 | 2026.10 |

</details>

## 기술 스택

<table>
  <tr>
    <td width="12%"><b>주력</b></td>
    <td><img src="https://skillicons.dev/icons?i=python,fastapi,docker,aws,nginx,pytorch,git&theme=light" height="36" alt="주력"><br><sub>LangGraph · LangChain · FastAPI · Python · OpenAI API · FAISS · Azure Speech · Docker · AWS · PyTorch</sub></td>
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
| 2024.07–2025.04 | **인하대 암호연구실 학부연구생** · BGV 동형암호 스킴과 modulus switching 구현, 랩미팅 발표 |
| 2023.10 | **GBIC 블록체인 해커톤 최우수상** (8팀 중) · 커피박 수거 보상 플랫폼 |
| 2023.12 | **프로보노 ICT 공모전 동상** · 고령 보행자 횡단보도 안전 시스템, 7개월 |
| 2023 | **정보통신공학과 학생회장 · 공과대학 학생회장 권한대행** · 총회·예산·감사, 16개 학과 축구 리그 |
| 2026.02 | **인하대학교 정보통신공학과 졸업** |

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2F8F7A,100:176B5B&height=90&section=footer" width="100%" alt="">
