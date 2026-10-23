# 연구자 개인 홈페이지 (GitHub Pages)

HTML과 CSS만으로 만든 정적 사이트입니다. 빌드 도구 없이 GitHub에 올리기만 하면 공개됩니다.

## 공개하는 방법

1. github.com에 로그인하고 **New repository**를 누릅니다.
2. 저장소 이름을 `내아이디.github.io` 로 정합니다. (예: 아이디가 `hong` 이면 `hong.github.io`) 공개 범위는 Public으로 둡니다.
3. 저장소 화면에서 **uploading an existing file**을 눌러 이 폴더 안의 파일을 모두 끌어다 놓고 **Commit changes**를 누릅니다. `index.html`이 저장소 맨 위에 있어야 합니다.
4. **Settings → Pages**에서 Source를 `Deploy from a branch`, Branch를 `main` / `(root)`로 두고 Save합니다.
5. 1~2분 뒤 `https://내아이디.github.io` 에서 열립니다.

## 먼저 바꿀 것

모든 페이지에서 아래 문구를 검색해 본인 정보로 바꾸세요. (VS Code 등에서 폴더 전체 검색·바꾸기를 쓰면 한 번에 됩니다.)

| 찾을 문구 | 바꿀 내용 |
|---|---|
| `이름`, `Your Name` | 본인 이름 |
| `○○대학교` | 소속 |
| `내-깃허브-아이디` | 본인 GitHub 아이디 |
| `you@example.com` | 연락용 이메일 |
| `20XX`, `〔성함〕` | 연도, 지도교수 등 실제 내용 |

`index.html`의 파란 안내 상자(`class="todo"`)는 다 채운 뒤 지우세요.

## 구성

- `index.html` 첫 화면, `about.html` CV, `research.html` 연구, `talks.html` 발표, `writing.html` 글 목록, `media.html` 미디어
- `posts/` 개별 글. `posts/hello.html`을 복사해 새 글을 만듭니다.
- `assets/style.css` 색과 글꼴. 맨 위 `:root` 값만 바꿔도 분위기가 달라집니다.

## 공개 전 확인

- 미발표 연구 내용, 지도교수·심사위원 정보처럼 공개해도 되는지 확인이 필요한 내용은 올리기 전에 한 번 더 점검하세요.
- 이메일 주소는 공개되면 스팸이 올 수 있으니, 필요하면 학교 메일을 쓰세요.
