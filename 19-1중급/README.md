# 19 Spring 중급

## 목차

### 01. Introduction & Complexity

- Introduction
- 시간 복잡도 분석

    연산 횟수 측정

    Example1: Bubble Sort Vs. Insertion Sort

    Example2: Linear Search Vs. Binary Search

- Big-O notation
- 주로 만나게 되는 시간 복잡도상의 대소관계

### 02. C++ STL & std::sort

- Faster Sorting Method (better than $O(N^2 )$)
- std::sort

    Example1: [BOJ 2751](https://www.acmicpc.net/problem/2751) 수 정렬하기 2

- Sorting with custom comparators

    Example2: [BOJ 11931](https://www.acmicpc.net/problem/11931) 수 정렬하기 4

    Example3: [BOJ 11650](https://www.acmicpc.net/problem/11650) 좌표 정렬하기

- std::string

    Example4: [BOJ 1181](https://www.acmicpc.net/problem/1181) 단어 정렬

- std::vector
- std::binary_search

    Eaxmple5: [BOJ 1920](https://www.acmicpc.net/problem/1920) 수 찾기

### 03. Stack, Queue, Deque

- Stack

    Stack operations

    std::stack

    Example1: [BOJ 9012](https://www.acmicpc.net/problem/9012) 괄호

    Example2: [BOJ 1918](https://www.acmicpc.net/problem/1918) 후위표기식

- Queue

    Queue operations

    std::queue

- Deque

    std::deque

    Example3: [BOJ 2164](https://www.acmicpc.net/problem/2164) 카드2

### 04. Dynamic Programming

- Introduction

    recursive relation & memoization

    Example1: Fibonacci Number

    Example2: Binomial Coefficient

- Time complexity analysis using memoization
- Examples

    Example3: [BOJ 1932](https://www.acmicpc.net/problem/1932) 정수 삼각형

    Example4: [BOJ 11048](https://www.acmicpc.net/problem/11048) 이동하기

### 05. Graph

- Introduction & Definition
- Terminology

    Directed & Undirected

    Adjacent & Incident

    Path

    Cycle

- Representation

    Adjacent Matrix

    Adjacent List

- Graph Search Algorithm

    Depth First Search (DFS)

    Breadth First Search (BFS)

    Time complexity analysis

- Problem set with solutions
    - [1260](https://www.acmicpc.net/problem/1260), [1012](https://www.acmicpc.net/problem/1012), [2583](https://www.acmicpc.net/problem/2583), [11724](https://www.acmicpc.net/problem/11724), [13023](https://www.acmicpc.net/problem/13023), [10271](https://www.acmicpc.net/problem/10271), [2178](https://www.acmicpc.net/problem/2178), [7562](https://www.acmicpc.net/problem/7562), [2644](https://www.acmicpc.net/problem/2644), [2206](https://www.acmicpc.net/problem/2206), [5427](https://www.acmicpc.net/problem/5427), [9019](https://www.acmicpc.net/problem/9019)

### 06. Tree

- Definition
- Representation
- Tree Traversal
- Binary Tree

    Representation

    Example1: [BOJ 1991](https://www.acmicpc.net/problem/1991) 트리 순회

- Priority Queue

    Partially Ordered Tree

    Implementing Balanced POT

    Heap

    Full implementation

    Example2: [BOJ 1715](https://www.acmicpc.net/problem/1715) 카드 정렬하기

### 07. 완전탐색 & 재귀 호출

- Exhausitive Search

    Example1: sum of 1 to N

    Example2: [BOJ 2309](https://www.acmicpc.net/problem/2309) 일곱 난쟁이

- Backtracking with recursion

    Example3: [BOJ 15650](https://www.acmicpc.net/problem/15650) N과 M (2)

    Example4: [BOJ 1182](https://www.acmicpc.net/problem/1182) 부분 수열의 합

### 08. Disjoint Set

- Definition
- DSU operations

    Find

    Union

    Union optimization

- Examples

    Example1: [BOJ 11724](https://www.acmicpc.net/problem/11724) 연결요소의 개수

    Example2: [BOJ 13244](https://www.acmicpc.net/problem/13244) 트리

    Example3: [BOJ 16562](https://www.acmicpc.net/problem/16562) 친구비

    Example4: [BOJ 10775](https://www.acmicpc.net/problem/10775) 공항

### 09. Minimum Spanning tree & Shortest Path

- MST Definition
- Kruskal's Algorithm

    Example1: [BOJ 1922](https://www.acmicpc.net/problem/1922) 네트워크 연결

- Prim's Algorithm
- Dijkstra's (Single Source Shortest Path without negative weight)
