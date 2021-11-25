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

<div class="notice--warning">
공지사항 예시
이 안에는 html테그가 들어오실수 있으십니다
<ul>
    <li>예시1</li>
    <li>예시2</li>
</ul>
</div>













