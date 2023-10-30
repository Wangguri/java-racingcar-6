# 초간단 자동차 경주 게임 기능 목록

- 사용자는 몇 번 게임을 시도할 것인지 입력할 수 있다. TryTimes / askTimes 완료


- 사용자는 N대의 각 자동차에 이름을 부여할 수 있다. CarName

    * 1) N대의 각 자동차에는 이름을 부여할 수 있다. (이름은 쉼표로 구분) inputCarName
    
    * 2) 자동차의 이름은 5글자 이하여야 한다. carNameCheck
    
    
- 사용자가 입력한 횟수 동안 N대의 자동차는 멈추거나 전진할 수 있다. CarRacing
        
    * 1) 0-9 사이 무작위 값을 생성한 후 생성된 값이 4 이상이면 전진한다. carMove
    
         
- 모든 라운드가 끝나면 우승자를 알려준다. Winner
  
    * 1) 자동차의 전진을 비교할 수 있다. compareCount
  
    * 2) 우승자는 한 명 이상이며, 여러 명이면 쉼표로 구분하여 보여준다. winnerPrint
    

- 사용자가 잘못된 값을 입력하면 IllegalArgumentException을 발생시킨 후 애플리케이션은 종료된다. 

