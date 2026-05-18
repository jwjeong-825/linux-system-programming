# System Data Files

## What are System Data Files?

Linux는 시스템 정보를 파일 형태로 관리한다.

사용자 정보, 그룹 정보, 시스템 설정 등이 파일로 저장된다.

---

## Important Files

### /etc/passwd

사용자 계정 정보 저장

```bash
cat /etc/passwd
```

포함 정보:
- username
- UID
- GID
- home directory
- shell

---

### /etc/group

그룹 정보 저장

```bash
cat /etc/group
```

---

### /etc/shadow

암호 정보 저장

일반 사용자는 접근 불가능

---

## User Information

Linux는 사용자마다 UID(User ID)를 가진다.

- root UID : 0
- 일반 사용자 : 1000 이상

---

## Main Functions

### getpwent()

사용자 정보 읽기

```c
getpwent();
```

---

### getgrent()

그룹 정보 읽기

```c
getgrent();
```

---

## What I Practiced

- Linux 사용자 구조 이해
- /etc/passwd 분석
- UID/GID 개념 학습
- system data file 접근 실습
