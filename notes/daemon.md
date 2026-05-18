# Daemon Process

## What is Daemon?

Daemon process는 백그라운드에서 계속 실행되는 process이다.

사용자와 직접 상호작용하지 않고 시스템 서비스를 수행한다.

---

## Features

- 백그라운드 실행
- terminal과 분리됨
- 시스템 서비스 제공
- 계속 실행 상태 유지

---

## Examples

- sshd
- httpd
- cron

---

## Daemon Creation

일반적으로 다음 과정을 거친다.

1. fork()
2. 부모 process 종료
3. setsid()
4. 작업 디렉토리 변경
5. 파일 권한 초기화

---

## Main Functions

### fork()

새로운 process 생성

```c
fork();
```

---

### setsid()

새로운 session 생성

```c
setsid();
```

---

## What I Practiced

- daemon process 개념 학습
- background process 이해
- Linux 서비스 구조 이해
- daemon 생성 과정 학습
