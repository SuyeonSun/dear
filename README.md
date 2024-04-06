# Dear

## **1. 프로젝트 설명**

### 개요

- 프로젝트 명
    - Dear
- 소개
    - 생산형 AI 기반의 편지지 생성 및 대필 서비스입니다. 사용자가 작성한 키워드를 기반으로 편지를 작성해주고, 다양한 부가 기능을 통해 편지에 대한 감정을 효과적으로 전달하고자 했습니다.
- 개발 기간
    - 2024.02.26 ~ 2024.04.05
- 팀원 소개
    - AI: 김동훈, 송찬의, 신혜승
    - Infra : 선수연, 김동훈
    - Frontend : 이가영, 김동훈, 신혜승, 전건휘, 송찬의
    - Backend: 김동훈, 선수연, 이가영, 신혜승, 전건휘

### 기획

- 기획 배경
    - 편지 쓰기가 익숙하지 않아서 편지를 쉽게 작성하고 싶은 사용자에게 도움이 되는 서비스를 제작하고 싶었습니다. 또한, 나만의 마음이 담긴 특별한 편지를 받고 싶은 사용자들의 마음을 고려하게 되었습니다.
- 핵심 기능
    - 편지 작성
        - 기분, 감정, 수신자의 키워드, 담고 싶은 추억 등을 직접 입력하여 AI에게 편지 생성을 맡겨볼 수 있습니다.
    - 우표 생성
        - 작성된 편지를 기반으로 세상에서 하나 뿐인 나만의 우표를 받아볼 수 있습니다.
    - 우표 판매
        - 내 편지 기반의 예쁜 우표를 우표 마켓에 판매할 수 있습니다. 다른 사용자들이 올린 우표를 구경하고 구매할 수 있습니다.
- 기술 특이점
    - 소셜 로그인: OAuth를 이용한 소셜 로그인 (카카오, 네이버, 로그인)
    - 우표 생성 AI: Stable Diffusion과 Pytorch를 사용한 Text To Image 우표 생성
    - 음악 생성 AI: Lost-Angeles-Music-Composer과 Pytorch를 사용한 Text to Music 음악 생성
    - 편지 템플릿 생성 AI: Open Api를 사용하여 Text Generation을 이용한 텍스트 생성

## **2. 프로젝트 실행 화면**

### 시연 영상
https://youtu.be/ZBIySCb51hQ
### 프로젝트 화면 이미지
<img src="https://github.com/SuyeonSun/test/assets/77823761/5eb3e7ec-7488-44cf-810d-e3cb499f54b3" width="150" height="300">
<img src="https://github.com/SuyeonSun/test/assets/77823761/fd508106-a2ac-4ffd-bd62-ced04da1060f" width="150" height="300">
<img src="https://github.com/SuyeonSun/test/assets/77823761/1446abe7-939e-4f27-b7e4-552c0a418f97" width="150" height="300">
<br>
<img src="https://github.com/SuyeonSun/test/assets/77823761/41c0493b-32ea-4ed2-a3a4-e0bf56a71ded" width="150" height="300">
<img src="https://github.com/SuyeonSun/test/assets/77823761/ec6db48d-9c49-46b3-bba9-4dac6b0c3a60" width="150" height="300">
<img src="https://github.com/SuyeonSun/test/assets/77823761/64aa4244-568d-4c02-85d1-fad5e709fec1" width="150" height="300">
<img src="https://github.com/SuyeonSun/test/assets/77823761/ee422a0d-f366-4aa4-af95-7f295784e88b" width="150" height="300">
<img src="https://github.com/SuyeonSun/test/assets/77823761/faee9f71-4ffd-4d28-a56c-e470dbd68645" width="300" height="300">
<img src="https://github.com/SuyeonSun/test/assets/77823761/45ac604c-2122-4751-bf8d-1ddff4e67666" width="170" height="300">
<br>
<img src="https://github.com/SuyeonSun/test/assets/77823761/4042030f-e040-4250-b2db-bfb823fdb551" width="150" height="300">
<br>
<img src="https://github.com/SuyeonSun/test/assets/77823761/4df3e787-6d03-4533-aea5-3008e7661ea2" width="150" height="300">
<img src="https://github.com/SuyeonSun/test/assets/77823761/b29959e0-c045-4aee-be2f-ae1b7d4cfbf2" width="150" height="300">
<br>
<img src="https://github.com/SuyeonSun/test/assets/77823761/0a65f04b-ad82-4c92-89dc-47b152aeb8cf" width="150" height="300">
<img src="https://github.com/SuyeonSun/test/assets/77823761/6b90f8fc-cb29-4fdd-9224-c7ed487364fd" width="150" height="300">
<br>
<img src="https://github.com/SuyeonSun/test/assets/77823761/770f72eb-ba99-4471-a2b7-67a057ddfa35" width="150" height="300">
<img src="https://github.com/SuyeonSun/test/assets/77823761/6c5264b8-a3fd-4758-88b8-d3e08940e4b1" width="150" height="300">
<img src="https://github.com/SuyeonSun/test/assets/77823761/f5eb6812-b18c-4897-8ea9-ffc05d48cf4a" width="150" height="300">

## **3. 기술 스택**
### Frontend

- React
- Styled-components
- React-Query
- Zustand
- Vite
- WebPack

### Backend

- Spring Boot
- Spring Cloud Gateway
- JPA
- QueryDSL
- Kafka

### DB

- MySQL
- Redis

### AI

- Django
- Pytorch

### Infra

- AWS
- Jenkins
- Nginx
- Docker

### Tool

- Jira
- Github
- Figma

## **4. 프로젝트 구조**

### MSA

장애의 격리와 자원 사용의 최적화를 위해 MSA 구조를 선택했습니다. 

- 회원과 편지 서버를 분리
    - 장애 격리
        - 각 서비스가 독립적으로 작동하기 때문에, 장애가 발생한 서비스를 격리하고 다른 서비스는 정상적 작동
    - 자원 사용의 최적화
        - 상대적으로 요청이 적은 회원 서버에 비해 빈번한 요청이 일어나는 편지(우표) 서버
        - 필요한 서비스만 사용하여 자원 사용을 최적화

### 서버 구조

기능에 따라 총 4개의 서버로 분리했습니다. 

- Api-Gateway-Service
    - 백엔드 서비스에 대한 API 트래픽을 수락, 변환, 라우팅 및 관리하는 중개자 역할
- Auth-Service
    - 회원가입 및 로그인 역할
- User-Service
    - 회원 정보 조회 및 닉네임 수정 역할
- letter-Service
    - 편지 작성 및 보내기, 편지 마켓, 우표 목록 등의 역할

### 데이터베이스 구조

MSA는 데이터베이스를 분리하지 않으면 데이터베이스 공유로 인한 강한 결합이 존재하기 때문에 완벽히 목표를 달성하기 어렵습니다. 그래서 회원의 UUID를 사용하여 데이터를 조회할 수 있도록 설계하고 2개의 데이터베이스로 분리하였습니다.

- User DB
<img src="https://github.com/SuyeonSun/test/assets/77823761/e702989c-5aa3-48dc-89e0-ea55fc8cb2a0">

- Letter DB
<img src="https://github.com/SuyeonSun/test/assets/77823761/f22e2276-a48d-450f-a79a-cff45078ea88">

### 인프라
<img src="https://github.com/SuyeonSun/test/assets/77823761/c75943ad-e89c-4c78-bc33-349b030b55a5">

- 일관된 환경 구성을 위한 도커의 사용
    - 도커 컨테이너는 이미지로 구성되어 있어 개발, 테스트, 배포 등의 환경을 일관되게 유지할 수 있기 때문에 도커를 활용했습니다.
- Jenkins로 CI/CD 구축
    - Jenkins로 CI/CD를 구축하여 master 브랜치에 push 이벤트 발생 시, build 하도록 구성했습니다.
