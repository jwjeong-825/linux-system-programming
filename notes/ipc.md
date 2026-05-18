# IPC

## What is IPC?

IPC(Inter Process Communication)는 process 간 데이터를 주고받는 기술이다.

독립적인 process들은 기본적으로 메모리를 공유하지 않기 때문에 IPC를 사용한다.

---

## IPC Methods

- Pipe
- FIFO
- Message Queue
- Shared Memory
- Socket

---

## Pipe

부모와 자식 process 사이 통신 방식

```c
pipe(fd);
```

---

## FIFO

이름 있는 pipe

```c
mkfifo("fifo_file", 0666);
```

서로 관계없는 process 간 통신 가능

---

## Shared Memory

여러 process가 같은 메모리 공간 공유

빠른 속도의 IPC 가능

---

## Socket

네트워크 기반 통신 가능

서버/클라이언트 구조에서 사용

---

## What I Practiced

- IPC 개념 학습
- pipe 사용 실습
- FIFO 기반 통신 실습
- server/client 구조 이해
