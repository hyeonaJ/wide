print('wide')
# sw 폴더를 전체 클릭하지말고, 만들어진 파일을 클릭한 후, 오른쪽 마우스를 클릭해서 Vcode 접속해서
1. pwd
2. git init
3. git add .
4. git commit -m " "
5. git remote add origin ~ (마우스 세번클릭해서 그대로 복사!)
6. git push origin master

여기까지가 기본적인 한 루트!

  ## 기본적으로 알아야 할 지식 ##
- 커밋(commit): 파일을 추가하거나 변경하는 내용을 저장소에 저장하는 작업. 그래서 변경되면 git add . git commit -m " " 까지
- 푸시(push): 파일을 추가하거나 변경내용을 원격 저장소에 업로드하는 작업. Also commit 후에 git push origin master까지 입력

- git log: 로컬 저장소의 커밋 히스토리를 탐색하는데 사용하는 명령
- git merge: 현재 브랜치에서 다른 지점에서 변경사항을 병합하는데 사용하는 명령어
다음 예시는 bugfix를 master 브랜치에 병합하는 내용
- git pull: 원격 브랜치의 변경사항을 캡처하기 위해 사용하는 명령어 다음 로컬 저장소의 master브랜치에 원격 저장소 origin의 master브랜치를 가져옴