---
title: "[AProject]자바스크립트 변수 선언 주의 사항"
date: "2021-07-16T20:40:32.169Z"
template: "post"
draft: false
slug: "work/AProject/no2"
category: "What I learned while working"
tags:
 - "work"
 - "AProject"
 - "javascript"
description: "자바스크립트 모듈 변수 선언시 주의 사항"
---

# 자바스크립트 모듈 변수 선언시 주의 사항
- - - - 

자바스크립를 모듈화 하여 사용 할 때 변수명을 지을때 주의 해야함

다른 모듈에서 중복으로 사용 할 수도 있기 때문에 변수를 묶어서 선언해주도록 함

```javascript

var member = {
    code : "100"
    name : "홍길동"
    age : "20"
}

console.log(member.code);
console.log(member.name);
console.log(member.age);


```
