## 문자열의 앞의 n글자

### 문제 설명
문자열 my_string과 정수 n이 매개변수로 주어질 때, my_string의 앞의 n글자로 이루어진 문자열을 return 하는 solution 함수를 작성해 주세요.

### 제한사항
+ my_string은 숫자와 알파벳으로 이루어져 있습니다.
+ 1 ≤ my_string의 길이 ≤ 1,000
+ 1 ≤ n ≤ my_string의 길이

```
function solution(my_string, n) {
    return my_string.substring(0,n);
}
```
+ my_string, n 매개변수 값 받음.
+ substring() 메서드 이용하여 0부터 n번째까지 문자열을 잘라서 return 반환
