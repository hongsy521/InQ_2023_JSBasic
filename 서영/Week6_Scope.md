*[홍서영 6주차 과제]*
<br>
counter1()함수를 호출하면 입력된 makeCounter()함수가 실행되도록 선언되었기 떄문에 위의 함수를 자동 실행하고 return 값으로 count의 값이 1씩 증가하여 출력된다. 하지만 이때 count는 정의되지 않은 변수이기 때문에 초기값으로 0을 받는다. 이후에는 count가 1씩 증가하여 두번째 alert에서는 1의 값이 출력되는 것을 확인할 수 있다.<br>
```Javascript
alert( counter() ); // 0
alert( counter() ); // 1
```
counter2()의 경우도 counter1()과 마찬가지로 makeCounter()함수를 호출하도록 선언되어있고 새로운 변수에 값을 저장하는 것이기 때문에 counter1()처럼 초기값으로는 0을 갖고 그 이후로는 count가 증가하는 값을 출력하게 된다.
<br>
```Javascript
alert( counter2() ); // 0
alert( counter2() ); // 1
```
