
![image](https://user-images.githubusercontent.com/73453283/206095042-0c6237e1-bfc8-4915-a6eb-6ace8875befa.png)

# EyesTalk
- 카카오클라우드 스쿨 개발자 1기 Final Project 입니다 
- EyesTalk은 WebRTC 기술을 사용한 화상통화 서비스 입니다
- 비대면 시대에 맞춰 협업, 소통 등을 위한 다양한 기능을 제공하는 `화상미팅 서비스 EyesTalk`에서 관심사에 맞는 회의 방을 만들어 소통해보세요!

> #### 프로젝트 개발 기간 : 2022.11.01 ~ 2022.12.13

<br>

## 👀 EyesTalk 서비스 
### 방 생성
- 방 생성자는 방이름, 수용인원, 닉네임, 비밀번호를 입력하고 방 생성
- 동일한 방의 이름으로 생성 될 수 없다 
- 수용인원은 4명 이하까지 설정 가능하다
- 비디오와 마이크를 ON/OFF 설정하여 접속 가능하다
<br>

![2022-12-09 13 46 44](https://user-images.githubusercontent.com/73453283/206626183-f8c82496-a0e5-4785-924d-6584e04b7a73.gif)


<br>

### 방 접속
- 방 제목을 선택하여 닉네임과 비밀번호를 입력하고 방 접속
- 방에 동일한 닉네임이 있을경우 다른 닉네임으로 접속
<br>

![2022-12-09 13 59 51](https://user-images.githubusercontent.com/73453283/206627850-94fc90b4-767e-4fd7-abce-b927e0017ff5.gif)




<br>

### 메인기능
- 카메라 ON/OFF
- 사운드 ON/OFF
- 화면공유
- 나가기
  - 방의 마지막 유저가 나갈 경우, 방이 자동으로 삭제 


![2022-12-09 14 14 14-min](https://user-images.githubusercontent.com/73453283/206630200-c2710cf4-d910-4c38-b739-6a6953163c9d.gif)


<br>

### 화상채팅
- 전체 채팅 전송 
- 사용자를 지정하여 DM(Direct Message) 전송 

<br>



### 검색기능
- 생성된 방 목록중 방 제목을 입력하여 검색
- 전체보기를 누르면 최신 생성 순으로 정렬된다

<br>

![2022-12-09 14 38 20](https://user-images.githubusercontent.com/73453283/206632148-d31c499b-a26f-4fdd-9bde-7714559434bb.gif)

<br>

<br>
<br>
<br>

## 👀 서비스 아키택쳐
![image](https://user-images.githubusercontent.com/73453283/207783670-1ffd9269-aa48-4341-aaac-f523a9d02f03.png)

<br>

## 👀 클라우드 아키텍쳐
![image](https://user-images.githubusercontent.com/73453283/207783929-2c16b559-7d64-4a91-9637-b68781910f70.png)
<br>

## 👀 유저 시나리오
![image](https://user-images.githubusercontent.com/73453283/206335547-11a53cb2-01fb-41fc-8902-3a9b761b97c7.png)


<br>
<br>

<br>

## 👀 EyesTalk
![image](https://user-images.githubusercontent.com/73453283/207780771-0d6f4ad1-6f8d-44f5-9013-9b3034d1b5e8.png)
![image](https://user-images.githubusercontent.com/73453283/207780868-3adcfc57-a486-49f3-8219-23e99ec7bacf.png)
![image](https://user-images.githubusercontent.com/73453283/207781154-e8df5bd1-4010-491a-abeb-323ae7179fd0.png)
![image](https://user-images.githubusercontent.com/73453283/207781176-cc1bb57a-a7c0-4e9f-af56-74883f2d358d.png)
![image](https://user-images.githubusercontent.com/73453283/207780986-08ee49d8-dac3-4cf4-9fce-dea2c012ae97.png)
![image](https://user-images.githubusercontent.com/73453283/207780955-32ef8152-6881-4ef3-a227-89b73888db9b.png)
![image](https://user-images.githubusercontent.com/73453283/207781235-7f8baea7-066a-4b94-81e2-403a8719bbc4.png)
![image](https://user-images.githubusercontent.com/73453283/207781440-cfaaff7a-d914-4f1f-969e-ec1f1d8459e3.png)
![image](https://user-images.githubusercontent.com/73453283/207781797-7cabdfea-d104-4f17-b24f-c64e0d75462d.png)
![image](https://user-images.githubusercontent.com/73453283/207782111-8eb15a6e-988e-487a-918e-d5023137159e.png)
![image](https://user-images.githubusercontent.com/73453283/207782159-a6e103ae-ea7e-4d29-a847-6756f97c9e9d.png)
![image](https://user-images.githubusercontent.com/73453283/207782359-e286bfa0-043e-4220-9ade-b25210731002.png)
![image](https://user-images.githubusercontent.com/73453283/207782391-23099003-b87f-4c2c-b2a1-9a16bfb26b8a.png)
![image](https://user-images.githubusercontent.com/73453283/207782451-ad92b8c2-ec7d-4128-bd28-1f90ad2e2248.png)



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


