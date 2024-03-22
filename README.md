# React
# 신정호 202030421

### 목차
- [1주차](#1주차-2024-03-06)
- [2주차](#2주차-2024-03-13)
- [3주차](#3주차-2024-03-20)

---
## 3주차 (2024-03-20)
### 오늘 배운 내용
- React란 무엇인가?
- React의 장점
- create-react-app (React 프로젝트 생성)
  
### React란 무엇인가?
- 웹 및 앱 유저 인터페이스를 위한 라이브러리이다.
- SPA를 <b  style = "color: red">쉽고 빠르게</b> 만들수 있도록 도와주는 도구이다.
  - SPA : Single Page Application

### React의 장점
- VDOM을 사용하면 변경 사항만 대해서 업데이트 하기 때문에 <b>속도가 빠르다</b>.
  - 즉, VDOM은 비동기식 방법으로 렌더링한다.
![VDOM과 DOM의 차이](./3week/image.png)
- <b>컴포넌트 기반</b> 구조로 이뤄져 있다.
  
### create-react-app (React 프로젝트 생성)
- 터미널 새로 생성한 후 ```npx create-react-app app-name```를 입력한다.
- 패키지 경로를 확인 후 진행할 것이냐고 물어볼 경우 y를 입력한다.
  - 물어보지 않는 경우도 있었으나, 설치가 가능했다.
- 성공적으로 프로젝트를 생성하면 아래와 같은 트리 구조가 나타나게 된다.
  ![React 프로젝트 구성](./3week/test-app/react_project.png)
  - node_modules
  - public
    - 앱을 컴파일 하는데 필요하지 않는 요소들을 넣는다.
    - 정적 파일들을 담는 곳이다.
      - html, 이미지 파일이 있다.
  - src
    - 앱이 컴파일 하는데 사용하는 요소들을 넣는다.
  - .gitignore
    - node_modules 폴더와 같이 용량이 크거나, 개발 계획서등 필요하지 않는 파일들을 제외할 때 쓰인다.
  - package.json
    - npm 명령어 혹은 앱 이름,버전 등에 쓰인다.
---

## 2주차 (2024-03-13)
### 오늘 배운 내용
- Github 초기화
- HTML은 무엇인가?

---

### Github 초기화
- Git 초기화 하는 명령어
  - ```git init```
- 각 디렉토리 별로 초기화 하는 명령어
  - 개인 PC 환경에서 사용할 때
    - ```git config --global user.name "userName"```
  - 공용 PC 환경에서 사용할 때
    - ```git config user.name "userName"```
    - ``` git config user.email```
- commit 및 message 쓰기
  - 영어가 기본으로 쓰인다.
  - message는 enter key 2번 누르고 쓰면 된다.

### HTML은 무엇인가?
- 웹 사이트를 구성하는 하나의 구성 요소다.
- Tag를 이용해 하나의 큰 뼈대를 만든다.

### Javasript는 무엇인가?
- 동적으로 변경되는 콘텐츠를 만들고, 멀티 미디어를 제어하며, 이미지에 애니메이션을 적용한다.
- 브라우저에서 행하는 작업들을 제어하는 스크립트이다.

### 기본 자료형
- var
  - 재선언이 가능하며, 재할당도 가능하다.
- let
  - 재선언이 불가능하며, 재할당은 가능하다.
- const
  - 재선언, 재할당이 불가능하다.

### JSON
```javascript
let a = {
  name : "jungho",
  telnum: "010-2446-7600",
}  
```

### Arrow Function
```javascript
let arrow = a => a + b;
```
---

## 1주차 (2024-03-06)
### 오늘 배운 내용
- Markdown 기본 사용법 및 태그
- 시멘틱 버전
  
---

### 제목 태그

# h1
## h2
### h3
#### h4
##### h5
###### h6

### 줄 바꿈

`<br>`을 쓰거나 스페이스 바 2번을 입력한다.
텍스트 입력<br>줄 바꿈.

### 리스트

1. 숫자형 리스트
- 글머리형 리스트

### 코드 블럭
- 백틱(``)을 사용해서 감싼다.
- 백틱 옆에 프로그래밍 언어를 적어주면 적용이 된다.

```js
let a = 12;
```

### 구분선
*** 을 쓰거나 --- 을 입력하면 된다.

### 글씨 효과
- *기울임*
- **굵게**
- ***기울이면서 굵게***

### 링크
- [네이버](https://naver.com)
- [문서 내 링크](#제목-태그)

### 이미지
![에스파 윈터](image.png)