# 🌱윤인규 포트폴리오

<div align = "center">
<img src="https://raw.githubusercontent.com/buinq/imageServer/main/img/%EC%9C%A4%EC%9D%B8%EA%B7%9C%EB%8B%98.jpg" alt="윤인규님" style="height:250px;" />
</div>
<br>

> 안녕하세요! 기록과 꾸준함의 중요성을 아는 개발자, 윤인규 입니다. 
>
> Email : tryingmybest24h@gmail.com
>
> Github : [https://github.com/inkyu-yoon](github.com/inkyu-yoon)
> 
> Blog : https://inkyu-yoon.github.io/

<br>

## Introduce
완벽한 계획이란 없다고 생각합니다. 최선을 기획하는 것 보다 최악의 상황을 대비하는 백엔드 개발자가 되는 것이 목표입니다.

도전을 좋아합니다. 남들이 쉽게 하지 않는 산티아고 순례길 · 마라톤 · 국토종주 등 다양한 도전을 하였고, 제가 가진 강점인 끈기로 모두 성공할 수 있었습니다. 

함께 성장하는 것을 좋아합니다. 2022년 10월 부터 [CS 전공 스터디](https://likelion.notion.site/1fc7e387b5634bde9fd922ee808a50dc)를 운영하고 있으며 매주 화요일마다 정해진 주제를 발표하고 질의응답하고 있습니다.

배운 것을 잊지 않기 위해, 그리고 같은 실수를 반복하지 않기 위해 꾸준히 [블로그](https://inkyu-yoon.github.io/)에 기록하는 것을 좋아합니다.

<br>

## 프로젝트
프로젝트 기능 동작에 대한 상세 설명은 Github Repository ReadMe.md 에 작성되어있습니다.

<br>


### [👟 ShoeKream](https://github.com/shoe-kream/shoekream)
> [Github](https://github.com/shoe-kream/shoekream)
>  
> **프로젝트 목표** : 한정판 상품 거래 플랫폼 Kream과 유사한 서비스  
> **참여 인원** : 2명  
> **개발 기간** : 2023.03 ~ 진행중  
> **사용 기술** : Java 17 · Spring Boot · Spring Security · JPA · MySQL · AWS EC2 · AWS S3 · Docker · Redis
> 
> **📌 프로젝트에 팀원으로서 기여한 사항**  
>  
> - HTTP Request Body 데이터 [유효성 검증 시 AOP 적용](https://inkyu-yoon.github.io/docs/Language/SpringBoot/ValidationAop)을 통한 비즈니스 로직 분리
> - Redis를 이용한 사용자 이메일 [인증 처리 구현](https://inkyu-yoon.github.io/docs/Language/SpringBoot/RedisAndAuth)
> - 메일 전송 기능 [비동기 처리 적용](https://inkyu-yoon.github.io/docs/Language/SpringBoot/EmailAsync) 후, 응답시간 `4.62s` → `0.725s`  로 `6.38`배 개선
> - 메일 전송 기능에 [AOP 적용을 통한 응답속도 개선과 코드 가독성 · 유연성 향상](https://inkyu-yoon.github.io/docs/Language/SpringBoot/EmailAop) - AsyncConfiguration · EventHandler · Custom Annotation 활용

<br>

### [🌱 GrowITh](https://github.com/inkyu-yoon/growith)
> [Github](https://github.com/inkyu-yoon/growith)
>  
> **프로젝트 목표** : IT 직군 커뮤니티 서비스  
> **참여 인원** : 개인 프로젝트  
> **개발 기간** : 2023.03 ~ 진행중  
> **사용 기술** : Java 17 · Spring Boot · Spring Security · JPA · MySQL · AWS EC2 · Docker · Querydsl
> 
> **📌 주요 개발 사항** 
>
> - [WebClient를 이용한](https://inkyu-yoon.github.io/docs/Language/SpringBoot/GithubLogin) Github API 활용
> - WireMock 라이브러리를 사용해 [외부 API Mock 웹 서버 테스트 코드](https://inkyu-yoon.github.io/docs/Language/SpringBoot/WebClientTest) 작성
> - GET 요청 시, 쿼리 파라미터로 전달되는 [Enum 타입 필드 매핑 처리 및 예외처리 개선](https://inkyu-yoon.github.io/docs/Language/SpringBoot/RequestParamEnum)
> - Request Body Enum 타입 필드 [validation 예외처리 개선](https://inkyu-yoon.github.io/docs/Language/SpringBoot/EnumValidation)


<br>

### [🏫 My Academy](https://github.com/mutsa-team6/myacademy)
> [Github](https://github.com/mutsa-team6/myacademy)
>  
> **프로젝트 목표** : 학원 관리와 관련된 모든 기능을 제공하는 서비스  
> **참여 인원** : 5명  
> **개발 기간** : 2023.01 ~ 2023.02  
> **사용 기술** : Java 11 · Spring Boot · Spring Security · JPA · MySQL · AWS EC2 · AWS S3 · Docker · Nginx · Redis · SonarQube  
> 
> **📌 프로젝트에 팀원으로서 기여한 사항**  
>  
> - [프로젝트 팀장](https://www.notion.so/3ebdea86f2f642699fa071b76c94d45f) · PM 역할 수행, 일정관리 · 회의진행 · [시연영상 제작](https://www.youtube.com/watch?v=tKeKN3qd58k) · [데모데이 발표](https://www.canva.com/design/DAFaeRUJKBk/PQHdXXa61qBj0EwnS3adSw/view?utm_content=DAFaeRUJKBk&utm_campaign=share_your_design&utm_medium=link&utm_source=shareyourdesignpanel) 및 [코드 컨벤션 제작](https://www.notion.so/16748ff592fd48d492156cf24bf87bf4)
> - 학원 정보 등록 시, Axios와 [국세청 API](https://www.data.go.kr/tcs/dss/selectApiDataDetailView.do?publicDataPk=15081808#/%EC%82%AC%EC%97%85%EC%9E%90%EB%93%B1%EB%A1%9D%EC%A0%95%EB%B3%B4%20%EC%A7%84%EC%9C%84%ED%99%95%EC%9D%B8%20API/validate)를 이용해 사업자 등록번호 검증 기능 구현
> - 사용자 경험 향상을 위한 구글 · 네이버 Oauth 2.0 [소셜 간편 로그인 기능 구현](https://inkyu-yoon.github.io/docs/Language/SpringBoot/OauthLogin)
> - 사용자 편의 향상 및 보안을 위한 In-Memory 데이터 스토리지 Redis를 이용한 [Refresh 토큰 시스템 구현](https://inkyu-yoon.github.io/docs/Language/SpringBoot/RefreshToken)
> - Service 로직 간소화와 데이터 검증을 위한, validation 라이브러리로 Request body 데이터 유효성 검증 적용
> - SonarQube로 코드 품질 분석 후, 검출된 Bugs `15`개와 Security Hotspots `8`개 모두 `0`개로 개선
> - Thymeleaf 를 사용한 프로젝트 내 모든 페이지 구현 (`33개`)
>

<br>

### [💌 SNS 게시판 프로젝트](https://github.com/inkyu-yoon/sns_project)
> [Github](https://github.com/inkyu-yoon/sns_project)
>  
> **프로젝트 목표** : 회원 가입 후 게시글 작성 · 조회 · 수정 · 삭제 · 댓글 · 좋아요 버튼 등을 할 수 있는 SNS 서비스  
> **참여 인원** : 개인 프로젝트  
> **개발 기간** : 2022.12 ~ 2022.01  
> **사용 기술** : Java 11 · Spring Boot · Spring Security · JPA · MySQL · AWS EC2 · Querydsl · Docker · Github Actions  
> 
> **📌 주요 개발 사항**  
>  
> - DockerCompose · Github Actions를 이용한 [CI/CD 파이프라인 구축](https://inkyu-yoon.github.io/docs/Learned/Docker/GitActionsCICD)
> - [Git submodule 적용](https://inkyu-yoon.github.io/docs/Learned/Git/GitSubmodule)을 통한 환경변수 보안 · 유지보수성 향상
> - Querydsl 적용을 통해 [쿼리 개수와 실행시간 최적화](https://inkyu-yoon.github.io/docs/Language/JPA/QuerydslRepo)
> - 게시글 제목 검색 · 회원명 검색 시, Querydsl 동적 쿼리 적용
> - Jacoco를 이용해 Rest Controller · Service 테스트 코드 커버리지 측정 및 커버리지 `100%` 달성
> - SSE 통신 기반 댓글 및 좋아요 알림 기능 추가
