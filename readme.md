# 팀 개발을 위한 Git, GitHub 시작하기

## Git, 그리고 GitHub

### 버전 관리란 무엇인가?

### Git, 그리고 GitHub

## Git을 설치하고 로컬저장소에서 커밋 관리하기

### 로컬저장소 만들기

### 첫 번째 커밋 만들기

```bash
git config --global user.email "awsawsjungseok@gmail.com"
```

```bash
git config --global user.name "ojs"
```

```bash
git add readme.md
```

```bash
git commit -m "first commit"
```

```bash
git add readme.md
```

```bash
git commit -m "second commit"
```

### 커밋 되돌리기

```bash
git log
```

```bash
git checkout 5813bb5
```

여기서 5813bb5는 커밋로그의 커밋 ID의 앞 7자리

```bash
git checkout -
```

## GitHub 원격저장소에 커밋 올리기

### 원격저장소 만들기

레포지토리 생성

### 원격저장소에 커밋 올리기

```bash
git remote add origin 레포지토리 주소
```

```bash
git push origin master
```

## GitHub 원격저장소의 커밋을 로컬저장소에 내려받기

### 원격저장소의 커밋을 로컬저장소에 내려받기

다른 로컬저장소 생성

```bash
git clone https://github.com/awsjungseok/gitstudy.git .
```

 
