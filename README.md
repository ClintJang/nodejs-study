# Node.js Study
>hyperledger 분석(공부)을 하다보니, <br />
golang과 node.js에 대해 궁금해졌습니다.  <br />
그 중에서 node.js를 공부시작하면서 공부한 내용을 공유하며 소스 및 내용을 정리할 목적으로 작성합니다. <br />
<br />
개발은 즐겁게~ 😀

# 자바스크립트 (JavaScript)
- 1994년 넷스케이프사, 브랜드 아이히(Brandan Eich)가 만듬.
- 명칭 : 모카(Mocha) -> 라이브스크립트(LiveScript) -> 자바스크립트
- 자바스크립트로 인하여 인터넷 속도 개선, 이용성 향상등으로 활용도 높아짐.
- 이후 웹 브라우저에서만이 아닌 다양한 형태의 자바스크립트를 활용한 자바스크립트의 등장
  - Node.js : 서버 사이드 네트워크 프로그래밍
  - [Angular.js](https://ko.wikipedia.org/wiki/AngularJS) : 오픈 소스 프론트엔드 웹 애플리케이션 프레임워크
  - TypeScript : 공식적으로 Microsoft 의 지원, 정적 타입의 자바스크립트

# Node.js (https://nodejs.org/ko/)
## [Node.js 란?](https://ko.wikipedia.org/wiki/Node.js)
> 확장성 있는 네트워크 애플리케이션(특히 서버 사이드) 개발에 사용되는 소프트웨어 플랫폼
- 서버 환경에서 자바스크립트를 사용해서 개발하려고 노력한 결과물
- CommonJS 표준
- V8 자바스크립트 엔진 기반
- **이벤트 기반의 비동기 방식**
- ~~스레드 기반의 동기 방식~~
  - 실제 플랫폼은 내부에서 여러 개의 스레드가 스레드 풀로 동작함, 애플리케이션 개발자가 처리 로직을 비동기로 처리해야 Node.js는 더 좋은 결과를 얻을 수 있습니다.
- 대규모 네트워크 어플리케이션 개발에 적합

## 장점
- 자바스크립트를 사용함으로써 많은 개발자에게 접근성이 용이
  - 프론트, 백엔드도 모두 알 수 있는 언어 (커뮤니케이션 비용 감소)
- 성능과 안정성 검증
  - ebay(이베이), PayPal(페이팔), Netflix(넷플릭스), LinkedIn(링크드인), Groupon(그루폰), Yammer(야머), Slack(슬랙)
  - GitHub:Atom 에디터 어플리케이션, Visual Studio Code 어플리케이션, Slack 데스트톱 어플리케이션, 워드프레스 데스크톱 어플리케이션
- 많은 개발자가 알아가고 있음
  - Node.js의 패키지 시스템인 npm의 사용자 증가 추세
  - https://insights.stackoverflow.com/survey/2018/ : 스택오버플러우 설문을 봐도 얼마나 사랑받는 지 알 수 있습니다.
  - 개발자가 많다는 것은 그만큼 검색하면 자료도 많고, 라이브러리도 많다는 것임.
- 손쉬운 비동기 프로그래밍
- 스레드 사용의 문제점이 없죠.
  - 동기화, 교착 상태(deadlock)

## 단점
- 실제 성능은 C, C++이 더 뛰어남
- 타입이 없는 JavaScript 언어의 특성
  - side effect가 날 확률이 높음, 안정성이 떨어짐.
  - 복잡한 소프트웨어에는 적합하지 않을 수 있음.
  
## Hello World
### 1. REPL (Read Eval Print Loop) 
> 실제 한줄 씩 코드를 입력해 볼 수 있는 공간을 이용해서 Hello world를 찍어보려고 합니다. 
- 콘솔에서 node를 실행시켜 REPL 화면이 나타나게 합니다.
```
$ node
> 
```
- 그리고 console.log('HelloWorld~:)'); 코드를 쳐서 HelloWorld를 찍어봅니다. 
```
>console.log('HelloWorld~:)');
HelloWorld~:)
undefined
> 
```
- 참고로 종료는 ..
```
> .exit

or

control + c
```

### 2. 초간단 HTTP 서버
> 내일? ㅋ

# 상세 만들어보기
- 정리.. 정리..
