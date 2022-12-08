
![image](https://user-images.githubusercontent.com/73453283/206095042-0c6237e1-bfc8-4915-a6eb-6ace8875befa.png)

# EyesTalk
- 카카오클라우드 스쿨 개발자 1기 Final Project 입니다 
- EyesTalk은 WebRTC 기술을 사용한 화상통화 서비스 입니다
- 비대면 시대에 맞춰 협업, 소통 등을 위한 다양한 기능을 제공하는 `화상미팅 서비스 EyesTalk`에서 관심사에 맞는 회의 방을 만들어 소통해보세요!

> #### 프로젝트 개발 기간 : 2022.11.01 ~ 2022.12.13

<br>

## 👀 EyesTalk 서비스 
### 방 생성
- 방 생성자는 방제목, 수용인원, 닉네임, 비밀번호를 입력하고 방 생성
- 이때 수용인원은 4명 이하까지 설정 가능
- 비디오와 마이크를 ON/OFF 설정하여 접속 가능 
<br>

![2022-12-08 09 11 50](https://user-images.githubusercontent.com/73453283/206324854-0251d303-19dd-43b8-a682-1008df37d375.gif)


<br>

### 방 접속
- 방 제목을 선택하여 닉네임과 비밀번호를 입력하고 방 접속
- 방에 동일한 닉네임이 있을경우 다른 닉네임으로 접속
<br>

![2022-12-08 09 21 50](https://user-images.githubusercontent.com/73453283/206325918-7a90fa9a-ce70-446e-8042-a0c300777ff9.gif)



<br>

### 메인기능
- 카메라 ON/OFF
- 사운드 ON/OFF
- 화면공유
- 나가기
  - 방의 마지막 유저가 나갈 경우, 방이 자동으로 삭제 

![2022-12-07 15 21 31-min](https://user-images.githubusercontent.com/73453283/206104753-8e6a2534-5139-4aa0-84b6-a96dc8d5e13e.gif)

<br>

### 화상채팅
- 전체 채팅 전송 
- 사용자를 지정하여 DM(Direct Message) 전송 


### 검색기능
- 생성된 방 목록중 방 제목을 입력하여 검색
- 전체보기를 누르면 최신 생성 순으로 정렬된다

<br>

![2022-12-07 14 39 20](https://user-images.githubusercontent.com/73453283/206097669-8ded328f-da61-4a68-a1f9-45a01fc3c05c.gif)

<br>

<br>
<br>
<br>

## 👀 서비스 아키택쳐
![image](https://user-images.githubusercontent.com/73453283/206053042-111d4ef5-ed29-408b-8037-224a2d9319b2.png)

<br>

## 👀 클라우드 아키텍쳐
![image](https://user-images.githubusercontent.com/73453283/206058652-2d2d6726-3461-4fd5-b6ab-94778d82ecbe.png)
<br>

## 👀 유저 시나리오
![image](https://user-images.githubusercontent.com/73453283/206053395-d6f99e0c-e5b0-4949-b9c3-8deafa2afd24.png)
<br>
<br>

## 👀 주요기술 및 라이브러리
#### Frontend Server [👉click](https://github.com/muji-StudyRoom/react-front)
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/> <img src="https://img.shields.io/badge/react-61DAFB?style=flat-square&logo=react&logoColor=black"/> <img src="https://img.shields.io/badge/WebRTC-007396?style=flat-square&logo=webrtc&logoColor=white"/> <img src="https://img.shields.io/badge/Socket.Io-010101?style=flat-square&logo=Socket.IO&logoColor=white"/>

#### Backend Server [👉click](https://github.com/muji-StudyRoom/spring-back)
<img src="https://img.shields.io/badge/springboot-6DB33F?style=flat-square&logo=SpringBoot&logoColor=white"/> <img src="https://img.shields.io/badge/Swagger:3.0-47A248?style=flat-square&logo=Swagger&logoColor=white"/> <img src="https://img.shields.io/badge/JPA-F05032?style=flat-square&logoColor=white"> <img src="https://img.shields.io/badge/MariaDB-007396?style=flat-square&logo=mariadb&logoColor=white"/> 

#### Signaling Server [👉click](https://github.com/muji-StudyRoom/server-python)
<img src="https://img.shields.io/badge/python-3776AB?style=flat-square&logo=python&logoColor=white"> <img src="https://img.shields.io/badge/flask-000000?style=flat-square&logo=flask&logoColor=white"> <img src="https://img.shields.io/badge/Redis-F80000?style=flat-square&logo=Redis&logoColor=white"> <img src="https://img.shields.io/badge/Socket.Io-010101?style=flat-square&logo=Socket.IO&logoColor=white"/> <img src="https://img.shields.io/badge/Elasticsearch-7952B3?style=flat-square&logo=Elasticsearch&logoColor=white"/>

#### Ops   [👉click](https://github.com/muji-StudyRoom/eyestalk-manifest)
<img src="https://img.shields.io/badge/Docker-2CA5E0?style=flat-square&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white"/> <img src="https://img.shields.io/badge/Kustomize-007396?style=flat-square&logo=#FF9900&logoColor=white"/> <img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=Argo&logoColor=white"/> <img src="https://img.shields.io/badge/Amazon CloudWatch-FF4F8B?style=flat-square&logo=Amazon CloudWatch&logoColor=white"/> <img src="https://img.shields.io/badge/Amazon EKS-000000?style=flat-square&logo=Amazon-EKS&logoColor=white"/> <img src="https://img.shields.io/badge/Amazon ECS-FF9900?style=flat-square&logo=Amazon ECS&logoColor=white"/> <img src="https://img.shields.io/badge/Kibana-7952B3?style=flat-square&logo=Kibana&logoColor=white"/> 


