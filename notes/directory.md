# Directory

## What is Directory?

Directory는 파일들을 저장하고 관리하는 공간이다.

Linux에서는 디렉토리도 파일의 한 종류로 관리된다.

---

## Main Functions

### opendir()

디렉토리 열기

```c
DIR *dir = opendir(".");
```

---

### readdir()

디렉토리 내부 파일 읽기

```c
readdir(dir);
```

---

### closedir()

디렉토리 닫기

```c
closedir(dir);
```

---

## Directory Commands

### pwd

현재 디렉토리 출력

```bash
pwd
```

---

### ls

파일 목록 출력

```bash
ls
```

---

### cd

디렉토리 이동

```bash
cd directory_name
```

---

## What I Practiced

- Linux 디렉토리 구조 이해
- opendir/readdir 사용
- 파일 목록 출력 실습
- 디렉토리 이동 및 관리 실습
