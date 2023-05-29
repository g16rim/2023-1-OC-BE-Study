# 9주차 WIL 
## 1. 람다와 스트림
### 람다
- 함수를 식으로 간단하게 표현하는 것
- 방법
```
int max(int a, int b) {
	return a > b ? a : b;
}
```
1) 메서드의 이름과 반환타입 제거
```
(int a, int b) {
	return a > b ? a : b;
}
```
2) '->'을 블록 {} 앞에 추가
```
(int a, int b) -> {
	return a > b ? a : b;
}
```
3) 반환 값이 있으면 그대로 적고, return과 ; 생략
```
(int a, int b) -> a > b ? a : b
```
4) 매개변수 타입이 추론 가능하면 생략 가능(대부분 생략)
```
(a, b) -> a > b ? a : b
```
### 스트림
- 자바 8부터 추가된 컬렉션의 저장 요소를 하나씩 참조해서 람다식으로 처리할 수 있도록 해주는 반복
## 2. Optional
- 자바 8부터 Optional<T> 클래스로 NullPointerException을 방지해줌 
