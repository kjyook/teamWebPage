+++
title = "git cli 사용법 - 소스 관리와 branch"
date = "2015-08-03T13:39:46+02:00"
tags = ["programming"]
categories = ["programming"]
banner = "img/banners/banner-3.jpg"
summary="[Git](https://github.com) CLI 중 add, commit, push에 대한 소스 관리와 branch 사용법에 대해 알려드립니다."
+++

# 소스 관리
----
## 소스 상태
----
### 관리 대상 여부 확인하기
- tracked(추적대상): 관리 대상
- untracked(추적대상 아님): 관리 대상 아님
- 확인하는 방법: git status

### 관리 대상의 상태 확인하기
- committed : 버전관리에 안전하게 저장됨, snapshot
- staged : 커밋할 대상이라고 표시된 상태
- modified : 파일이 수정되었지만 staged 되지 않음
- tracked인 파일은 변경을 감지함
- untracked인 파일은 변경을 감지하지 않음
- untracked인 파일이 새로 생긴 것은 감지함

### 관리 대상으로 만들기
- git add <file 또는 디렉토리>  
    * untracked 파일을 tracked로 변경  
    * 동시에 staged로 변경  
    * 이미 tracked이고 modified인 경우 staged로 변경  
    * 디렉토리를 지정한 경우 하위의 모든 파일까지 변경  

- 예시)  
    * git add hello.py  
    * git status  

### Commit하기
- git commit
    * staged된 파일만 커밋할 수 있음  
    * 커밋 메시지 입력(필수)  
    * git commit -m "의미있는 메시지"  
    * git commit 후 편집기에서 입력  
    * git commit -a는 staged로 변경하고 커밋  

- 예시)  
    * git commit -m "hello.py 생성"  
    * git status  
    * git status --short 또는 git status -s    