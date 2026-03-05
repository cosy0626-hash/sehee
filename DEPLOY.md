# GitHub Pages 배포 가이드

## 🚀 빠른 시작 (5분 완성)

### 1️⃣ GitHub 계정 만들기
- https://github.com 접속
- **Sign up** 클릭
- 이메일, 비밀번호 입력 후 가입

### 2️⃣ 새 저장소 만들기
1. 로그인 후 오른쪽 위 **+** 버튼 클릭
2. **New repository** 선택
3. 저장소 이름 입력: `student-learning-platform` (또는 원하는 이름)
4. ⚠️ **Public** 선택 (무료 호스팅 필수!)
5. **Create repository** 버튼 클릭

### 3️⃣ 파일 업로드
1. 생성된 저장소 페이지에서 **uploading an existing file** 링크 클릭
2. 아래 9개 파일을 모두 드래그앤드롭:
   ```
   ✅ index.html
   ✅ home.html
   ✅ science-detail.html
   ✅ social-detail.html
   ✅ science-review.html
   ✅ social-review.html
   ✅ complete.html
   ✅ styles.css
   ✅ README.md
   ```
3. 맨 아래 **Commit changes** 버튼 클릭

### 4️⃣ GitHub Pages 활성화
1. 저장소 상단 **⚙️ Settings** 클릭
2. 왼쪽 메뉴 **Pages** 클릭
3. **Source** 섹션:
   - Branch: **main** 선택
   - Folder: **/ (root)** 선택
4. **Save** 버튼 클릭
5. ✅ 상단에 "Your site is published at..." 메시지 확인

### 5️⃣ 사이트 접속 (1~2분 대기)
- 생성된 URL로 접속:
  ```
  https://[당신의계정명].github.io/[저장소명]/
  ```
- 예시: `https://john-doe.github.io/student-learning-platform/`

---

## 📱 모바일에서 확인하기

1. 생성된 URL을 모바일 브라우저로 접속
2. 홈 화면에 추가 (앱처럼 사용 가능)

---

## 🔄 파일 수정 후 업데이트 방법

### 방법 1: 웹에서 직접 수정
1. GitHub 저장소 페이지 이동
2. 수정할 파일 클릭 (예: `index.html`)
3. 연필 아이콘(✏️) 클릭
4. 코드 수정
5. **Commit changes** 클릭
6. 1~2분 후 자동 반영

### 방법 2: 파일 삭제 후 재업로드
1. 기존 파일 클릭 → 휴지통 아이콘 → 삭제
2. **Add file** → **Upload files**
3. 수정된 파일 업로드
4. **Commit changes** 클릭

---

## ⚠️ 주의사항

### ✅ 반드시 지켜야 할 것

1. **파일명 정확히**: 대소문자 구분됨
   - ❌ `Index.html` (대문자 I)
   - ✅ `index.html` (소문자 i)

2. **모든 파일 업로드**: 하나라도 빠지면 에러
   - 9개 파일 모두 확인

3. **Public 저장소**: Private는 유료

4. **index.html이 첫 페이지**: 
   - 자동으로 로그인 페이지가 첫 화면

### 🐛 문제 해결

**"404 Not Found" 에러가 나요!**
- 1~5분 대기 후 새로고침 (F5)
- Settings → Pages에서 Branch 재저장
- 캐시 삭제 후 재접속 (Ctrl+Shift+R)

**페이지가 안 바뀌어요!**
- GitHub에서 파일 수정 후 1~2분 대기
- 브라우저 캐시 삭제 (Ctrl+Shift+Delete)
- 시크릿 모드로 접속

**CSS가 안 먹혀요!**
- styles.css 파일도 함께 업로드했는지 확인
- 파일명 정확한지 확인 (`styles.css`)

---

## 📊 배포 확인 체크리스트

```
✅ GitHub 저장소 생성 (Public)
✅ 9개 파일 모두 업로드
✅ Settings → Pages 활성화
✅ Branch: main, Folder: / (root) 선택
✅ 1~2분 대기
✅ URL 접속 확인
✅ 로그인 페이지 정상 표시
✅ 홈 → 상세 → 리뷰 페이지 이동 테스트
```

---

## 🎯 배포 완료 후

1. **URL 공유**: 
   - 친구, 선생님께 링크 전달
   - QR 코드 생성 (https://www.qr-code-generator.com)

2. **README 업데이트**:
   - README.md 파일 하단에 실제 URL 추가

3. **테스트**:
   - 여러 기기에서 접속 확인
   - 모바일, 태블릿에서 정상 작동 확인

---

## 💡 추가 팁

### GitHub Desktop 사용 (더 편리함)

1. **설치**: https://desktop.github.com
2. **저장소 클론**: File → Clone repository
3. **파일 수정**: 로컬에서 편집
4. **커밋 & 푸시**: 
   - 변경사항 확인
   - 커밋 메시지 입력
   - Push origin 클릭
5. **자동 배포**: 푸시 후 1~2분이면 반영

### VS Code 사용 (개발자용)

1. **VS Code 설치**: https://code.visualstudio.com
2. **Git 연동**: Source Control 탭
3. **커밋 & 푸시**: 좌측 아이콘 클릭

---

## 🔗 유용한 링크

- **GitHub Pages 공식 문서**: https://pages.github.com
- **Markdown 가이드**: https://guides.github.com/features/mastering-markdown
- **GitHub 가이드**: https://guides.github.com

---

**배포 성공하면 README.md 파일 하단에 URL을 꼭 추가하세요!** 🎉

```markdown
## 🔗 배포 URL
https://your-username.github.io/student-learning-platform/
```
