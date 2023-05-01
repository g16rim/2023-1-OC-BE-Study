# 5주차 WIL
## 1. 객체지향 패러다임과 객체란?
### 객체지향 패러다임
- 객체지향적인 사고의 틀
- 프로그램의 각 기능과 데이터를 객체로 바라보는 사고
### 객체
- 클래스에서 정의한 것을 메모리 상에 할당하여 구현된 실체

## 2.   객체 지향의 4 대 특성
1. 추상화(Abstraction)
- 필요한 부분만 추출하여 모델링하는 것
2. 캡슐화(Encapsulation)
- 외부에 필요한 기능만 공개하고, 나머지는 숨김
- 외부에 공개되는 부분은 변경을 최소화시킴
3.  다형성(Polymorphism)
- class 차원의 encapsulation을 구현한 구조
4. 상속(Inheritance)
- superclass의 재사용

## 3. 오버라이딩 vs 오버로딩
### 오버라이딩
- superclass로부터 상속 받은 method를 subclass에서 재정의하는 것
- dynamic binding
### 오버로딩
- 함수 이름만 같음

## 4. call by value? call by reference?
### call by value
- 값에 의한 호출
- 인자로 받은 값을 복사 -> 새로운 주소를 갖게 됨
### call by reference
- 참조에 의한 호출
- 주소값을 참조
