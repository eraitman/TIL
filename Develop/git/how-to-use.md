# git 기본사용법

## 1.git init
* git 레파지토리로 사용하고 싶은 폴더로 이동
* `git init` 실행 

## 2.git 원격지 추가하기
* `git remote add origin [url]`
> 여기서 origin이 뭘 뜻하는 거지?

## 3.소스 수정
* 변경 후 stasy 변경 스테이징(staging)확인
* 로컬레파지토리에서 commit

## 4.push / commit?
* `git pull origin master`
* 원격레파지토리로 push~!
> To-do : 좀더 상세히 알아보자

# 더 알아볼것
## merge
## fetch

# 문제해결
## 01. `refusing to merge unrelated histories` 문구 해결
* `git pull origin master --allow-unrelated-histories`

