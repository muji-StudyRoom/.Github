![KakaoTalk_Image_2022-12-07-09-41-27](https://user-images.githubusercontent.com/73453283/206058999-38396216-f7cd-4e61-8f4e-40c6c14af4b4.png)

## EyesTalk
카카오클라우드 스쿨 개발자 1기 Final Project
WebRTC 화상통화 서비스 EyesTalk

## Overview
**Eyes Talk**은 비대면 시대에 맞춰 협업, 소통 등을 위한 다양한 기능을 제공하는 화상미팅 서비스입니다. 관심사에 맞는 회의 방을 만들어 소통해보세요!

### 프로젝트 기간 - 2022.11.01 ~ 2022.12.13
<br>
<br>
<br>

## EyesTalk 서비스 
### 방 생성
- 방 생성자는 방제목, 수용인원, 닉네임, 비밀번호를 입력하고 방을 생성할 수 있다
- 이때 수용인원은 4명 이하까지 설정이 가능하다
- 비디오와 마이크를 ON/OFF 설정하여 접속이 가능하다
<br>

![한자공부방생성](https://user-images.githubusercontent.com/73453283/205802622-0f3a8072-fdf0-42c6-a0c9-e678984abc3f.gif)

<br>

### 방 접속
- 방 제목을 선택하여 닉네임과 비밀번호를 입력하고 방을 접속할 수 있다
- 방에 동일한 닉네임이 있을경우 다른 닉네임으로 접속해야한다

<br>

### 메인기능
- 나가기
  - 방의 마지막 유저가 나갈 경우, 방이 자동으로 삭제된다
- 카메라 ON/OFF
- 사운드 ON/OFF
- 화면공유

<br>

### 화상채팅
- 전체 채팅이 가능하다
- 사용자를 지정하여 DM(Direct Message)을 보낼 수 있다


### 검색기능
- 생성된 방 목록중 방 제목을 입력하여 검색 할 수 있다
<br>

![검색기능](https://user-images.githubusercontent.com/73453283/205800531-1b77adab-a221-47f2-886a-219df6d15235.gif)
<br>

<br>
<br>
<br>

## 서비스 아키택쳐
![image](https://user-images.githubusercontent.com/73453283/206053042-111d4ef5-ed29-408b-8037-224a2d9319b2.png)

<br>

## 클라우드 아키텍쳐
![image](https://user-images.githubusercontent.com/73453283/206058652-2d2d6726-3461-4fd5-b6ab-94778d82ecbe.png)
<br>

## 유저 시나리오
![image](https://user-images.githubusercontent.com/73453283/206053395-d6f99e0c-e5b0-4949-b9c3-8deafa2afd24.png)
<br>
<br>

## 주요기술 및 라이브러리
#### Frontend Server
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/> <img src="https://img.shields.io/badge/react-61DAFB?style=flat-square&logo=react&logoColor=black"/> <img src="https://img.shields.io/badge/WebRTC_Socket.IO-007396?style=flat-square&logo=SocketIO&logoColor=white"/>

#### Backend Server [👉click](https://github.com/muji-StudyRoom/spring-back)
<img src="https://img.shields.io/badge/springboot-6DB33F?style=flat-square&logo=SpringBoot&logoColor=white"/> <img src="https://img.shields.io/badge/Swagger:3.0-47A248?style=flat-square&logo=Swagger&logoColor=white"/> <img src="https://img.shields.io/badge/JPA-F05032?style=flat-square&logoColor=white">

#### Signarling Server 
<img src="https://img.shields.io/badge/python-3776AB?style=flat-square&logo=python&logoColor=white"> <img src="https://img.shields.io/badge/flask-000000?style=flat-square&logo=flask&logoColor=white"> <img src="https://img.shields.io/badge/WebRTC_Socket.IO-007396?style=flat-square&logo=SocketIO&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-F80000?style=flat-square&logo=Redis&logoColor=white"> 

#### Ops   [👉click](https://github.com/muji-StudyRoom/eyestalk-manifest)
<img src="https://img.shields.io/badge/Amazon EKS-FF9900?style=flat-square&logo=Amazon-EKS&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2CA5E0?style=flat-square&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white"/> <img src="https://img.shields.io/badge/Kustomize-007396?style=flat-square&logo=#FF9900&logoColor=white"/> <img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=Argo&logoColor=white"/>
