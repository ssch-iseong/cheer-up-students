# 💪 수험생 응원 메시지 사이트

수험생들을 위한 따뜻한 응원 메시지를 주고받을 수 있는 웹사이트입니다.

## 🌟 주요 기능

### 📝 응원 메시지 작성 (index.html)
- 누구나 쉽게 응원 메시지 작성 가능
- 500자 제한 및 실시간 글자 수 카운터
- 개인정보 수집 없이 익명으로 참여
- 반응형 디자인으로 모든 기기 지원

### 💝 응원 메시지 보기 (view.html)
- 모든 응원 메시지를 한눈에 볼 수 있는 갤러리
- **특별한 기능들:**
  - 🎈 떠다니는 하트 애니메이션
  - ✨ 5초마다 바뀌는 랜덤 명언
  - 🔍 필터 기능 (전체/최신/인기)
  - ❤️ 좋아요 버튼 (하트 이펙트 포함)
  - 📤 메시지 공유 기능
  - 📱 완전 반응형 디자인

## 🚀 배포하기

### GitHub Pages 사용
1. **저장소 생성**
   ```bash
   # GitHub에서 새 repository 생성
   # Repository name: encouragement-messages
   # Public으로 설정
   ```

2. **파일 업로드**
   ```bash
   git clone https://github.com/your-username/encouragement-messages.git
   cd encouragement-messages
   
   # index.html, view.html, README.md 파일들 복사
   
   git add .
   git commit -m "응원 메시지 사이트 추가"
   git push origin main
   ```

3. **GitHub Pages 활성화**
   - Repository Settings → Pages
   - Source: Deploy from a branch
   - Branch: main / (root)
   - Save 클릭

4. **배포 완료**
   - 몇 분 후 https://your-username.github.io/encouragement-messages/ 에서 접속 가능

### 다른 호스팅 서비스
- **Netlify**: 드래그 앤 드롭으로 간단 배포
- **Vercel**: GitHub 연동으로 자동 배포
- **Firebase Hosting**: Google의 무료 호스팅

## 💻 기술 스택

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Storage**: LocalStorage (브라우저 로컬 저장)
- **Design**: 
  - 그라데이션 배경
  - 글래스모피즘 효과
  - 부드러운 애니메이션
  - 반응형 레이아웃

## 📱 호환성

- ✅ Chrome, Firefox, Safari, Edge
- ✅ 데스크톱, 태블릿, 모바일
- ✅ iOS Safari, Chrome Mobile

## 🎨 디자인 특징

### 색상 팔레트
- **메시지 작성**: 보라색 그라데이션 (#667eea → #764ba2)
- **메시지 보기**: 핑크색 그라데이션 (#f093fb → #f5576c)
- **카드**: 반투명 흰색 (rgba(255,255,255,0.95))

### 애니메이션
- 카드 호버 시 3D 회전 효과
- 떠다니는 하트 파티클
- 좋아요 클릭 시 하트 이펙트
- 부드러운 페이드인/아웃

## 📖 사용법

1. **메시지 작성하기**
   - index.html 접속
   - 텍스트 영역에 응원 메시지 입력
   - "응원 메시지 전송하기" 버튼 클릭

2. **메시지 보기**
   - view.html 접속 (또는 "전체 응원 메시지 보러가기" 링크 클릭)
   - 필터를 통해 원하는 메시지 선택
   - 좋아요, 공유 기능 활용

## 🔧 커스터마이징

### 색상 변경
```css
/* 배경 그라데이션 변경 */
background: linear-gradient(135deg, #your-color1, #your-color2);
```

### 명언 추가
```javascript
// view.html의 motivationQuotes 배열에 추가
const motivationQuotes = [
    "기존 명언들...",
    "새로운 명언 추가!"
];
```

## 🤝 기여하기

1. Fork 프로젝트
2. Feature 브랜치 생성 (`git checkout -b feature/새로운기능`)
3. 변경사항 커밋 (`git commit -am '새로운 기능 추가'`)
4. 브랜치에 Push (`git push origin feature/새로운기능`)
5. Pull Request 생성

## 📄 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다.

## 💡 개선 아이디어

- [ ] 관리자 페이지 (부적절한 메시지 삭제)
- [ ] 카테고리별 분류 (과목별, 시험 종류별)
- [ ] 다크 모드 지원
- [ ] 메시지 검색 기능
- [ ] SNS 공유 기능 강화
- [ ] 백엔드 연동 (데이터베이스 저장)

---

**🎯 목표**: 수험생들에게 작은 위로와 큰 힘이 되는 공간 만들기

**💌 메시지**: 힘든 시기를 보내고 있는 모든 수험생들을 응원합니다!
