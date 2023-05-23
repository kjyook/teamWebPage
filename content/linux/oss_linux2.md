+++
title = "Open Source-Linux"
date = "2023-05-23"
tags = ["linux", "programming", "os"]
categories = ["linux"]
banner = "img/banners/banner-4.jpg"
authors = ["KJJ"]
+++

 
  ### Linux 기본 명령2

   #### 파일 속성 수정

    chown : 파일의 소유자 수정
    chmod : 파일의 권한 수정

   #### 파일 다루기 

     mkdir : 디렉토리 만들기
     rmdir : 디렉토리 지우기
     cp : 복사
     touch : 빈 파일 만들기
     mv : 파일이나 디렉토리를 옮기거나 이름을 변경
     rm : 지우기 파일이나 디렉토리를 지울 수 있(강력한 옵션 ; rm -rf <파일 또는 디렉토리 이름>)
     find : 파일 찾기 (find / -name 문자열)
     which : 경로에 있는 파일 찾기
     tree : 디렉토리를 트리모양으로 보기

  #### 텍스트 파일 보기
   
    more
    cat
    head [-n 줄수]: 맨 앞의 10줄만 보기[ -n에 설정한 줄 수 만큼 보기 ]
    tail [-n 줄수]: 맨 뒤의 10줄만 보기 [ -n에 설정한 줄 수 만큼 보기 ]
    grep : 지정된 문자열이 포함된 행만 표시

 #### 주요 디렉토리 및 파일

    /etc : 시스템 환경 설정에 대한 파일들이 저장된 디렉토리
    /etc/passwd : 사용자 계정
    /etc/group : 사용자 그룹
    /etc/os-release : 배포판 버전 정보
    ~/.bashrc : bash 설정 파일
    /tmp : 임지 파일들을 저장하는 디렉토리
    /etc/apt/soruces.list : 패키지 저장소 목록을 저장

 #### 파이프

 ps : 프로세스를 보는 명령, 현재 셸의 실행 프로세스 표시

    ps -ef : 현재 시스템에서 실행 중인 모든 프로세스 목록 표시
    ps -ef | grep python : python 이란 문자열이 있는 프로세스 행 표시

 #### 주요 시스템 명령

    uname : os 정보 보기 (uname -a)
    cat /etc/os-release : 배포판 정보 보기
    id : 사용중인 계정에 대한 정보
    uptime : 실행된 시간
    last reboot : 부팅된 시간
    ip addr : ip 주소 보기

   #### 패키지 완리 (Ubuntu, Debian)

   apt : 패키지 관리 명령(관리자 권한 필요)
     
     sudo apt update : 패키지 목록 업데이트
     sudo apt upgrade : 설치된 패키지(소프트웨어)들을 최신 버전으로 업그레이드
     sudo apt install <설치할 패키지 이름> : 패키지 설치

   



   










