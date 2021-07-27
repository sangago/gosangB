---
title: "[AProject]오픈그래프"
date: "2021-07-22T20:40:32.169Z"
template: "post"
draft: false
slug: "work/AProject/no3"
category: "What I learned while working"
tags:
 - "work"
 - "AProject"
 - "open graph"
 - "meta tag"
 - "cash"
description: "카카오스토리와 페이스북 공유하기에서의 오픈그래프"
---

# 카카오스토리와 페이스북 공유하기에서의 오픈그래프 유의사항
- - - - 


## 공유하려는 링크는 인코딩 해야함.


파라미터뿐만 아니라 전체링크를 인코딩 해야 함

링크를 공유하면 링크를 카카오스토리(또는페이스북)페이지에서 한번 더 암호화 함

예를들어 https://www.naver.com?member=홍길동 링크를 암호화 하는 경우 

링크가 암호화 되면서 예약문자가 생길 수도 있음. (/ :  = & + -)

복호화 하는 과정에서 예약 문자로 인해 URL주소가 온전하지 않음.



## OG TAG를 수정했는데 내용이 바뀌지 않는 경우 캐시 삭제

카카오톡, 카카오스토리, 페이스북 모두 캐시를 직접 제거해줘야 함


- 카카오

https://developers.kakao.com/tool/clear/og


- 페이스북

https://developers.facebook.com/tools/debug
