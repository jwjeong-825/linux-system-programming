# Process

## What is Process?

Process는 실행 중인 프로그램이다.

프로그램이 메모리에 올라와 실행되면 process가 된다.

운영체제는 여러 process를 관리하며 CPU를 할당한다.

---

## Process Features

- PID(Process ID)를 가짐
- 독립적인 메모리 공간 사용
- CPU 자원을 할당받아 실행

---

## Main System Calls

### fork()

새로운 process 생성

```c
fork();
```

부모 프로세스를 복사하여 자식 프로세스를 생성한다.

---

### exec()

현재 process를 새로운 프로그램으로 실행

```c
exec();
```

---

### wait()

자식 process 종료 대기

```c
wait();
```

---

## Process States

- Ready
- Running
- Waiting
- Terminated

---

## What I Practiced

- process 개념 학습
- fork() 사용 실습
- 부모/자식 process 이해
- process 실행 흐름 확인
