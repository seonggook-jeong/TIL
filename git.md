# Git

> Git은 분산버전관리시스템(DVCS)이다.
>
> 소스코드의 버전 및 이력을 관리할 수 있다.

## 준비하기

윈도우에서 Git을 활용하기 위해서 [git bash](https://gitforwindows.org)를 설치한다.

git을 활용하기 위해서 GUI툴인 `source tree`, `github desktop` 등을 활용할 수도 있다.

초기 설치를 완료한 이후에 컴퓨터에 `author` 정보를 입력한다. github에 가입된 이메일과 일치되어야 커밋 이력들이 관리된다.

```bash
$git config --global user.name seonggook-jeong
$git config --global user.email okepower@naver.com
```

## 로컬 저장소(repository) 활용하기

### 1. 저장소 초기화

```bash
$ git init
Initialized empty Git repository in C:/Users/student/OneDrive - 서울시립대학교/이미지AI/TIL/.git/
(master) $
```

* `.git` 폴더가 생성되며, 여기에 git와 관련된 모든 정보가 저장된다.
* git bash에 `(master)` 라고 표현되는데, 이는 `master` 브랜치에 있다는 뜻이다.

## 2. add

`working directory` , 즉 작업 공간에서 변경된 사항을 이력으로 저장하기 위해서는 반드시 `staging area` 를 거쳐야 한다.

```bash
$git add markdown.md  #특정 파일
$git add images/  #특정 폴더
$git add .  #현재 디렉토리
```



