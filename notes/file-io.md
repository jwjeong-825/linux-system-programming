# File I/O

## What is File I/O?

File I/O는 파일을 읽고(write) 쓰는(read) 작업이다.

Linux에서는 파일도 하나의 자원(resource)으로 관리된다.

---

## Main System Calls

### open()

파일 열기

```c
open("test.txt", O_RDONLY);
```

---

### read()

파일 읽기

```c
read(fd, buffer, size);
```

- fd : file descriptor
- buffer : 저장 공간
- size : 읽을 크기

---

### write()

파일 쓰기

```c
write(fd, buffer, size);
```

---

### close()

파일 닫기

```c
close(fd);
```

---

## File Descriptor

Linux에서는 파일을 숫자로 관리한다.

예시:
- 0 : standard input
- 1 : standard output
- 2 : standard error

---

## What I Practiced

- open/read/write/close 사용
- file descriptor 이해
- Linux 파일 처리 실습
- system call 기반 파일 입출력 학습
