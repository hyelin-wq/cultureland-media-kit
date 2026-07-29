# 2026 컬쳐랜드 광고 상품 소개서 — GitHub Pages 배포 가이드

이 폴더(`index.html` + `pages/` 폴더)를 그대로 GitHub 저장소에 올리면, 고정된 URL로 언제든 열람 가능한 웹페이지가 됩니다.

## 최초 배포 (1회만)

1. github.com 에서 새 저장소(Repository) 생성 (예: `cultureland-media-kit`), Public 또는 Private 선택
2. 이 폴더 안의 모든 파일(`index.html`, `pages/` 폴더 전체, 이 README)을 저장소에 업로드
   - GitHub 웹사이트에서 "Add file → Upload files"로 드래그 앤 드롭 가능
3. 저장소 메뉴 Settings → Pages 이동
4. "Branch"를 `main` (또는 `master`), 폴더는 `/root`로 설정 후 Save
5. 1~2분 후 상단에 표시되는 주소로 접속 확인
   - 형식: `https://[깃허브계정].github.io/cultureland-media-kit/`
   - 이 주소가 앞으로 고정 URL이 됩니다.

## 이후 내용 변경 시

- 텍스트/가격 등 내용이 바뀌면 해당 페이지 PDF를 다시 이미지로 변환해 `pages/page-XX.jpg`만 교체하고 재업로드하면 됩니다.
- 파일명과 폴더 구조만 유지하면 URL은 절대 바뀌지 않습니다.
- 페이지가 추가/삭제되는 경우에는 `index.html`의 목차(sections) 부분만 같이 수정이 필요합니다 (이 부분은 요청 주시면 반영해 드립니다).

## 참고

- Private 저장소도 GitHub Pages 사용 가능하나, 요금제에 따라 제한이 있을 수 있어 조직의 GitHub 플랜을 확인해 주세요.
- 사내 보안상 외부 공개가 어렵다면 GitHub Pages 대신 사내 웹서버의 동일 폴더 구조에 그대로 올려도 같은 방식으로 동작합니다.
