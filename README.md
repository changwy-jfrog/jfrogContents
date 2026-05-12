# JFrog Curation & Xray — Animated Demo

JFrog Curation과 Xray가 어떻게 서로 다른 보안 계층에서 동작하는지를 보여주는 인터랙티브 애니메이션입니다.
An interactive animation illustrating how JFrog Curation and Xray operate as two distinct security layers.

## Live Demos

### Animation
- 🇰🇷 한국어판: <https://changwy-jfrog.github.io/jfrogContents/Curation%20vs%20Xray.html>
- 🇬🇧 English: <https://changwy-jfrog.github.io/jfrogContents/Curation%20vs%20Xray%20-%20EN.html>

### Still (단일 정지 화면)
- 🇰🇷 한국어판: <https://changwy-jfrog.github.io/jfrogContents/Curation%20vs%20Xray%20-%20Still.html>
- 🇬🇧 English: <https://changwy-jfrog.github.io/jfrogContents/Curation%20vs%20Xray%20-%20Still%20-%20EN.html>

### Concept Diagrams (PNG)
- [1. Before vs After](https://changwy-jfrog.github.io/jfrogContents/1.%20Before%20vs%20After.png)
- [2. Attack Defense](https://changwy-jfrog.github.io/jfrogContents/2.%20Attack%20Defense.png)
- [3. Workflow Timeline](https://changwy-jfrog.github.io/jfrogContents/3.%20Workflow%20Timeline.png)
- [4. CVE Disclosure](https://changwy-jfrog.github.io/jfrogContents/4.%20CVE%20Disclosure.png)
- [5. Integrated Architecture](https://changwy-jfrog.github.io/jfrogContents/5.%20Integrated%20Architecture.png)

> GitHub Pages로 호스팅되는 실제 재생 페이지입니다. 저장소 내 `.html` 파일을 직접 클릭하면 소스 코드 뷰로 열리니, 위 링크를 사용해 주세요.

## Story

- **Curation — Door Guard**: 외부 패키지가 저장소에 들어오기 전에 정책에 따라 차단합니다.
- **Xray — Internal Patrol**: 이미 저장된 아티팩트를 지속적으로 스캔하고, 새로운 CVE가 공개되면 영향받는 패키지를 즉시 식별합니다.

## Tech

- Pure HTML + CSS + Vanilla JavaScript (no build, no framework)
- 1600×900 고정 스테이지가 뷰포트에 맞춰 자동 스케일링
- Open Sans Variable Font (포함)

## License

Internal demo asset for JFrog presentation use.
