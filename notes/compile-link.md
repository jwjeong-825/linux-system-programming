# Compile & Link

## What is Compile?

Compile은 사람이 작성한 C 소스코드를 기계어로 변환하는 과정이다.

gcc compiler를 사용하여 실행 파일을 생성할 수 있다.

---

## Compilation Process

1. Preprocessing
2. Compilation
3. Assembly
4. Linking

---

## GCC Command

```bash
gcc main.c
```

실행 파일 생성

---

## Output File

```bash
gcc -o main main.c
```

- main.c : source file
- main : output executable file

---

## Object File

```bash
gcc -c main.c
```

object file 생성

---

## Link

여러 object file을 하나의 실행 파일로 연결하는 과정

---

## What I Practiced

- gcc compile 실습
- executable file 생성
- object file 이해
- compile/link 과정 학습
