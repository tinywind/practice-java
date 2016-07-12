#1. 두 정수 더하기(A+B)
* 입력값 A와 B의 합을 구하는 함수를 기술하시오.
* 함수의 원형은 다음과 같다.
```
 int sum(int A, int B)
```
* A와 B의 범위는 Integer.MIN_VALUE 에서 Integer.MAX_VALUE 이다.
* 결과값은 A와 B의 합이다.
* 만약 결과값이 Integer 의 표현 범위를 벗어나면, -1을 돌려준다.
* tag: `자료형` `형변환` `조건문`
   
#2. 마름표 표현
* 다음을 출력하는 함수를 기술하시오. (A가 5일때의 결과값이다.)


 ![capture](https://raw.githubusercontent.com/tinywind/practice-programming/master/grammar/practice-2.PNG "comment")
* 함수의 원형은 다음과 같다.
```
 void print(int A)
```
* A의 범위는 0에서 100 이다.
* tag: `반복문`

#3. 1사이의 가장 큰 격차
* 입력값 A[]에서 1사이의 0의 갯수가 가장 큰 경우, 0의 갯수는 몇 개인지 구하는 함수를 기술하시오.
* 함수의 원형은 다음과 같다.
```
 [JAVA] int maxGap(int A[])
 [C] unsigned int max_gap(int A[], unsigned int N) 
```
* 배열 A의 각 요소(element)는 0또는 1이다. N은 배열 A의 크기를 나타낸다.
* 배열 A의 길이는 2에서 100 이다.
* tag: `배열`