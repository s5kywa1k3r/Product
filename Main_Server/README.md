## Server

Server 쪽을 구현하는 디렉토리 입니다.

<br>

### 현재 사용 버전

> nodejs: 12.14.0  
> npm: 6.13.4

그 외 모듈들에 대한 버전은 package.json에서 자동 빌드됩니다.

<br>

### 빌드 및 실행 방법

-   Main_Server 디렉토리에 도달해 있는지 확인합니다.

```zsh
$ cd API
$ npm install       # API 모듈 설치
$ npm build         # API 코드 빌드
$ cd ../
$ npm install       # 서버 모듈 설치
$ npm run dev       # 서버 실행
```

이 후, 차례대로 하면 실행되는 것을 확인할 수 있습니다.

1. <localhost:3000> 에 접속합니다.
2. 기존 url localhost:3000 로 접속합니다.
3. process를 끝내고 싶다면 실행했던 terminal로 이동하여 `ctrl+c`를 입력하면 종료됩니다.

<br>

### 진행하면서 바뀔 사항

-   이 후, 진행이 되는 부분에 있어 수정 반영하겠습니다.
-   Interface도 계속 수정 반영할 예정입니다.
