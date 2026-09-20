# Le_몬 Coding

블록 코딩(엔트리, LEGO SPIKE)에서 시작해 Python 알고리즘, GDevelop 모바일 게임, Unity까지 이어진 코딩 기록입니다.

[![Portfolio](https://img.shields.io/badge/GitHub-portfolio-black?logo=github)](https://github.com/le-mon-dev/portfolio)
[![Animating](https://img.shields.io/badge/GitHub-animating-black?logo=github)](https://github.com/le-mon-dev/animating)
[![Entry](https://img.shields.io/badge/Entry-%EB%A1%9C%EC%97%94-2ecc71)](https://playentry.org/profile/5c962ab2174736078326fdc5/project)

## 한눈에 보기

| 시기 | 도구 | 내용 |
|---|---|---|
| 2020.12 ~ 2025.07 | 엔트리(Entry) | 블록 코딩 게임·애니메이션 작품 232개 |
| 2020 ~ 2023 | Python, C++ | 정보올림피아드(KOI 지역예선, 세종 정보올림피아드) 문제 풀이 |
| 2023.01 | 엔트리, Python, 마이크로비트 | 디지털새싹캠프: 엔트리 RC카, 마이크로비트 센서 프로그래밍 |
| 2025.09 ~ 2025.11 | GDevelop | Android 모바일 게임 3종 (Run & Bow, Tappy Plane, IDK) |
| 2025 ~ | Unity 6 (URP 2D) | 모바일 게임 프로젝트 |
| 2026.08 | LEGO SPIKE Prime | 로봇대회: 센서 기반 자율주행 로봇 제작·프로그래밍 |

---

## 로봇대회 (2026.08) — LEGO SPIKE Prime

LEGO SPIKE Prime 허브에 컬러 센서, 거리 센서, 모터를 연결하고 스마트폰을 거치한 자율주행 로봇을 만들었습니다.
SPIKE 앱의 블록 코딩으로 센서 값에 따라 주행을 제어합니다. 메모에 포트 배치를 정리했습니다 (A: 컬러 센서, B: 팔 센서, C/D: 모터, E/F: 거리 센서).

| 로봇 | 코드 |
|:---:|:---:|
| ![](robot-competition-2026/03.jpg) | ![](robot-competition-2026/10.jpg) |
| ![](robot-competition-2026/08.jpg) | ![](robot-competition-2026/11.jpg) |

사진 12장 전체: [`robot-competition-2026/`](robot-competition-2026/)

---

## GDevelop 모바일 게임 (2025)

[GDevelop](https://editor.gdevelop.io/) 클라우드에 만든 프로젝트 3개입니다. 모두 Android 터치 조작 기준으로 설계했습니다.

![프로젝트 목록](gdevelop/project-list.jpg)

### Run & Bow (Shoot'n Run) — 2025.09.17

레트로 감성의 횡스크롤 플랫포머. 화면 버튼으로 점프·공격·방어하며 점점 빨라지는 속도 속에서 적을 피합니다.
씬 3개(Menu, 게임, Shop), 확장 기능 4개(ButtonStates, FireBullet, Flash, Health), 외부 레이아웃으로 구간(0_1~0_4, Boss)을 구성했습니다.
스토리지에 최고 점수·돈·업그레이드 상태를 저장하고, 상점에서 방어력·검·돈 획득량을 업그레이드합니다.

| | |
|:---:|:---:|
| ![](gdevelop/run-and-bow/01_project-manager.jpg) | ![](gdevelop/run-and-bow/02_scene-editor_objects.jpg) |
| ![](gdevelop/run-and-bow/03_events_scene-start.jpg) | ![](gdevelop/run-and-bow_knight.png) |

스프라이트 에셋: [`gdevelop/shootn-run-assets/`](gdevelop/shootn-run-assets/) (기사 idle·stagger, 코인, 사망 애니메이션, 타일)

### Tappy Plane — 2025.10.20

비행기를 탭으로 조종해 기둥 사이를 통과하는 Flappy Bird 스타일 게임. GDevelop 튜토리얼을 바탕으로 만들고 리더보드, 화면 흔들림, 전환 효과를 붙였습니다. 상태 변수(NotStarted → GamePlaying)로 게임 흐름을 관리합니다.

| | |
|:---:|:---:|
| ![](gdevelop/tappy-plane/01_project-manager.jpg) | ![](gdevelop/tappy-plane/02_game-scene_objects.jpg) |
| ![](gdevelop/tappy-plane/03_events.jpg) | |

### IDK — 2025.11.18

실루엣 스타일의 터렛 방어 게임 프로토타입. 화면 조이스틱으로 터렛을 조준하고, 변수로 터렛 위치(1~3)를 전환합니다.

| | |
|:---:|:---:|
| ![](gdevelop/idk/01_scene.jpg) | ![](gdevelop/idk/02_events.jpg) |

---

## 알고리즘 — 정보올림피아드

Python(일부 C++)으로 직접 풀어 본 코드입니다. 문제별 접근 방법은 [`algorithms/README.md`](algorithms/README.md)에 정리했습니다.

| 폴더 | 내용 |
|---|---|
| `algorithms/sejong-olympiad-3rd/` | 세종 정보올림피아드 제3회 8문제 (단가 계산부터 트리 지름까지) |
| `algorithms/koi-2020` ~ `koi-2023` | KOI 지역예선 6문제 (조롱박, 지우기, 4등분, 빵, 크림빵, 대피소) |
| `algorithms/practice/` | 파일 입출력 연습 |

---

## 엔트리 (2020.12 ~ 2025.07)

첫 게임 「벽을 타지마 2」(2020.12)부터 232개 작품을 만들었습니다. 전체 목록은 [`entry/projects.tsv`](entry/projects.tsv), 정리된 표는 [portfolio/games/entry](https://github.com/le-mon-dev/portfolio/tree/main/games/entry)에 있습니다.

| 날짜 | 대표 작품 | 조회 |
|---|---|---|
| 2020.12 | [제가 만든건데... ㅎㅎ 좀 그래요(영자님이 오셨다)](https://playentry.org/project/5fc613f8904ac60174fa0d45) | 376 |
| 2020.12 | [벽을타지마 2](https://playentry.org/project/5fc8d8e3d3b8d00086901cb6) | 68 |
| 2022.08 | [프사 움직이게 하는 법](https://playentry.org/project/62f5c78aaab8ca0146510958) | 343 |
| 2022.06 | [11인 대합작:이무진,신호등](https://playentry.org/project/62bc17529b40fa00c20a7a59) | 245 |
| 2022.09 | [물리엔진](https://playentry.org/project/63252bb5fac86700dad9c80b) | 36 |
| 2025.04 | [[반전] 리버스 점프맵](https://playentry.org/project/67eceea36a4b1cedad6b3897) | 57 |
| 2025.06 | [히트맨](https://playentry.org/project/6855623824840d105eb4357c) | 18 |

### 작업 화면 캡처 (2022)

2022년 1월 ~ 12월 엔트리 작품을 만들면서 녹화한 화면에서 뽑은 캡처입니다. 블록 코드 화면 23장, 전체 34장은 [`entry/captures/`](entry/captures/)에 있습니다.

| | | |
|:---:|:---:|:---:|
| ![](entry/captures/2022-01-24_19-06-28_작품_만들기.jpg) | ![](entry/captures/2022-01-24_19-10-43_작품_만들기.jpg) | ![](entry/captures/2022-01-24_19-17-40_작품_만들기.jpg) |
| ![](entry/captures/2022-01-24_19-29-40_작품_만들기.jpg) | ![](entry/captures/2022-01-24_19-33-55_작품_만들기.jpg) | ![](entry/captures/2022-01-25_09-43-40_작품_만들기.jpg) |
| ![](entry/captures/2022-01-25_09-50-40_작품_만들기.jpg) | ![](entry/captures/2022-01-25_09-55-58_작품_만들기.jpg) | ![](entry/captures/2022-01-25_10-08-44_작품_만들기.jpg) |
| ![](entry/captures/2022-01-25_10-50-14_작품_만들기.jpg) | ![](entry/captures/2022-01-25_16-15-04_작품_만들기.jpg) | ![](entry/captures/2022-01-28_17-52-49_작품_만들기.jpg) |
| ![](entry/captures/2022-02-03_17-08-39_작품_만들기.jpg) | ![](entry/captures/2022-02-03_17-09-26_작품_만들기.jpg) | ![](entry/captures/2022-02-03_17-17-56_작품_만들기.jpg) |
| ![](entry/captures/2022-03-12_18-30-30_새_탭.jpg) | ![](entry/captures/2022-03-12_6-40-28_새_탭.jpg) | ![](entry/captures/2022-06-09_21-09-18_작품_만들기.jpg) |
| ![](entry/captures/2022-07-08_7-19-21_작품_만들기.jpg) | ![](entry/captures/2022-07-08_7-19-47_작품_만들기.jpg) | ![](entry/captures/2022-07-08_7-20-22_작품_만들기.jpg) |
| ![](entry/captures/2022-12-19_20-02-28_작품_만들기.jpg) | ![](entry/captures/2022-12-21_07-11-23_타이포그래피.jpg) | |

![벽을타지마 배경](entry/벽을타지마_배경.png)

---

## Unity 모바일 게임

Unity 6 (6000.0) URP 2D 템플릿으로 시작한 프로젝트. `unity-mobile-game/` 폴더를 Unity Hub에 추가하면 열립니다.

---

## 도구

Entry · LEGO SPIKE App · Python · C++ · GDevelop 5 · Unity 6 · PyCharm · VS Code
