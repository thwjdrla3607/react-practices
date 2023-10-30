ex01: js Module 번들링 하기
                : 모듈들의 의존성 관계를 파악하여 그룹화시켜주는 작업

1. 설치 패키지
$ npm i -D express webpack webpack-cli

2. 스크립팅w
    "scripts": {
        "start: "node dev-server",
        "build": "npx webpack ./src/index.js -o ./public"
    }

3. 빌드
$ npm run build

4. 실행
$ npm start