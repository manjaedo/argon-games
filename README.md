# 🕹️ Argon Games (아르곤 아케이드 & 웹앱 모음집)

> **제미나이 4 아르곤(Gemini 4 Argon) 모델과 함께 제작한 고전 명작 아케이드 복원작 및 인터랙티브 웹앱 종합 모음집입니다.**

---

## 🎮 포함된 프로젝트 목록 (Games & Apps)

| 프로젝트 | 카테고리 / 원작 | 주요 기술 | 바로가기 |
| :--- | :--- | :--- | :---: |
| **🏎️ [Rally-X](./rally-x/)** | 1980 Namco 아케이드 레이싱 | HTML5 Canvas, Web Audio API, 미니맵 레이더 | [게임 실행](./rally-x/index.html) |
| **🐍 [Snake Byte Apple II](./snake-byte-apple2/)** | 1982 Sirius Software 고전 명작 | Apple II DOS 3.3 부팅 인트로, 3종 CRT 모드, 28개 스테이지 | [게임 실행](./snake-byte-apple2/index.html) |
| **📜 [오늘의 조선 야사](./joseon-daily-yasa/)** | 역사 리더 웹앱 (조선왕조실록 & 야사) | 순수 JS/CSS, 종이책 한지 UI, 다크모드, PWA | [웹앱 실행](./joseon-daily-yasa/index.html) |

---

## 🌟 프로젝트 개요

### 1. 🏎️ Rally-X (방방카 랠리-X)
* 1980년 남코(Namco)의 전설적인 미로 레이싱 게임 복원작
* **특징:**
  * 블루카(플레이어)와 추격하는 레드카 AI
  * 연막(Smoke Screen) 분사 시스템으로 추격 차량 회전/마비
  * 우측 실시간 레이더(Radar) 미니맵으로 깃발(S) 및 적 위치 탐지
  * 외부 음원 파일 없는 Web Audio 실시간 신디사이저 사운드 구현

### 2. 🐍 Snake Byte (Apple II 명작 복원)
* 1982년 Sirius Software의 Apple II 8비트 명작 스네이크 바이트 복원작
* **특징:**
  * Apple II 전원 비프음 및 Disk II 트랙 0 헤드 캘리브레이션 구동음 재현
  * DOS 3.3 `CATALOG` 및 Hi-Res 메모리 인터리브 블라인드 로딩 효과
  * 3가지 CRT 모니터 모드 (`M` 키): 컬러(Hi-Res 6색), 주홍색(Amber), 녹색(Green P31)
  * 4단계 난이도 및 28개 전체 스테이지 수록

### 3. 📜 오늘의 조선 야사 (朝鮮野史錄)
* 《조선왕조실록》의 실제 엄숙한 기록 뒤에 숨은 기이한 일, 궁중 비화, 기인들의 야담을 매일 읽는 리더 웹앱
* **특징:**
  * 오늘 날짜(양력)와 실제 역사 속 날짜 자동 매칭
  * 한지 질감의 라이트 모드 및 야간 독서용 다크 모드
  * 5대 테마 카테고리 필터 (기이한 일, 궁중 비화, 야담·기인, 왕의 일상, 명장면 모음)

---

## 💻 로컬에서 실행하기

별도의 패키지 설치(`npm install`)가 필요 없는 가벼운 순수 웹 기술(HTML, CSS, JavaScript)로 제작되어 브라우저에서 바로 열거나 간단한 로컬 서버로 즉시 구동할 수 있습니다.

### 방법 1: 루트 포털 바로 열기
루트 디렉토리의 [`index.html`](./index.html) 파일을 브라우저로 더블 클릭하여 엽니다.

### 방법 2: 파이썬 로컬 서버 실행
```bash
# 저장소 루트에서 로컬 웹 서버 실행
python3 -m http.server 8080
```
브라우저에서 `http://localhost:8080`에 접속하면 아케이드 포털이 열립니다.

---

## 📂 디렉토리 구조

```text
argon-games/
├── index.html            # 종합 아케이드 포털 런처
├── README.md             # 프로젝트 안내 문서
├── joseon-daily-yasa/    # 오늘의 조선 야사 웹앱
│   ├── index.html
│   ├── styles.css
│   ├── app.js
│   └── data.js
├── rally-x/              # 1980 남코 랠리-X
│   ├── index.html
│   ├── style.css
│   └── game.js
└── snake-byte-apple2/    # 1982 Apple II 스네이크 바이트
    └── index.html
```
