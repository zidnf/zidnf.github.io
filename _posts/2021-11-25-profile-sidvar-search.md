---
layout: single
title: "github blog author profile, sidebar, 검색기능"
categories: github
tag: github
toc: true
author_profile: false
sidebar:
    nav: "docs"
---



# 1. author profile show/hide

![화면 캡처 2021-11-25 090803](/images/2021-11-25-profile-sidvar-search/화면 캡처 2021-11-25 090803.png)

좌측에 보이는 author profile이 게시물에도 따라다니는데

이걸 보이게 안보이게 하는 옵션이

![화면 캡처 2021-11-25 090940](/images/2021-11-25-profile-sidvar-search/화면 캡처 2021-11-25 090940.png)

해당 md파일 상단에

author_profile: false를 주시는겁니다

![화면 캡처 2021-11-25 091432](/images/2021-11-25-profile-sidvar-search/화면 캡처 2021-11-25 091432.png)

author profile이 사라진것을 확인할 수 있습니다



# 2. sidebar navigation

author profile 대신 메뉴가 있는 sidebar로 변경이 가능한데

해당 게시물 md파일에

일단 author_profile: false 를 해주시고

![화면 캡처 2021-11-25 092551](/images/2021-11-25-profile-sidvar-search/화면 캡처 2021-11-25 092551.png)

_data폴더에 있는 navifation.yml 파일을 열어주세요

![화면 캡처 2021-11-25 093350](/images/2021-11-25-profile-sidvar-search/화면 캡처 2021-11-25 093350.png)

다 적으셨으면 다시 md파일로 돌아오셔서

![화면 캡처 2021-11-25 093701](/images/2021-11-25-profile-sidvar-search/화면 캡처 2021-11-25 093701.png)

sidebar:

​	nav: "docs"

설정을 해주시면 됩니다

![화면 캡처 2021-11-25 093923](/images/2021-11-25-profile-sidvar-search/화면 캡처 2021-11-25 093923.png)

author profile대신

저희가 설정한 sidebar가 나오게 됩니다

클릭하면 해당 링크가 잘 설정된 것을 확인할 수 있습니다



# 3. 검색기능

![화면 캡처 2021-11-25 094704](/images/2021-11-25-profile-sidvar-search/화면 캡처 2021-11-25 094704.png)

_pages 폴더에

search.md파일을 하나 생성하도록 하겠습니다

![화면 캡처 2021-11-25 094843](/images/2021-11-25-profile-sidvar-search/화면 캡처 2021-11-25 094843.png)

해당 search.md파일에 적어주시면 됩니다



_data폴더에 navigation.yml파일로 오셔서

![화면 캡처 2021-11-25 095001](/images/2021-11-25-profile-sidvar-search/화면 캡처 2021-11-25 095001.png)

main부분에 title과 url을 적어주시면 됩니다



![화면 캡처 2021-11-25 095318](../images/2021-11-25-profile-sidvar-search/화면 캡처 2021-11-25 095318.png)

그러면 오른쪽 상단에 Search링크가 걸리게 됩니다

![화면 캡처 2021-11-25 095338](../images/2021-11-25-profile-sidvar-search/화면 캡처 2021-11-25 095338.png)

원하는 게시물을 쉽게  찾으실 수 있습니다



만약 해당 게시물이 검색이 되는 것을 원치 않으시면

해당 게시물 md파일 상단에

search: false

를 넣어주시면 해당 게시물은 검색이 되지 않습니다
