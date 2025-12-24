# homedodo — 2025 Christmas Home Party Guide

이 저장소에는 발표용 HTML 파일 `home.html`이 포함되어 있습니다. 외부에서 브라우저로 바로 열어 볼 수 있도록 아래 방법들을 정리했습니다.

## 1) 빠른 링크 (정적 파일 링크)
- 소스(특정 커밋) HTML 파일(읽기 전용):
  - https://github.com/deh0304-do/homedodo/blob/a2b2599772236fbccbfc36ca90c48fd837d0c3be/home.html
- 같은 파일의 raw 버전(브라우저에 따라 바로 열리거나 내용이 텍스트로 보일 수 있음):
  - https://raw.githubusercontent.com/deh0304-do/homedodo/a2b2599772236fbccbfc36ca90c48fd837d0c3be/home.html

> 참고: raw.githubusercontent.com 링크는 파일의 실제 내용을 내려받아 보여줍니다. 일부 브라우저는 보안 정책상 HTML을 렌더링하지 않고 텍스트로 표시할 수 있습니다.

## 2) 권장 — GitHub Pages로 호스팅 (외부에서 HTML을 그대로 렌더링)
1. 저장소의 Settings → Pages로 이동합니다.
2. "Source" 또는 "배포" 섹션에서 브랜치(예: `main` 또는 `gh-pages`)와 `/ (root)` 디렉터리를 선택하고 저장합니다.
3. 설정 후 제공되는 퍼블릭 URL은 일반적으로 다음 형식입니다:
   - https://<GitHub사용자명>.github.io/<저장소명>/
   예시: https://deh0304-do.github.io/homedodo/
4. 위 URL에 `home.html`을 붙이면 외부에서 바로 접속 가능한 페이지가 됩니다:
   - https://deh0304-do.github.io/homedodo/home.html

주의: Pages가 활성화되기까지 몇 분이 걸릴 수 있습니다. 만약 페이지가 404를 반환하면 브랜치와 경로 설정을 확인하세요.

## 3) 로컬에서 미리보기 (개발용)
- 간단한 Python HTTP 서버를 사용:
  1. 저장소 루트에서 터미널 실행
  2. Python 3인 경우: `python -m http.server 8000`
  3. 브라우저에서 `http://localhost:8000/home.html` 열기

- VSCode의 Live Server 확장 같이 정적 파일을 서비스하는 툴을 사용해도 좋습니다.

## 4) 권한 및 CORS 관련 참고
- GitHub Pages는 정적 호스팅을 제공하므로 CORS 문제 없이 외부에서 HTML/CSS/JS가 정상 동작합니다.
- 만약 외부 스크립트(CDN 등)를 차단하는 환경이라면 내부 리소스로 대체가 필요할 수 있습니다.

## 5) 추가 요청
- 원하시면 제가 바로 `README.md` 파일을 저장소 루트에 추가해 드립니다. (자동으로 GitHub Pages 설정은 변경하지 않습니다.)

---

작성자: deh0304-do
파일: README.md
