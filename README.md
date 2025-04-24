# 🎟️ timer – Electron 기반 오전 11시 티켓 타이머

이 앱은 매일 **KST 기준 오전 11시까지 남은 시간**을 정밀하게 카운트다운하는 미니멀한 타이머입니다.  
실시간 서버 시간(인터파크 기준)에 동기화되어 정확한 티켓팅 타이밍을 맞출 수 있습니다.

---

## 📦 설치 방법

### 1. 프로젝트 클론 또는 다운로드
```bash
git clone https://github.com/your-id/timer.git
cd timer
```

또는 ZIP 다운로드 후 압축 해제

---

## ⚙️ 실행 방법

### 1. 의존성 설치
```bash
npm install
```

### 2. 실행
```bash
npx electron .
```

또는

```bash
npm start
```

---

## 🧰 환경별 준비 사항

| 운영체제 | 사전 설치 사항 |
|----------|----------------|
| Windows  | [Node.js LTS 설치](https://nodejs.org) |
| macOS    | Homebrew로 node 설치 권장: `brew install node` |
| Linux    | apt 등으로 node + npm 설치<br>`sudo apt install nodejs npm` |
| WSL      | Node.js 설치 후 `npx electron .` 실행 가능<br>GUI 출력을 위해 WSLg 또는 X 서버 필요 |

---

## 📁 프로젝트 구조

```bash
timer/
├── index.html       # 타이머 UI (오전 11시 기준)
├── main.js          # Electron 메인 프로세스
├── package.json     # 프로젝트 설정 및 실행 스크립트
```

---

## 🔧 주요 기능
- 매일 오전 11시까지 남은 시간 표시 (서버 시간 기준)
- 밀리초 단위 카운트다운
- 가볍고 미니멀한 UI (눈에 띄지 않음)

---

## 📝 라이선스
MIT License
