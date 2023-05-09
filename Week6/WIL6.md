# 6주차 WIL
## 1. 추상 클래스와 인터페이스
### 추상 클래스
- abstract class
- IS-A
- 추상 메서드를 선언하고, 자식 클래스에서 구현하도록 하는 클래스
- 상속을 위한 클래스
- 객체 생성 불가
### 인터페이스
- interface
- HAS-A
- 구현할 메서드 선언해놓는 곳
- 다중 상속(구현) 가능



## 2. static과 final 그리고 불변 객체
### static
- 객체에 고정되는 것이 아니라 클래스에 고정
- 모든 객체가 메모리를 공유
- 가비지 컬렉터가 관여하지 않음
### final
- Java에서 불변 객체를 생성하기 위한 키워드
### 불변 객체
- 객체 생성 이후 내부의 상태가 변하지 않는 객체
- 예: Java의 String 클래스