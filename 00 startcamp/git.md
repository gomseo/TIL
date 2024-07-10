# git 필기
## 커밋/푸쉬 규칙
* 꼭 항상 절대!!! add, commit, push는 최상단 폴더에서 작업하기

## 내가 사용하고 있는 컴퓨터에서 처음으로 깃 작업을 할때 한번만 하면 됨
### `git config` : 계정설정 및 추가
* `git config --global user.name 나의 유저네임`
* `git config --global user.email 나의 이메일`
### 계정확인하려면
* `git config --global user.name`
* `git config --global user.email`
### 잘못 입력 시 한번 더 입력하면 코드 수정 가능

## 처음으로 git을 시작할때 한번만 하면 되는 작업
### `git init`
### `git remote`
* `git remote add origin 나의 깃헙의 원격저장소(github) 레포 주소`
* `git remote -v` : 내가 등록한 원격저장소 레포 주소 확인
* `git remote remove origin` : 등록한 원격저장소 삭제

## working directory에 변동이 있을때마다 하는 작업
### `git add`
### `git commit`
### `git push`

## 상태 확인
### working directory에서
- `git status`
    - add 전/후
### staging area에서(.git)
- `git status`
    - 추적이 되고 있는지만 확인가능
- `git log`
    - commit 이후에만 확인가능
    - `--oneline` : 간결하게 보여줌
