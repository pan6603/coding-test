## ad 제거하기

### 문제 설명
문자열 배열 strArr가 주어집니다. <br>
배열 내의 문자열 중 "ad"라는 부분 문자열을 포함하고 있는 모든 문자열을 제거하고 남은 문자열을 순서를 유지하여 배열로 return 하는 solution 함수를 완성해 주세요.

### 제한사항
+ 1 ≤ strArr의 길이 ≤ 1,000
+ 1 ≤ strArr의 원소의 길이 ≤ 20
+ strArr의 원소는 알파벳 소문자로 이루어진 문자열입니다.

```
function solution(strArr) {
    var answer = strArr.filter(str => !str.includes("ad"));
    return answer;
}
```
+ strArr 매개변수를 받음.
+ filter() 메소드를 사용하여, ad가 포함 된 배열 인덱스를 빼고 전부 answer 변수에 담기.
+ return 으로 반환 
