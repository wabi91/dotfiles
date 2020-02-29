``` 
___       __   ________  ________  ___          ________  ________  _________  ________ ___  ___       _______      
|\  \     |\  \|\   __  \|\   __  \|\  \        |\   ___ \|\   __  \|\___   ___\\  _____\\  \|\  \     |\  ___ \     
\ \  \    \ \  \ \  \|\  \ \  \|\ /\ \  \       \ \  \_|\ \ \  \|\  \|___ \  \_\ \  \__/\ \  \ \  \    \ \   __/|    
 \ \  \  __\ \  \ \   __  \ \   __  \ \  \       \ \  \ \\ \ \  \\\  \   \ \  \ \ \   __\\ \  \ \  \    \ \  \_|/__  
  \ \  \|\__\_\  \ \  \ \  \ \  \|\  \ \  \       \ \  \_\\ \ \  \\\  \   \ \  \ \ \  \_| \ \  \ \  \____\ \  \_|\ \ 
   \ \____________\ \__\ \__\ \_______\ \__\       \ \_______\ \_______\   \ \__\ \ \__\   \ \__\ \_______\ \_______\
    \|____________|\|__|\|__|\|_______|\|__|        \|_______|\|_______|    \|__|  \|__|    \|__|\|_______|\|_______|

```


# .gitconfig

### 사용될 라이브러리 fzf

Git 편의를 위해 사용될 라이브러리 [fzf install](https://github.com/junegunn/fzf) 을 합니다.

#### 사용될 키
```
esc: 취소
tab: 선택/선택취소
enter: 확인
```

#### Using Homebrew
[Homebrew](http://brew.sh/)로 다운로드
```sh
brew install fzf
```
esc: 취소, tab: 선택/선택취소, enter: 확인

|GIT alias 명령어|설명|부가 설명|
|------|---|---|
|git s|스테이터스 간단하게 변경 내용 보기|status --short|
|git nb|새로운 브랜치 생성 & 전환| - |
|git cb|마스터 브랜치에 머지된 브랜치 삭제| - |
|git db|원하는 브랜치명 선택 후 삭제|'tab'키 다수 선택 가능|
|git ch|원하는 브랜치명 선택해서 전환| - |
|git ia|라인 단위로 stage에 추가할 때 사용| git ia -p |
|git id|라인 단위로 diff 볼 때 사용| git id -p |
|git a|변경점 있는 파일 선택후, stage에 올림|'tab'키 다수 선택 가능|
|git re|state에 올린 파일 중 선택후 stage에서 내림|'tab'키 다수 선택 가능|
|git rmdiff|변경점 있는 파일 선택 후 삭제|'tab'키 다수 선택 가능|
|git chdiff|변경점 있는 파일 선택 후 되돌리기|'tab'키 다수 선택 가능|
|git pu|push upstream|2가지 전제조건<br/>remote는 origin 고정이다.<br/>remote와 local 브랜치 이름이 같다.|

#### 참고 링크
[Homebrew](http://brew.sh/)

[fzf](https://github.com/junegunn/fzf)

[oh-my-zsh 내장 alias](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/git/git.plugin.zsh)

