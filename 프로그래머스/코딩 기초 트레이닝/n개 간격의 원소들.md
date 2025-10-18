## n개 간격의 원소들

### 문제 설명 
<p>
  정수 리스트 num_list와 정수 n이 주어질 때, num_list의 첫 번째 원소부터 마지막 원소까지 n개 간격으로 저장되어있는 원소들을 차례로 담은 리스트를 return하도록 solution 함수를 완성해주세요.
</p>

### 제한사항 
+ 5 ≤ num_list의 길이 ≤ 20
+ 1 ≤ num_list의 원소 ≤ 9
+ 1 ≤ n ≤ 4


```
function solution(num_list, n) {
    var answer = [];

    for (let i = 0; i < num_list.length; i+=n) {
        answer.push(num_list[i]);
       
    }
    
    return answer;
}
```

+ num_list, n 매개변수를 받음.
+ for문 사용하여, i+=n 증감 
+ push() 통해서 answer 배열 변수에 담기 
