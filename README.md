# AI Engineer Portfolio

AI/Computer Science 전공 대학생을 위한 개인 포트폴리오 웹사이트입니다.
순수 HTML5 / CSS3 / JavaScript로 제작되어 GitHub Pages에서 바로 배포할 수 있습니다.

## ✨ 주요 기능
- 반응형 디자인 (PC / 태블릿 / 모바일)
- 🌙 다크모드 (localStorage에 설정 저장)
- 부드러운 스크롤 & 섹션 Fade-in 애니메이션
- 프로젝트 카드 Hover 효과
- 스킬 Progress Bar 시각화
- SEO Meta Tag & Open Graph 적용
- 접근성(aria-label, 시맨틱 태그) 고려

## 📁 프로젝트 구조
```
portfolio/
├── index.html      # 메인 페이지 (모든 섹션)
├── style.css       # 스타일 & 다크모드 & 반응형
├── script.js       # 다크모드/메뉴/스크롤 애니메이션
├── resume.pdf      # 이력서 (직접 추가)
└── README.md
```

## 📄 페이지 구성
Hero · About Me · Education · Skills · Projects · Experience · Resume · Career Goal · Contact

## 🚀 GitHub Pages 배포 방법
1. GitHub에서 새 저장소 생성 (예: `portfolio`)
2. 파일 업로드 후 커밋
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/yourusername/portfolio.git
   git push -u origin main
   ```
3. 저장소 **Settings → Pages** 이동
4. **Source** 를 `main` 브랜치 `/ (root)` 로 설정 후 Save
5. 잠시 후 `https://yourusername.github.io/portfolio/` 에서 확인

## 🛠 커스터마이징
- `index.html`의 `Your Name`, 이메일, GitHub/LinkedIn 링크를 본인 정보로 교체
- `resume.pdf` 파일을 같은 폴더에 추가
- 프로필 사진은 `.hero-photo` 영역에 `<img>` 태그로 교체 가능
- Accent 색상은 `style.css`의 `:root --accent` 변수로 일괄 변경

## 📜 License
MIT License — 자유롭게 사용 및 수정하세요.
