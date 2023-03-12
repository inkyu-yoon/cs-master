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


<br>

## Introduce
완벽한 계획이란 없다고 생각합니다. 최선을 기획하는 것 보다 최악의 상황을 대비하는 백엔드 개발자가 되는 것이 목표입니다.

도전을 좋아합니다. 남들이 쉽게 하지 않는 [산티아고 순례길 · 마라톤 · 국토종주](https://blog.naver.com/inkyu312) 등 다양한 도전을 하였고, 제가 가진 강점인 끈기로 모두 성공할 수 있었습니다. 

함께 성장하는 것을 좋아합니다. 2022년 10월 부터 [CS 전공 스터디](https://likelion.notion.site/1fc7e387b5634bde9fd922ee808a50dc)를 운영하고 있으며 매주 화요일마다 정해진 주제를 발표하고 질의응답하고 있습니다.

배운 것을 잊지 않기 위해, 그리고 같은 실수를 반복하지 않기 위해 꾸준히 [블로그](https://inkyu-yoon.github.io/)에 기록하는 것을 좋아합니다.

<br>

## 프로젝트
### [🏫 My Academy](https://github.com/mutsa-team6/myacademy)
> [Github](https://github.com/mutsa-team6/myacademy) · [배포 주소](http://ec2-13-209-97-187.ap-northeast-2.compute.amazonaws.com/)  
>  
> **참여 인원** : 5명  
> **개발 기간** : 2023.01 ~ 2023.02  
> **사용 기술** : Java 11 · Spring Boot 2.7.7 · Spring Security · JPA · MySQL 8.0 · AWS EC2 · AWS S3 · Docker · Nginx · Redis · SonarQube  
> 
> **📌 프로젝트에 팀원으로서 기여한 사항**  
>  
> 1.  [프로젝트 팀장](https://likelion.notion.site/3ebdea86f2f642699fa071b76c94d45f) · PM 역할 수행 · [코드 컨벤션 제작](https://inkyu-yoon.github.io/docs/Project/CodeConvention) · 일정관리 · 회의진행 · [데모데이 발표](https://www.canva.com/design/DAFaeRUJKBk/PQHdXXa61qBj0EwnS3adSw/view?utm_content=DAFaeRUJKBk&utm_campaign=share_your_design&utm_medium=link&utm_source=shareyourdesignpanel) → 프로젝트 마감일 1주일 전 기능 개발 완료 · [프로젝트 우수상](https://tryingmybest24.notion.site/2-d44ca58384c24c99a061caed3645014e) 수상  
> 2.  학원 등록 시, [국세청 API](https://www.data.go.kr/tcs/dss/selectApiDataDetailView.do?publicDataPk=15081808#/%EC%82%AC%EC%97%85%EC%9E%90%EB%93%B1%EB%A1%9D%EC%A0%95%EB%B3%B4%20%EC%A7%84%EC%9C%84%ED%99%95%EC%9D%B8%20API/validate)를 이용해 사업자 등록번호 유효성 판단 기능 구현  
> 3. 구글 · 네이버 Oauth 2.0 [소셜 간편 로그인 기능 구현](https://inkyu-yoon.github.io/docs/Language/SpringBoot/OauthLogin#9-%ED%85%8C%EC%8A%A4%ED%8A%B8)   
> 4.  Redis를 이용한 [Refresh 토큰 시스템 구현](https://inkyu-yoon.github.io/docs/Language/SpringBoot/RefreshToken)  
> 5.  Controller 단에서 validation 라이브러리로 Request body 데이터 유효성 검증 적용  
> 6.  Sonarqube로 코드 품질 분석 후, 검출된 Bugs `15`개와 Security Hotspots `8`개 모두 `0`개로 개선  
> 7.  Controller와 Thymeleaf 적용한, 프로젝트 내 모든 UI 페이지 구현 (페이지 총 `33`개)
>

<br>

### [💌 SNS 게시판 프로젝트](https://github.com/inkyu-yoon/sns_project)
> [Github](https://github.com/inkyu-yoon/sns_project) · [배포 주소](http://ec2-13-231-48-116.ap-northeast-1.compute.amazonaws.com:8080/)  
>  
> **참여 인원** : 개인 프로젝트  
> **개발 기간** : 2022.12 ~ 2022.01  
> **사용 기술** : Java 11 · Spring Boot 2.7.5 · Spring Security · JPA · MySQL 8.0 · AWS EC2 · Querydsl · Docker · Github Actions  
> 
> **📌 주요 개발 사항**  
>  
> 1.  [Swagger](http://ec2-13-231-48-116.ap-northeast-1.compute.amazonaws.com:8080/swagger-ui/)를 이용한 API 문서화
> 2.  Dockerfile · sh 스크립트 · crontab 활용한 GitLab CI/CD 파이프라인 구축 
→  이후에, DockerCompose · Github Actions CI/CD [파이프라인 구축](https://inkyu-yoon.github.io/docs/Learned/Docker/GitActionsCICD)하여 약 `3분 30초` → 약 `1분 30초`로 개선  
> 3. [Git submodule 적용](https://inkyu-yoon.github.io/docs/Learned/Git/GitSubmodule)을 통한 환경변수 보안 · 유지보수성 향상
> 4.  사용자 로그인 성공 시, jwt token를 사용자 local storage에 보관 후, Spring Security로 인증 · 인가 관리 
> 5.   Querydsl 적용을 통해 쿼리 개수와 실행시간 [최적화](https://inkyu-yoon.github.io/docs/Language/JPA/UseQuerydsl)  
> 6.  게시글 제목 검색 · 회원명 검색 시, Querydsl 동적 쿼리 적용
> 7.  Jacoco를 이용해 Rest Controller · Service 테스트 코드 커버리지 `100%` 
> 8. SSE 통신 기반 댓글 및 좋아요 알림 기능 추가

<br>

### [🏣 전국 병 · 의원 데이터 웹 페이지 프로젝트](https://github.com/inkyu-yoon/hospital_web)
> [Github](https://github.com/inkyu-yoon/hospital_web) · [배포 주소](http://ec2-13-231-48-116.ap-northeast-1.compute.amazonaws.com:8081/hospitals)  
>
> **개발 기간** : 2022.11 ~ 2022.12  
> **사용 기술** : Java 11 · Spring Boot 2.7.5 · Spring Security · Jdbc · JPA · MySQL 8.0 · AWS EC2 · Docker 
> 
> **📌 주요 개발 사항**  
>  
> 1. t3 small EC2 인스턴스 생성 후, Docker 이용하여 MySQL과 Gradle 프로젝트 배포  
> 2. 지역명 · 병원명 검색 기능 · 상세 정보 조회 기능 · 리뷰 조회/작성 기능 · 게시판 기능 구현 
> 3. Jwt 인증 방식적용 
> 4.   `121,005`개의 csv 형식의 대용량 병·의원 데이터를 JdbcTemplate batchUpdate 적용을 통해 [DB 입력 최적화](https://inkyu-yoon.github.io/docs/Language/Spring/JdbcBatchUpdate) (t3 small 인스턴스 기준, JPA 사용시 데이터 입력 시간 `74분` 소요 → `12초`로 개선)
>
