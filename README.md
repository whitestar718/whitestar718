<!--
  ┌─────────────────────────────────────────────────────────────┐
  │  GitHub 프로필 대문                                            │
  │  배포처: whitestar718/whitestar718 저장소의 README.md          │
  │  원본:   whitestar718/260710_Claude26 · PROFILE_README_sample.md │
  │                                                               │
  │  수정할 때는 원본을 고치고 배포처로 복사한다.                    │
  │  헤더가 assets/header-*.svg 를 상대경로로 참조하므로            │
  │  README.md 만 옮기면 헤더가 깨진다. assets/ 를 반드시 동반할 것. │
  └─────────────────────────────────────────────────────────────┘
-->

<!-- ============ 헤더 (자체 제작 SVG · 외부 서비스 없음) ============ -->
<!-- 벡터라 어떤 해상도에서도 깨지지 않는다. 색을 바꾸려면 SVG 안의 #30A787을 교체. -->
<div align="center">

<img src="assets/header-light.svg#gh-light-mode-only" width="100%" alt="EUN HAECHAN — All-round AI Vision Engineer"/>
<img src="assets/header-dark.svg#gh-dark-mode-only" width="100%" alt="EUN HAECHAN — All-round AI Vision Engineer"/>

### 데이터의 중요성을 아는 AI 비전 엔지니어

**현장의 문제를 해결하는 AI 파이프라인 디자인**&nbsp;&nbsp;·&nbsp;&nbsp;**ASPICE 4.0 표준 프로세스 기반 개발**

<br/>

<!-- ============ 상단 뱃지 (연락처 / 방문자) ============ -->
<img src="https://komarev.com/ghpvc/?username=whitestar718&style=flat-square&color=30A787&label=Profile+Views" alt="views"/>
&nbsp;
<a href="mailto:whitestar718@naver.com"><img src="https://img.shields.io/badge/Email-whitestar718@naver.com-30A787?style=flat-square&logo=gmail&logoColor=white" alt="email"/></a>

</div>

<br/>

<!-- ============ 소개 ============ -->
## 👋 소개

안녕하세요, **올라운더 AI 비전 엔지니어 은해찬**입니다.

- 🔬 **의료·진단 영상**부터 **산업 검사·보안**까지, 카메라가 보는 문제라면 데이터부터 모델, 배포까지 끝까지 책임집니다.
- 🧩 **데이터 중심의 사고**로 문제에 접근합니다. 성능이 안 나오는 구간을 데이터에서 진단하고, 고객사를 설득해 파이프라인을 돌려 해결하는 방식으로 일합니다.
- 📐 **ASPICE 4.0 표준 프로세스**에 따라 개발합니다. 요구사항 추적부터 검증까지, 재현 가능하고 감사 가능한 개발을 지향합니다.
- 🗂️ 현재 **인캐빈센싱 사업본부의 형상관리자(Configuration Manager)**를 병행하며, 산출물·베이스라인·변경 이력을 체계적으로 관리하고 있습니다.
- 📱 학습된 모델을 **온디바이스(Android/NPU)** 로 포팅하는 것까지가 제 일이라고 생각합니다.

<br/>

<!-- ============ 기술 스택 배지 ============ -->
## 🛠️ Tech Stack

**AI / Vision**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)

**Mobile / On-device**

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)

**Quality / Verification**

![SureSoft STATIC](https://img.shields.io/badge/SureSoft%20STATIC-1D6350?style=for-the-badge&logoColor=white)
![SureSoft CT 2024](https://img.shields.io/badge/SureSoft%20CT%202024-1D6350?style=for-the-badge&logoColor=white)

**Collaboration & Tools**

![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Confluence](https://img.shields.io/badge/Confluence-172B4D?style=for-the-badge&logo=confluence&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Weights & Biases](https://img.shields.io/badge/W&B-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=black)

<br/>

<!-- ============ 대표 프로젝트 ============ -->
## 🚀 대표 프로젝트

### 🩺 POCT 항체 자가진단 키트 정량 분석
> 스마트폰으로 촬영한 진단 키트에서 **항체 농도를 정량**. `detection`이 라인 ROI를 찾고 `regression`이 농도 연속값을 예측하는 **2단 파이프라인**.
>
> **고농도 구간에서 발색이 오히려 옅어져** 농도 구분이 무너지는 난제를, 모델 튜닝이 아니라 **해당 구간 재촬영을 고객사에 요청**해 해결. 성능으로 설득하자 고객사가 먼저 데이터를 제안하는 협업으로 전환됐습니다.
>
> `R² 0.95+` · 프로테옴텍(현 프로티아) · 2022.09–2023.03 · 정부과제 1.1억 · 기술이전 완료
>
> ![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![Kotlin](https://img.shields.io/badge/-Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

<br/>

<!-- ============ GitHub (동적 배지) ============ -->
## 📊 GitHub

<div align="center">

![Followers](https://img.shields.io/github/followers/whitestar718?style=for-the-badge&logo=github&logoColor=white&label=Followers&color=30A787&labelColor=1D6350)
![Stars](https://img.shields.io/github/stars/whitestar718?style=for-the-badge&logo=github&logoColor=white&label=Stars&color=30A787&labelColor=1D6350)
![Profile Views](https://komarev.com/ghpvc/?username=whitestar718&style=for-the-badge&color=30A787&label=PROFILE+VIEWS)

</div>

<br/>

<!-- ============ 하단 ============ -->
<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:30A787,50:1D6350,100:123F33&height=100&section=footer" alt="footer"/>

</div>
