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
