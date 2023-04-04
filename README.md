![image](https://user-images.githubusercontent.com/112916825/229807684-80bcee1b-6cec-40ac-925b-4c7c2926efec.png)
# 우연을 가장한 필연? 우연을 가장한 필름! 우가필🎥

### 🤨 내가 좋아할만한 영화 누가 알려주면 좋겠다!
넘쳐나는 영화, 뭘 봐야할 지 도무지 모르겠어!<br>
영화 고르다 잠 잘 시간이 되어버린 적이 한두번이 아니야....😩<br>
<br>
<br>
분명 재미있을 줄 알았는데 내 취향이랑 너무 안맞는 영화구만...<br>
내 취향에 안맞는 영화보다가 중도포기해서 버리는 시간 너무 아까워🤯<br>
<br>
<br>
나의 취향은 무엇인가...<br>
내가 좋아하는 장르가 뭔지,, 내가 좋아하는 감독과 배우는 누구인지,,,<br>
누가 분석해서 알려주면 재밌겠다!😎
<br>
<br>
<br>
### 🎥 영화 대홍수의 시대, 우연을 가장한 필연으로 여러분들을 위해 탄생했습니다!
<b>사용자의 행동 패턴 데이터를 바탕으로 취향을 파악</b><br>
메인페이지에서 사용자의 취향영화를 추천,<br>
마이페이지에서 사용자의 선호 장르, 감독, 배우 분석결과 제공<br> 
사용자에게 우연을 가장한 필연의 영화를 추천해드립니다💓<br> 
<br> 
<br>
최신영화가 제대로 업데이트 안될까봐 걱정할 필요 No!<br>
<b>서버리스 개발방법으로 추가 업데이트 없이 최신 정보를 제공한답니다</b>🤭<br> 
<br>
<br>
시간을 때우기 위한 적당한 영화가 아닌<br>
나에게 꼭 맞는 영화를 보며 여러분의 소중한 시간을 보내주세요.🥰<br>
<br>
<b>UGotFilm</b>이 추천해주는 영화를 보며<br>
여러분의 소중한 시간을 보다<br>
더 행복한 시간으로 채워냈으면 좋겠습니다.<br>
<br>

## 개발규모
- 6명
- 4주(2023.02.08 ~ 2023.03.08)
<br>

## 프로젝트 진행과정
<div align="center">
<img src="https://user-images.githubusercontent.com/112916825/229915065-e47a532a-47d5-4a53-817b-56613f5a2e60.png">
</div>
- (회의록)

<br>

## ERD
![image](https://user-images.githubusercontent.com/112916825/229819631-05540c94-f9f4-45ff-a072-c1522583aef0.png)
<br>

## UseCase
### 사용자
<div align="center">
<img src="https://user-images.githubusercontent.com/112916825/229819788-735276af-17f9-42f5-a3de-137f3d3d1b49.png">
</div>

### 관리자
<div align="center">
<img src="https://user-images.githubusercontent.com/112916825/229820006-82722358-d1ae-4c96-bf1f-882da3af2746.png">
</div>
<br>

## 주요기능
### 🎥 로그인 및 회원가입
```
- 회원전용 사이트로 운영
- 로그인 후 마이페이지에서 개인정보 수정 가능(닉네임, 출생년도, 비밀번호 수정가능)
```
### 🎥 메인페이지
```
- 현재상영작, 현재 인기작, 장르별 영화 추천 (tmdb API 활용)
- 전체선호 영화 추천 영화 리스트 제공
- 성별선호 영화 추천 영화 리스트 제공
- 연령별 영화 추천 영화 리스트 제공
- 장르별(인기순, 평점순) 영화 리스트 제공
- 유저와 같은 영화를 많이 클릭한 대조군 유저의 영화 리스트 활용, 유저에게 대조군 유저의 영화 리스트 중 아직 보지 않은 영화 리스트 제공
```
### 🎥 검색
```
- 영화 제목 검색
- 인물(감독, 배우) 검색
```
### 🎥 영화 상세페이지
```
- 해당 영화의 줄거리, 장르, 개봉일 제공
- 감독 및 배우진 정보 제공
- 한줄평 작성 가능 (관리자 및 작성자만 삭제 가능)
```
### 🎥 인물 상세페이지
```
- 해당 인물의 필모그래피 확인가능
```
### 🎥 마이페이지
```
- 유저가 클릭한 영화 및 인물을 바탕으로 유저의 취향 분석결과 제공
- 확인하고 싶은 키워드 클릭 시 해당 내용으로 이동
- 선호 감독, 배우, 장르를 많이 클릭한 순으로 제공
```
### 🎥 공지 게시판
```
- 작성한 글에 답글 및 댓글 작성 가능
```
### 🎥 관리자 페이지
```
- 관리자 등급의 ID만 접근가능
- 한줄평 관리가능 (삭제가능)
- 회원 등급 수정가능 (관리자, 매니저, 일반회원, 탈퇴)
```
<br>

## 담당
- Frontend : 영화, 인물정보 저장(axios를 활용한 백엔드 서버와 통신기능)
- Backend : 데이터 저장, 파이썬활용 큐레이션
<br>

## 사용 기술
- Frontend : <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white"/>&nbsp;&nbsp;<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white"/>&nbsp;&nbsp;<img src="https://img.shields.io/badge/Javascript-F7DF1E?style=flat&logo=Javascript&logoColor=white"/>&nbsp;&nbsp;<img src="https://img.shields.io/badge/jQuery-0769AD?style=flat&logo=jQuery&logoColor=white"/>&nbsp;&nbsp;<img src="https://img.shields.io/badge/Ajax-000000?style=flat&logoColor=white" />&nbsp;&nbsp;<img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=React&logoColor=white"/>&nbsp;&nbsp;<img src="https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=Bootstrap&logoColor=white"/>
- Backend : <img src="https://img.shields.io/badge/Java-007396?style=flat&logoColor=white" />&nbsp;&nbsp;<img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat&logo=Spring Boot&logoColor=white"/>&nbsp;&nbsp;<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=Python&logoColor=white"/>&nbsp;&nbsp;<img src="https://img.shields.io/badge/flask-000000?style=flat&logo=flask&logoColor=white"/>
- Database : <img src="https://img.shields.io/badge/Oracle-F80000?style=flat&logo=Oracle&logoColor=white"/>&nbsp;&nbsp;<img src="https://img.shields.io/badge/Mybatis-000000?style=flat&logo=Fluentd&logoColor=white" />

- API : tmdbAPI
<br>

## 사용 툴
<img src="https://img.shields.io/badge/EclipseIDE-2C2255?style=flat&logo=Eclipse IDE&logoColor=white"/>&nbsp;&nbsp;<img src="https://img.shields.io/badge/VisualStudioCode-007ACC?style=flat&logo=Visual Studio Code&logoColor=white"/>
<br>
<br>

## 웹페이지 시연영상
<p>UGotFilm을 클릭해주세요!</p>

[![video Label](http://img.youtube.com/vi/1J-S5kbfgYo/0.jpg)](https://youtu.be/1J-S5kbfgYo)

