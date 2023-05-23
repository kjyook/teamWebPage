+++
title = "Open Source-Linux"
date = "2023-05-23"
tags = ["linux", "programming", "os"]
categories = ["linux"]
banner = "img/banners/banner-4.jpg"
authors = ["KJJ"]
+++

Linux = LInux Kernel 기반의 오픈 소스 Unix 계열 운영체제들을 의미함 (Wikipedia)


 운영 체제(OS; operating system)의 구성 : kernel, library, utilities, user interface -> 4 가지

 OS Kernel = 운영체제의 핵심 -> 하드웨어 관리 및 프로그램 실행
 커널의 기능 4가지 -> 메모리 관리, 프로세스 관리, 장치 드라이버, 시스템 호출 및 보안 

 
  ### Linux 기본 명령1

   #### 셸
    셸 확인 : ps
    셸 변경 : 셸 프로그램 실행 
    셸 탈출 : exit

   #### 파일 보기
     ls, ls -a, ls -l, ll = 파일 목록 보기
     . = 현재 디렉토리
     .. = 상위(부모) 디렉토리
     .으로 시작되는 파일 = 숨김 파일

   파일 종류 = 파일, 디렉토리, 링크, 파이프

   #### 파일 권한 (파일 모드)
    총 9글자 -> owser 3글자/group 3글자/other 3글자 
    읽기 = r, 쓰기 = w, 실행 = x
    2진수 값 -> 허용 = 1. 금지 = 0
    예시- rwx : 7, --- : 0, 

   #### 디렉토리
   루트 디렉토리 : 모든 디렉토리의 출발점
   디렉토리 위치 : 절대 경로(루트 디렉토리 부터), 상대 경로(현재 디렉토리부터)

     / : 루트 디렉토리
     ~ : 홈 디렉토리
     .. : 상위 디렉토리
     . : 현재 디렉토리


  이동 : cd (읽기 권한이 없으면 이동할 수 없음)

    cd<경로> : <경로>로 이동
    cd.. : 상위로 이동
    cd 또는 cd~ : 홈 디렉토리로 이동
    cd ~ : 이전에 있던 디렉토리로 이동
    현재 위치 확인 : pwd

