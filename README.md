# java-racingcar-precourse
1. 사용자 입력 처리
   + 자동차 이름 입력 기능
     + 사용자에게 쉼표로 구분된 자동차 이름을 입력받는다.
     + 입력된 이름이 5자를 넘는 경우 IllegalArgumentException을 발생시킨다.
   + 이동 횟수 입력 기능
     + 사용자가 몇 번의 이동을 정할 지를 입력받는다.
     + 입력값이 정수인지 검사한다. 정수가 아닌 경우 IllegalArgumentException을 발생시킨다.

2. 자동차 객체 생성
   + 자동차 이름을 필드로 가지며, 현재 위치를 기록한다.
   + move() 메서드를 구현하여 무작위 값이 4 이상일 경우에만 전진하도록 한다.
   + 자동차 이름과 현재 위치를 출력하는 기능을 제공한다.

3. 게임 진행 로직
   + 무작위 값 생성
     + 0에서 9까지의 무작위 값을 생성한다.
   + 자동차 전진 여부 결정
     + 무작위 값이 4 이상일 경우에만 해당 자동차가 전진한다.
   + 자동차 전진 및 상태 출력
     + 각 라운드마다 모든 자동차가 전진할 지 멈출 지를 결정한 후, 현재 상태를 출력한다.

4. 우승자 결정
   + 우승자 판별
     + 모든 이동이 끝난 후 가장 멀리 간 자동차를 우승자로 결정한다.
     + 우승자가 여러 명일 경우 쉼표로 구분하여 출력한다.
