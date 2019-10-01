# Project ARIES [![GitHub license](https://img.shields.io/github/license/DokySp/ARIES)](https://github.com/DokySp/ARIES)

 - **1차 개발 마무리**
    - 2019.06.19 ~ 08.19 **(2M)**
 - **공개 여부**
    - :x: (2019.08. ~ )

# Try out!
 - [AREazy.com](https://areazy.com)

<br>

# 구조
### Frontend
 - `Vue.js` 기반 프론트엔드
 - `vue create` 명령어로 생성(vue-cli-3.x)
 - [readme.md](https://github.com/DokySp/ARIES/blob/master/frontend/protocol.md)

### Backend & Publish Server
 - `node.js` 기반 백엔드 + 배포용 서버
 - `express-generator`로 프로젝트 생성
 - [readme.md](https://github.com/DokySp/ARIES/blob/master/backend/protocol.md)

### 필요한 패키지
 - package: `nodejs`, `npm`, `mongodb`
 - npm global(for Dev): `nodemon`, `live-server`, `@vue/cli`, `babel-cli`

<br>

# 초기 설정
 1. `$ git clone https://github.com/DokySp/ARIES`
 2. backend/public 안에 내용 백업
 3. backend, frontend 폴더에서 `$ npm install`
 4. frontend에서 `$ npm run build`
 5. 빌드 완료 후, 2번에서 백업한 내용을 다시 backend/public 폴더에 복원
 6. 백엔드 [readme.md](https://github.com/DokySp/ARIES/blob/master/backend/protocol.md) 읽어보기
 7. backend폴더에서 `$ npm run start`

# To-Do
 - 배포 관련 브렌치 혹은 자동화 툴 제작
 - 계정 관련 작업 진행 및 세션 도입

# References
 - [JS Standard](https://github.com/standard/standard)
 - [Travis-ci](https://travis-ci.org)
 - [참고 1](https://m.blog.naver.com/PostView.nhn?blogId=silver889&logNo=220083873954&proxyReferer=https%3A%2F%2Fwww.google.com%2F)

