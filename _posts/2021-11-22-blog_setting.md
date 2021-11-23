---
layout: single
title: "github blog 설정"
categories: github
tag: github
---

이번에는 간단한 블로그 설정을 알아볼껀데

간단한 예제들만 다룰 예정이니 본인이 좀 더 꾸미거나 많은 걸 해보고 싶으시다면

https://mmistakes.github.io/minimal-mistakes/docs/configuration/

사이트에 많은 정보들이 있습니다



우선 Visual Studio Code를 켜주셔야합니다
Typora처럼 파일 -> 폴더 열기 -> github 폴더 선택 방식으로
불러 오시면 됩니다

폴더 트리쪽에 보시면 _config.yml이라는 파일을 이용해
설정값을 바꿔보겠습니다

![스크린샷(59)](/images/2021-11-22-blog_setting/스크린샷(59).png)

기존 default값입니다



![스크린샷(57)](/images/2021-11-22-blog_setting/스크린샷(57).png)

- 15번 라인 minimal_mistakes_skin

  테마를 설정값입니다

  default를 -> plum 으로 바꿔보겠습니다

![스크린샷(58)](/images/2021-11-22-blog_setting/스크린샷(58)-16376881540201.png)

테마가 변경된것을 확인할 수 있습니다

(저는 다시 default로 바꿨습니다)

![스크린샷(60)](/images/2021-11-22-blog_setting/스크린샷(60).png)

- 18줄 locale설정 (언어설정)

  en-US -> ko-KR

- 19줄 좌측상단 title

  본인이 원하는 title

- 20줄 윈도우 title

  '|' 로 구분값 설정

- 21줄 좌측상단 subtitle

  본인이 원하는 subtitle

- 22줄 하단 이름

  본인이 원하는 이름

![스크린샷(44)](/images/2021-11-22-blog_setting/스크린샷(44).png)

![스크린샷(58-1)](/images/2021-11-22-blog_setting/스크린샷(58-1)-16376887441982.png)

![화면 캡처 2021-11-24 023634](/images/2021-11-22-blog_setting/화면 캡처 2021-11-24 023634.png)

- 103줄 Site Author

  좌측 이름 , bio , 사는 곳 , 이메일

![스크린샷(64)](/images/2021-11-22-blog_setting/스크린샷(64).png)





![스크린샷(61)](/images/2021-11-22-blog_setting/스크린샷(61).png)

- 28줄 로고

  우선 폴더를 하나 만들건데

  assets안에 images라는 폴더를 하나 생성해 줍니다

  ![스크린샷(62)](/images/2021-11-22-blog_setting/스크린샷(62).png)

  그다음 드래그 앤 드랍으로 원하시는 로고 사진을 images폴더에 넣습니다

  

  ![스크린샷(63)](/images/2021-11-22-blog_setting/스크린샷(63).png)

  뒤에 적혀있는 "/assets/images/88x88.png"만 남기시고 

  주석은 지워주시면 됩니다

  그다음 자신이 넣은 이미지 파일명만 바꾸시면 로고가 바뀌는것을 확인하실 수 있습니다

  "/assets/images/88x88.png" -> "/assets/images/img.jpg"
  ![스크린샷(64)](/images/2021-11-22-blog_setting/스크린샷(64)-16376901111313.png)



![스크린샷(65)](/images/2021-11-22-blog_setting/스크린샷(65).png)

- 30줄 네비게이션 추가

  주석을 풀어주시고 false를 true로 바꿔주시면 됩니다

![스크린샷(66)](/images/2021-11-22-blog_setting/스크린샷(66).png)

게시판에 들어가 보시면 게시물 상단에 

네비게이션이 생성되었습니다



![스크린샷(68)](/images/2021-11-22-blog_setting/스크린샷(68).png)

- 279줄 게시글 날짜 표기

  가장 하단에  show_date: true 와

  date_format: "%Y-%m-%d"를 넣어주시면 됩니다
  ![스크린샷(69)](/images/2021-11-22-blog_setting/스크린샷(69).png)

