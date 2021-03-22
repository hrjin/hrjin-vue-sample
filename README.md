# hrjin-vue-sample

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

---

### 1. vue-cli로 Vue 프로젝트 생성하는 법
```
1) npm install -g @vue/cli
2) vue create hrjin-vue-sample
3) npm run serve
3) http://localhost:8080
```

### 2. Vue 프로젝트 디렉토리 구조
```
- src/ : 실제 대부분의 코딩이 이루어지는 디렉토리입니다.
  - assets/ : 이미지 등.. 어플리케이션에서 사용되는 파일들이 모여 있는 디렉토리입니다.
  - components/ : Vue 컴포넌트들이 모여 있는 디렉토리입니다.
  - router/ : vue-router 설정을 하는 디렉토리입니다.
  - App.vue : 가장 최상위 컴포넌트입니다.
  - main.js : 가장 먼저 실행되는 javascript 파일입니다. Vue 인스턴스를 생성하는 역활을 합니다.
- index.html : 어플리케이션의 뼈대가 되는 html 파일입니다.(<div id="app"></div>에 마운팅 되는 이유는 main.js를 살펴보면 알 수 있습니다.)

> 출처 : https://beomy.tistory.com/40
```

### 3-1. Exercise - 초기 Layout 설정
1. 인스턴스 생성(Footer.vue, Header.vue, HelloWorld.vue...)
2. 생성한 인스턴스들로 컴포넌트 구성
3. 순서 : main.js -> App.vue -> index.html
