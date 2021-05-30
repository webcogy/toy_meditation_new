# 토이프로젝트 - 명상&힐링

- 사용기술
  - HTML
  - CSS
    - styled-components - 미작업
  - JS
    - typescript
    - react
    - redux - 미작업
    - nextjs
    - nodejs
      - express
  - DB firebase
  - storybook - 미작업

### [1] nextjs 프로젝트 설치 및 환경설정

```
// 설치 (nextjs)
npx create-next-app [원하는 파일명] --typescript

// 시작
yarn dev
```

| 참고 (nextjs 필요한 것만 빨리 배우기): https://velog.io/@jakeseo_me/Next.js-%EB%B9%A8%EB%A6%AC-%EB%B0%B0%EC%9A%B0%EA%B8%B0-y0jz9oebn0#nextjs%EC%9D%98-%EB%8C%80%ED%91%9C%EC%A0%81-%ED%8A%B9%EC%A7%95%EC%9D%B4%EC%9E%90-%EC%9E%A5%EC%A0%90

### 2. Node.js express 설치하기

```
npm install express --save

// 추가 라이브러리 설치

1) post 통신시 데이터를 읽어들이는 라이브러리
npm install body-parser --save

2) 세션 기능을 활성화 시키는 라이브러리다. 웹개발 로그인 부분에서 필수적이라고 할 수 있다.
npm install express-session
```

// nextjs와 nodejs port 완전 분리해야 개발이 더 편하다.
nextjs port:3000
nodejs port:3080

| 참고 : https://ichi.pro/ko/nodejs-baeg-endeuleul-sayonghayeo-next-js-aeb-eul-gaebalhago-bildeuhaneun-bangbeob-typescript-beojeon-193852778883920
