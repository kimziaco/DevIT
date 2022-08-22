# DevIT
> 개발자 구인 구직 서비스 <br/>
> https://devit.shop/

<br/>

## 0. 총 코드
담당 개발자 : 이다혜 <br/>
> 유레카 서버 : https://github.com/ekgpgdi/devit-eureka-server <br/>
> 게이트웨이 : gateway : https://github.com/ekgpgdi/devit-gateway <br/>
> 인증 서비스 : gateway : https://github.com/ekgpgdi/devit-certification-service <br/>


담당 개발자 : 김지호 <br/>
> 게시물 서비스 : https://github.com/kimziaco/devit-board <br/>
 

담당 개발자 : 김대희
> 유저 서비스 : https://github.com/eet43/devit-user <br/>
> 채팅 서비스 : https://github.com/eet43/devit-chat <br/>

<br/>

> 프론트 : https://github.com/ekgpgdi/devit-front

<br/>

## 1. 제작 기간 & 참여 인원
* 2022.06.24 ~ 2022.07.29
* 3명 : [이다혜](https://github.com/ekgpgdi), [김지호](https://github.com/kimziaco?tab=repositories), [김대희](https://github.com/eet43)
<br/>

## 2. 사용 기술
<b>```Back-end```<b/>
* Java11
* Spring Boot 2.7.1
* Gradle 7.4.1
* Spring Data JPA
* H2
* MySQL 8.0.29
* Spring Security
* JWT
* Spring Cloud Eureka
* RabbitMQ
* Swagger

<b>```Front-end```<b/>
* HTML
* JavaScript
* Bootstrap

<br/>

## 3. ERD 설계

<img width="639" alt="스크린샷 2022-08-09 오후 4 27 57" src="https://user-images.githubusercontent.com/84092014/183590368-612bee33-4c73-4739-a265-0365dc22a75c.png">

 <img width="378" alt="스크린샷 2022-08-09 오후 4 28 09" src="https://user-images.githubusercontent.com/84092014/183590427-832e23ce-0ac3-4670-82e3-ca471412a0e2.png">



<br/>
<br/>

## 4. 핵심 기능
이 서비스의 핵심 기능은 구인자와 구직자의 결제입니다. <br/>
현재는 결제를 경험해보기 위하여 포인트 형태로 구현해두었습니다. <br/>
 

<img width="644" alt="스크린샷 2022-08-22 오전 11 03 25" src="https://user-images.githubusercontent.com/88760828/185824791-880ed144-ec49-43d8-bb63-5e04d90f30d2.png">

<br/>

## 5. 아키텍처도
<img width="699" alt="스크린샷 2022-08-22 오후 9 10 27" src="https://user-images.githubusercontent.com/88760828/185918599-aaa99e8b-5509-4fc4-81e8-0f49bdbc28cb.png">

<img width="692" alt="스크린샷 2022-08-22 오후 9 10 35" src="https://user-images.githubusercontent.com/88760828/185918608-3a16ef5c-379a-404b-a476-30fc4f30a79f.png">

<br/>

## 6. 핵심 트러블 슈팅
<details><summary>고객 피드백 반영</summary>

[고객 피드백 확인](https://hungry-snipe-f2e.notion.site/0790cc60a2794a0db2f1015ca6d2cf41) 참고

1. http 요청에 대한 처리 <br/>
2. 회원가입 시 이메일 검증 추가
3. 각 도메인의 자료형이 달라 생기는 문제 해결
4. XSS 공격에 대한 대처
5. 게시글 작성 시간과 현재 시간의 불일치 해결
6. 사진 크기에 따른 업로드 에러 해결
7. 메세지큐 무한 롤백으로 인한 서버 마비 현상 해결


</details>
