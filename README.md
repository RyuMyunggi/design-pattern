# design-pattern
design-pattern study by python

## 디자인 패턴이란

* 디자인 패턴은 GoF(Gang of Four)가 주어진 여러 문제에 대한 해결책으로 제시
* + GoF란 GOF의 디자인 패턴을 집필한 네 명의 저자를 지칭
* 소프트 웨어 설계 단계에서 흔히 발생하는 여러 문제의 해결책으로 총 23개의 디자인 패턴을 제시

## 디자인 패턴의 주요기능
* 언어에 독립적이며 모든 프로그래밍 언어에 적용할 수 있음
* 새로운 패턴이 연구중임
* 목적에 맞게 변경될 수 있기 때문에 개발자에게 유용함
* 여러 프로젝트에서 재사용 될 수 있음
* 신뢰 할 수 있는 솔루션

## 디자인 패턴의 용어
* 스니펫(snippet): 디비에 연결하는 파이썬 코드 등의 특수한 목적을 위한 코드
* 디자인(design): 특정 문제를 해결하기 위한 해결책 
* 스탠다드(standard): 문제를 해결하는 대표적인 방식. 포괄적이며 현재 상황에 적합한 방식
* 패턴(pattern): 유사한 문제들을 모두 해결할 수 있는 유효성이 검증된 효율적인 해결책

## 디자인 패턴의 분류
* GoF 책에서는 23개의 디자인 패턴을 다음 3개의 범주로 분류
* 생성, 구조, 행위 패턴

### 생성패턴
* 객체가 생성되는 방식을 기반으로 작동함
* 객체 생성 관련 상세 로직을 숨김
* 코드와 생성되는 객체의 클래스는 서로 독립적
* ex) 싱글톤 패턴은 생성 패턴의 한 종류임

### 구조패턴
* 클래스와 객체를 더큰 결과물로 합칠 수 있는 구조로 설계
* 구조가 단순해지고,클래스와 객체 간의 상호관계를 파악할 수 있어야함
* 클래스 상속과 컴포지션에 의존
* ex) 어댑터 패턴은 구조 패턴의 한 종류임

### 행위패턴
* 객체 간의 상호작용과 책임을 기반으로 작동
* 객체는 상호작용하지만 느슨하게 결합되어야함
* ex) 옵져버 패턴은 행위 패턴의 한 종류임
