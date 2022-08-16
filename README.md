# GIT Command  

## 커밋 할 파일 지정
```sh
  # 수정된 파일 전체 지정
  git add .
  
  # 수정된 파일 하나만 지정
  git add 파일명
  
  # 수정된 폴더 지정
  git add 폴더명
```
***
## 파일 삭제 커밋
### 주의 할 점 로컬 파일 삭제하고 할 것

```sh
  git rm 파일명 or git rm --cached 파일명
  git commit -m "remove 파일명"
  git push 
```
***
## 리모트 관련 command
```sh
  # remote 확인
  git remote -v
  
  # remote 삭제
  git remote remove origin
```
