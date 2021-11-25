---
layout: single
title: "github blog 공지사항, 버튼, 영상추가"
categories: github
tag: github
toc: true
author_profile: false
---



오늘은 공지사항, 버튼, 영상 추가하기를 해보겠습니다



# 1. 공지사항 (notice)

https://mmistakes.github.io/minimal-mistakes/docs/utility-classes/

주소에 오시면

![화면 캡처 2021-11-25 122351](/images/2021-11-25-notice-button-video/화면 캡처 2021-11-25 122351.png)

여러가지 예시들이 있는데

공지사항 글귀 뒤에 

{}안에 

본인이 원하시는 설정값을 적어주시면 됩니다

저는 : .notice--warning 라는 설정값을 넣어주겠습니다



![화면 캡처 2021-11-25 123541](/images/2021-11-25-notice-button-video/화면 캡처 2021-11-25 123541.png)


해당 게시물 md파일로 오셔서 

공지사항을 한번 적어보겠습니다

공지사항 예시
{: .notice--warning}

![화면 캡처 2021-11-25 123726](/images/2021-11-25-notice-button-video/화면 캡처 2021-11-25 123726.png)

베너형식으로 나오게 됩니다

한줄이 아니라 여러줄에 적용하고 싶으시다면



![화면 캡처 2021-11-25 123909](/images/2021-11-25-notice-button-video/화면 캡처 2021-11-25 123909.png)

가장 마지막 부분 

Notice Headline에 적혀있는것 처럼 

div테그로 감싸주시면 됩니다



![화면 캡처 2021-11-25 124156](/images/2021-11-25-notice-button-video/화면 캡처 2021-11-25 124156.png)



<div class="notice--warning">
공지사항 예시
이 안에는 html테그가 들어올 수 있으십니다
<ul>
    <li>예시1</li>
    <li>예시2</li>
</ul>
</div>

![화면 캡처 2021-11-25 124710](/images/2021-11-25-notice-button-video/화면 캡처 2021-11-25 124710.png)



# 2. 버튼



![화면 캡처 2021-11-25 125138](/images/2021-11-25-notice-button-video/화면 캡처 2021-11-25 125138.png)

해당 사이트에 가시면 버튼에 대한 설명이 잘 나와있는데

이중 Success 를 한번 만들어보겠습니다



![화면 캡처 2021-11-25 125411](/images/2021-11-25-notice-button-video/화면 캡처 2021-11-25 125411.png)

드래그 한 부분을 복사

게시물 md파일로 오셔서 붙여넣기

![화면 캡처 2021-11-25 125533](/images/2021-11-25-notice-button-video/화면 캡처 2021-11-25 125533-16378126981281.png)



link는 구글 홈페이지로 적어보겠습니다

![화면 캡처 2021-11-25 125934](/images/2021-11-25-notice-button-video/화면 캡처 2021-11-25 125934.png)



[Text](https://google.com){: .btn .btn--success}

