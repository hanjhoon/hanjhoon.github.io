Git 명령어

1. 폴더 내부 우클릭 -> git bash here

2. git config --global user.name
"hanjhoon"

3. git config --global user.email
"hanjongh0726@gmail.com"

4. git init

5. git remote add origin

6. git remote -v

7. touch 파일명
파일 생성
8. ls
파일/폴더 목록 확인
9. git add .
 변경 사항 스테이징
10 git status
스테이징 되어 있는 파일 확인 / 빨간색 : 변경 사항이 있으나 인덱스에 반영 안 됨
11 git commit -m "커밋 메시지"

12. git log

13. git push origin master
origin에 master 브랜치를 업로드
14. git add 파일명
특정 파일만 스테이징 / 초록색 : 작업 트리의 변경사항이 스테이징 영역에 반영 됨
15. git reset
언스테이지(추적 해제)
16. git commit

17. git reset 커밋 주소

18. .gitignore

19. git rm -r --cached .
현재 장소에 있는 파일들을 인덱스에서 일괄 삭제 처리
20. get remote -v
원격 저장소의 연결 상태 체크
21. git push 저장소 이름 브렌치 이름
