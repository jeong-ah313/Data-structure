# Data-structure
* 자료구조 공부-python


## [1]python_prac
#### 실습1. python 연습
##### Q1. 구구단의 단을 입력 받아 역순으로 출력한다. 0이 입력되면 프로그램을 종료한다.
##### Q2. 문자열 msg = “Data Structures in Python”을 선언하고, 먼저 이 문자열을 그대로 출력하고, 다음 모두 대문자로 바꿔 출력하고, 다음 모두 소문자로 바꿔 출력하고, 마지막으로 소문자는 대문자로 대문자는 소문자로 바꿔 출력한다.
##### Q3. 어느 식당의 음식에 대한 가격 정보를 다음과 같이 딕셔너리로 표현하자. 
* price = {‘콩나물해장국’:400, ‘갈비탕’:9000, ‘돈가스’:8000} 
##### 여기에 새로운 메뉴 ‘펫타이’를 7000원에 추가하고, 모든 메뉴와 가격을 출력하는 코드를 작성한다. 또한 모든 메뉴의 가격을 500원 내리는 코드를 작성한다.
##### Q4. 리스트 lst = [7, 2, 6, 4, 5]와 같이 리스트를 선언하고 리스트의 모든 값을 더해 결과를 반환하는 함수를 구현한 후 함수 호출하여 결과를 출력한다.
##### Q5. 구구단의 단을 입력 받아 2단부터 입력 받은 단까지 수평으로 출력한다. 0이 입력되면 프로그램을 종료한다.
##### Q6. 숫자 피라미드의 높이를 입력 받아 다음과 같이 출력되도록 한다. 0가 입력되면 프로그램을 종료한다. 교과서에 힌트를 참조한다.

## [2]python_set
#### 실습2. Class 연습
##### Q1. Bag을 클래스 사용하여 구현한다. Bag을 다음과 같이 정의할 때 구현되지 않은 멤버 함수를 구현하여 아래의 Bag을 사용한 코드를 실행할 때 주어진 결과와 같이 되도록 한다.
##### Q2. 리스트에 있는 데이터의 최솟값, 최댓값을 찾는 findMinMax() 함수를 이용하여 파일 “input.txt”에 있는 연, 월, 일로 주어진 날짜를 읽어 출력하고 가장 오래된 날짜와 가장 늦은 날짜를 출력하도록 한다.
##### Q3. 파일 “input2.txt”에는 한 줄에 기준 날짜와 날짜 수가 주어진다. 기준 날짜에서 날짜 수만큼 진행한 후의 날짜를 출력한다. 하루를 증가시키는 멤버 함수 increment()를 구현하여 사용한다. 필요하면 보조 멤버 함수를 추가하여 사용한다.
* [힌트] 멤버 함수 increment()는 날짜를 하나 증가 시키는 함수로서 다음과 같이 생각해볼 수 있다. 현재 날짜가 달의 맨 끝 날이 아니면 하루 증가시킨다. 예를 들면 2021년 9월 5일이면 2021년 9월 6일이 된다. 반면 날짜가 달의 맨 끝 날이면 연/월/일의 일을 1로 하고 달을 검사하여 12월이면 달이 1이 되고 연도는 1년 증가 시킨다. 즉 2020년 12월 31일이면 2021년 1월 1일이 된다. 만일 달을 검사하여 12월이 아니라면 달을 하나 증가시키고 날은 1로 한다. 즉 2020년 9월 30일이면 2020년 10월 1일이 된다. 달의 맨 끝 날을 구하는 lastDayOfTheMonth()는 1, 3, 5, 7, 8, 10, 12월이면 31일 4, 6, 9, 11월이면 30일, 2월은 윤년이면 29일 평년이면 28일이 되니 쉽게 만들 수 있다.
##### Q4. 파일 “input3.txt”에는 한 줄에 기준 날짜와 날짜 수가 주어진다. 첫 번째 주어진 날짜에서 두 번째 날짜까지의 경과한 날짜 수를 셈하여 출력한다. 문제 3에서 사용한 하루를 증가시키는 멤버 함수 increment()를 이용하여 구한다.
##### Q5. 하노이 탑을 구현한다. 원판의 수를 입력 받아 0가 될 때까지 진행하며 원판의 이동과 이동 횟수를 출력한다.


## [3]python_list
#### 실습3. 리스트와 집합
##### Q1. 리스트 구현 
##### 리스트를 클래스 사용하여 구현한다.
* a 22 (add 멤버 함수에 해당) => ‘33’ 데이터를 리스트의 맨 끝에 삽입한다. 
* remove 33 => ‘33’ 데이터를 리스트에서 삭제한다. ‘33’ 데이터가 없으면 없다는 메시지 보낸다. 
* search 33 => ‘33’ 데이터를 리스트에서 탐색한다. ‘33’ 데이터가 없으면 없다는 메시지 보낸다. 
* m 2 3 4 8 1 9 => m은 merge(합병)를 의미하며 m 다음의 임의의 데이터는 리스트로 받아들여 합병한다. 
* dup => 중복된 요소를 제거한다.

##### Q2. 라인 에디터
##### 파일 “input.txt”을 읽어 라인 번호와 함께 화면에 출력한다. 문제 1에서 만든 클래스ArrayList를 사용하며 라인 에디터는 교과서의 것과 대동소이하나 다음과 같은 명령어를 실행하도록 한다.
##### Q3. 집합을 클래스 사용하여 구현한다. 클래스 Set를 다음과 같이 정의할 때 구현되지 않은 멤버 함수를 구현하고 실행한 결과와 같이 되도록 코딩한다. 교과서에 주어진 멤버 함수 외에 다음과 같은 새로운 멤버 함수를 사용하여 실행한다. 
* __eq__(): 두 개의 집합이 같은지 판단, 이것을 구현하면 두 집합 사이에 ‘==’ 연산자 사용하여 같은지 판단할 수 있다.
isSubstring(): 부분 집합 (subset) 여부 판단
isProperSubstring(): 진부분 집합(proper subset) 여부 판단

## [4]python_stack
#### 실습4. Stack
##### Q1. 스택 구현 
##### 스택을 클래스 사용하여 구현한다. 클래스 Stack을 다음과 같이 정의할 때 구현되지 않은 멤버 함수를 구현하고 실행한 결과와 같이 되도록 코딩한다. 명령 프롬프트에서 m을 입력하면 파일 “input.txt”에 있는 문장을 한 라인씩 읽어 괄호 쌍을 검사한다.
##### Q2. 십진수를 이진수로 변환
##### 문제 1에서 만든 클래스 Stack을 사용하여 십진수를 이진수로 변환하는 함수를 만들어 테스트한다. 십진수를 입력하면 이진수로 바꾸어 출력하되 -1을 입력하면 종료한다.
##### 십진수를 이진수로 변환하는 방법은 다음과 같이 스택을 사용하여 변환한다. 예를 들면 십진수 11을 이진수로 나타내면 1011이 된다. 십진수 11을 2로 나눈 나머지 1을 스택에 저장하고 몫 5를 다시 2로 나누어 나머지 1을 스택에 저장하고 또 몫 2를 2로 나누어 나머지 0을 스택에 저장하며, 이 과정을 반복해서 2미만이 된 몫을 스택에 저장한 후 스택에 저장된 숫자를 pop하여 출력하면 원하는 이진수를 얻게 된다.
##### Q3. 미로찾기
##### 주어진 파일(“maze.txt”)에 미로가 그려져 있다. ‘1’은 통과 할 수 없는 블록을 나타내며 ‘0’은 통과 할 수 있는 통로를 나타낸다. ‘E’는 탈출할 수 있는 위치를 나타낸다. 첫 줄은 미로의 행과 열의 수를 나타낸다. 입력 파일 (“input1.txt”)에 처음 시작 위치를 나타내는 행, 열이 주어져 있다. 첫 행과 첫 열은 1로 나타낸다 (교과서는 0로 나타냄). 각 줄의 시작 위치에서 미로를 탈출할 수 있는지 판단한다. 
* [힌트] “maze.txt”에 주어진 미로를 리스트 사용하여 이차원 배열로 나타내어 처리한다. 우선 리스트에 저장된 이차원 배열을 출력해보고 이상이 없으면 다음 단계로 진행한다.

## [5]python_queue, deque
#### 실습5. Queue and Deque
##### Q1. 큐 구현 
##### 큐를 클래스 사용하여 원형 큐로 구현한다. 클래스 큐를 다음과 같이 정의할 때 구현되지 않은 멤버 함수를 구현하고 실행한 결과와 같이 되도록 코딩한다. 큐의 초기 크기는 3으로 하고 (MAX_SIZE = 3) 큐가 가득 차면 큐의 크기를 2배로 늘려 데이터를 수용하도록 한다. 
##### Q2. 데이터 분류
##### 문제 1에서 만든 클래스 큐를 사용하여 입력 파일 “input.txt”에 있는 데이터를 문자열, 정수, 실수로 분류하여 3개의 큐를 만들어 저장한다. 정수와 실수가 저장된 큐는 데이터 합을 구해 출력한다.
##### Q3. 덱 구현
##### 문제 1에서 만든 원형 큐를 상속하여 덱을 구현한다. 클래스 덱을 다음과 같이 정의할 때 구현되지 않은 멤버 함수를 구현하고 실행한 결과와 같이 되도록 코딩 한다. 덱의 초기 크기는 3으로 하고 (MAX_SIZE = 3) 덱이 가득 차면 덱의 크기를 2배로 늘려 데이터를 수용하도록 한다.  
##### Q4. palindrome(회문) 테스트
##### Palindrome(회문)은 앞뒤 어느 쪽을 읽어도 같은 단어, 문장을 의미한다. 예를 들어 “level”, “2002”는 palindrome이다. 파일 “input1.txt”에 있는 문장을 읽어 palindrome인지 아닌지 판단하는 프로그램을 작성한다. Palindrome을 판단하는 방법은 여러가지 있으나 여기서는 한 줄의 각 문자를 덱에 저장한 후, 덱의 양쪽 끝에서 데이터의 중간까지 삭제하여 비교하는 방법을 사용한다. 덱은 문제 3에서 만든 것을 사용한다. 문장 중에 알파벳 문자는 대/소문자 구분하지 않고 검사한다

## [6]python_stack, list
#### 실습6. Unsorted Linked List
##### Q1. 연결 구조로 Stack 구현 
##### 스택을 연결 구조 사용하여 구현한다. 클래스 Stack을 다음과 같이 정의할 때 구현되지 않은 멤버 함수를 구현하고 실행한 결과와 같이 되도록 코딩한다. 
##### Q2. Unsorted Linked List
##### 정렬되지 않은 리스트를 연결 구조 사용하여 구현한다. 클래스 UnsortedLinkedList를 다음과 같이 정의할 때 구현되지 않은 멤버 함수를 구현하고 실행한 결과와 같이 되도록 코딩한다.


## [7]python_Circular-queue
#### 실습7. Deque, Circular Doubly Linked List
##### Q1. 연결 구조로 Deque 구현 
##### 덱을 이중 연결 구조 사용하여 구현한다. 클래스 LinkedDeque을 다음과 같이 정의할 때 구현되지 않은 멤버 함수를 구현하고 실행한 결과와 같이 되도록 코딩한다. 
##### Q2. 원형 이중 연결 리스트 (Circular Doubly Linked List)
##### 원형 이중 연결 리스트를 구현한다. 클래스 CircularDoublyLinkedList를 다음과 같이 정의할 때 구현되지 않은 멤버 함수를 구현하고 실행한 결과와 같이 되도록 코딩한다. 
##### Q3.  요세푸스 문제
##### 문제 2에서 구현한 원형 이중 연결 리스트를 사용하여 요세푸스 문제를 해결한다.

## [8]python_Search-tree
#### 실습8. 정렬, 탐색, 해싱
##### Q1. 정렬
##### 주어진 데이터에 대해서 버블 정렬, 선택 정렬, 삽입 정렬을 사용하여 출력한다. 정렬 방법을 이해하기 위해서 각 패스마다 배열에 저장된 데이터를 출력한다.
* [조건]
* 데이터는 다음을 사용한다. => data = [24, 15, 29, 11, 47, 12]
* 실습 노트에 각 정렬 방법에 대해서 각 패스마다 정렬되는 과정을 연습한다.
* 버블 정렬, 선택 정렬, 삽입 정렬의 3개 정렬 방법의 실행 시간은 O(n2)이 되며 2개의 for 루프 사용하여 구현한다.
* 각 정렬 방법에 대해 같은 배열을 사용하기 위해서 정렬하기 전에 복사해서 사용한다. (copy 사용)
##### Q2. 정렬 시간 측정
##### 난수 발생기를 사용하여 배열에 정수를 저장한다. 배열에 있는 정수를 버블 정렬, 선택 정렬, 삽입 정렬하여 각 정렬 방법마다 시간 측정을 하여 비교한다. 또한 파이썬 리스트에서 제공하는 sort()를 사용하여 비교한다.
##### Q3. 탐색
##### 난수 발생기를 사용하여 배열에 정수를 저장한다. 배열을 deepcopy 하여 파이썬 리스트에서 제공하는 sort()를 사용하여 정렬한 후 임의의 숫자에 대해서 정렬되지 않은 데이터에 대해서는 순차 탐색과 정렬된 데이터에 대해서는 이진 탐색하여 시간 측정을 비교한다. 데이터를 찾으면 해당 인덱스를 출력한다.
 ##### Q4. 4: 해시 테이블을 체이닝 사용하여 구현
 ##### 입력 파일 “student.txt”를 읽어 해시 테이블에 저장한다. “student.txt” 파일은 학생에 대한 정보가 저장되어 있다. 한 라인에 학번, 학생 이름, 성적으로 구성되어 있다. 해시 테이블에 저장할 때 엔트리는 학번을 키로, 학번, 학생 이름, 성적으로 구성된 레코드를 값으로 하여 저장한다. 충돌이 일어나면 체이닝 사용하여 연결한다. Student 클래스 만들어 사용한다. 삽입/탐색/삭제/출력에 대해서 구현한 해시 테이블을 테스트한다. 초기 테이블 크기는 5로 한다.

## [9]python_Tree, priority-queu
#### 실습9. 이진 트리, 우선 순위 큐
##### Q1. 이진 트리
##### 이진 트리의 노드와 트리를 다음과 같이 정의하여 buildTree() 실행하면 다음과 같은 트리를 만들게 된다. 실제로 그렇게 되는지 buildTree()에 있는 코드를 확인한다. 
* (사진 생략했습니다.)
##### Q2. 우선 순위 큐
##### 힙을 사용하여 우선 순위 큐를 구현한다. enqueue(), dequeue()를 실행하고 출력은 문제 1과 같이 시각적으로 힙의 모양을 알 수 있게 출력한다. 

## [10]python_binary search tree
#### 실습10. 이진 탐색 트리
##### Q1. 순환적인 방법으로 이진 탐색 트리 구현
##### 순환적인 방법으로 이진 탐색 트리를 구현하여 삽입/탐색/삭제/출력을 테스트 한다.
##### Q2. 반복적인 방법으로 이진 탐색 트리 구현
##### 반복적인 방법으로 이진 탐색 트리를 구현하여 삽입/탐색/삭제/출력을 테스트 한다.이진 트리
##### Q3. 다음의 멤버 함수 구현
##### 이진 탐색 트리에서 다음의 멤버 함수를 구현한다. 필요 시 보조 함수 사용한다. 이진 탐색 트리는 앞에서 구현한 순환적인 방법, 반복적인 방법 어느 것을 사용해도 무방하다.


## [11]python_sort
#### 실습11. 고급 정렬
##### Q1. 셸 정렬/힙 정렬/병합 정렬/퀵정렬 
##### 난수 발생기를 사용하여 배열에 정수 15개를 저장한다. 배열의 정수를 셸 정렬, 힙 정렬, 병합 정렬, 퀵 정렬하여 출력한다. 
##### Q2. 문제 1의 각 정렬 방법마다 다음의 데이터 개수에 대하여 시간 측정을 하여 비교한다. Python에서 제공하는 sort()함수 사용하여 비교한다. 시간 측정은 실습 8과 같은 방법으로 한다.
* [조건] 데이터 개수: 100000, 500000, 1000000 
