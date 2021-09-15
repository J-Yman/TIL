# VSCode 터미널에서 코드를 원격 저장소에 저장하는 방법

## 1. 깃허브에 repository 를 생성한다.

## 2. 생성한 리포지토리 주소를 복사해둔다.
* 밑에 5번에서 쓰인다.

## 3. 프로젝트 루트 폴더에 가서 터미널에 `git init` 을 입력한다.
* 깃 저장소임을 선언하는 명령어.

## 4. 이어서 터미널에 아래 두 명령어를 차례로 입력한다.
* `git config --local user.name "유저이름"`
* `git config --local user.email "유저이메일"`
* 위 명령어들은 이 저장소를 사용하는 유저가 누구인지 알려주기 위함이다.
* `git config --list` 명령어로 설정을 확인할 수 있다.

## 5. 원격 저장소를 연결한다.
* 터미널에 `git remote add 저장소별명 2에서복사한주소` 를 입력한다.
* ex : `git remote add main https://github.com/J-Yman/Bornga`


## 6. `git add` 명령어로 push 할 파일들을 store 상태로 만든다.
* `git add 파일경로/파일이름`

## 7. `git commit -m "메시지"` 명령어로 store 상태의 파일들을 커밋한다.
* ex : git commit -m "feat : 라우팅 처리"

## 8. `git push -u 저장소별명 브랜치명` 명령어로 원격 저장소에 커밋된 내용을 push한다.
* ex: `git push -u main main` 

## 9. 깃 로그인 팝업 창이 뜨면 로그인한다. 끝!

