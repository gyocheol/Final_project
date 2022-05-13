npm install -g expo-cli

https://tyrannocoding.tistory.com/58



Unsupported SDK version: our app builders do not support SDK version 45, yet. The latest SDK version is 45.0.0.
Unsupported SDK version
Error: Unsupported SDK version

sdk오류 뜨면

```
npm install -g eas-cli
eas build -p android
```


node 문제있을때
```python
node -v  # node 버전 확인
npm cache clean -f # 캐시 삭제
npm install -g n # nodejs 버전관리 플러그인
```

```python
n latest # 최신버전
n lts # lts 버전
n stable # 안정버전
```

nodejs를 업데이트 한 후 npm도 업데이트 합니다.

```python
npm -v # npm 버전 확인
npm install -g n # npm 업데이트(global 경로)
```



처음부터

goorm ide 터미널 react native 로 터미널 생성

1. 터미널 : expo install react-native-webview
2. App.js : import * as React from 'react'; import { WebView } from 'react-native-webview'; export default class App extends React.Component {  render() {    return <**WebView** source={{ uri: '원하는url' }} style={{ marginTop: 20 }} />;  } }
3. 터미널 : npm install -g expo-cli





