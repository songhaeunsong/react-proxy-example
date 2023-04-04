### 과제1

- webpack dev server의 proxy 기능을 사용해 우회하여 응답을 받아옵니다.

### 과제2

api2 라는 폴더가 존재하고 있습니다. 여러 개의 도메인에서 응답을 받아와야 하는 경우가 종종 있습니다. 이럴 때는 유연하게 proxy를 설정할 필요가 있습니다.

- webpack dev server의 proxy 기능 대신 http-proxy-middleware의 proxy 기능을 사용하여 proxy를 유연히 설정해 2개의 도메인에서 모두 응답을 받아옵니다.
- api2에 관련된 fetch 함수를 만들고, 컴포넌트를 하나 이상 만들어 2개의 도메인에서 모두 응답을 받아오는지 테스트 해봅니다.
