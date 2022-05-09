### undefined와 null의 차이점을 설명하세요.

> undefined 은 변수를 선언하고 값을 할당하지 않은 상태이다.
> null 은 변수를 선언하고 빈 값을 할당한 상태(빈 객체)이다.
> undefined 는 자료형이 없는 상태이다. 따라서 typeof를 통해 자료형을 확인해보면 null은 onject 로, undefined 는 undefined 가 출력되는 것을 확인할 수 있다.

### 요약

> console.log(typeof undefined) //undefined
> console.log(typeof null) //object
> console.log(undefined == null) //true
