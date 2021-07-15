# Git Command

## Git

### Git initialize
```bash
git init
git config --global user.name "jayden-dragon"
git config --global user.email "gsjang95@gmail.com"
```

### Git present status
```bash
git status
```

### Git add changes
```bash
git add -A
git add --all
git add *

git filename
```
### Git reflect changes & commit
```bash
git commit -m "message" 
```

### Git log
```bash
git log
```

### Git reset 
```bash
git reset commit_num --hard         // commit_num '상태로' 되돌리고 삭제하기 
```

### Git revert
```
git revert commit_num               // commit_num '상태를' 없애고, 없앤 commit을 남김
```

### new branch 생성
```bash
git branch branch_name
```

### branch 변경
```bash
git checkout branch_name
```

### branch 리스트 확인
```bash
git branch
```

### master-branch 합체
```bash
git merge branch_name
```

### branch 삭제
```bash
git branch -D branch_name
```

### all log 확인
```bash
git log --graph --all --decorate
```

### branch 합치기
```bash
git rebase branch_name       // merge와 차이점 : 기존 커밋 이력이 변경됨
```

## Github

### Github 원격저장소 생성
```bash
git remote add remote_repo_name https://github.com/user_name/repo_name.git
```

### Github 원격저장소와 연결
```bash
git push -u origin master  // 브랜치의 기본이름 master, 원격저장소의 기본이름 origin
```

### 소스코드 수정 후 업데이트
```bash
git add file_name
git commit -m "commit" 
git push origin master
```

### .gitinore 
Github에 올릴 필요가 없는 파일


### Github에서 소스 받아오기
```bash
git clone hhttps://github.com/
```

### 원격 저장소에 들어가지 않고 변경사항을 확인하는 방법
```bash
git fetch
git status
```

### 변경된 내용을 받아오는 방법
```bash
git pull origin master
```

### git branch 생성 후 이동
```bash
git branch branch1
git checkout branch1

git checkout -b branch_name
```

### git push branch
```bash
git add workBranch1
git commit -m "add workBranch1"
git push origin branch1
```

### branch 삭제
```bash
git branch -d branch1
git push origin --delete origin/branch1
```

### local & remote branch 확인
```bash
git branch -a
```

### 원격 브랜치를 로컬 브랜치로 받아오기
```bash
git checkout -b branch1 origin/branch1
```

