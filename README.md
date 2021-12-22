# Sprint-stringify-json

## StringifyJSON

이번 스프린트는 재귀를 이용해 브라우저에서 제공하는 주요 기능 중 하나인 `JSON.stringify` 함수를 직접 구현할 것입니다.

이전 강의에서 `JSON.stringify`는 객체를 JSON으로 변경하는 메소드인 것을 배웠습니다. **이 함수를 직접 구현하기 위해서는 재귀 사용을 권장합니다. 왜냐하면 자바스크립트 객체와 JSON은 대표적인 트리 구조를 가졌고, (객체의 값으로 객체를 포함합니다.) 이는 전형적인 재귀 탐색이 가능한 구조이기 때문입니다.** 어떻게 풀어야 할지 생각이 잘 나지 않는다면, 코플릿 재귀 문제 풀었던 방법을 다시 기억해보면서 부모와 자식의 구조가 같은 트리 구조는 어떤 조건에 재귀 호출을 하는게 좋을지 고민해보세요.

### Getting Started
[repository 주소](https://github.com/codestates/im-sprint-stringify-json) 에서 fork 및 clone 후 Pull Request로 제출하세요

### Bare minimum Requirements
- `src/stringifyJSON.js`에서 `stringifyJSON` 함수를 직접 구현해보고 spec 테스트를 통과시키세요.

### [JSON에 관한 나의 정리](https://velog.io/@gil0127/JSON-%EA%B0%9D%EC%B2%B4%EC%97%90-%EA%B4%80%ED%95%98%EC%97%AC)

----------------
