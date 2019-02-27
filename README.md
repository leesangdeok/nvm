# nvm
node.js 버전관리

### nvm (node.js 버전관리) 설치  
```bash
# curl
$ curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.34.0/install.sh | bash

# wget
$ wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.34.0/install.sh | bash
```

* bash_profile 에 소스 추가 (~/.bash_profile, ~/.zshrc, ~/.profile, or ~/.bashrc)
```bash
$ vi ~/.bash_profile

export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
```

* bash_profile 갱신
```bash
$ source ~/.bash_profile 
```

## node.js 설치

* node 버전 확인 및 설치
```bash
# node 버전 목록
$ nvm ls 

# latest version
$ nvm install node 

# specific version
$ nvm install 6.14.4
```

* node 버전 변경
```bash
# node 버전 변경
$ nvm use 10.25.0

# node 버전 확인
$ node -v
```
