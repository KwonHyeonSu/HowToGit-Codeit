# HowToGit-Codeit

git init -> 버전관리 시작 , .git 폴더 생성

commit -> 사용자 이름, 이메일 주소 지정하기

git config --global user.name "soo"
git config --global user.email "gustngusrud1@naver.com"

git add calculator.py

got commit -m "Create calulator.py" -> 커밋 메시지

git status -> 변경될 사항과 아닌 것을 확인

git add . -> 변경된 모든 사항을 staging Area에 추가

git reset calculator.py -> stating Area에서 제거

git push -> (local -> hub)

git pull -> (hub -> local)

git log -> 커밋 히스토리 내역 확인

git log --pretty=oneline -> 예쁘게 한줄로 출력

git show ->구체적으로 어떻게 수정이 되었는지

git commit -> -m 옵션 없이 긴 커밋 메시지를 저장 가능

git commit --amend -> 가장 최근에 수정한 commit 메시지 수정가능

git config alias.history 'log --pretty=oneline' -> git history라는 명령어가 git log --pretty=oneline이라는 명령어로 대체됨

git diff (첫번째 commit id) (두번째 commit id) ->  첫번째와 두번째의 commit 차이

git reset --hard (commit id) -> head를 바꾸어 working directory의 내용을 아얘 바꿔버림

```
Git은 내부적으로 크게 3가지 종류의 작업 영역을 두고 동작합니다.

각 작업 영역의 이름은

working directory
staging area
repository
```

git reset 뒤의 명령어 차이   

![image](https://user-images.githubusercontent.com/48755297/87432313-c8e72280-c622-11ea-85ec-bcf0ab467d75.png)

git reset --hard HEAD~2 -> Commit 2번 이전 내용으로
git reset --hard HEAD^ -> Commit 바로 이전 내용으로
