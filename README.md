# backend

## 주제: 위치, 시간 기반 채팅 웹사이트
### 기본적인 채팅 기능 구현
로그인, 회원가입, 정보확인, 친구추가, 위치확인, 채팅

### 추가 중요 기능
위치, 시간 기반 채팅 기능
같은 위치에 있을 경우에 지정한 시간 안에 읽을 수 있는 랑데뷰 메세지 기능 추가


### 실행

    npm start

---
### 구조 설명
- bin: 실행 파일을 관습적으로 /bin 에 넣어둔다고 함. npm start를 하면 bin 내의  www.js를 통해 서버가 구동
- modules: 모듈 파일
- public: 외부에서 접근 가능한 파일
- routes: 라우터
- view: 템플릿 파일
- app.js : 익스프레스 서버 코드가 담긴 파일, 서버 구동의 핵심
- package-lock.json: 패키지간 의존관계를 명확하게 표시하는 파일
- package.json: 프로젝트에 대한 정보와 사용 중인 패키지에 대한 정보를 담은 파일

---

### 추가 사항
처음 파일을 받고 npm install을 터미널에 입력하면 패키지가 node_modules 폴더가 만들어지고 패키지가 설치
