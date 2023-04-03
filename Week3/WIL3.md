# 3주차 WIL

## 1. 의존과 의존성
- 스프링에서 의존 : 객체 간의 의존
## 2. @Autowired 의존성 주입
- 생성자에 @Autowired가 있으면 스프링이 연관된 객체를 스프링 컨테이너에서 찾아서 넣어준다.
- DI (Dependency Injection), 의존성 주입
## 3. DIP
- Dependency Inversion Principle, 의존성 역전의 원칙
- 상위 모듈이 하위 모듈에 의존해서는 안 된다.
- 하위 모듈이 상위 모듈에서 정의한 추상 타입에 의존해야 한다.
## 4. 스프링 빈과 스프링 컨테이너란?
### 스프링 빈
- 자바 객체
### 스프링 컨테이너
- 자바 객체의 생명 주기(생성->소멸)를 관리한다.
- BeanFactory
- ApplicationContext
	- 대부분의 경우 사용하고, BeanFactory 기능 포괄하면서 추가적인 기능 제공한다.
## 5. JDBC와 JPA?
### JDBC
- Java Database Connectivity
- DB에 접근할 수 있도록 Java에서 제공하는 API
### JPA
- Java Persistence API
- 내부적으로 JDBC를 사용한다.
- Java ORM 기술에 대한 API 표준 명세
