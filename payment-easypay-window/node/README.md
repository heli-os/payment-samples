# payment-easypay-window/node

Node.js 를 이용한 결제창 샘플입니다. Express로 구성되었습니다.

## 실행 요구조건

- Node.js >= 14.0.0
- npm

## 테스트하기

샘플 소스에서 아래 명령어를 실행하면 서버가 실행됩니다.

```sh
$ npm install
$ node app.js
```

서버가 실행된 후, `http://localhost:8080`로 접속해서 테스트할 수 있습니다.

* 테스트 코드는 기본적으로 삼성페이가 설정되어 있습니다. 다른 간편결제사를 테스트하고 싶다면 `index.ejs` 파일에서 `let easyPay`에 할당된 간편결제사 코드를 수정해주세요.
* 카카오페이는 테스트 환경에서 사용할 수 없습니다.