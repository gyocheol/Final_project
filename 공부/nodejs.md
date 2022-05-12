ERROR: Node.js version 16.15.0 is no longer supported.

expo-cli supports following Node.js versions:
* >=10.13.0 <11.0.0 (Active LTS)
* >=12.0.0 <13.0.0 (Active LTS)
* >=13.0.0 <14.0.0 (Current Release)



npm i expo-cli

하면 expo깔림

근데 port 오류

listen EADDRINUSE: address already in use :::19002
Error: listen EADDRINUSE: address already in use :::19002



윈도우에서 포트를 사용하는 프로세스 확인

netstat -ano




노드 버전 확인 : node -v
npm 버전 확인 : npm -v
node 버전 업 :

1. curl -sL https://deb.nodesource.com/setup_16.x | sudo -E bash -
2. sudo apt-get install -y nodejs



실패..