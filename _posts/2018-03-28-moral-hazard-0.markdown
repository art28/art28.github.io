---
layout: post
title: "Moral Hazard"
date: "2018-03-28 22:21:21 +0900"
excerpt: "무엇을 공부할까요?"
tags: [Moral Hazard]
comments: true
---
본 포스트는 서울대학교 경제학부 김선구 교수님의 "계약 경제학" 수업을 기본으로 만들어졌습니다. 그 외에 다양한 논문들의 이론이나 해석들이 포함되어 있으나 필기를 세세히 하지 못하여 인용을 표시하지 못하는 점 미리 양해 부탁드립니다.
{: .notice}

# Theory of Contract
우리는 살면서 수많은 약속을 합니다. 학교나 회사에 정해진 시간에 나가는 것도, 등록금을 내거나 월급을 받는 것도 모두 일종의 약속입니다. 계약은 "약속"이 법률적 구속력을 가지는 형태를 의미합니다. 계약은 일상적인 약속과 달리 법적인 강제력을 가지기 때문에, 상호 신뢰에 기반한 안정적인 경제활동을 가능하게 합니다. 우리가 기상 천 외한 약속들을 만들어 낼 수 있듯이, 계약도 당사자들의 이해관계에 따라 무한한 형태로 나타날 수 있습니다. 예를 들어, 특히 보험 쪽에서 신기한 계약들이 많은데, 일본의 한 보험회사는 건강보험 계약의 일부로, 하루의 8000보 이상을 걸으면 보험료의 일부를 현금으로 돌려준다고 합니다.([참조](http://www.edaily.co.kr/news/news_detail.asp?newsId=01977846615966640&mediaCodeNo=257){:target="_ blank"}). 보험 회사는 피보험자가 건강 관리를 소홀히 하는 것을 막고, 피보험자는 자신의 건강을 관리하면서 돈을 더 받는 선택지를 하나 더 고를 수 있게 되는 것이죠.

문제는, 계약의 이러한 이점에도 불구하고, 계약을 통해서 완벽하게 통제할 수 없는 행동들이 있다는 사실입니다. 특히 최악의 경우에는 계약을 통해 계약의 당사자 모두가 얻는 효용이 감소하기도 합니다. 우리는 이 중 특정한 계약 문제의 해결에 초점을 맞출 것입니다.

## The Basics in the Principal-Agent Model
우리는 수많은 계약 중에서도, 주인(Principal-P)과 대리인(Agent-A)을 주로 살펴볼 것입니다. 주인-대리인 모델은 사회의 많은 곳에서 발견할 수 있습니다. 가장 흔하게는 기업의 주주(주인)와 CEO(대리인), 같은 곳에서 시선을 좀 더 내려서 CEO(주인)와 직원(대리인), 과거로 가면 지주(주인)와 소작농(대리인), 그리고 위에서 언급한 보험 사례도 주인(보험회사)과 대리인(피보험자)의 관계입니다.

## Moral Hazard
Moral Hazard는 한국에 "도덕적 해이"라는 직역으로 더 많이 알려져 있습니다.
>감추어진 행동이 문제가 되는 상황에서 정보를 가진 측이 정보를 가지지 못한 측의 이익에 반하는 행동을 취하는 경향을 말한다.

네이버 백과의 도덕적 해이에 대한 정의입니다. 재밌는 점은, 정의에 "도덕"이라는 단어가 전혀 등장하지 않는다는 사실입니다.
사실, 도덕적 해이는 전혀 '도덕적'인 현상이 아닙니다. 도덕적 해이는 철저히 경제적인 현상으로, 주인-대리인 모델에서 나타나는 문제입니다. 도덕적 해이를 이 관점에서 다시 정의해보겠습니다.

1. 주인(Principal)이 대리인(Agent)에게 행동(Action)을 위임한다(**Action Delegation**)
2. 주인은 대리인의 행동 선택을 직접적으로 관찰할 수 없다.(**Information Asymmetry**)
- 다만 그 선택과 불완전하게 연관된 다른 몇몇 변수들은 관찰할 수 있다.
3. 주인은 대리인이, 자신(주인)의 이익을 위해 행동하기를 원한다. 하지만 대리인은 대리인 자신의 이익을 위해서 행동한다.(**Conflict of Interest**)

요약하면, 주인이, (1) 대리인에게 어떤 행위를 위임하는 계약의 형태에서, (2) 대리인이 어떤 행동을 할지 직접 관찰할 수 없는 상황에, (3) 주인과 대리인의 이해관계가 동일하지 않음으로써 발생하는 문제입니다. 이 정도면 많은 계약을 포함할 수 있다는 게 느껴지시나요?

## (참고) Adverse Selection
역선택(Adverse Selection) 문제 역시 계약 문제의 일종이고, 도덕적 해이와 혼동하기 쉬운, 매우 유사한 개념입니다. 이 포스팅 시리즈에서 주로 다룰 내용은 아니지만, 도덕적 해이와의 차이점을 대조해보면 도덕적 해이가 어떤 상황을 의미하는지 더 쉽게 파악할 수 있을 것 같아 설명해봅니다.

|         | 변수     | 변수의 특징 |  목표 |
|:--------|:-------:|--------:|---------:|
| **도덕적 해이**<br/>Hidden-Action problem| 대리인의 **노력**<br/>대리인의 **선택**| 선택하는 것<br/>주인이 통제할 수 있다.   | 어떻게 대리인이 주인을 위한 <br/>행동을 하게 만들수 있을까?
|----
| **역선택**<br/>Hidden-Knowledge problem   | 상대방의 **특성**<br/>상대방의 **기호**   | 주어진 것<br/>주인이 통제할 수 없다.   | 어떻게 상대방이 자신의 특성을 <br/>진실되게 드러내도록 할 수 있을까?
{: rules="groups"}

역선택은 **불완전한 특징 정보**로 인해 합리적으로 계약을 선택할 수 없는 상태를 의미합니다. 예를 들어, 제가 작년에 서울대입구역 레코드 상점에서 디자인이 예뻐 보이는 이어폰을 하나 샀습니다. 하지만 휴대폰에 꼽아 음악을 들어보니 온갖 소음과 난해한 사운드로 하루 만에 폐기 처분하였는데요, 이런 경우가 상품의 특성을 구매 계약 이전에 알 수 없는 데서 오는 역선택의 전형적인 사례라고 할 수 있습니다. 따라서 역선택에서는 이 정보 비대칭을 해결하는 데 초점을 둡니다. 왜냐하면 이미 존재하는 이어폰의 품질을 계약 전후로 올릴 수는 없기 때문입니다. 반면에 우리가 집중해서 볼 도덕적 해이는, 정보 비대칭 상황에서, 대리인이 스스로 주인에게도 유리한 행동을 선택하는 것이 자신에게도 이득이 되는, 주인이 대리인에 특정 행동을 유도(induce)하는 해결 방식에 초점을 둔다는 차이가 있습니다.


## 도덕적 해이의 사례
더 확실한 이해를 위해 도덕적 해이의 사례 몇 개를 위의 정의에 맞추어 소개하겠습니다.
1. 주주(주인) - CEO(대리인)
- Action-Delegation: 회사 경영(Management)
- Interest-Confilction: 기업 가치 극대화 vs 개인적 이익
- 사례: 회사의 공적 자원을 사적으로 사용하는 것(Overuse of Perk), 이사회 장악(Managerial Entrenchment), 고위험 사업 투기(Dual Agency Problem)
2. CEO(주인) - 직원(대리인)
- Action-Delegation: 업무(Work)
- Interest-Confilction: 근면 노동 vs 게으른 노동
- CEO는 직원이 열심히 일하기 원하지만, 직원은 해고되지 않고 같은 임금을 받는 선에서 최대한 게으르게 일하려 한다.
3. 지주(주인) - 소작농(대리인)
- Action-Delegation: 경작(Cultivate)
- Interest-Confliction: 소작농이 자기가 직접 소유한 땅만 열심히 경작하고, 지주에게 대여한 땅은 소홀히 대하는 경우
4. 보험회사(주인) - 피보험자(대리인)
- Action-Delegation: 주의 의무(Due care)
- Interest-Confilction: 예를 들어 18세기 영국에서 존재했던 화재보험의 전액 보장 체계의 경우, 자기 집에 불이 나는 것을 방조하는 경우가 종종 있었다고 한다.
5. 유권자(주인) - 정치인(대리인)
- 주인-대리인 문제는 생각보다 가까운 많은 곳에 존재합니다.

## 마무리
사실 계약 세부 내용의 번형을 통해 주인-대리인 문제를 해결하는 방식이 오래된 전통은 아닙니다. 특히 위의 사례 중 지주와 소작농 간의 문제는, 불과 몇십 년 전까지만 하더라도, 소유권이 달라서 생기는 현상이기 때문에 지주가 소작농에게 토지를 파는 극단적인 소유권 이전으로만 해결할 수 있다는 Chicago 학파의 의견이 주류를 차지하고 있었습니다. 이 문제를 계약으로 풀 수 있다는 가능성을 제시한 사람은 한 중국인 학자였다고 합니다. 그리고 현재에는 실제로 다양한 형태의 계약을 통해 몇몇 도덕적 해이 문제를 극복하고 있습니다. 다음 포스팅에는 실제로 현실에서 자주 보이는 계약의 유형과 그 경제학적 함의에 대해 알아보도록 하겠습니다.

<br/>
<h4 style="text-align:right"> <a href="/blog/moral-hazard-1"> 다음 포스트 : Contract Examples</a></h4>
