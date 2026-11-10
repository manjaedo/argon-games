# 🕹️ Argon Games (아르곤 레트로 아케이드 게임 모음집)

> **제미나이 4 아르곤(Gemini 4 Argon) 모델과 함께 제작한 1980년대 고전 명작 아케이드 복원작 모음집입니다.**

---

## 🎮 게임 목록 (Classic Games)

| 게임명 | 원작 / 출시 연도 | 주요 기술 | 바로가기 |
| :--- | :--- | :--- | :---: |
| **🏎️ [Rally-X](./rally-x/)** | 1980 Namco 아케이드 레이싱 | HTML5 Canvas, Web Audio API, 미니맵 레이더 | [게임 플레이](./rally-x/index.html) |
| **🐍 [Snake Byte Apple II](./snake-byte-apple2/)** | 1982 Sirius Software 고전 명작 | Apple II DOS 3.3 부팅 인트로, 3종 CRT 모드, 28개 스테이지 | [게임 플레이](./snake-byte-apple2/index.html) |

---

## 🌟 게임 상세 소개

### 1. 🏎️ Rally-X (방방카 랠리-X)
* 1980년 남코(Namco)의 전설적인 미로 레이싱 게임 웹 표준 복원작
* **특징:**
  * 블루카(플레이어)와 추격하는 레드카 AI
  * 연막(Smoke Screen) 분사 시스템으로 추격 차량 회전/마비
  * 우측 실시간 레이더(Radar) 미니맵으로 깃발(S) 및 적 위치 탐지
  * 외부 음원 파일 없는 Web Audio 실시간 신디사이저 사운드 구현
* **조작:** 방향키 / `WASD`, 연막: `Space` 또는 `Z`

### 2. 🐍 Snake Byte (Apple II 명작 복원)
* 1982년 Sirius Software의 Apple II 8비트 명작 스네이크 바이트 복원작
* **특징:**
  * Apple II 전원 비프음 및 Disk II 트랙 0 헤드 캘리브레이션 구동음 재현
  * DOS 3.3 `CATALOG` 및 Hi-Res 메모리 인터리브 블라인드 로딩 효과
  * 3가지 CRT 모니터 모드 (`M` 키): 컬러(Hi-Res 6색), 주홍색(Amber), 녹색(Green P31)
  * 4단계 난이도 및 28개 전체 스테이지 수록
* **조작:** 4-KEY(방향키/`WASD`) 또는 2-KEY(좌/우 90° 회전) 모드

---

## 💻 실행 방법

### 웹에서 바로 플레이 (GitHub Pages)
👉 **[https://manjaedo.github.io/argon-games/](https://manjaedo.github.io/argon-games/)**

### 로컬에서 실행하기
* 루트 디렉토리의 [`index.html`](./index.html) 파일을 브라우저로 더블 클릭하거나,
* 터미널에서 `python3 -m http.server 8080` 실행 후 `http://localhost:8080` 접속

---

## 📂 디렉토리 구조

```text
argon-games/
├── index.html            # 아케이드 종합 런처 포털
├── README.md             # 프로젝트 소개 문서
├── rally-x/              # 1980 남코 랠리-X
│   ├── index.html
│   ├── style.css
│   └── game.js
└── snake-byte-apple2/    # 1982 Apple II 스네이크 바이트
    └── index.html
```
