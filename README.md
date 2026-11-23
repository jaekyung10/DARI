
<div align="center">

# 🌐 DARI

### Connecting People Beyond Boundaries

**언어와 문화, 시차의 경계를 넘어 모두가 연결되는 AI 회의 협업 서비스**

<br>

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=reactrouter&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white)

<br>

**LIKELION 중앙해커톤 | 본선 진출 프로젝트**

</div>

---

## 💙 About DARI

> **"다른 언어, 다른 문화, 다른 시간대에서도 함께할 수 있도록."**
>
> 글로벌 협업의 경계를 연결하는 AI 회의 파트너

**DARI**는 다국적·리모트 팀이 겪는 언어, 문화, 지리, 조직적 경계를 완화하기 위한 **AI 기반 회의 보조 서비스**입니다.

글로벌 팀의 구성원들은 서로 다른 문화적 커뮤니케이션 방식과 언어, 시간대 때문에 회의 준비부터 진행, 후속 업무 관리까지 다양한 어려움을 겪습니다.

DARI는 이러한 문제를 해결하기 위해 **회의 전 · 회의 중 · 회의 후**의 전체 협업 과정을 하나의 서비스로 연결합니다.

<br>

## ✨ Key Features

### 01. Before Meeting — 회의 준비

| 기능 | 설명 |
|---|---|
| 🤖 **AI Persona Rehearsal** | 상대방의 문화적 커뮤니케이션 스타일을 반영한 AI 페르소나와 회의 리허설 |
| 📝 **Speaking Cards** | 리허설 피드백을 바탕으로 실전 회의에서 활용할 발언 카드 관리 |
| 🌍 **Timezone Tracker** | 국가별 시차와 참여 가능 시간을 고려한 회의 일정 조율 |
| ⚖️ **Fairness Tracking** | 특정 구성원에게 불리한 새벽·야간 회의가 반복되지 않도록 형평성 확인 |

### 02. During Meeting — 실시간 회의

| 기능 | 설명 |
|---|---|
| 💬 **Real-time Translation** | 서로 다른 언어를 사용하는 참여자 간 실시간 번역 지원 |
| 🎤 **Meeting Progress** | 회의 진행 상황과 참여자 정보를 실시간으로 확인 |
| 🗂️ **Speaking Card Support** | 회의 전에 준비한 발언 카드를 실제 회의에서 활용 |
| 🖥️ **Screen Sharing** | 원격 회의 중 화면 공유 기능 지원 |

### 03. After Meeting — 회의 후 관리

| 기능 | 설명 |
|---|---|
| 📄 **AI Meeting Summary** | 회의 내용을 요약하여 주요 논의 사항 정리 |
| ✅ **Action Items** | 회의 후 실행해야 할 업무와 후속 작업 확인 |
| 📊 **Meeting Report** | 회의 결과 및 관련 정보 확인 |

<br>

## 🛠️ Tech Stack

### Frontend

| Category | Technologies |
|---|---|
| **Framework** | React |
| **Language** | JavaScript |
| **Build Tool** | Vite |
| **Routing** | React Router |
| **HTTP Client** | Axios |
| **Code Quality** | ESLint |
| **Collaboration** | Git, GitHub |

<br>

## 👩‍💻 My Contributions

**Role: Frontend Developer**

DARI 프로젝트에서 React 기반 프론트엔드 개발에 참여하여 글로벌 회의 협업 서비스의 사용자 인터페이스를 구현했습니다.

### 주요 담당 업무

**01. 공통 레이아웃 및 화면 구성**
- Header, Sidebar, AppLayout 등 공통 UI 구성
- 페이지별 라우팅 및 반응형 레이아웃 구현
- 홈 및 인증 화면 구성

**02. AI 리허설 및 발언 카드**
- 문화권별 AI 페르소나를 활용한 리허설 UI 구현
- AI 코치 피드백 및 번역 결과 표시
- 발언 카드 저장 및 관리 화면 구현

**03. 시차 형평성 트래커**
- 국가별 시간대와 참여 가능 시간 UI 구현
- 참여자별 일정을 30분 단위로 시각화
- 회의 가능 시간과 형평성 관련 정보 표시

**04. 실시간 회의 화면**
- 실시간 회의 진행 상황 UI 구현
- 회의 참여자 정보 및 상태 표시

<br>

## 📁 Project Structure

프론트엔드의 주요 페이지 구성입니다.

```text
src/
├── api/             # API 통신
├── pages/
│   ├── auth/        # 로그인 및 회원가입
│   ├── cards/       # 발언 카드
│   ├── home/        # 홈
│   ├── meeting/     # 실시간 회의
│   ├── mypage/      # 마이페이지
│   ├── rehearsal/   # AI 리허설
│   ├── summary/     # 회의 요약
│   └── tracker/     # 시차 형평성 트래커
│
└── App.jsx          # 애플리케이션 구성
```

> 주요 디렉터리만 표시했으며, 상세 구조는 실제 소스 코드를 참고하세요.

<br>

## 🚀 Getting Started

**1. Clone Repository**

```bash
git clone https://github.com/yuu-nn/DARI.git
cd DARI
```

**2. Install Dependencies**

프론트엔드 프로젝트 디렉터리에서 실행합니다.

```bash
npm install
```

**3. Run Development Server**

```bash
npm run dev
```

**4. Build & Lint**

```bash
npm run build
npm run lint
```

**5. Preview Production Build**

```bash
npm run preview
```

<br>

## 🔄 Service Workflow

DARI는 글로벌 팀의 회의 전 과정을 연결합니다.

```text
┌───────────────────────────┐
│       Before Meeting      │
│                           │
│    AI Persona Rehearsal   │
│       Speaking Cards      │
│       Timezone Tracker    │
└─────────────┬─────────────┘
              │
              ▼
┌───────────────────────────┐
│       During Meeting      │
│                           │
│    Real-time Translation  │
│      Meeting Progress     │
│      Speaking Cards       │
└─────────────┬─────────────┘
              │
              ▼
┌───────────────────────────┐
│       After Meeting       │
│                           │
│      AI Meeting Summary   │
│        Action Items       │
│        Meeting Report     │
└───────────────────────────┘
```

<br>

## 🎯 Project Goals

**01. Language Barrier**

실시간 번역을 통해 언어가 다른 구성원들도 회의에 참여할 수 있도록 지원합니다.

**02. Cultural Barrier**

AI 페르소나 리허설을 통해 서로 다른 문화권의 커뮤니케이션 방식을 이해하고 준비하도록 돕습니다.

**03. Geographical Barrier**

시차 형평성 트래커를 활용하여 특정 구성원에게 반복적으로 불리한 회의 시간을 줄이고자 합니다.

**04. Organizational Barrier**

회의 준비, 진행, 요약 및 후속 업무 관리를 연결하여 글로벌 팀의 협업 효율을 높이고자 합니다.

---

<div align="center">

### 🌐 DARI

**Beyond Language. Beyond Culture. Beyond Boundaries.**

Made with 💙 for **LIKELION 중앙해커톤**

</div>
