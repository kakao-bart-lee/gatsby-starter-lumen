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

자바스크립트, 타입스크립트 초보가 이런 코드를 처음 봤을 때의 느낌을 표현하자면 "ㅖ?" 였습니다.

next.js 의 프로젝트 혹은 디렉토리의 구조도 익숙하지 않습니다. 먼저 프런트엔트..의 리액트쪽도 있고 여기에 next.js의 API 서버 기능에.. 디렉토리 단위로 API 라우팅을 잡아주다보니 꽤나 복잡해보입니다. 또, (프런트쪽을 제대로 보지 못하여 확실하진 않지만) 프런트와 백엔드에서 공통으로 사용되는 유틸리티 혹은 기타 모듈 등을 같은 디렉토리 하위에서 관리하는 것도 백엔드는 백엔드에서 프런트엔드는 프런트엔드에서 해왔던 경험으로써는 편하지는 않습니다. 나중에 앞이나 뒤 중 어느 한쪽에만 scale out 혹은 긴 작업들이 필요해지는 시점에 어떻게 해야할지 상상을 해보면 결국 레알 백엔드 레이어가 하나 더 생기지 않을까 하네요.

'좋은' 프로젝트 구조에 대해서도 코드 리뷰 중 이야기가 나왔는데요.

- https://stackoverflow.com/questions/53854104/is-this-next-js-folder-structure-recommended
- https://dev.to/vadorequest/a-2021-guide-about-structuring-your-next-js-project-in-a-flexible-and-efficient-way-472

를 참고해보면 좋을 것 같습니다. 뭐가 정답인지는 모르겠어요. 다른 웹프레임웍 할 때도 한번은 컴포넌트의 성격별로 모아보거나 주제별로 모아보거나 했는데 각기 장단점이 있었씁니다.

## Code review

현재 회사, 부서에서는 안타깝게도 코드리뷰를 깊게 하지는 못하고 있습니다. 핑계일 수 있지만 일에 비해 사람이 많이 부족하다보니 페어는 커녕 각기 다른 일을 하는 경우가 허다 합니다. 그래서 리뷰 요청이 오더라도 해당 주제에 대해 같이 알고 있지 못하는 경우가 많아 리뷰라기보단 스크리닝에 가까운 절차로 진행하고 있습니다.

이번 스터디에서는 같은 주제와 기능에 대해 각기 자기만의 방식으로 개발하고 서로 리뷰하니 실력에 관계없이 배울점이 있어 참 좋네요.


![corin](/media/nodejs/roll-out-corin.png)

코딩 초보를 과연 탈출할 수 있을 것인가!