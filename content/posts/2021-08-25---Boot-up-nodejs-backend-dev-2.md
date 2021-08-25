---
title: 실가백개발 (2주차)
date: "2021-08-25T02:05:37.121Z"
template: "post"
draft: false
slug: "node-js-study-2"
category: "dev"
tags:
  - "nodejs"
  - "typescript"
  - "javascript"
  - "programmers"
description: "javascript 코린이 탈출을 위한 몸부림"
socialImage: "/media/nodejs/nodejs_bg.png"
---

[![nodejs_bg](/media/nodejs/nodejs_bg.png)](https://programmers.co.kr/learn/courses/12547)

## Intro

[실무와 가까워지는 Node.js 백엔드 개발](https://programmers.co.kr/learn/courses/12547) 2주차 내용 입니다.

지난주와는 달리 무척이나 격하게 달린 강의 & 스터디였습니다. 지난주가 스트레칭하고 50m 달리기 했다면 이번주는 5000m 달리기 한 것 같아요. 왠지 다음주는 철인 3종 경기 할듯. 여러가지로 힘들었는데요.

일단 표면상으로는 많이 완성된, 프런트쪽은 완성이고 백엔드쪽도 틀은 갖추어진 next.js 로 구축된 서비스에서 부족한 API를 채워나가는 과정입니다. 아마 다른 백엔드 작업 해보신 분들은 대충 감 잡으실꺼에요. 어떤 느낌인지. 그런데.. 한번도 실무.. 까지도 아니고 API 제공을 안해본 사람이라면 좀 어렵지 않을까 싶었어요. 실제로 저랑 같이 듣는 분도 수업 듣으며 멘붕 오셨습니다. 저 역시도 typescript나 next.js 에 익숙하지 않기 때문에 꽤 빠른 호흡으로 진행되는 강의를 따라가기 힘들었습니다.

![super_fast_class](/media/nodejs/super_fast_class.png)

javascript나 typescript 를 아주 짧게 짧게 이미 있는 코드를 수정해본 것이 다여서 지금처럼 본격적으로 코드를 작성해본 것은 처음이라 생소한 내용들이 많았습니다. 평소 트위터에 돌아다니는 javascript meme을 보면서 저것은 해로운 언어다 라고 두려워하고 있긴 했습니다만 다른 언어에서 보지 못했던 내용들을 보니 무섭긴 하네요.

## What did I learn

[구조분해할당(Destructuring assignment)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment)

제일 무서웠던 부분입니다. typescript여서 그나마 좀 괜찮았는데 type이 없는 javascript였다면.. 뭔가 작성자가 모르는 사이에 이상한 값이 들어가지 않을까 하는 부분이었습니다. 전개 구문(spread syntax)과 함께 사용하면 코드량을 많이 줄여주긴 하는데,

![dest_spread](/media/nodejs/dest_spread.png)

코린이가 이런 코드를 처음 봤을 때의 느낌을 표현하자면 "ㅖ?" 였습니다.

리팩토링 부분은 스터디 대장님이 리뷰 달아주시면 이어서 하겠습니다.


![corin](/media/nodejs/roll-out-corin.png)

코딩 초보를 과연 탈출할 수 있을 것인가!