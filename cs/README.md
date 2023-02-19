# CS-study

<hr>

# 운영체제
- 프로세스와 스레드의 차이
- 멀티스레드
  - 장점과 단점
  - 멀티스레드 vs 멀티프로세스
- 스케줄러의 종류
  - 장기 스케줄러
  - 단기 스케줄러
  - 중기 스케줄러
- CPU 스케줄러
  - FCFS
  - SJF
  - SRT
  - Priority scheduling
  - RR
- 동기와 비동기의 차이
- 프로세스 동기화
  - Critical Section
  - 해결책
    - Lock
    - Semaphores
    - 모니터
- 메모리 관리 전략
  - 메모리 관리 배경
  - Paging
  - Segmentation
- 가상 메모리
  - 배경
  - 가상 메모리가 하는 일
  - Demand Paging (요구 페이징)
  - 페이지 교체 알고리즘
- 캐시의 지역성
  - Locality
  - Caching line



# 자료구조
- 선형 자료구조 
  - Array
  - List
  - HashTable
  - Queue
  - Heap
  - Stack
- 비선형 자료구조
  - Graph
  - Tree
    - Binary Tree
    - Full Binary Tree
    - Complete Binary Tree
    - Binary Search Tree
   - Trie
- 정렬 알고리즘
  - 선택 정렬, 거품 정렬, 삽입 정렬
  - 병합 정렬, 퀵 정렬, 힙 정렬
- 이분 탐색
- 동적계획법
- 최단 경로
- 최소 비용(MST)

# 데이터베이스
- 데이터베이스
   - 데이터베이스를 사용하는 이유
   - 데이터베이스 성능
- Sharding&Master/Slave(2)
- Index
   - Index 란 무엇인가
   - Index 의 자료구조
   - Primary index vs Secondary index
   - Composite index
   - Index 의 성능과 고려해야할 사항
   - Clustered index, Non-Clustered index
- 정규화에 대해서
   - 정규화 탄생 배경
   - 정규화란 무엇인가
   - 정규화의 종류
   - 정규화의 장단점
- Transaction
    - 트랜잭션(Transaction)이란 무엇인가?
    - 트랜잭션과 Lock
    - 트랜잭션의 특성
    - 트랜잭션의 상태
    - 트랜잭션을 사용할 때 주의할 점
    - 트랜잭션 격리수준
    - ACID
    - 교착상태
- Statement vs PreparedStatement
- NoSQL
    - 정의
    - CAP 이론
      - 일관성
      - 가용성
      - 네트워크 분할 허용성
    - 저장방식에 따른 분류
       - Key-Value Model
       - Document Model
       - Column Model

# 네트워크

- OSI 7 계층

- TCP 3 way handshake & 4 way handshake

- TCP/IP 흐름제어 & 혼잡제어

- UDP

- 대칭키 & 공개키

- HTTP & HTTPS
  - HTTP status code
  - HTTP METHOD
  - HTTP 특징
  - HTTP와 HTTPS의 차이

- HTTP 1.1 vs HTTP 2.0 vs HTTP 3.0

- REST, RESTFUL, REST API

- Web Server VS WAS

- CORS

- COOKIE & SESSION

- JWT

- TLS/SSL handshake

- 로드 밸런싱(Load Balancing)

- Blocking,Non-blocking & Synchronous,Asynchronous

- Blocking & Non-Blocking I/O

- 웹 통신의 큰 흐름
  - www.naver.com 을 입력했을 때 일어나는 일

- DNS Round Robin 방식

---

# Java

객체지향
 - 4가지 특징
 - 5원칙 (SOLID)
 - 객체지향 vs 절차지향 vs 함수형 프로그래밍
- JDK, JRE, JVM
 - 컴파일 과정
 - 컴파일 언어 vs 인터프리터 언어
 - JVM 메모리 구조
 - Garbage Collector 동작과정
 - Java8의 큰 특징 + Java11과의 차이점
---
- Java 기초
 - 접근제어자
 - 클래스, 객체, 인스턴스 차이
 - Overloading vs Overriding
 - Primitive type vs Reference type
    - Call by Reference vs Call by Value
    - Wrapper Class
 - interface vs abstract class
 - Checked Exception vs UnChecked Exception
 - static
 - final
 - generic
 - stream, lambda
 - Reflection & Dynamic Proxy
---

- Java 컬렉션
 - hashcode() & equals()
 - Thread Safe & Syncronized
 - String
 - String vs StringBuffer vs StringBuilder
 - Immutable Object
 - String a = "" vs String a = new String("")
- List
 - ArrayList vs LinkedList
- Map
  - HashTable vs HashMap vs LinkedHashMap vs TreeMap
  - HashMap vs ConcurrentHashMap

---

# 📌 Spring

Servlet
 - 개념
 - tomcat
 - servlet container
 - 동작과정

Spring 기본
 - Spring vs Spring MVC vs Spring Boot
     - MVC1 vs MVC2
 - dispatcher servlet
 - IoC
 - DI
 - Bean, Component
     - @Component @Service @Controller
 - Container
 - VO vs DTO vs DAO

Spring 심화
 - AOP
    - JDK Dynamic Proxy
    - CGLIB
 - interceptor
    - filter와 차이점
 - Spring 전체 동작과정

JPA
 - JDBC, Spring JDBC
 - Sql Mapper(MyBatis), ORM
 - JPA, Hibernate
 - 영속성 컨텍스트
 - 즉시/지연 로딩
 - 프록시
 - 고아객체
 - 단뱡향/양방향 매핑
 - N + 1 문제

테스트
 - DDD, TDD
 - Junit4 vs Junit5
 - 단위, 통합, 인수 테스트
 - stub, mock
 - SpringBoot 계층별 테스트 방법
- 테스트 커버리지 (JACOCO)

