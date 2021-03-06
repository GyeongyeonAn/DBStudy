## DB란?
- 특정 조직의 여러 사용자가 공유하여 사용할 수 있도록 통합해서 저장한 운영 데이터 집합이다.

---

## 파일 시스템의 단점
 1. 같은 내용의 데이터가 여러 파일에 중복 저장되기 때문에, 데이터의 일관성과 데이터의       무결성을 유지하기 어렵다.
 2. 응용 프로그램이 데이터 파일에 종속적이다. 
 3. 데이터 파일에 대한 동시 공유, 보안, 회복 기능이 부족하다.
 4. 새로운 응용 프로그램을 개발하려면 파일에서 데이터 관리 기능을 모두 포함시켜야 하기      때문에, 개발이 쉽지 않다.

---

## DBMS의 주요 기능
1. 정의 기능(DDL) : 데이터베이스 구조를 정의하거나 수정할 수 있다.
2. 조작 기능(DML) : 데이터를 삽입, 삭제, 수정, 검색하는 연산을 할 수 있다.
3. 제어 기능(DCL) : 데이터를 항상 정확하고 안전하게 유지할 수 있다.

---

## DBMS의 장점과 단점
### 장점: 
1. 데이터 중복을 통제할 수 있다.
2. 데이터 독립성이 확보된다.
3. 데이터를 동시 공유할 수 있다.
4. 데이터 보안이 향상된다.
5. 데이터 무결성을 유지할 수 있다.
6. 표준화할 수 있다.
7. 장애 발생 시 회복이 가능하다.
8. 응용 프로그램 개발 비용이 줄어든다.   


### 단점: 
1. 비용이 많이 든다.
2. 백업과 회복 방법이 복잡하다.
3. 중앙 집중 관리로 인한 취약점이 존재한다.

---

## DBMS의 발전 과정
1세대: 네트워크 DBMS(그래프 형태), 계층 DBMS(트리 형태)
2세대: 관계 DBMS(테이블 형태)
3세대: 객체지향 DBMS(객체를 이용), 객체관계 DBMS(객체 DBMS + 관계 DBMS)
4세대: NoSQL DBMS, NewSQL DBMS

## NoSQL DBMS
- 불필요한 Join의 최소화
- 유연성있는 서버 구조 제공
- 비정형 데이터 구조로 설계비용 감소
- Read/Write가 빠르며 빅데이터 처리가 가능
- 저렴한 비용으로 분산처리 및 병렬처리 가능

4번 장점의 경우는 반드시는 아닙니다. 일반적인 관계형 데이터베이스가 빠른 경우도 많습니다.
그리고 비정형 데이터로 인해  관계형 데이터베이스보다 1.5배정도 용량을 많이 차지 합니다.

출처: https://cionman.tistory.com/44 [Suwoni블로그]

예) 몽고디비, H베이스, 카산드라, 레디스, 네오포제이, 오리엔트DB 등

## NewSQL DBMS: 관계 DBMS의 장점 + NoSQL의 확장성 및 유연성

- 특정 조직의 여러 사용자가 공유하여 사용할 수 있도록 통합해서 저장한 운영 데이터 집합이다.

---

## 파일 시스템의 단점

 1. 같은 내용의 데이터가 여러 파일에 중복 저장되기 때문에, 데이터의 일관성과 데이터의       무결성을 유지하기 어렵다.
 2. 응용 프로그램이 데이터 파일에 종속적이다. 
 3. 데이터 파일에 대한 동시 공유, 보안, 회복 기능이 부족하다.
 4. 새로운 응용 프로그램을 개발하려면 파일에서 데이터 관리 기능을 모두 포함시켜야 하기      때문에, 개발이 쉽지 않다.

---

## DBMS의 주요 기능

1. 정의 기능(DDL) : 데이터베이스 구조를 정의하거나 수정할 수 있다.
2. 조작 기능(DML) : 데이터를 삽입, 삭제, 수정, 검색하는 연산을 할 수 있다.
3. 제어 기능(DCL) : 데이터를 항상 정확하고 안전하게 유지할 수 있다.

---

## DBMS의 장점과 단점

### 장점: 
1. 데이터 중복을 통제할 수 있다.
2. 데이터 독립성이 확보된다.
3. 데이터를 동시 공유할 수 있다.
4. 데이터 보안이 향상된다.
5. 데이터 무결성을 유지할 수 있다.
6. 표준화할 수 있다.
7. 장애 발생 시 회복이 가능하다.
8. 응용 프로그램 개발 비용이 줄어든다.   

### 단점: 
1. 비용이 많이 든다.
2. 백업과 회복 방법이 복잡하다.
3. 중앙 집중 관리로 인한 취약점이 존재한다.

---

## DBMS의 발전 과정

1세대: 네트워크 DBMS(그래프 형태), 계층 DBMS(트리 형태)
2세대: 관계 DBMS(테이블 형태)
3세대: 객체지향 DBMS(객체를 이용), 객체관계 DBMS(객체 DBMS + 관계 DBMS)
4세대: NoSQL DBMS, NewSQL DBMS

## NoSQL DBMS
- 불필요한 Join의 최소화
- 유연성있는 서버 구조 제공
- 비정형 데이터 구조로 설계비용 감소
- Read/Write가 빠르며 빅데이터 처리가 가능
- 저렴한 비용으로 분산처리 및 병렬처리 가능

4번 장점의 경우는 반드시는 아닙니다. 일반적인 관계형 데이터베이스가 빠른 경우도 많습니다.
그리고 비정형 데이터로 인해  관계형 데이터베이스보다 1.5배정도 용량을 많이 차지 합니다.

출처: https://cionman.tistory.com/44 [Suwoni블로그]

예) 몽고디비, H베이스, 카산드라, 레디스, 네오포제이, 오리엔트DB 등

## NewSQL DBMS
- 관계 DBMS의 장점 + NoSQL의 확장성 및 유연성

예) 구글 스패너, 볼트DB, 누오DB 등예) 구글 스패너, 볼트DB, 누오DB 등

---

## DB 용어정리
- 스키마(schema): 데이터베이스에 저장되는 데이터 구조와 제약조건을 정의한 것
- 인스턴스(instance): 스키마에 따라 데이터베이스에 실제로 저장된 값
- 릴레이션(relation): 하나의 개체에 관한 데이터를 차원 테이블의 구조로 저장한 것
- 속성(attribute): 릴레이션의 열
- 튜플(tuple): 릴레이션의 행
- 도메인(domain): 하나의 속성이 가질 수 있는 모든 값의 집합 (데이터 타입으로 정의)
- 널(null): 속성 값을 아직 모르거나 해당되는 값이 없음을 표현
- 차수(degree): 하나의 릴레이션에서 속성의 전체 개수
- 카디널리티(cardicality): 하나의 릴레이션에서 튜플의 전체 개수
---

## 데이터베이스의 구조
- 외부 단계(external level): 개별 사용자 관점
- 개념 단계(conceptual level): 조직 전체의 관점
- 내부 단계(internal level): 물리적인 저장 장치의 관점

### 외부 단계
- 데이터베이스를 개별 사용자 관점에서 이해하고 표현하는 단계
- 데이터베이스 하나에 외부 스키마가 여러 개 존재할 수 있음

### 개념 단계
- 데이터베이스를 조직 전체으 관점에서 이해하고 표현하는 단계
- 데이터베이스 하나에 개념 스키마가 하나만 존재함

### 내부 단계
- 데이터베이스를 저장 장치의 관점에서 이해하고 표현하는 단계
- 데이터베이스 하나에 내부 스키마가 하나만 존재함

데이터베이스를 3단계 구조로 나누고 단계별로 스키마를 유지하며 스키마 사이의 대응 관계를 정의하는 궁극적인 목적은 데이터 독립성의 실현을 위해서다.

---

## 데이터 언어
- 데이터 정의어(DDL: Data Definition Language) : 스키마를 정의, 수정, 삭제하기 위해 사용
- 데이터 조작어(DML: Data Manipulation Language) : 데이터의 삽입, 삭제, 수정, 검색 등의 처리를 요구하기 위해 사용
- 데이터 제어어(DCL: Data Control Language) : 내부적으로 필요한 규칙이나 기법을 정의하기 위해 사용

---

## 릴레이션의 특성
- 튜플의 유일성: 하나의 릴레이션에는 동일한 튜플이 존재할 수 없다.
- 튜플의 무순서: 하나의 릴레이션에서 튜플 사이의 순서는 무의미하다.
- 속성의 무순서: 하나의 릴레이션에서 속성 사이의 순서는 무의미하다.
- 속성의 원자성: 속성 값으로 원자 값만 사용할 수 있다.
