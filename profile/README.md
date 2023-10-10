# 2023 상명대학교 컴퓨터과학과 캡스톤 프로젝트 - 대동유어지도
<img width="850" alt="스크린샷 2023-10-10 오후 11 23 00" src="https://github.com/daedongyourjido/.github/assets/90092013/2f74cbca-6163-4071-aa03-410049b74124"> 


## 목차
1. [프로젝트 개요](#프로젝트개요)<br/>
2. [아이디어 소개](#아이디어소개)<br/>
3. [기능 소개](#기능소개)<br/>
4. [기술 스택](#기술스택)<br/>
5. [주요 기능 시연](#주요기능)<br/>
1). [메인 페이지](#메인페이지)<br/>
2). [회원정보 CRUD](#회원정보)<br/>
3). [게시물 CRUD](#게시물)<br/>
4). [게시판](#게시판)<br/>
5). [프로필](#프로필)<br/>
6). [기타 기능](#기타기능)<br/>

<br />

<a name='프로젝트개요' />

## 1. 프로젝트 개요

'대동유어지도'는 여행 콘텐츠에 특화된 위치 기반 SNS 플랫폼입니다. <br/><br/>
지역별 게시판에서 원하는 게시물을 확인하고, 나만의 특별한 여행 기록을 만들어 나갈 수 있습니다.<br/>

<br/><br/>

<a name='아이디어소개' />

## 2. 아이디어 소개

'대동유어지도'의 아이디어는 여행을 준비하는 과정에서 정보를 찾기가 너무 불편하다는 점에서 시작되었습니다.<br/><br/>
여행 정보를 얻기 위해서는 수많은 검색과 사이트 방문을 거쳐야 하고, 그마저도 정보의 부족이나 관련성 없는 정보들로 인해 원하는 정보를 찾지 못한 채, 시간만 낭비해버리는 일도 종종 있었죠.<br/>
또, 여행을 다녀온 뒤에는 단순히 여행 사진을 잔뜩 업로드한 뒤, 이곳이 어디였는지조차 까먹을 정도로 의미 없는 기록들을 하곤 했습니다 🤔<br/><br/>
그래서 저희는 여행자들, 즉 여행을 떠나려는 사람들과 여행에서 돌아온 사람들에게 정말 필요한 서비스를 개발하기로 했습니다.<br/>

<br/><br/>

<a name='기능소개' />

## 3. 기능 소개

이를 위해 '대동유어지도'는 기존의 사진 기반 SNS 방식에서 지역별 게시판과 각 지역별 업로드 양을 보여주는 히트맵, 나만의 히트맵 등의 기능을 추가하여 개발하기로 하였습니다.<br/><br/>
<img width="300" alt="스크린샷 2023-10-10 오후 11 22 08" src="https://github.com/daedongyourjido/.github/assets/90092013/4a0b444f-3f20-40aa-adf0-b393734e27ce">
<br/><br/>
사용자는 원하는 지역별 게시판에서 여행 정보를 얻어 여행 계획을 세울 수 있고, 여행을 다녀온 뒤 여행 게시물을 작성하여 나만의 히트맵을 채워감으로써 보람을 느낄 수 있습니다.<br/><br/>
이로써 '대동유어지도'는 여행 정보가 생산됨과 동시에 소비되도록 하여, 자연스럽게 최적화된 여행 콘텐츠를 제공할 수 있도록 개발된 플랫폼입니다.<br/>

<br/><br/>

<a name='기술스택' />

## 4. 기술 스택

### Environment
<img src="https://img.shields.io/badge/visual studio code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"> <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white"> <img src="https://img.shields.io/badge/github actions-F05032?style=for-the-badge&logo=githubactions&logoColor=white">

### Configuration
<img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white">

### FrontEnd
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white"> <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=white"> <img src="https://img.shields.io/badge/redux-764ABC?style=for-the-badge&logo=redux&logoColor=white"> <img src="https://img.shields.io/badge/kakao-FFCD00?style=for-the-badge&logo=kakao&logoColor=white"> <img src="https://img.shields.io/badge/mui-007FFF?style=for-the-badge&logo=mui&logoColor=white"> <img src="https://img.shields.io/badge/webpack-8DD6F9?style=for-the-badge&logo=webpack&logoColor=white"> <img src="https://img.shields.io/badge/cypress-17202C?style=for-the-badge&logo=cypress&logoColor=white">

### Communication
<img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white"> <img src="https://img.shields.io/badge/discord-5865F2?style=for-the-badge&logo=discord&logoColor=white"> <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">


<br/>

<a name='주요기능' />

## 5. 주요 기능 시연

<a name='메인페이지' />
<br/><br/>

### 1) 메인 페이지 (히트맵)

![heatMap](https://github.com/daedongyourjido/.github/assets/90092013/b0026172-a647-4b3e-a3ac-2299a6d658f8)

지도상에서 각 지역별로 업로드된 게시물의 양에 따라 폴리곤의 색상이 구분되어, **히트맵** 형식으로 표현됩니다. 게시물이 많이 업로드 될수록 밝은 색으로 표시되어, **지역별 인기도**를 한눈에 확인할 수 있습니다.

또한 지도 상에 커서를 올리게 되면, 현재 가리키고 있는 지역이 어떤 지역인지에 대한 정보와 함께, 해당 지역 게시판에 업로드된 게시물이 랜덤하게 슬라이드로 보여지게 됩니다.

<br/>

---

<br/>

<a name='회원정보' />

### 2) 회원 정보 CRUD

![login](https://github.com/daedongyourjido/.github/assets/90092013/25a939a7-66b4-450d-8911-50161e3935ee)

회원정보 관리 기능을 구현하였습니다. 회원가입부터 가입된 계정으로 로그인, 회원정보 수정, 탈퇴까지 가능하도록 하였습니다.

### a) 회원가입 

![signUp](https://github.com/daedongyourjido/.github/assets/90092013/8f01a4b8-ae55-4ee6-b78f-4b679a983248)

이메일과 비밀번호, 닉네임을 이용하여 **회원정보를 생성**할 수 있도록 하였고, 이메일은 **중복확인 절차**를 거치도록 하였습니다.

또한 **인증메일**을 발송하여 이메일 인증 절차를 구현하였습니다.

### b) 회원정보 수정

![changePropic](https://github.com/daedongyourjido/.github/assets/90092013/eb20ca87-0122-4f05-b20d-1bccd44b6846)

프로필 페이지로 이동하여 **프로필 사진**을 변경할 수 있고, 설정 페이지로 이동하여 **닉네임**과 **비밀번호**를 수정할 수 있도록 하였습니다.

### c) 회원정보 탈퇴

![withdraw](https://github.com/daedongyourjido/.github/assets/90092013/5613d3b7-ef5c-4940-8c6b-267096ff0142)

마지막으로 **회원정보 탈퇴 기능**까지 구현하였습니다.

<br/>

---

<br/>

<a name='게시물' />

### 3) 게시물 CRUD

### a) 업로드

![upload](https://github.com/daedongyourjido/.github/assets/90092013/74c75286-c000-4b62-90ef-ff29dc9c00dc)

게시물은 **이미지 / 지역 / 제목 / 내용**을 업로드할 수 있으며, 업로드 된 이후에는 해당 지역 게시물 페이지로 이동되어, 직접 게시물을 확인할 수 있도록 하였습니다.

### b) 수정

![update](https://github.com/daedongyourjido/.github/assets/90092013/05ca98c8-9889-4611-8054-16428c94b2af)

업로드된 게시물은 모든 내용을 **수정**할 수 있도록 구현하였습니다.

### c) 삭제

![delete](https://github.com/daedongyourjido/.github/assets/90092013/4a3c7174-c70b-4deb-8697-0fe52f697a14)

게시물을 **삭제**할 수 있습니다.

### d) 사용자 상호작용

![ezgif com-optimize](https://github.com/daedongyourjido/.github/assets/90092013/a55c0517-e587-48fb-a4cd-c9f78f2df37d)

게시물에 대한 **댓글과 좋아요** 기능을 구현하였습니다. 또한 **알림** 기능을 구현하여 사용자 상호작용을 강화하였습니다.

<br/>

---

<br/>

<a name='게시판' />

### 4) 게시판

각 지역별 게시판입니다. 

![board](https://github.com/daedongyourjido/.github/assets/90092013/1ad32ef9-311f-4296-833c-ca008a0abf7d)

페이지 우측에서 **게시물 목록**을 확인할 수 있습니다.

상단의 **필터**를 통하여 게시물을 최신순, 추천순, 오래된순으로 정렬하여 확인할 수 있으며, 마지막으로 자신이 **팔로우**한 사용자들의 게시물들을 모아 볼 수 있도록 하였습니다.

![boardRandom](https://github.com/daedongyourjido/.github/assets/90092013/831890ce-2b9f-4d9b-837a-0add4a9e07a3)

페이지 좌측에는 **추천 게시물**을 슬라이더로 넘겨볼 수 있도록 하였습니다. 원하는 게시물은 직접 확인할 수도 있습니다.

<br/>

---

<br/>

<a name='프로필' />

### 5) 프로필

### a) 나만의 히트맵

프로필 페이지에서는 해당 사용자가 지역별로 업로드한 게시물의 양에 따라 생성된 **히트맵**을 확인할 수 있습니다.

![myHeatMap](https://github.com/daedongyourjido/.github/assets/90092013/04d4037e-d81e-42ff-b090-03a0549b3518)

또한 위치별 필터에서는 지도 상의 원하는 지역을 클릭하여 해당 사용자가 업로드한 각 지역별 게시물들을 모아서 볼 수 있습니다.

### b) 팔로우 / 팔로워 리스트

![followFollower](https://github.com/daedongyourjido/.github/assets/90092013/7dace68c-0bab-4b15-860d-7fdeff6f140f)

정보를 클릭하여 **팔로우 팔로워** 리스트를 확인할 수 있습니다.

### c) 팔로잉

누군가를 **팔로우**할 수도 있습니다. 

![follow](https://github.com/daedongyourjido/.github/assets/90092013/745c97a8-f352-4e43-8fc8-cb2e39f91dce)

원하는 사용자의 프로필 페이지에서 **팔로우 버튼**을 클릭하여 팔로우를 **추가**할 수 있습니다.

팔로우 상태가 되면, 팔로우 버튼 대신 **팔로잉 상태**를 표시하게 됩니다. 해당 상태을 다시 클릭하여 팔로우를 **취소**할 수도 있습니다.

![unfollow](https://github.com/daedongyourjido/.github/assets/90092013/71ee41bc-cc9b-4306-8708-93cff3e8504f)

<br/>

---

<br/>

<a name='기타기능' />

### 6) 기타 기능

### a) 검색

검색창에서 **사용자 및 게시물**을 검색할 수 있습니다. 검색어를 입력하면 해당하는 결과가 표시됩니다.

![search-post](https://github.com/daedongyourjido/.github/assets/90092013/eed6631f-41f9-4c7d-9339-15a58c34031b)

결과로 **게시물**이 검색될 경우, 게시물을 직접 확인할 수 있습니다.

![search-user](https://github.com/daedongyourjido/.github/assets/90092013/0c8a851e-8c54-4a54-88f3-c567ccd5a69f)

결과로 **사용자**가 검색될 경우, 사용자를 팔로우하거나 프로필 페이지로 이동할 수 있습니다.


