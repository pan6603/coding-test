## A 강조하기

### 문제 설명
문자열 myString이 주어집니다. <br>
myString에서 알파벳 "a"가 등장하면 전부 "A"로 변환하고, "A"가 아닌 모든 대문자 알파벳은 소문자 알파벳으로 변환하여 return 하는 solution 함수를 완성하세요.

### 제한사항
+ 1 ≤ myString의 길이 ≤ 20
+ myString은 알파벳으로 이루어진 문자열입니다.

```
function solution(myString) {
    var answer = myString.toLowerCase();
    var result = answer.replaceAll("a", "A");
    
    return result;
}
```
+ myString 매개변수 값을 받음.
+ myString 매개변수 값을 toLowerCase() 메소드 통해서 소문자로 변경하기
+ replaceAll() 메소드 통해서 소문자 a 값을 대문자 A로 변경하기
