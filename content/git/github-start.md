+++
title = "GitHub 시작하기"
date = "2015-08-03T13:39:46+02:00"
tags = ["programming"]
categories = ["programming"]
banner = "img/banners/banner-3.jpg"
summary="git을 기반으로 한 원격 저장소 호스팅 서비스 [GitHub](https://github.com)를 시작하기. SSH key를 등록하고, 저장소를 만들고, git clone 명령어를 이용합니다."
+++

## SSH key 등록하기
1. 오른쪽 위 프로필  
2. settings  
3. SSH and GPG keys   
4. New SSH key 등록  
```
cat id_rsa.pub
```
자신의 SSH key의 public 파일을 복사해서 등록하기

***

## 저장소 만들기
1. 오른쪽 위 +  
2. New repository 

***

## git clone
1. Clone URL 복사 
```
git clone git@github.com:[GitHub 아이디]/[repository 이름].git
``` 
2. 내 PC(WSL)에서 작업  
    * 저장소와 연결할 위치의 상위 폴더에서  
    * git clone [URL] 
    * 확인:  
        - cd [repository 이름] 
        - ll or tree  
    * 원격저장소 확인 :
        - git remote -v
