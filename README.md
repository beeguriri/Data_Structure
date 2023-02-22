# Data_Structure
자바 자료구조 수업 (\lec** )
+ Lec01_03
  + 배열정렬, ArrayList, Iterator
  + list 중복 제거, 정렬
  + 인터페이스 Comparable, comparator 구현, binarysearch
+ Lec04 : Stack, Queue
  + Stack : 후입선출
  + Queue : 선입선출
  + Point class를 이용한 `circular queue`
    + push(data) : rear 증가(rear = (rear+1)%capacity) 후, 그 위치에 data push
    + pop() : data pop 후 front 증가(front = (front+1)%capacity)
    + dump() : front -> rear까지 출력 또는 front -> capacity-1까지 출력 후 0 -> rear 까지 출력
+ Lec05 : Recursion
+ Lec05_EightQueen_Problem (without recursion (using stack) / using recursion) 
  + `8-Queen` problem
    + genericStack, Point Class 이용
      + array[0][0]에 퀸 배치 후, 행에 대한 모든 열 검사 후 다음 행으로 넘어감
      + 퀸 배치 가능한 경우 포인트로 해당 위치 받아서 스택에 push
      + 한 행에 퀸 배치 불가능 할 경우 스택에서 해당위치 pop
      + pop된 위치 (이전 행)의 열을 한칸 증가한 후 다시 수행
      + 스택 사이즈가 퀸 배열 사이즈와 같으면 정답 출력
    + EightQueenB : Backtracking 연습 (non-recursion으로 구현)
      + 최초 정답 하나만 출력,. while loop 수정 중
    + `EightQueenB_Allsolution` : Backtracking 연습 (non-recursion으로 구현)
      + 정답갯수 92개 이후 반복찍힘현상, while loop 조건 수정 필요...
    + EightQueenR : recursion으로 구현, 8퀸 정답 92개 출력
      
##
자바 자료구조 예제 (\example)
+ 0128 Chapter2 기본자료구조
+ 0205 Chapter5 재귀알고리즘
+ 0212 Chapter5 재귀알고리즘 `퀸배치`

##
자바 자료구조 연습문제 (\practice)
+ 0128 Chapter2 기본자료구조 연습문제

##
로컬 저장소
+ local path : D:\HJ\java_test\edu\자료구조src
+ local_home : D:\Coding Practice\edu\src_DataStructures
