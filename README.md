# IDCard-Welcome

지원사업 발표 시 NFC 요원증 데모용 웹페이지입니다.

## 프로젝트 소개

**IDCard-Welcome**은 NFC 카드를 이용한 인터랙티브한 웹 데모 애플리케이션입니다. NFC 요원증을 태그하면 레이더 스캔 애니메이션이 표시되고, 미션 클리어 시 보상(Ne-Coin)을 획득하는 경험을 제공합니다.

- 저장소: https://github.com/black4305/IDCard-Welcome
- 기술 스택: HTML, CSS, JavaScript (순수 웹 기술)
- 배포: GitHub Pages 지원
- 요구사항: 없음 (단일 HTML 파일, 별도 빌드/설치 불필요)

## 주요 기능

### 🎯 NFC 카드 연동
NFC 요원증을 웹페이지에 태그하여 자동으로 웹페이지로 이동합니다.

### 📡 레이더 스캔 애니메이션
NFC 카드 인식 후 레이더 스캔 로딩 애니메이션이 표시됩니다.

### 🏆 미션 클리어 보상
레이더 스캔 완료 후 미션 클리어 보상 화면이 나타나며 **Ne-Coin** 포인트를 획득합니다.

### 📱 모바일 최적화
스마트폰 환경에서 완벽하게 동작하며 NFC 기능을 최대한 활용합니다.

## 사용 방법

### 1단계: GitHub Pages 배포
프로젝트를 GitHub Pages로 배포합니다.

```bash
# GitHub 저장소에 푸시
git push origin main
```

### 2단계: NFC 카드 기록
NFC 카드에 다음 URL을 기록합니다:

```
https://black4305.github.io/IDCard-Welcome/
```

또는 자신의 GitHub Pages 주소로 변경:

```
https://[your-github-username].github.io/IDCard-Welcome/
```

### 3단계: 카드 태그
스마트폰의 NFC 리더 기능을 활성화한 후 기록된 NFC 카드를 태그합니다.

### 4단계: 웹페이지 표시
자동으로 웹페이지가 열리고 레이더 스캔 애니메이션이 시작됩니다.

### 5단계: 보상 획득
애니메이션 완료 후 미션 클리어 보상 화면에서 **Ne-Coin**을 획득합니다.

## 배포 방법

### GitHub Pages로 배포

#### 1. 저장소 설정 확인
GitHub의 저장소 Settings → Pages에서 다음을 확인합니다:
- **Source**: `main` 브랜치 (또는 `master`)
- **Folder**: `/ (root)`

#### 2. 배포 확인
몇 분 후 다음 주소에서 웹페이지에 접속할 수 있습니다:

```
https://[your-github-username].github.io/IDCard-Welcome/
```

#### 3. NFC 카드에 URL 기록
NFC 기록 도구나 앱을 사용하여 배포된 GitHub Pages URL을 NFC 카드에 기록합니다.

## 파일 구조

```
IDCard-Welcome/
├── README.md           # 이 파일
├── index.html          # 메인 웹페이지 (HTML, CSS, JavaScript 포함)
└── .git/              # Git 저장소
```

## 기술 사항

- **HTML5**: 페이지 구조 및 NFC 연동
- **CSS3**: 레이더 스캔 애니메이션 및 반응형 디자인
- **JavaScript**: 사용자 인터랙션 및 보상 로직
- **모바일 최적화**: Viewport 설정 및 터치 친화적 UI

## 라이선스

이 프로젝트는 자유롭게 사용, 수정, 배포할 수 있습니다.

## 기여

버그 리포트나 기능 제안은 GitHub Issues를 통해 제출해주세요.

---

**작성일**: 2026년 2월 27일
