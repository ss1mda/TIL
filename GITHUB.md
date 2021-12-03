# GitHub 설정

``` 
초기 설정(이름, 이메일)
$ git config --global user.name "Your Name"
$ git config --global user.email you@example.com

설정 확인
$cat ~/.gitconfig
```

``` 
폴더 만들기
$mkdir 폴더 명

파일 만들기
$touch 파일 명
*필수 파일 : README.MD, .gitignore(파일 중에 숨겨야 하는 파일을 설정, gitignore.io 사이트)

폴더를 레포지토리로 업그레이드
$git init

현재 상태 확인
$git status

git 추가
$git add
git 전부 추가
$git add . 

git commit 추가
$git commit -m 'first commit'

github 연결 
$git remote add origin 주소

github 올리기
$git push -u origin master

github 연결된 상태 확인
$git remote -v
```







