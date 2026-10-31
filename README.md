# (주)아모젠파워 웹사이트

아모젠파워 회사 소개 사이트입니다. 빌드 과정이 없는 정적 사이트(HTML + CSS)라서 Vercel, Netlify, GitHub Pages 어디에나 그대로 배포할 수 있습니다.

## 파일 구성

- `index.html`: 메인 페이지 (회사소개, 개발사업, 핵심기술, 개발로드맵, 문의)
- `privacy.html`: 개인정보처리방침
- `assets/styles.css`: 디자인 스타일
- `assets/favicon.svg`: 브라우저 탭 아이콘

## 자주 바꾸는 곳

- **연락처**: `index.html`에서 `contact@ammogenpower.co.kr`, `010-0000-0000`을 실제 값으로 바꿉니다. (현재 임시 값)
- **이미지**: 회색 박스(`class="ph"`)가 이미지 자리입니다. 사진을 `assets/`에 넣고 `<img>`로 바꿉니다.

## 배포

- **Vercel**: vercel.com → Add New → Project → 이 레포 선택 → Deploy. 설정은 기본값 그대로 두면 됩니다.
- **GitHub Pages**: 레포 Settings → Pages → Source를 `Deploy from a branch`, Branch를 `main` / `(root)`로 저장합니다.

디자인 원본은 Figma 파일 "암모에너지 웹사이트 시안"의 "아모젠파워 메인" 페이지입니다.
