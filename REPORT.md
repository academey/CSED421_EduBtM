# EduBtM Report

Name: Park hyun joon

Student id: 20150968

# Problem Analysis

### edubtm_BinarySearch
Idx 를 통해서 주어진 key 보다 작거나 같은 값이 있는 index 를 리턴한다.
이 때, 페이지에 슬롯이 없으면 idx 는 -1 을 리턴하도록 만든다.


### edubtm_Compact
슬롯을 들몬셔 데이터 영역에 object 들을 넣어준다. 
만약 slot No 가 파라미터로 오면 예외로 마지막으로 처리한다.

### edubtm_Compare
정렬에 쓰이는 key를 비교해주는 함수이다.

### EduBtm_CreateIndex
처음 트리를 초기화해주기 위한 함수이다.
이 때, init leaf node 를 해준다.

### edubtm_Delete

Binary Search 를 통해서 삭제할 object 를 찾는다.
그리고 해당 idx 를 찾았다면 재귀적으로 제거해 나간다.

### EduBTM_Fetch
root 부터 시작해서 binary search 로 해당 서브 트리를 리커시브하게 찾아서 탐색 조건에 맞는 leaf page 를 찾아낸다.
그리고 comp operator 의 조건에 맞춰서 해당 범위를 서치하면서 결과를 얻어낸다.

# Design For Problem Solving

## High Level

FILL WITH YOUR HIGH LEVEL DESIGN

## Low Level

FILL WITH YOUR LOW LEVEL (CODE LEVEL) DESIGN

# Mapping Between Implementation And the Design

FILL WITH YOUR CODE IMPLEMENTATION DESCRIPTION