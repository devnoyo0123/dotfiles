# dotfiles

# 1. Brewfile 생성하기
현재 맥에서 다음 명령어를 실행하여 설치된 모든 패키지 목록을 Brewfile로 저장합니다:

```bash
brew bundle dump
```
이 명령어는 현재 디렉토리에 Brewfile이라는 파일을 생성합니다. 이 파일에는 현재 설치된:

# 2. 새 맥에서 설치
Homebrew 설치
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

# 3. Brewfile로 패키지 설치
```bash
brew bundle --file=~/Documents/Brewfile
```
