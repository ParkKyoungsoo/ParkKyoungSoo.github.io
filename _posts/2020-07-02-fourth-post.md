---
layout: post
title: Happy House( Web Page )
featured-img: mainbg1
---


# Happy House
![HappyHouseMain](https://user-images.githubusercontent.com/44697835/86885828-e3a42d80-c130-11ea-9519-b94d80e11ba2.png)<center>메인 페이지</center>  


  
![HappyHouseBoard](https://user-images.githubusercontent.com/44697835/86887150-1bac7000-c133-11ea-9532-16bfbac082ab.png)<center>공지사항 페이지</center>    



![HappyHouseSearch](https://user-images.githubusercontent.com/44697835/86887247-3ed71f80-c133-11ea-8242-16edf65fecd5.png)<center>부동산 매물 조회 및 주변 상권 조회</center>  

  
    


### 목적
공공 데이터 API와 구글 맵 API를 사용한 부동산 매물 조회 사이트


### 제작 기간
2020년 5월 ~ 2020년 6월


### 내용
공공 데이터 API와 구글 맵 API를 사용하여 이용자들에게 시,도 별 부동산 거래정보를 제공하는 웹 페이지 입니다. 

공공 데이터 중 아파트 매매, 전/월세, 연립다세대 매매, 전/월세 데이터, 상권 데이터와 구글맵 API를 사용하여 이용자에게 정보를 제공합니다. 

시ㆍ도, 구ㆍ군, 읍ㆍ면ㆍ동 코드와 거래형식(아파트 매매, 아파트 전/월세, 연립다세대 매매, 연립다세대 전/월세)을 이용하여 데이터들을 조회한 뒤 데이터에 있는 좌표를 이용하여 구글 맵에 마커들을 표시합니다. 해당 마커들을 클릭 할 시 선택한 건물에 대한 모든 매물 목록들을 조회 할 수 있습니다.

또한 상권 데이터 API에서 반경과 상권 코드를 이용하여 지도 중심에서 특정 반경내에 있는 상권들을 조회 할 수 있습니다. 상권은 7가지의 코드(소매, 음식, 여가, 교육, 생활, 숙박, 부동산) 로 구분이 됩니다.

추가적으로 최근에 이슈가 되고 있는 코로나의 상황을 보여주고자 해당 시ㆍ도에서 1개월동안의 코로나 확진자, 격리해제, 사망자수를 구글 차트 API를 이용하여 표시해 주고 있습니다. 해당 데이터는 공공 API에 반영되어 있는 가장 최근의 1개월 데이터 입니다.

공지사항에서는 로그인 한 유저가 관리자인 경우에만 글 작성, 수정, 삭제가 가능합니다. 게시판 페이지에서는 페이징 처리를 하여 한 페이지에 최대 10개의 글이 표시가 됩니다. 각 글들은 작성자 ID, 글 번호, 글 제목으로 검색이 가능 합니다. 



### 개발환경
![html_css_js](https://user-images.githubusercontent.com/44697835/86319956-acd1a180-bc70-11ea-946e-09a11a71fb27.png) &nbsp; &nbsp; ![vue](https://user-images.githubusercontent.com/44697835/86319509-a3940500-bc6f-11ea-815e-6f7612ee657a.png) &nbsp; &nbsp; ![jquery_2](https://user-images.githubusercontent.com/44697835/86319481-9a0a9d00-bc6f-11ea-855e-e0bf301d8185.png)  &nbsp; &nbsp;  ![java](https://user-images.githubusercontent.com/44697835/86319460-9119cb80-bc6f-11ea-9cb2-92a5c15f47b5.png) &nbsp; &nbsp; ![springboot_2](https://user-images.githubusercontent.com/44697835/86319498-9f67e780-bc6f-11ea-8c9d-ae4c7948c638.png)  &nbsp; &nbsp;  ![mysql](https://user-images.githubusercontent.com/44697835/86319496-9d058d80-bc6f-11ea-9e23-93d8990d2fd4.png) 


