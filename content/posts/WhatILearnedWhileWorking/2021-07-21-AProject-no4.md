---
title: "[AProject]자바스크립트 캐시"
date: "2021-07-25T20:40:32.169Z"
template: "post"
draft: false
slug: "work/AProject/no4"
category: "What I learned while working"
tags:
 - "work"
 - "AProject"
 - "javascript"
 - "cash"
description: "자바스크립트 캐시"
---

# 자바스크립트 캐시
- - - - 


자바스크립트 첨부 할 떄

```html
<script type="text/javascript" src="js/check.js">
```

위와 같은 방식은 js 파일을 수정했을 경우 캐시로 인해 수정된 내용이 바로 적용되지 않음


```html
<script type="text/javascript" src="<c:url value="js/check.js"/>">
```
위와 같은 방식은 수정했을 경우 캐시없이 바로 적용 됨
