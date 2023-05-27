+++
title = "소스 관리: add, commit, 복구"
date = "2023-05-27"
tags = ["git"]
categories = ["git"]
banner = "img/banners/git-iresy-banner-2.jpg"
summary="git 소스를 관리하기. add, commit 등의 명령어와 branch에 대해 이해합니다."
author = ["iresy"]
+++

## 관리 대상으로 만들기
```
git add [file 또는 디렉토리]
```
* untracked 파일을 tracked로 변경
* 동시에 staged로 변경
* 이미 tracked이고 modified인 경우 staged로 변경
* 디렉토리를 지정한 경우 하위의 모든 파일까지 변경

***

## Commit하기
* git commit
* staged된 파일만 커밋할 수 있음
* 커밋 메시지 입력(필수)
```
git commit -m "의미있는 메시지"  
```
* git commit 후 편집기에서 입력  
* git commit -a는 staged로 변경하고 커밋

***

## 복구
### 되돌리기
* 버전 관리 시스템이므로 과거의 스냅샷으로 되돌릴 수 있음, 즉 잘 못 수정된 것을 얼마든지 되돌릴 수 있음
* 하지만 잘 못 되돌린 것은 다시 되돌릴 수 없으므로 되돌리는 작업은 각별한 주의를 요함
### 완료한 커밋 수정
```
git commit --amend //커밋 재작성
```
* 수정을 한 후 하나의 커밋으로 기록됨
### 파일 상태를 unstage로 변경
```
git reset HEAD <파일>
```
### stage되지 않은 파일을 되돌리기
```
git checkout -- <file>
```
### Modified 파일을 되돌리기
```
git checkout -- <file>
```
* 수정한 내용이 모두 사라지므로 주의 해서 사용
* 브랜치를 사용해야 함
### 이전 커밋으로 되돌리기
* 마지막 커밋을 취소
```
git revert <되돌리고 싶은 커밋 이름>
```
* 특정 커밋으로 이동
```
git reset --hard <이동하려는 이전 커밋 이름>
```
* 협업을 할 경우 되돌리기를 주의해야 하며, 자신만의 브랜치를 만들어서 하는 것이 좋음

***

## branch
### branch란?
* 코드를 통째로 복사해서 독립적으로 개발
* 새로운 작업은 브랜치를 만들어서 하고 완성되면 합병
* 어떻게 브랜치를 만들고 합병할 지 전략 필요
    - 브랜치 워크플로
### branch 명령
```
git branch : 브랜치 보기
git branch <새 브랜치 이름> : 브랜치 만들기
git checkout <브랜치 이름> : 브랜치 이동
git checkout -b <새 브랜치 이름> : 브랜치를 만들고 이동
git merge : 브랜치 합병
git log --oneline --decorate --graph --all : 로그에 브랜치가 잘 나타나게 표시
git branch -d <브랜치 이름> : 브랜치 삭제
```