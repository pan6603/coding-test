## 문자열의 뒤의 n글자

### 문제 설명
문자열 my_string과 정수 n이 매개변수로 주어질 때, my_string의 뒤의 n글자로 이루어진 문자열을 return 하는 solution 함수를 작성해 주세요.

### 제한사항
+ my_string은 숫자와 알파벳으로 이루어져 있습니다.
+ 1 ≤ my_string의 길이 ≤ 1,000
+ 1 ≤ n ≤ my_string의 길이

```
function solution(my_string, n) {
    let answer = my_string.split("").reverse().join(""); 
    let result = answer.substring(0, n);

   return result.split("").reverse().join("");
}
```
+ my_string와 n값을 매개변수 받음.
+ split("") 이용하여 배열 만들기, 그리고 나서 reverse() 메서드 사용하여 문자열 뒤집기
+ substring() 메서드 사용하여 n번째 까지 출력하기
+ result 변수에 담아져 있는 데이터를 reverse() 메서드를 사용하여 다시 뒤집기 

