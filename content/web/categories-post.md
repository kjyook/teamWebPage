+++
title = "Web Site"
date = "2023-05-22T21:29:20+02:00"
tags = ["programming", "theme", "hugo"]
categories = ["web"]
banner = "https://pbs.twimg.com/media/FYKkjkraUAAEL7j?format=jpg&name=large"
authors = ["souvenirs"]
+++

## 웹 사이트(Web Site)

---

### 정적 사이트(Static Site)

- 미리 작성된 웹페이지 파일들을 서비스하는 사이트

- 서버에서 프로그램 실행이 필요없이 HTML, CSS, JavaScript 파일들을 제공

- Web Server(HTTP Server) 필요

- 클라이언트 사이드의 동적 웹페이지도 정적 사이트에 포함

- 서버의 웹페이지를 수정하지 않는 한 항상 같은 페이지가 보임

- 개발이 쉽고 서비스의 속도가 빠름

- 예) www.kau.ac.kr

---

### 동적 사이트(Dynamic Site)

- 미리 만들어져 있는 페이지 파일을 서비스하는 것이 아니라 클라이언트의 요청에 따라 웹페이지를 만들어서 서비스

- 사이트의 내용이 수시로 그리고 사용자의 요청에 따라 다른 내용과 모양으로 만들어져 서비스

- (Web) Application Server 필요

- 개발이 어렵고 서비스 반응 속도가 느림

- 우리가 사용하는 대부분의 대규모 서비스 사이트

- 예) lms.kau.ac.kr

---

## 정적 사이트(Static Site)

---

### 정적 사이트 만들기

- 정적 사이트는 일종의 웹 문서로 프로그램 로직과 모듈화 개념이 없으므로 페이지 내용과 모양을 HTML과 CSS로 모두 만들어야 함

- 규모가 크고 공통된 부분이 있을 때 개발 효율성이 매우 안 좋음

- 규모가 크면 사이트의 관리와 업데이트가 매우 어렵고 비효율적임

- 정적 사이트를 효율적으로 만들기 위한 도구가 필요

---