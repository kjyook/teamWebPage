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

### 정적 사이트 만들기

- 정적 사이트는 일종의 웹 문서로 프로그램 로직과 모듈화 개념이 없으므로 페이지 내용과 모양을 HTML과 CSS로 모두 만들어야 함

- 규모가 크고 공통된 부분이 있을 때 개발 효율성이 매우 안 좋음

- 규모가 크면 사이트의 관리와 업데이트가 매우 어렵고 비효율적임

- 정적 사이트를 효율적으로 만들기 위한 도구가 필요

---

### 정적 사이트 생성기(Static Site Generator; SSG)

- 쉽고 효과적인 방법으로 정적 사이트를 만들어 주는 도구

- 주로 마크업 언어, 템플릿과 모듈 기능을 기반으로 동일한 작업을 반복하지 않게 해주며 편집이 편리한 문서로부터 HTML을 생성해 줌

- 초기 개발 및 업데이트가 편리하고 효율적임

- 다양한 SSG 툴들이 존재 : Hugo, Jekyll, Gatsby, Hexo, Ghost, Astro, …

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