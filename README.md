# himnuszkorea.github.io

GitHub Pages 사용자 사이트(도메인 루트). 하는 일은 셋뿐이다.

- **첫 화면** `index.html` — 들어오면 곧바로 [산재맵](https://himnuszkorea.github.io/sanjaemap/)(저장소 `himnuszkorea/sanjaemap`)으로 넘긴다(2026-10-20 — 전엔 「산재맵 열기」 안내 페이지였다). 본문 안내는 자바스크립트·refresh 가 안 될 때의 대비로 남겨 둔다.
- **네이버 서치어드바이저 소유 확인** — 네이버는 하위 경로(`/sanjaemap`) 등록을 받지 않아(「URL을 호스트 단위로 입력해주세요」) 이 루트로 등록했다. `index.html` 의 `naver-site-verification` 태그를 지우면 확인이 풀린다.
- **`robots.txt` · `sitemap.xml`** — robots.txt 는 도메인 루트에만 둘 수 있다. 사이트맵은 산재맵 주소 하나만 담는다(루트는 넘김 페이지라 뺐다, 10-20).

산재맵 숫자(6,742곳·220곳)가 바뀌면 이 첫 화면도 같이 고친다.

## 딸린 페이지(검색 제외 · 사이트맵 미등록)

- `/subsidy-nav/` — 지원금 내비게이션 모의계산기(10-23). 원본은 `사외공모전/계획/A21_KEAD규제개선/모의계산기/`.
- `/kimst-demo/` — KIMST 공모전 제안 「내 과제 판본 찾기」 정산 규정 상담 시연판(11-05, 개인 제안 · KIMST 공식 아님). 원본은 `사외공모전/계획/D08_KIMST혁신아이디어/시연판/`(`build.py` 로 만든 `index.html` 을 복사).
