---
title:  "[Code Complete 2] 7부 - 소프트웨어 장인정신"
search: true
categories: 
  - 독서
tags:
  - CodeComplete2
classes: wide
---

# 31장: 레이아웃과 스타일
## 31.1 레이아웃 기초 지식
## 31.2 레이아웃 기법
## 31.3 레이아웃 스타일
## 31.4 제어 구조의 레이아웃
## 31.5 개별 명령문 레이아웃
- 여러분이 작성한 코드를 읽게 될 사람을 불쌍히 여겨라. 
## 31.6 주석 레이아웃
## 31.7 루틴 레이아웃
## 31.8 클래스 레이아웃
참고 서적

# 32장: 스스로를 설명하는 코드
## 32.1 외부 문서
## 32.2 문서화를 위한 프로그래밍 스타일
## 32.3 주석을 작성할 것인가? 작성하지 않을 것인가?
## 32.4 효과적인 주석을 위한 핵심 사항
- 주석 쓰는 데 시간이 많이 드는 경우
  - 1. 주석 작성방식이 복잡한 경우, 새로운 방식을 찾아라. /***/ 이런거로 시간낭비 하지 말고. 작성방식 자체가 복잡하면 수정도 복잡해서 업데이트도 안되고 없느니만 못하다.
  - 2. 프로그램이 뭘 하는지 몰라서 주석 쓰는 게 어려운 경우. 주석과는 상관없이, 반드시 시간을 들여 프로그램을 이해하고 넘어가야 하는 상황이다.
- 코드를 짜느라 주석 쓰는 일이 방해처럼 느껴진다면 코드가 너무 복잡하다는 듯이다. 설계를 단순화해라. 의사코드를 먼저 설계하고 그걸 주석으로 바꾸는 시도를 하라. 
## 32.5 주석 스타일
- 코드의 목적을 써라. 행위를 쓰지 말고. '문자열에서 $를 찾는다' 라고 하지 말고, '문자열 마지막 글자($)를 찾는다' 이런 식으로.
- 생략하지 마라. 좋은 프로그래밍 방식을 어긴 이유를 써라. 트리키한 코드에 주석 달지 말고, 코드를 고쳐라. 
## 32.6 IEEE 표준
- N/A

# 33장: 개발자의 성격
## 33.1 성격은 주제를 벗어난 것 아닌가?
- 훌륭한 프로그래머가 되고 싶다면, 훌륭해지는 것은 여러분 자신의 책임이다. 즉 여러분의 개인적인 성격이 중요하다. 지성은 어떻게 할 수 없지만, 성격은 바꿀 수 있다. 재능이 아니라 노력이 필요하다.
## 33.2 지성과 겸손
- 자기 자신을 과대평가 하지 마라. 모든 프로그래밍 습관의 목표는 두뇌 세포의 짐을 덜어주는 것이다. (ex - 함수는 짧게. 이해가 쉽게 리팩토링 하는 것. egoless programming.)
- 자신의 오류 가능성을 보충하는 겸손한 프로그래머는 자신뿐만 아니라 다른 사람들도 이해하기 쉽고 오류가 적은 코드를 작성한다.
## 33.3 호기심
- 기술이 빠르게 변하는 산업이니만큼 호기심은 매우 중요하다.
- 호기심을 훈련하고 학슴에 우선순위를 두기 위해서 할 수 있는 활동들
  - 새로운 언어 배우기 - 효율적인 프로그램을 위한 한 가지 핵심은 실수를 더 빨리 하고 실수로부터 배우는 것이다. 실수를 하는 것은 죄악이 아니다. 실수로부터 배우지 못하는 것이 죄악이다.
  - 문제 해결에 관한 책 읽기 - Conceptual Blockbusting (James adams)
  - 성공적인 프로젝트에 대해 배운다 - 존경하는 프로그래머의 코드를 찾아 배운다. 그리고 내 코드를 비평해 줄 수 있는 세계적인 수준의 프로그램을 찾아라.
  - 매뉴얼을 읽어라 - 공포증이 만연해 있지만, 라이브러리 매뉴얼을 읽는 건 제대로 된 투자이다.
  - 정기 간행물 읽기
## 33.4 지적인 정직함
- 전문가가 아니라면 전문가인 체 하지 않는 것
- 실수를 인정하는 것
- 작동하는지 확인하려고 컴파일하기보다 이해하려 노력하는 것
- **현실적인 일정표를 제공하고 일정 조정을 요청받을 때 자신의 입장을 지키는 것.**
  - 일정을 협상할 수는 없다. 그건 1마일에 몇 피트인지를 협상하는 것과 같다. 일정이 아니라, 영향을 미치는 것들을 협상하라. 성능을 줄이든, 범위를 줄이든, 사람을 늘리든, 일정을 늘리든.
## 33.5 의사소통과 협동
- 프로그래밍은 가장 먼저 (코드를 통한) 다른 프로그래머와의 의사 소통이다. 읽기 좋은 코드를 만들어라.
## 33.6 창의성과 훈련
- 규칙과 규약이 중요하다.
## 33.7 게으름
- 게으름을 올바르게 표출해라. 미루지 말고, 재미없는 일을 생산적으로 처리하는 방법을 찾아라. 툴을 짜든지.
- 무리함은 추가적이고 불필요한 노력이다. 이는 노력은 하지만 일을 마무리 못한다는 걸 보여준다. 단순한 움직임을 진행이라고 생각하기 쉽고, 바쁜 것 자체가 생산적이라고 오인되기 쉽다. 무뇌 상태로 일하지 마라. 머리를 써라.
## 33.8 덜 중요한 특성
- 인내력 - 언제 그만두어야 할지, 언제까지 해보고 다른 방법을 시도할지 스스로 정해야 한다.
## 33.9 습관
- 처음부터 좋은 습관을 들여라. 
참고 자료

# 34장: 소프트웨어 장인정신에 대한 주제
## 34.1 복잡성 정복
- 책에서 다룬 복잡성 정복을 위한 방법들의 요약.
- 복잡성을 줄이는 일은 효율적인 프로그래머가 되기 위한 가장 중요한 핵심 요소이다.
## 34.2 자신에게 맞는 프로세스 선택
- 하향식, 상향식, 점증적 통합, 빅뱅 통합, T자 통합, ... 등등. 프로세스는 다양하다.
- 프로세스가 중요한 이유는, 품질이 처음부터 고려되어야 하기 떄문이다.
- '프로세스보다는 코드가 중요하다'라고 생각할 수 있지만, 프로세스를 이해하지 못하면 두뇌를 낭비하게 된다.
## 34.3 컴퓨터보다 사람을 위한 프로그램을 작성하라
- N/A
## 34.4 언어에 얽매이지 말고 언어를 활용하는 프로그램을 작성하라
- 원하는 기능을 툴에서 제공하지 않는다면 만들어라. 언어에서 제공하는 기능을 금지하고 싶다면 규약을 만들어라.
## 34.5 규약을 활용하여 핵심에 집중
- N/A
## 34.6 문제 중심의 프로그래밍
- 복잡성을 다루는 또 다른 방법은 가능한 높은 추상화 단계에서 작업하는 것이다. 최상위 수준 코드에서는 해결하려는 문제를 기술해야 한다. i/j/stack 어쩌고 하는 내용이 아니라. 그러니, 코드는 추상화 수준에 맞추어 작성되어야 한다.
## 34.7 낙석을 주의하라
- 컴파일러 등 도구의 경고를 챙기고.
- '의심으로부터 오는 짜증'과 같이 지적인 경고에도 주의해라.
## 34.8 반복, 반복, 또 반복
- 소프트웨어 설계는 발견적 프로세스이며, 반복적으로 개정하고 향상시켜야 한다.
## 34.9 소프트웨어와 신조를 떼어 놓아라
- 유연하라.

# 35장: 더 많은 정보를 얻으려면
## 35.1 소프트웨어 구현에 관한 정보
- 실용주의 프로그래머, 생각하는 프로그래밍, 익스트림 프로그래밍, 프로그래밍 수련법, 
## 35.2 구현 외의 주제
## 35.3 정기 간행물
## 35.4 소프트웨어 개발자의 독서 계획
## 35.5 전문가 협회에 가입