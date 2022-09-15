# test-1
깃허브 연습하기

- 깃 연결 방법
  + 이름 설정
    - `git config --global user.name "이름"`
  + 이메일 설정
    - `git config --global user.email "이메일"`
  + 기본 편집기 변경
    - `git config --global core.editor "실행파일 경로"`

- 깃 설정
  + `git status`
  + `git log --stat`
  + `git diff`

- 깃허브 연결 방법
  + 폴더 생성
    - `mkdir hello-git`
  + 깃 설정
    - `git init`

- 깃 커밋 방법
  + 스테이징 추가 (git add 파일명)
    - `git add hello.txt`
  + 커밋 (git commit -m "메시지명")
    - `git commit -m "txt_create"`
  + 스테이징 및 커밋 처리(git commit **-am** "메시지명")
    - `git commit -am "message2"`

- 브랜치 생성 방법
  + 브랜치 생성
    - `git branch 브랜치명`
  + 브랜치 변경
    - `git checkout 브랜치명`
  + 다른 브랜치와 병합(merge)
    - `git merge 브랜치명`
  + 병합 취소
    - `git merge --abort`

- 깃허브 push, pull 방법
  + 깃허브 연결
    - `git remote add origin https://github.com/blackzon01/test-1.git`
  + 깃허브 연결 확인
    - `git remote -v`
  + 깃허브 업로드
    - `git push -u origin master` 
  + 깃허브 다운로드
    - `git pull origin master`
  + ssh 연결(보안)
    - ```
        ssh-keygen
        cd ~/.ssh
        cat id_rsa.pub
      ```
    - gitbash에 조회한 ssh 값을 github 설정에 입력

- 기타
  + 깃에서 제외파일 목록 관리 (.gitignore)
    - 파일 `파일명.txt`
    - 폴더 `temp/`
    - 확장자 `.txt`
  + 되돌리기
    - 작업 되돌리기 `git checkout -- 파일명.txt`
    - 스테이징 되돌리기 `git reset HEAD 파일명.txt`
    - 특정 커밋 되돌리기 `git reset --hard 커밋코드`
    

+ 
