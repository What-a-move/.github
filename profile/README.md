<p align="center">
  <img src="https://raw.githubusercontent.com/What-a-move/.github/754260f66716502c38d3018b816f225a376578b9/assets/focuson-logo.png" width="260" alt="FocusOn 로고">
</p>

<h1 align="center">FocusOn</h1>

<h3 align="center">학습 흐름을 기록하고, 다시 집중할 수 있도록</h3>

<p align="center">
  Desktop과 Chrome Extension으로 학습 활동을 기록하고<br>
  AI가 목표 관련성을 분석해 집중을 돕는 학습 보조 서비스
</p>

## 💡 프로젝트 소개

**FocusOn**은 사용자가 세운 목표와 현재 활동을 비교해 학습에 집중할 수 있도록 도와줍니다.

macOS 앱과 Chrome의 학습 흐름을 바탕으로 현재 활동과 목표의 관련성을 살펴보고, 지속적인 이탈을 알아차려 다시 집중할 수 있도록 돕습니다. 사용자를 평가하거나 웹사이트를 강제로 차단하지 않습니다.

> **학습 목표 설정 → 활동 기록 → AI 분석 → 집중 피드백 → 학습 리포트**

## ✨ 주요 기능

| 구분 | 기능 |
| --- | --- |
| **학습 관리** | 하나의 학습 목표와 시간을 설정하고 세션·타이머를 관리합니다. AI가 모호한 목표를 구체화하도록 돕습니다. |
| **활동 기록** | macOS 활성 앱과 Chrome의 활성 탭·페이지 이동 흐름을 확인합니다. |
| **AI 분석** | 현재 활동과 학습 목표의 관련성을 판단합니다. 판단이 불확실한 활동은 이탈로 취급하지 않습니다. |
| **카메라 보조 분석** | 선택 동의 후 Apple Vision으로 얼굴·눈·시선 상태를 기기 안에서 분석합니다. |
| **집중 피드백** | 목표와 무관한 활동이 지속되면 설정한 방식으로 알리고 학습 복귀를 돕습니다. |
| **개인정보 보호** | 카메라 원본은 저장·전송하지 않으며, 제외 앱·사이트와 민감 화면은 콘텐츠 분석에서 제외합니다. |
| **학습 리포트** | 세션·일간 집중 기록과 집중 달력, 핵심 개념과 다음 시작 지점을 담은 학습 정리를 제공합니다. |

## 🧩 서비스 구성

| 구성 | 역할 |
| --- | --- |
| **Desktop** | 학습 세션·타이머, macOS 활동 확인, 화면 분석과 로컬 카메라 분석을 담당합니다. |
| **Extension** | 현재 탭과 페이지 이동을 확인하고, 허용된 페이지에서 분석에 필요한 텍스트를 수집합니다. |
| **Server** | 인증·기기 연결·세션·사용자 설정·분석 정책·리포트를 관리합니다. |
| **AI** | 목표를 명확히 정하도록 돕고 현재 활동의 목표 관련성을 분석합니다. |

## 🛠 기술 스택

### Client

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![Chrome Extension](https://img.shields.io/badge/Chrome_Extension-4285F4?style=flat-square&logo=googlechrome&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![Apple Vision](https://img.shields.io/badge/Apple_Vision-000000?style=flat-square&logo=apple&logoColor=white)

### Server

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white)

### AI · Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Kiwi](https://img.shields.io/badge/Kiwi-6BA539?style=flat-square)
![Qwen](https://img.shields.io/badge/Qwen-615CED?style=flat-square)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square)
![LangGraph](https://img.shields.io/badge/LangGraph-20232A?style=flat-square&logo=langgraph&logoColor=white)

## 👥 Members

<table>
  <tr>
    <td align="center" width="180">
      <a href="https://github.com/ja2x0n">
        <img src="https://avatars.githubusercontent.com/u/227317381?v=4" width="120" alt="ja2x0n 프로필 사진"><br>
        <strong>ja2x0n</strong>
      </a><br>
      Front-End · Design
    </td>
    <td align="center" width="180">
      <a href="https://github.com/parkjinuk09">
        <img src="https://avatars.githubusercontent.com/u/208936362?v=4" width="120" alt="parkjinuk09 프로필 사진"><br>
        <strong>parkjinuk09</strong>
      </a><br>
      Back-End
    </td>
    <td align="center" width="180">
      <a href="https://github.com/wonu1016">
        <img src="https://avatars.githubusercontent.com/u/204160927?v=4" width="120" alt="wonu1016 프로필 사진"><br>
        <strong>wonu1016</strong>
      </a><br>
      Back-End
    </td>
    <td align="center" width="180">
      <a href="https://github.com/kshi3430">
        <img src="https://avatars.githubusercontent.com/u/213933596?v=4" width="120" alt="kshi3430 프로필 사진"><br>
        <strong>kshi3430</strong>
      </a><br>
      AI
    </td>
    <td align="center" width="180">
      <a href="https://github.com/lyg123d">
        <img src="https://avatars.githubusercontent.com/u/213933562?v=4" width="120" alt="lyg123d 프로필 사진"><br>
        <strong>lyg123d</strong>
      </a><br>
      AI
    </td>
  </tr>
</table>
