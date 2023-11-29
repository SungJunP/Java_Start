#김영한의 자바 입문 - 코드로 시작하는 자바 첫걸음

# 변수 타입 정리

# 다음 타입은 실무에서 거의 사용하지 않는다.
- `byte` : 표현 길이가 너무 작다. 또 자바는 기본으로 4byte( `int` )를 효율적으로 계산하도록 설계되어 있다. `int`
를 사용하자.
- `byte` 타입을 직접 선언하고 여기에 숫자 값을 대입해서 계산하는 일은 거의 없다.
대신에 파일을 바이트 단위로 다루기 때문에 파일 전송, 파일 복사 등에 주로 사용된다.
- `short` : 표현 길이가 너무 작다. 또 자바는 기본으로 4byte( `int` )를 효율적으로 계산하도록 설계되어 있다. `int` 를 사용하자
- `float` : 표현 길이와 정밀도가 낮다. 실수형은 `double` 을 사용하자.
- `char` : 문자 하나를 표현하는 일은 거의 없다. 문자 하나를 표현할 때도 문자열을 사용할 수 있다.
- 예를 들어 `String a = "b"` 와 같이 사용하면 된다.

# 자주 사용하는 타입
- 정수- `int` , `long` :자바는정수에기본으로 `int` 를사용한다.만약20억이넘을것같으면 `long` 을쓰면된 다.
파일을 다룰 때는 `byte` 를 사용한다.
- 실수 - `double` : 실수는 고민하지 말고 `double` 을 쓰면 된다.
- 불린형 - `boolean` : `true` , `false` 참 거짓을 표현한다. 이후 조건문에서 자주 사용된다.
- 문자열 - `String` : 문자를 다룰 때는 문자 하나든 문자열이든 모두 `String` 을 사용하는 것이 편리하다.
- 자주 사용하는 타입을 제외하고 실무에서 나머지를 사용하는 경우는 거의 없다. 그나마 파일 전송시에 `byte` 를 사용하 는 것 정도이다.

##변수 명명 규칙

- 변수 이름은 숫자로 시작할 수 없다. (예: `1num` , `1st` )
- 그러나 숫자를 이름에 포함하는 것은 가능하다 (예: `myVar1` , `num1` ).
- 이름에는 공백이 들어갈 수 없다.
- 자바의 예약어를 변수 이름으로 사용할 수 없다. (예: `int` , `class` , `public` )
- 변수 이름에는 영문자(`a-z` , `A-Z` ), 숫자(`0-9` ), 달러 기호(`$` ) 또는 밑줄(`_` )만 사용할 수 있다.
- 소문자로 시작하는 낙타 표기법
- 변수 이름은 소문자로 시작하는 것이 일반적이다. 여러 단어로 이루어진 변수 이름의 경우, 첫 번째 단어는 소문자로 시작하고 그 이후의 각 단어는 대문자로 시작하는 낙타 표기법(camel case)를 사용한다. (예:
`orderDetail` , `myAccount` )
