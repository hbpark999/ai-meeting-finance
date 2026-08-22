# 전자파 AI 연구반 교육행사 비용 시뮬레이터

GitHub Pages와 Notion Embed에 바로 사용할 수 있는 정적 HTML 계산기입니다.

## GitHub Pages 배포

1. GitHub에 새 저장소를 만듭니다.
2. 이 폴더의 `index.html`, `.nojekyll`, `README.md`를 저장소 루트에 올립니다.
3. 저장소의 `Settings` > `Pages`에서 배포 소스를 `Deploy from a branch`로 선택합니다.
4. Branch를 `main` / root로 지정합니다.
5. 발급된 `https://사용자명.github.io/저장소명/` 주소를 Notion에서 `/embed`로 넣습니다.

## Notion 연결

Notion 페이지에서 `/embed`를 입력한 뒤 GitHub Pages URL을 붙여 넣으면 계산기가 페이지 안에 표시됩니다.

멤버 전용으로 운영하려면 Notion 페이지 권한은 멤버만 보이도록 제한하고, 계산기 URL은 외부에 공유하지 않는 방식으로 1차 운영할 수 있습니다. 더 강한 접근 제한이 필요하면 Vercel과 로그인/비밀번호 방식을 쓰는 편이 좋습니다.
