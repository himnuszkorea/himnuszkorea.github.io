# himnuszkorea.github.io

GitHub Pages 사용자 사이트(도메인 루트). 하는 일은 셋뿐이다.

- **첫 화면** `index.html` — 들어오면 곧바로 [산재맵](https://himnuszkorea.github.io/sanjaemap/)(저장소 `himnuszkorea/sanjaemap`)으로 넘긴다(2026-10-20 — 전엔 「산재맵 열기」 안내 페이지였다). 본문 안내는 자바스크립트·refresh 가 안 될 때의 대비로 남겨 둔다.
- **네이버 서치어드바이저 소유 확인** — 네이버는 하위 경로(`/sanjaemap`) 등록을 받지 않아(「URL을 호스트 단위로 입력해주세요」) 이 루트로 등록했다. `index.html` 의 `naver-site-verification` 태그를 지우면 확인이 풀린다.
- **`robots.txt` · `sitemap.xml`** — robots.txt 는 도메인 루트에만 둘 수 있다. 사이트맵은 산재맵 주소 하나만 담는다(루트는 넘김 페이지라 뺐다, 10-20).

산재맵 숫자(6,742곳·220곳)가 바뀌면 이 첫 화면도 같이 고친다.
