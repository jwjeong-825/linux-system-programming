# Signal

## What is Signal?

Signal은 운영체제가 process에게 보내는 비동기 이벤트이다.

특정 상황이 발생했을 때 process에 알림을 전달한다.

---

## Examples of Signals

- SIGINT
- SIGKILL
- SIGSTOP
- SIGTERM

---

## SIGINT

```bash
Ctrl + C
```

터미널에서 실행 중인 process 종료 요청

---

## Signal Handling

process는 signal을 처리할 수 있다.

```c
signal(SIGINT, handler);
```

특정 signal이 발생했을 때 handler 함수 실행

---

## Common Functions

### signal()

signal 처리 함수 등록

```c
signal(SIGINT, handler);
```

---

### kill()

특정 process에 signal 전송

```c
kill(pid, SIGKILL);
```

---

## What I Practiced

- signal 개념 학습
- Ctrl + C 동작 이해
- signal handler 실습
- process 제어 실습
