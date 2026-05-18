# Thread

## What is Thread?

Thread는 process 내부에서 실행되는 작업 흐름이다.

하나의 process 안에서 여러 thread가 동시에 실행될 수 있다.

---

## Process vs Thread

### Process

- 독립적인 메모리 공간 사용
- 생성 비용이 큼

### Thread

- 같은 process 메모리 공유
- 생성 비용이 상대적으로 적음

---

## Multi Thread

여러 작업을 동시에 수행 가능

예시:
- 웹 서버
- 게임
- 채팅 프로그램

---

## POSIX Thread

Linux에서는 pthread 라이브러리를 사용한다.

---

## Main Functions

### pthread_create()

새로운 thread 생성

```c
pthread_create();
```

---

### pthread_join()

thread 종료 대기

```c
pthread_join();
```

---

## What I Practiced

- thread 개념 학습
- multi-thread 구조 이해
- pthread 사용 실습
- process와 thread 차이 이해
