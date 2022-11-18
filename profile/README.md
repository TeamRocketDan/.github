# 🚀  로켓단의 한국정복
- 피드를 통한 추억 기록과 실시간 채팅 기능을 활용한 새로운 여행 SNS 서비스를 제공합니다. 

## **💪 기획 배경**
- 먼저 각자 구현 및 사용해 보고 싶었던 기능 및 기술을 취합해보았습니다.
- 프론트엔드는 지도를 활용하여, 보다 시각적으로 다가갈 수 있는 서비스를 제공하고 싶다는 의견을 주셨습니다.
- 백엔드는 웹소켓 및 NoSQL을 활용하여 실시간 채팅 서비스를 구현해 보고 싶다는 의견을 주셨습니다.
- 지도를 활용하고, 채팅 기능을 포함한 웹서비스에 대해 각자 아이디어를 모았습니다. 
- 최종적으로 로켓단은 한국정복을 통해 여행과 일상을 자유롭게 공유 하는 SNS 서비스를 제공하기로 하였습니다.

## **💪 주요 기능**
- 가장 최신의 피드와 지역(시도, 구) 검색을 통해 원하는 지역의 피드를 한번에 볼 수 있습니다.
- 나의 피드 페이지를 통해 여행에서 느꼈던 행복한 추억을 공유하고 저장할 수 있습니다.
- 피드에 지역을 지정해서, 내가 방문한 지역을 지도에서 한 눈에 확인 할 수 있습니다.
- 가고 싶은 지역의 채팅방을 개설해 동행을 모아 또 다른 추억을 만들 수 있습니다.
- 여행을 추억하고, 또 여행을 계획하여, 과거와 미래를 한 번에 관리할 수 있는 서비스입니다.

## **💪 기술 특장점**
- backend
    - CRUD 구현을 통해, MVC 패턴 활용
    - OAUTH2를 이용한 소셜 로그인 기능
    - SpringSecurity를 통한 refreshToken 활용 
    - RabbitMQ와 WebSocket Stomp를 활용한 chatting 기능
    - Spring Batch를 활용한 Redis → MongoDB chatting message back up
    - Querydsl을 활용하여 동적쿼리 작성 및 쿼리 최적화
    - Jenkins pipeline을 구축하여 CI/CD 적용
    - Nginx, AWS ELB를 활용하여 Load Balancing 적용
- frontend
    - recoil을 활용하여 전역 상태 관리
    - recoil-persist를 이용해 localStorage에 일부 상태 저장하여 로그인 하는 동안 안정적으로 상태 관리
    - 피드, 채팅, 팔로우 리스트는 쿼리스트링 또는 react-js-pagination api를 이용해 페이지네이션 기능 구현
    - 카카오 지도 api 연동하여 커스텀 마커 표시, 클러스터러 기능 사용
    - custom hook을 만들어서 로그인이 먼저 필요한 페이지에서 반복 사용
    - Intersection Observer로 채팅방 이전 메세지 불러오기 무한 스크롤 구현
    - Backend 와의 통신 방식 RESTful API 적용

## 🗄 [로켓단의 한국정복 API 명세서](https://nebula-catboat-ea3.notion.site/API-f8e38669f5ff4a1ca76c02379a44413a)

## 🖌 [로켓단의 한국정복 피그마](https://www.figma.com/file/SMJ8qB7DGRhI7SmovOpD3c/%EB%A1%9C%EC%BC%93%EB%8B%A8-%ED%94%BC%EA%B7%B8%EB%A7%88?node-id=1%3A206)

## 💾 [로켓단의 한국정복 ERD](https://www.erdcloud.com/d/mBqzY3pZMaAueigMB)

## 🧱 로켓단의 한국정복 구성도
![teamrocket_flow](https://user-images.githubusercontent.com/67041069/201728725-6611c514-e1a5-4d78-9060-8965be25fd1c.png)


## ⚒ 로켓단의 한국정복 기술 스택
![teamrocket_stack](https://user-images.githubusercontent.com/67041069/201720679-cc43212e-969b-4577-9bd8-2bf195cd72ce.png)

## **💪 팀원 소개**
- 유형진 : 
- 김우진 : 
- 한규빈 : 
- 박귀우 : 
- 김가빈 : 
- 김유민 :  
