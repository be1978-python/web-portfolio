# 작업 상영관 게시하기

1. https://github.com/new 에서 Public 저장소를 만듭니다. 예: web-portfolio. Add README를 선택하면 바로 파일을 올릴 수 있습니다.
2. 저장소의 Add file → Upload files에서 이 패키지의 **docs 폴더 자체**를 끌어 놓고 Commit changes를 누릅니다. 저장소 최상위에 docs/index.html이 생겨야 합니다.
3. Settings → Pages → Build and deployment → Source: Deploy from a branch → main → /docs → Save를 선택합니다. 기본 브랜치 이름이 다르면 파일을 올린 브랜치를 선택합니다.
4. Actions에서 pages build and deployment가 초록색이 되면 Settings → Pages → Visit site로 엽니다. 일반 저장소 주소는 https://계정명.github.io/저장소명/ 입니다.

## 다음 작품 올리기

- 영상: 저장소에서 docs/videos를 연 뒤 Add file → Upload files로 MP4 또는 WebM을 올리고 커밋하세요. 파일 이름이 표시 제목입니다. 같은 이름의 .txt를 함께 올리면 영상 아래에 출처 링크가 생깁니다.
- 한 파일짜리 페이지: docs/pages에 작품이름.html을 올리세요.
- 이미지·CSS 등이 있는 페이지: docs/pages에 작품이름 폴더를 끌어 놓으세요. 폴더 안 첫 파일은 index.html이어야 합니다. 이미지 등은 상대 경로로 연결하세요. 사이트에는 HTML/CSS/JS 등 완성된 정적 파일을 올립니다.
- 저장할 때마다 GitHub Pages가 첫 화면 목록을 다시 만듭니다. docs/index.html의 앞부분(---)과 docs/_config.yml을 유지하세요. 목록은 GitHub의 Jekyll 빌드에서 만들어집니다.
- 웹 업로드는 파일당 25 MiB, 한 번에 100개까지입니다. 더 큰 영상은 압축하거나 외부 영상 서비스에 올린 뒤 해당 영상을 연결하는 HTML 페이지를 docs/pages에 넣으세요.
