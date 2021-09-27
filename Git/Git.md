# 🔍 Git이란?
    -> Git이란 파일 버전 관리 시스템을 말한다.

### 🧷 Git을 사용하기 위한 필요 요소
    - 개인 컴퓨터
    - USB
    - 회사 서버
    - 클라우드(Github 등..)
        -> 저는 Github을 사용해서 버전관리를 할 예정입니다!
        * 여기서 Github이란 Git 원격저장소 입니다.


### 🧷 Git을 사용하는 두 가지 방법
    - CLI (Command-line interface)
    - GUI (Graphical user interface)

### 🧷 Git에서 사용되는 명령어

    🔹 로컬 저장소 생성 
    - git init
        해당 명령어 사용 시 명령어를 작성한 폴더에 .git이라는 숨겨진 폴더가 생성된다.
        이것이 바로 로컬 저장소! 이 로컬 저장소에 생성된 버전 정보, 원격 저장소 주소 등이 저장된다.
        ❗️ 원격 저장소에서 내 컴퓨터로 저장소를 받아올 경우는 로컬 저장소가 자동으로 생긴다.
        ❗️ 반드시 한 폴더에 하나의 로컬 저장소만 유지하여야 한다.

    🔹 git 전역 사용자 설정
    - git config --global user.name "Kiyoon Park"
    - git cinfig --global user.email kiyoon1008@gmail.com

    🔹 commit을 원하는 파일 선택하기(스테이지에 올리기)
    - git add .
        ❗️ 파일을 선택하여 add할 경우에는 dot 대신 파일명을 입력한다.

    🔹 스테이지에 올라간 파일 commit하기
    - git commit -m "message"

    🔹 생성된 commit 확인하기
    - git log

    🔹 로컬 저장소에 원격 저장소 주소 알려주기
    - git remote add origin https://github.com/아이디/이름.git

    🔹 생성된 commit을 push하기
    - git push origin master

    🔹 원격 저장소의 변경사항을 로컬 저장소에 불러오기
    - git pull origin master

    🔹 원격 저장소를 내 컴퓨터에 불러오기
    - git clone https://github.com/아이디/이름.git .
        ❗️ 명령어 입력 후 dot을 입력해야 현재 폴더에 내려받아진다.
        dot을 찍지 않을 경우에는 폴더가 생성됨.





    