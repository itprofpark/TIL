CLI명령어-00_basic_cli.md

Git 명령어-01_git.md



### Git 저장소

`$git init` git init으로 새로 만들어진 저장소는 .git폴더가 생성됨

`$git clone https: github.com/ test`

git add와 git commit으로 관리할 파일을 지정하고, 영구적으로 저장할 수 있음

`$git add *.java`

`$git commit -m 'init project version' `

### Git의 기본 Workflow

- (Possible init or clone) Init a repo
- Edit files
- Stage the changes
- Review your changes
- Commit the changes

`gits status` : 파일 상태를 확인할 수 있음

#### 저장소에 저장하기 위한 상태 이해

- 워킹 디렉토리 파일 상태
  - Tracked(관리대상)
  - untrackted(비관리대상)



### repository

### Git Remote(Push)

* `git remote`:  Remote Repository 주소를 등록(GitHub Repo주소)
  * `git remote add origin (주소)`:remote repo의 주소를 origin이라는 별칭으로 등록
* `git push (별칭) (브랜치이름) `:별칭으로 브랜치를 push(올리기, 내컴퓨터->깃허브 동기화)
  * `git push origin master`: origin으로 master브랜치를 전송
* `git pull ( 별칭) (브랜치  이름)` : `별칭`으로부터 `브랜치`를 pull(내려받기, 깃허브->내컴퓨터 동기화)
* `git clone (주소)` : 주소로부터 repository가져오기







