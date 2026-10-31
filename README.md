# (주)아모젠파워 웹사이트

아모젠파워 회사 소개 사이트입니다. 빌드 과정이 없는 정적 사이트(HTML + CSS)라서 Vercel, Netlify, GitHub Pages 어디에나 그대로 배포할 수 있습니다.

## 파일 구성

- `index.html`: 메인 페이지 (회사소개, 대표 인사말, 개발사업, 핵심기술, 개발로드맵, 문의)
- `greeting.html`: 예전 대표 인사말 주소. 메인 페이지의 인사말 위치로 자동 이동합니다.
- `privacy.html`: 개인정보처리방침
- `assets/styles.css`: 디자인 스타일
- `assets/favicon.svg`: 브라우저 탭 아이콘

## 자주 바꾸는 곳

- **연락처**: `index.html`에서 `contact@ammogenpower.co.kr`, `010-0000-0000`을 실제 값으로 바꿉니다. (현재 임시 값)
- **이미지**: 모든 사진은 `assets/images/`에 있습니다. 같은 파일 이름으로 덮어쓰면 코드를 고치지 않아도 바뀝니다. 지금 들어간 사진은 와이어프레임 시안에서 잘라 온 임시 이미지입니다.

  | 파일 | 위치 | 권장 크기 |
  |---|---|---|
  | `hero.jpg` | 맨 위 큰 이미지 | 1600×1100 이상 |
  | `about.jpg` | 회사소개 오른쪽 | 1200×1200 이상 |
  | `business-1.jpg` ~ `business-3.jpg` | 개발사업 카드 3개 | 1000×600 이상 |
  | `tech-1.png` ~ `tech-4.png` | 핵심기술 아이콘 (흰색, 투명 배경) | 160×160 |
  | `roadmap-1.jpg` ~ `roadmap-4.jpg` | 개발 로드맵 4단계 (흰 배경 제품 사진) | 600×400 이상 |
  | `logo-mark.png` | 헤더·푸터 로고 심볼 (투명 배경) | 144×144 이상 |

## 배포

- `assets/styles.css`를 고치면 `index.html`, `privacy.html`의 `styles.css?v=숫자`도 하나 올려 주세요. 방문자 브라우저가 예전 디자인을 기억하지 않고 바로 새 디자인을 받습니다.

- **Vercel**: vercel.com → Add New → Project → 이 레포 선택 → Deploy. 설정은 기본값 그대로 두면 됩니다.
- **GitHub Pages**: 레포 Settings → Pages → Source를 `Deploy from a branch`, Branch를 `main` / `(root)`로 저장합니다.

디자인 원본은 Figma 파일 "암모에너지 웹사이트 시안"의 "아모젠파워 메인" 페이지입니다.
