# [2차시] 재판 속 협력 예제 🧑‍⚖️

## 메인 시나리오 (유스케이스 명)
1. 재판하라
2. 목격자를 불러오라
3. 증인석에 입장하라
4. 증언하라

## 일차 액터
1. 사용자
2. 재판관
3. 하얀 토끼
4. 재판관

## 주요 성공 시나리오
1. 재판이 시작된다. (재판을 요청하는 것은 우리다.)
2. 재판관은 하얀 토끼에게 목격자를 요구한다. (하얀 토끼의 선택은 랜덤이다.) / 하얀 토끼가 재판관의 말을 거부한다. -> 재판이 종료된다.
3. 하얀 토끼는 재판관의 말을 듣는다. -> 하얀 토끼는 증인을 불러온다. (증인의 선택은 랜덤이다.) / 증인이 증언을 거부한다. -> 재판이 종료된다.
4. 증인이 증언을 거부하지 않는다. -> 증인은 대답을 한다.

## 확장
모든 인물이 다른 인물로 대체 될 수 있다.

## 기한
주 마다 정해봐요~



<details>
<summary> [1차시] 커피 공화국 예제 ☕️</summary>
<div markdown="1">

## 메인 시나리오
1. Customer가 Cashier에게 커피를 주문한다.
2. Cashier는 Manager에게 주문 내역을 전달한다.
3. Manager는 커피를 제조할 Barista를 선택한다.
4. Barista는 커피를 만든다.
5. Manager는 커피가 완성되면 Customer에게 전달한다.

## 세부 사항
1. Customer은 2명 이상이다. (주문하고 싶은 메뉴 이름과 현재 가진 돈이 얼마인지를 알고 있어야 한다.)
2. Cashier는 1명이다.
3. Barista는 2명 이상이다.
4. Manager는 1명이다.
5. Only *Coffee* 만 가능 (차? 샌드위치? 안됨)
6. 메뉴판에는 각 음료의 이름과 가격이 제공되어야 한다.

## 일정
- 3월 27일까지 해보자!
- 3월 20일에는 중간 공유를 해보자

</div>
</details>
