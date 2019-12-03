# Git을 이용한 프로젝트 관리
## Git 처음 설치
### https://git-scm.com 에서 git 프로그램을 다운로드 하여 기본설치한다.
### Git을 처음 설치하는 컴퓨터에서는 아래의 명령을 한번만 실행한다.
~~~bash
git config --global user.email "booldook@gmail.com"
git config --global user.name "booldook"
~~~

### 본인의 프로젝트 폴더를 vscode에서 폴더열기로 열고 터미널창 [ctrl+j] 을 열고 아래의 명령을 실행한다.
~~~bash
git init
# 본인의 github에서 가장 긴 줄을 복사하여 아래에 붙여 실행한다.
git remote add origin https://github.com/booldook/2019-ay-pf-sample.git
~~~

### 집에서 연결하기 위해서는 아래의 과정을 (프로젝트별로)한번만 거친다
~~~bash
git clone https://github.com/booldook/2019-ay-pf-sample.git
~~~
