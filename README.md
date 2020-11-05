## 예시

![Example](./docs/example.png)

## 요구사항

- 인증번호 버튼은 제외하고 input만 구현해 주세요.
- 입력된 핸드폰 번호에 자동으로 dash를 붙여주세요.

## TIP

string에서 숫자를 제외한 값은 모두 지우는 정규식

```typescript
const numberString = inputString.replace(/[^0-9]/g, '');
```
