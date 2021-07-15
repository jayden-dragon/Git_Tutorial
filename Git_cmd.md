# Git Command

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

### .gitnore 
Github에 올릴 필요가 없는 파일

