# Standard I/O

## What is Standard I/O?

Standard I/O는 C 언어에서 제공하는 표준 입출력 라이브러리이다.

stdio.h를 사용하여 파일 및 입출력을 처리한다.

---

## Standard Streams

- stdin
- stdout
- stderr

---

## Main Functions

### printf()

출력 함수

```c
printf("Hello");
```

---

### scanf()

입력 함수

```c
scanf("%d", &num);
```

---

### fopen()

파일 열기

```c
fopen("test.txt", "r");
```

---

### fclose()

파일 닫기

```c
fclose(fp);
```

---

## Standard I/O vs System Call

### Standard I/O

- buffering 사용
- 사용하기 편리함
- stdio.h 기반

### System Call I/O

- 운영체제 직접 호출
- low-level I/O
- open/read/write 사용

---

## What I Practiced

- stdio.h 사용
- printf/scanf 실습
- fopen/fclose 사용
- standard I/O와 system call 차이 이해
