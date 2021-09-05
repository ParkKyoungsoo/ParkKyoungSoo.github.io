---
layout: post
title: 마이리틀댕댕( Web Page )
featured-img: dangdang
---


# 마이리틀댕댕
<center><img src="https://user-images.githubusercontent.com/44697835/100569899-c99efd80-3312-11eb-90d4-7a27d688f3ac.gif" /></center><center>메인 페이지</center><br />


<center><img src="https://user-images.githubusercontent.com/44697835/100570793-ec321600-3314-11eb-8893-fe99ff044955.gif" /></center><center>성향 파악 설문 페이지</center><br />   


<img src="https://user-images.githubusercontent.com/44697835/100570387-04556580-3314-11eb-8283-a0b2a1c56621.png" width="49%"/><img src="https://user-images.githubusercontent.com/44697835/100570389-07e8ec80-3314-11eb-8dc6-bb82fb927584.png" width="49%"/><center>매칭동물 페이지(위: 리스트형 | 아래: 카드형)</center><br />    


  
    


## 목적
실시간 동영상 스트리밍 기능과 매칭 설문을 통한 유기견 입양 서비스


## 제작 기간
2020년 10월 12일 ~ 2020년 11월 20일


## 역할
vue와 vuex를 이용한 FE 개발 및 디버그, aws와 nginx를 이용한 front페이지 배포

## 내용
유기동물들의 보호소 생활을 실시간 스트리밍을 통해 보여주고, 설문을 통하여 나의 성향과 맞는 유기동물들을 추천해주는 웹 사이트 입니다.
동물들의 성격을 4가지 성향(순종성향, 활동성향, 적응성향, 관계성향)에 따라 총 16가지로 분류하였습니다.(ex. 활동성향 -> 동적성향, 정적성향) 동물들의 성격의 경우 임의로 결정을 하였으나, 사설 동물보호소의 인터뷰 결과 보호소에서는 각 동물들의 행동에 따라 성격이 파악 가능하다고 하였습니다.

해외 사이트인 https://pawslikeme.com/ 를 참고하여 사이트를 제작 하였습니다. 추가적으로 실시간 스트리밍을 통하여 유기동물이 보호소에서 적응하는 모습들과 이 동물들도 다른 반려동물들과 차이가 없다는것을 보여주고자 하였습니다. 또한 후원 시스템을 도입하여 유기동물 입양이 불가능한 이용자도 다른 방법으로 도움을 줄 수 있는 방법을 모색하였습니다.


## 후기
SSAFY에서 진행한 마지막 프로젝트입니다. 프로젝트 주제도 빨리 정해지고 개발도 빠르게 시작했다고 생각했지만 후반부로 갈수록 개발 시간이 촉박다하고 느껴졌습니다.
프로젝트에서 컴포넌트만 변경하기 위해 v-if문을 통하여 컴포넌트들을 변경하였으나, 프로젝트 마지막에 동적 컴포넌트를 알게 되어 프로젝트 일부분만 동적컴포넌트가 적용이 되어있습니다. 메인페이지에서는 트랜지션을 처음 사용해 보았습니다.
 


## 개발환경
![KakaoTalk_20201124_134153609](https://user-images.githubusercontent.com/44697835/100572262-631cde00-3318-11eb-99c7-1c1ed37d6720.png)
 
## Github
[마이리틀댕댕](https://github.com/ParkKyoungsoo/MyLittleDangDang)

## 시연영상
<style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; } .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style><div class='embed-container'><iframe src='https://www.youtube.com/embed/2DJOlpAY0xo' frameborder='0' allowfullscreen></iframe></div>
