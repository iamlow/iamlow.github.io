---
layout: post
title:  "Windows 10과 Ubuntu 16.04.02 LTS 듀얼부팅"
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
    - Ubuntu 16.04.02 LTS 설치
        - 파티션 설정시(Installation type 메뉴) ->  **Install Ubuntu alongside Windows Boot Manager**

  ![spring_in_action](http://image.kyobobook.co.kr/images/book/large/388/l9791185890388.jpg)

- 스프링부트 코드공작소(Spring Boot in Action)

  ![spring_boot_in_action](http://image.kyobobook.co.kr/images/book/large/534/l9791187345534.jpg)
  - IDE를 STS를 설치하여 사용함
    - Spring Boot 예제를 테스트하기 위하여 Eclipse와 Buildship Plugin 간에 호환성 문제로 인하여 Stable 버전이 아닌 Nightly 버전응 사용함.
    - 참고: [https://github.com/spring-projects/spring-ide/issues/90](https://github.com/spring-projects/spring-ide/issues/90)
  - Grails 예제를 테스트 하기 위하여 GGTS를 설치하였으나, 버전이 2.4라서 사용못함.
-  Java 8 in Action

  ![java8_in_action](http://image.kyobobook.co.kr/images/book/large/796/l9788968481796.jpg)
