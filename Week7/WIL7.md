# 7주차 WIL
## 객체 지향 설계의 5원칙 
- 객체 지향 설계에서 지켜야 할 소프트웨어 개발 원칙 5개 
- SOLID
- 코드 확장과 유지 보수가 쉬워진다.
### 1. 단일 책임 원칙(SRP)
Single Responsibility Principle
#### 개념
- 클래스는 하나의 책임만 가진다.
#### 장점
- coupling이 감소한다.
- 모듈화가 잘 지켜진다. 
### 2. 개방 폐쇄 원칙(OCP)
Open Closed Principle
#### 개념
- 확장에는 열려있고, 수정에는 닫혀 있는다. 
#### 장점
- 새로운 변경 사항이 생겼을 때 코드를 추가하는 대응은 쉽고, 객체를 직접 수정하는 일은 없다.
### 3. 리스코프 치환 원칙(LSP)
Liskov Substitution Principle
#### 개념
- 서브 타입은 언제나 기반(부모) 타입으로 교체할 수 있다.
#### 장점
- Polymorphism을 잘 따른다.
### 4. 인터페이스 분리 원칙(ISP)
Interface Segregation Principle
#### 개념
- 인터페이스를 클라이언트의 사용 목적에 따라 잘게 분리해야 한다.
- SRP의 Interface 버전 원칙
#### 장점
- cohesion이 높다.
### 5. 의존 역전 원칙(DIP)
Dependency Inversion Principle
#### 개념
- Class를 직접 참조하지 않고, Class의 상위 요소인 Interface를 참조한다.
- Interface에 의존한다.
#### 장점
- 클래스 간의 coupling을 낮춘다.
