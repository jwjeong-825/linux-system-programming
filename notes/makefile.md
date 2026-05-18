# Makefile

## What is Makefile?

Makefile은 프로그램의 컴파일 과정을 자동화하는 파일이다.

반복적인 gcc 명령어 입력을 줄이고,
프로젝트 빌드를 쉽게 관리할 수 있다.

---

## Basic Structure

```makefile
target: dependency
	command
```

- target : 생성할 파일
- dependency : 필요한 파일
- command : 실행 명령어

---

## Example

```makefile
main: main.c
	gcc -o main main.c
```

---

## Build Command

```bash
make
```

현재 디렉토리의 Makefile 실행

---

## Clean Command

```makefile
clean:
	rm -f main
```

실행 파일 삭제

실행:

```bash
make clean
```

---

## What I Practiced

- gcc compile 과정 이해
- Makefile 구조 학습
- build 자동화 실습
- make / make clean 사용
