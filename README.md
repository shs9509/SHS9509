<p align="center">
<img src ="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fshs9509&count_bg=%23ABB7FF&title_bg=%23313131&icon=github.svg&icon_color=%23FFFFFF&title=hits&edge_flat=false"/>




``` 
안녕하세요. 매일 새로운것을 배워가며 끈기있게 나아가는 프론트 개발자입니다.
```

## 😁Introduce

- 이름
  - 신형식
- email
  - ssej09072@naver.com
- 이력
  - 충남고등학교 졸업 (2011.03 ~ 2014.02 )
  - 충남대학교 정보통신공학과 졸업 (2014.03 ~ 2020.02)
  - 삼성 청년 소프트웨어 아카데미 5기 (2021.01 ~ 2021.12)
  - 삼성 청년 소프트웨어 아카데미 5기 실습코치 (2022.01 ~ 현재 )
- 취미
  - 자전거, 러닝, 여행
- 자격증
  - 정보처리기사 (2021.06)



## 🎬Projects

![ssuangview250](https://user-images.githubusercontent.com/77470435/156956198-a4f0457a-9bd0-4654-be56-9b23262d452a.png)
#### 1. AI 면접평가 서비스 "쓰앵뷰"

- 소개  
  - '쓰앵뷰'는 STT를 통한 발음 분석과 표정분석을 통해서 AI 면접을 평가 해줍니다.
  - 한국어, 영어 2개국어를 지원합니다.
  - 어려울 수 있는 영어 면접을 위해서 유튜브 기반으로 영어 면접 연습을 진행할 수 있습니다.
- 기간 
  - 21.10.11 ~ 21.11.26 (7주)
  - 22.02.01 ~ 진행 중 (**코드 리팩토링 진행 중**)
- 관련 기술
  - `React`, `Material-UI`, `Spring boot`, `Flask`, `AWS`, `Doker`, `NGINX`, `JenKins`, `GitLab`, `Jira`
  - `Redux`, `Typescript`
- 주요 내용
  - STT를 사용하여 인터뷰를 스크립트화하여 준비된 스크립트와 비교해서 점수를 매깁니다.
  - 인터뷰 도중 표정분석을 통해서 긍정적인, 부정적인 표정을 판별하고 점수를 매깁니다.
  - 발음점수와 표정점수를 총합하여 인터뷰의 총 점수를 나타냅니다.
  - 영어 면접을 준비하기 위한 Youtube를 활용한 쉐도잉 기능을 제공합니다.
- 상세 업무 및 성과
  - `annyang API`를 활용하여 한/영을 지원하는 STT 기능을 구현했습니다.
  - `React`를 활용한 Frontend영역 페이지 구현했습니다.
  - `recharts`를 활용하여 사용자의 표정 분포를 시각화했습니다.
- 리팩토링 (진행 중)
  - `Redux`를 통해서 상태관리를 진행했습니다.
  - `Typescript`를 적용하였습니다.

- 링크
  - [repository](https://github.com/shs9509/pjt_ssuangview)

-------------------------------------------------------

![leadME250](https://user-images.githubusercontent.com/77470435/156956200-b1512e35-0d9d-4c99-8003-7ffdb2b44f43.png)
#### 2. 빅데이터 기반 영화 추천 서비스 "LeadME"

- 소개 
  - 'LEAD ME'는 빅데이터 기반으로 사용자에게 맞는 영화를 선정해줍니다.
  - 기존의 설문을 통해서 사용자의 취향을 파악하거나 MBTI 검사를 통해서 사용자의 성향에 맞는 영화들을 파악하고 추천해 드립니다.
- 기간 
  - 21.08.30 ~ 21.10.08 (6주)
- 관련 기술
  - `React`, `Material-UI`, `Django`, `Doker`, `JenKins`, `GitLab`, `Jira`
- 주요 내용
  - *Cold Start*를 위해서 설문을 통해 영화 취향을 분석합니다.
  - MBTI로 알아보는 나의 영화 취향 파악
  - 나의 영화 성향 차트 확인
- 상세 업무 및 성과
  - `React`를 활용한 Frontend영역 페이지를 구현 했습니다.
  - `recharts`를 활용하여 사용자의 영화선호 분포 데이터 시각화 했습니다.
  - 기능마다 콘텐츠 필터링과 협업 필터링을 활용하여 다양한 유형의 영화들을 추천했습니다.
- 링크
  - [repository](https://github.com/shs9509/pjt_LeadME)

--------------------------------------------------------------

![pipl250](https://user-images.githubusercontent.com/77470435/156956197-209698ee-243a-4bea-8468-82e09337cdf6.png)
#### 3. 약속기반 SNS "Pipl"

- 소개 
  - Pipl 은 SNS 상에서 모임/약속을 쉽게 잡아주는 소셜 플랫폼입니다.
  - 모임/약속을 잡는 가장 첫 단추인, 사람들에게 말하는 과정을 Pipl 을 이용하여 손쉽게 전달할 수 있습니다.
- 기간 
  - 21.07.12 ~ 21.08.20 (6주)
- 관련 기술
  - `Vue`, `Vue bootstrap`, `Spring boot`, `JPA`, `Maria DB`, `Firebase`, `AWS`, `kakaomap`, `Doker`, `JenKins`, `GitLab`, `Jira`
- 주요 내용
  - 약속과 게시물에 대해서 CRD 기능과 무한스크롤 기능을 갖춘 SNS
  - 카카오 맵을 활용한 사용자 GPS 정보 사용 동의 하에 약속 1시간 전부터 약속 대상자들의 위치를 확인을 통해서 'no show'를 방지 할 수 있습니다.
    - 현재 위치와 목적지의 거리를 계산해서 예산 시간을 보여줍니다.

  - 팔로우한 유저가 약속을 생성하면 알림을 확인할 수 있습니다.

- 상세 업무 및 성과
  - `Vue` 를 활용하여 Frontend영역 페이지 구현할 수 있게 되었습니다.
  - `Git`, `Jira`를 통한 프로젝트 관리 및 협업 효율을 올릴 수 있었습니다.
  - 사용자 경험을 개선할 수있는 UI/UX 구현을 진행했습니다.
    - Darkmode
    - 온보딩 페이지
    - 화상 약속기능
    - 카카오 로그인
- 링크
  - [repository](https://github.com/shs9509/pjt_Pipl)

-----------------------------------

![Memovie250](https://user-images.githubusercontent.com/77470435/156956196-4feabf5c-7d65-4f0a-915d-680dd1ca9d26.png)
#### 4. Memovie

- 소개 
  - 영화의 상세정보를 보여주며 더불어 영화를 추천해줍니다.
  - 레트로 디자인으로 ’window98’의 디자인을 택하였고 그에 맞는 기능으로서 ‘n년전 박스오피스 순위’를 보여줍니다.
- 기간 
  - 21.05.20 ~ 21.05.27 (1주)
- 관련 기술
  - `Vue`, `bootstrap`, `Django`, `jwt`, `GitLab`
- 주요 내용
  - TMDB, 네이버, 박스오피스 영화 API를 활용하여 영화 데이터를 불러와 컨텐츠를 구성했습니다. 
  - 사용자가 '좋아요'를 누른 장르를 파악하여 비슷한 장르로 영화를 추천해줍니다.
  - 박스오피스 API를 활용하여 1,5,10년 전 박스오피스 10위권의 영화들을 보여줍니다.   
- 상세 업무 및 성과
  - 명세서에 맞춰서 서비스 구현한 경험을 얻었습니다. 
  - 박스오피스API에서 포스터를 제공하지 않기 때문에
    - 네이버 영화 검색 API를 통해서 박스오피스의 영화의 이름을 통해 이미지를 얻어서 박스오피스 모델에 이미지를 추가하여 해결했습니다.
  - `Django` 를 활용하여 데이터를 구성하여 프론트엔드에 원하는 데이터를 전송했습니다.
- 링크
  - [repository](https://github.com/shs9509/pjt_MeMovie)

-----------------------------
  
![review250](https://user-images.githubusercontent.com/77470435/156956191-dc772ba6-da55-4a32-9a21-8cc1a8d11344.png)
#### 5. Book review site

- 소개 
  - Django를 사용한 개인 프로젝트로 책과 그에 해당되는 리뷰를 올립니다.
  - 댓글로서 책에 대한 평을 공유할 수 있으며 평점을 매길 수 있습니다.
- 기간 
  - 21.04.03 ~ 21.06.09 (10주)
- 관련 기술
  - `bootstrap`, `Django`
- 주요 내용
  - 책의 리뷰를 생성할 수 있습니다.
    - 리뷰 생성시 개인적으로 장르를 생성해서 만들 수있으면 해당 장르로 분류 탭이 생성됩니다.
  - 리뷰에는 댓글을 통해서 의견공유가 가능하며 점수를 매길 수 있습니다.
- 상세 업무 및 성과
  - `Django` 를 활용하여 CRUD 기능 구현
  - 모델 설계를 하는데 프로젝트에 맞게 구성해야한다는 것을 알았습니다.
  - 장고에 대해서 ORM, 쿼리셋의 학습과 활용을 진행했습니다.
- 링크
  - [repository](https://github.com/shs9509/pjt_book_review_site)



## Awards & Licenses

### 🏆 Award

- 삼성 청년 SW 아카데미 자율프로젝트 결선 발표회 우수상 ( 2021.11.30 )

- 삼성 청년 SW 아카데미 자율프로젝트 우수상 (1등) ( 2021.11.26 )
- 삼성 청년 SW 아카데미 공통프로젝트 우수상 (2등) ( 2021.08.20 )

### 🎫 Licenses

- 정보처리기사 (2021.06)



## 🚴‍♂️ Activity

- 삼성청년소프트웨어아카데미(SSAFY) 5기 (2021.01 ~ 2021.12)

- SSAFY 5기 Discord 채널 운영 (2021.01 ~ 진행 중)

  

-----------

<h3><center>🏹Enable Teck Stack</center><h3/>


<center><img src="https://img.shields.io/badge/Python-3766AB?style=flat-square&logo=Python&logoColor=white"/><img src="https://img.shields.io/badge/Vue-4FC08D?style=flat-square&logo=Vue.js&logoColor=white"/><img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=white"/></center>
<center><img src="https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white"/><img src="https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white"/><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=white"/></center>
<center><img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=Git&logoColor=white"/><img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=Django&logoColor=white"/></center>

