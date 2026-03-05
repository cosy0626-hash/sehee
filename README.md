# 오늘 우리 수업은 - 학생 학습 플랫폼

초등학교 학생들을 위한 학습 맥락 공유 및 학습 리뷰 작성 플랫폼입니다.

## 📚 프로젝트 소개

교사가 매 차시 수업 맥락을 공유하고, 학생들이 수업 후 학습 리뷰를 작성하여 선생님께 피드백을 전달하는 웹 플랫폼입니다.

### 주요 기능

- 🎓 **간편한 로그인**: 닉네임과 비밀번호로 간단하게 접근
- 📚 **오늘의 수업**: 오늘 배울 과목과 차시 한눈에 확인
- 🔬 **학습 맥락 카드**: 학습목표, 오늘 활동, 준비물 등 확인
- 📝 **학습 리뷰**: 수업 후 감정, 어려움, 이해도를 간단히 기록
- 📁 **과목별 기록**: 과거 수업 내역 누적 관리

## 🖥️ 화면 구성

1. **index.html** - 로그인 페이지
2. **home.html** - 메인 홈 (오늘의 수업)
3. **science-detail.html** - 과학 학습 맥락
4. **social-detail.html** - 사회 학습 맥락
5. **science-review.html** - 과학 학습 리뷰
6. **social-review.html** - 사회 학습 리뷰
7. **complete.html** - 제출 완료
8. **styles.css** - 통합 스타일시트

## 🎨 디자인 특징

- 📱 태블릿 최적화 UI
- 🎨 과목별 색상 구분 (과학: 초록, 사회: 오렌지)
- 💫 부드러운 애니메이션 효과
- 🌈 보라색 그라데이션 배경
- ✨ 손글씨 폰트 (Gaegu) 적용

## 🚀 로컬 실행 방법

1. 모든 파일을 하나의 폴더에 저장
2. `index.html` 파일을 브라우저로 열기
3. 아무 닉네임/비밀번호 입력 후 로그인

## 🌐 GitHub Pages 배포 방법

### 방법 1: 웹에서 직접 업로드

1. GitHub 저장소 생성 (Public)
2. 모든 파일 업로드
3. Settings → Pages → Branch: main 선택
4. Save 후 1~2분 대기
5. 생성된 URL 확인

### 방법 2: GitHub Desktop 사용

1. GitHub Desktop 설치
2. 저장소 클론 또는 생성
3. 모든 파일 복사
4. Commit & Publish
5. Settings → Pages 활성화

## 📂 파일 구조

```
project/
├── index.html              # 로그인
├── home.html               # 홈
├── science-detail.html     # 과학 상세
├── social-detail.html      # 사회 상세
├── science-review.html     # 과학 리뷰
├── social-review.html      # 사회 리뷰
├── complete.html           # 완료
├── styles.css              # 스타일
└── README.md               # 설명서
```

## 🎯 사용 흐름

```
로그인 → 홈 → 과목 선택 → 학습 맥락 확인 → 학습 리뷰 작성 → 완료
```

## 💾 데이터 저장

- 현재는 프로토타입으로 `sessionStorage` 사용
- 실제 서비스 시 백엔드 API 연동 필요
- 로그인 정보는 세션에만 저장 (새로고침 시 유지)

## 🎓 사용 대상

- 초등학교 3~6학년 학생
- 교사 (학습 맥락 구성 및 리뷰 확인)

## 🛠️ 기술 스택

- HTML5
- CSS3 (Grid, Flexbox, Gradient, Animation)
- Vanilla JavaScript (ES6+)
- Google Fonts (Noto Sans KR, Gaegu)

## 📱 브라우저 호환성

- Chrome (최신)
- Safari (최신)
- Firefox (최신)
- Edge (최신)

## 📝 라이선스

이 프로젝트는 교육 목적으로 제작되었습니다.

## 👨‍💻 개발 정보

- 제작: CXP 기획팀
- 버전: 1.0.0
- 최종 수정: 2026-03-05

## 🔗 배포 URL

배포 후 이곳에 URL을 추가하세요:
```
https://your-username.github.io/your-repo-name/
```

---

**문의사항이나 개선 제안은 Issues 탭에 남겨주세요!** 😊
