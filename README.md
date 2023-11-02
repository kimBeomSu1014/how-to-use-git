# how-to-use-git

## Git 명령어
### 저장소 생성
``` git init ```

### 저장소 복제/다운로드
``` git clone ${url} ```

### 브랜치 명령어
브랜치 목록 보기
``` git branch ```

브랜치 생성 및 이동
``` git checkout -b ${branch-name} ```

master(main) 브랜치로 이동
``` git checkout master(main) ```

브랜치 삭제
``` git branch -d ${branch-name} ```

원격 서버로 브랜치 전송
``` git push origin ${branch-name} ```

---
### 푸쉬 명령어
변경사항 브랜치에 올리기
``` git push origin ${branch-name} ``` -> master,main 가능

원격 서버(클라우드) 등록
``` git remote add origin ${address or url} ```

원격 서버(클라우드) 삭제
``` git remote remove <${address or url}> ``` 주소는 선택

---
### 갱신/병합 명령어
원격 서버로부터 가져와 병합하기
``` git pull origin ${branch-name} ```

현재 브랜치와 다른 브랜치 병합하기
``` git merge ${branch-name} ```

병합 전 바뀐 내용 보기
``` git diff ${branch-name} ${branch-name} ```

---
### 작업 확인하기
커밋 내용 확인 및 식별자 부여
``` git log ```

커밋 상황 확인
``` git status ```

---
### 백업,롤백 작업
변경 사항을 변경 전으로 돌리기
``` git checkout -- <${file-name}> ```

원격 서버의 프로젝트 현상태 가져오기
``` git fetch origin ```

---
