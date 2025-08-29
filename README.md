# 👁️ 시선(Siseon) - Server

> 뉴스와 시사에 관심은 많지만, 어렵고 재미없어 꾸준히 읽지 못하는 20대 청년들을 위한 앱 '시선'의 프론트엔입니다.  

이 레포지토리는 FastAPI로 만들어진 [시선 백엔드 레포지토리](https://github.com/seoeng/siseon-backend)와 통신합니다.

---


## 🚀 개발기간
- 2025.08.27(수)~


## 🌟 주요기능
* **AI 요약:** 바쁜 당신을 위해 AI가 매일 새로운 뉴스를 세 문장으로 요약해줘요.
* **오늘의 퀴즈:** 요약된 뉴스를 바탕으로 생성된 퀴즈를 풀며 핵심 내용을 완벽하게 익힐 수 있어요.
* **성장 트래킹:** 퀴즈를 풀며 얻은 포인트와 연속 학습 기록(스트릭)으로 나의 성장을 한눈에 확인하세요.
* **관심사 필터:** 내가 원하는 분야의 뉴스만 골라볼 수 있어요. (개발 예정)
  

## 🛠️ 기술 스택

| 구분 | 기술명 |
|---|---|
| **프론트엔드** | ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white) |
| **백엔드** | ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) |
| **데이터베이스**| ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) |
| **AI** | ![OpenAI](https://img.shields.io/badge/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white) |
| **배포** | ![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white) |

## ⚙️ 설치 및 실행 방법

### 1. 사전 요구사항

* [Flutter SDK](https://flutter.dev/docs/get-started/install)
* [Android Studio](https://developer.android.com/studio) 또는 [Visual Studio Code](https://code.visualstudio.com/)
* iOS 개발을 위한 [Xcode](https://developer.apple.com/xcode/) (macOS 전용)

### 2. 프로젝트 클론 및 설정

```bash
# 1. GitHub에서 프로젝트 클론
git clone [https://github.com/당신의_깃허브_ID/siseon-frontend.git](https://github.com/당신의_깃허브_ID/siseon-frontend.git)
cd siseon-frontend

# 2. 필요한 패키지 설치
flutter pub get
```

### 3. 백엔드 서버 연결 설정

```bash
# 프로젝트 내 설정파일에 로컬 백엔드 서버의 주소 입력
# 1. lib 폴더 아래에 config.dart 파일 생성
# 2. 아래 내용 파일에 추가

// lib/config.dart
const String apiBaseUrl = "[http://127.0.0.1:8000](http://127.0.0.1:8000)";
```

### 4. 앱 실행
```bash
# 연결된 디바이스나 에뮬레이터에서 앱 실행
flutter run
```
