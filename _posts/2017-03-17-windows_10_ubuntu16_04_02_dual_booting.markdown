---
layout: post
title:  "Windows 10과 Ubuntu 16.04.02 LTS 듀얼부팅(UEFI)"
date:   2017-03-17 09:24:00 +0900
categories: application
---
- UEFI용 OS 설치용 USB 만들기
    - [Rufus](https://rufus.akeo.ie/)를 사용하여 OS 설치용 USB 만들기
    - **디스크 형식과 부팅 시스템 유형** -> **GPT 파티션 형식의 UEFI 컴퓨터**로 설정<br>
        (Windows10 과 Ubuntu 16.04.02 LTS 공통설정사항)        
    - Windows 10용과 Ubuntu 16.04.02 LTS용 USB 생성
- BIOS 설정
    - **Secure Boot** -> **Disabled**
    - **UEFI Only**
    - **CSM -> Disabled**
- OS 설치
    - Windows 10 설치
        - 설치 시 또는 설치 후 Ubuntu를 설치할 공간을 확보해 놓아야 한다.
    - Ubuntu 16.04.02 LTS 설치
        - 파티션 설정시(Installation type) ->  **Install Ubuntu alongside Windows Boot Manager**
        - 인터넷을 검색해 보면 위 설정으로 설치하면 Grub2에서 Windows10으로 멀티부팅이 안된다는 글들을 볼 수 있는데, 이것은 Secure Boot 설정때문인 것으로 판단된다.
