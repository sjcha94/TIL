# git & github 특강 1일차 정리

## 1. **git 초기 설정**  
최초 한번만 설정, **Who** & **e-mail** 으로 고유 사용자 판별  
``` bash
$ git config --global user.name "이름"
$ git config --global user.email "메일 주소"
```
확인 작업 필수.
``` bash
$ git config --global -l

또는

$ git config --global --list
```


## 2. **git init**  
현재 작업 중인 디렉토리를 **Git**으로 관리한다는 명령어.  
MAC OS의 경우 **(master)** 표시가 되지 않는다. Terminal 업그레이드로 가능  
``` bash
$ git init
Initialized empty Git repository in C:/Users/kyle/git-practice/.git/
kyle@KYLE MINGW64 ~/git-practice (master)  
```
> 단, 홈 디렉토리에서는 설정해서는 안된다.   
> 또한, 중첩이 금지된다. 터미널에 이미 (master)가 존재할 경우, 절대 입력 X  



