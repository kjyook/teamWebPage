+++
title = "Markdown syntax"
date = "2023-05-21T21:29:20+02:00"
tags = ["go"]
categories = ["web"]
banner = "https://t1.daumcdn.net/cfile/tistory/164662504F576B8112"
facebook_author = "GolangSociety"
+++

## 정적 사이트(Static Site)

---

### 정적 사이트 생성기(Static Site Generator; SSG)

- 쉽고 효과적인 방법으로 정적 사이트를 만들어 주는 도구

- 주로 마크업 언어, 템플릿과 모듈 기능을 기반으로 동일한 작업을 반복하지 않게 해주며 편집이 편리한 문서로부터 HTML을 생성해 줌

- 초기 개발 및 업데이트가 편리하고 효율적임

- 다양한 SSG 툴들이 존재 : Hugo, Jekyll, Gatsby, Hexo, Ghost, Astro, …

---

### Hugo

- Go 언어로 만들어진 정적 사이트 생성기

- 빌드 속도가 빠름

- 많은 테마(Theme)

---

### Jekyll

- Ruby 언어로 만들어진 정적 사이트 생성기

- GitHub에서 지원(자동 배포)

- 빌드 속도가 느림

---

### Gatsby

- React+Graphql 기반의 정적 사이트 생성기

- Graphql을 이용한 데이터 관리 기능

- 빌드 속도가 느림

---

## 개인 웹사이트

---

### 개인 웹사이트 만들기

- Hugo SSG를 이용

- Developer Portfolio Theme을 사용

---

### 개인 웹사이트 퍼블리싱

- GitHub Pages의 개인 페이지 이용

- 로컬저장소에 서브모듈 추가

- Theme과 퍼블리싱용 디렉토리를 서브모듈로 추가

---