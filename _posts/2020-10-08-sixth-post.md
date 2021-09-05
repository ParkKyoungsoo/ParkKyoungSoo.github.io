---
layout: post
title: 머물래( Web Page )
featured-img: home1
---


# 머물래
![메인화면](https://user-images.githubusercontent.com/44697835/100577048-b562fc80-3322-11eb-83c2-63f08e8b6c0f.png)<center>메인 페이지</center>  
 
![파티모집](https://user-images.githubusercontent.com/44697835/100577053-b72cc000-3322-11eb-9c7a-fc327de7c186.png)<center>배달 파티 모집</center>    

![채팅](https://user-images.githubusercontent.com/44697835/100577058-b8f68380-3322-11eb-91da-25b35a74f815.png)<center>파티 모집을 위한 채팅</center>    

![리뷰](https://user-images.githubusercontent.com/44697835/100577059-ba27b080-3322-11eb-8391-34d31ce283c7.png)<center>리뷰 작성</center>  

  
    


## 목적
사용자의 위치 및 리뷰 기반 배달음식 추천 서비스 및 배달최소금액 충족을 위한 배달 파티 시스템


## 제작 기간
2020년 8월 31일 ~ 2020년 10월 08일


## 역할
Vue를 이용한 각 페이지 제작 및 AWS, NGINX를 이용한 무중단 배포

## 내용
SSAFY에서 제공된 맛집데이터를 분석하여 유저의 리뷰, 위치기반 배달음식 추천 사이트 입니다. 또한 배달을 시킬때 최소 주문금액 및 배달료에 대한 부담을 해결하고자 배달 파티 시스템을 생각하였습니다. 사용자 A가 특정 가게의 치킨에 대해 배달 파티를 모집하면, 같은 주소의 사이트 이용자 B가 해당 파티에 참여하게 되고 치킨값 + 배달료는 2명의 사용자가 계산을 하게 됩니다. 이에 대한 금액 계산은 카카오페이의 더치페이 기능을 사용할 예정이었으나, 실제 사업자 발급을 할 수 없기에 구현까지는 할 수 없었습니다.


## 후기
여러모로 부족함이 많았던 프로젝트 였습니다. 처음으로 팀장을 맡아 진행을 하였으나 팀원의 역할 분배 실패, 지체된 주제 선정으로 인해 개발의 시작이 많이 늦었습니다. 또한 Django를 AWS에서 실행시키던 도중 권한부여를 잘못하는 바람에 제공되었던 aws서버에 접근을 할 수 없었고, 이 때문에 개인 aws서버에 Django를 다시 올려야 했습니다. 때문에 온전히 개발에 집중하지 못하고 서버와 사루틑 하는 과정때문에 프로젝트가 더욱 딜레이 되었습니다. 이러한 딜레이 때문에 빅데이터 분석에 필요한 알고리즘등을 전혀 관여하지 못해 빅데이터를 이용한 프로젝트를 했다고 말 할수 없는 프로젝트가 되버렸습니다.

프로젝트를 진행하면서 팀장에게 필요한 역량은 개발 뿐만이 아니라는것을 배울 수 있는 프로젝트였습니다.


## 개발환경
![image](https://user-images.githubusercontent.com/44697835/95402712-58168480-094b-11eb-84c9-a26053ea8b36.png)

## Github
[머물래](https://github.com/ParkKyoungsoo/meomulrea)


## 시연영상
<style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; } .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style><div class='embed-container'><iframe src='https://www.youtube.com/embed/D3KPND9Nt7c' frameborder='0' allowfullscreen></iframe></div>
