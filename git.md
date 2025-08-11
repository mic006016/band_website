# GIT

## 처음 한번만 실행하는 명령어
```bash
# git hub, userid, email
git config --global user.name "userid"
git config --global user.email "userid@mail.com"
```

## Repository 처음 생성한 후, 로컬폴더와 연동시키기
```bash
# 내 로컬폴더에 git을 사용하게 설정
git init 
# 생성한 github repository와 연동 설정
git remote add origin https://github.com/repository_name.git
```

## 작업 명령
```bash
# 레퍼지토리를 복제
git clone repository_name

# 로컬 명령 : 대상 파일 및 폴더를 staging상태로 만든다.
git add .
git add 파일명

# 로컬: stage에 올라가있는 대상을 하나의 commit(저장상태)으로 만든다.
git commit -m "메시지"

# 로컬 -> 원격 commit을 동기화시키기.
git push

# 원격 -> 로컬로 commit을 동기화 시킨다
git pull
```