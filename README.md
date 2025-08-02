# 🧠 Top 40 Problem-Solving Interview Questions by Pattern

A curated list of 40 must-practice coding problems commonly asked in top tech interviews, organized by problem-solving **patterns**.

---

## ✅ Patterns Covered

1. Sliding Window
1. Two Pointers
1. Fast & Slow Pointers
1. Stack
1. Binary Search
1. DFS/BFS
1. Topological Sort
1. Heap / Priority Queue
1. Backtracking
1. Dynamic Programming
1. Tree DFS/BFS
1. Prefix Sum / Tricks
1. Sorting & Greedy
1. Design
1. Trie, Union-Find, Matrix Traversal

---

## 📋 Problem List

### 🔄 Sliding Window

1. [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/)  
   `DS:` String, HashSet | `Time:` O(n)  
   `Note:` Use HashMap/Set to track characters

2. [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/)  
   `DS:` String, HashMap | `Time:` O(n)  
   `Note:` Two hash maps – one for required, one for window

3. [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/)  
   `DS:` Deque | `Time:` O(n)  
   `Note:` Maintain decreasing deque

---

### ↔️ Two Pointers

4. [Container With Most Water](https://leetcode.com/problems/container-with-most-water/)  
   `DS:` Array | `Time:` O(n)  
   `Note:` Shrink window from sides, track max area

5. [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/)  
   `DS:` Array | `Time:` O(n)  
   `Note:` Use leftMax and rightMax pointers

---

### 🧮 Hashing / Prefix Suffix

6. [Two Sum](https://leetcode.com/problems/two-sum/)  
   `DS:` Array, HashMap | `Time:` O(n)  
   `Note:` Complement pattern

7. [Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/)  
   `DS:` Array | `Time:` O(n)  
   `Note:` Avoid using division

---

### 🌀 Fast & Slow Pointers

8. [Detect Cycle in Linked List](https://leetcode.com/problems/linked-list-cycle/)  
   `DS:` Linked List | `Time:` O(n)  
   `Note:` Floyd’s Cycle Detection

9. [Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/)  
   `DS:` Linked List | `Time:` O(n)  
   `Note:` Reverse second half

---

### 🧱 Stack

10. [Valid Parentheses](https://leetcode.com/problems/valid-parentheses/)  
    `DS:` String, Stack | `Time:` O(n)  
    `Note:` Match opening and closing

11. [Min Stack](https://leetcode.com/problems/min-stack/)  
    `DS:` Stack | `Time:` O(1) per operation  
    `Note:` Track min with auxiliary stack

---

### 🔍 Binary Search

12. [Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/)  
    `DS:` Array | `Time:` O(log n)  
    `Note:` Handle pivot logic

13. [Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/)  
    `DS:` Array | `Time:` O(log n)  
    `Note:` Binary search on rotated array

14. [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/)  
    `DS:` Array | `Time:` O(log(min(n,m)))  
    `Note:` Partition logic in binary search

---

### 🌐 DFS / BFS

15. [Number of Islands](https://leetcode.com/problems/number-of-islands/)  
    `DS:` Grid | `Time:` O(m\*n)  
    `Note:` Mark visited on grid

16. [Clone Graph](https://leetcode.com/problems/clone-graph/)  
    `DS:` Graph, HashMap | `Time:` O(V+E)  
    `Note:` Use visited map

17. [Word Ladder](https://leetcode.com/problems/word-ladder/)  
    `DS:` Graph | `Time:` O(N \* L^2)  
    `Note:` Transform word by word

18. [Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/)  
    `DS:` Tree, Queue | `Time:` O(n)  
    `Note:` Queue for level tracking

---

### ⛓ Topological Sort

19. [Course Schedule](https://leetcode.com/problems/course-schedule/)  
    `DS:` Graph | `Time:` O(V + E)  
    `Note:` Kahn’s algorithm or DFS cycle detection

---

### 🔢 Heap / Priority Queue

20. [Kth Largest Element in Array](https://leetcode.com/problems/kth-largest-element-in-an-array/)  
    `DS:` Heap | `Time:` O(n log k)  
    `Note:` Min Heap of size k

21. [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/)  
    `DS:` Heap, HashMap | `Time:` O(n log k)  
    `Note:` Frequency map + Heap

22. [Merge K Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/)  
    `DS:` Linked List, Heap | `Time:` O(N log k)  
    `Note:` Min Heap of list nodes

---

### 🔁 Backtracking

23. [Subsets](https://leetcode.com/problems/subsets/)  
    `DS:` Array | `Time:` O(2^n)  
    `Note:` DFS include/exclude

24. [Permutations](https://leetcode.com/problems/permutations/)  
    `DS:` Array | `Time:` O(n!)  
    `Note:` Track used elements

25. [Combination Sum](https://leetcode.com/problems/combination-sum/)  
    `DS:` Array | `Time:` O(2^n)  
    `Note:` Include current or skip

---

### 📐 Dynamic Programming

26. [Maximum Subarray](https://leetcode.com/problems/maximum-subarray/)  
    `DS:` Array | `Time:` O(n)  
    `Note:` Kadane’s Algorithm

27. [Coin Change](https://leetcode.com/problems/coin-change/)  
    `DS:` Array | `Time:` O(amount \* coins)  
    `Note:` Bottom-up DP

28. [Decode Ways](https://leetcode.com/problems/decode-ways/)  
    `DS:` String | `Time:` O(n)  
    `Note:` dp[i] = dp[i-1] + dp[i-2]

---

### 🌳 Trees (DFS / Recursion / Serialization)

29. [Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/)  
    `DS:` Tree | `Time:` O(n)

30. [Lowest Common Ancestor](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/)  
    `DS:` Tree | `Time:` O(n)

31. [Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/)  
    `DS:` Tree | `Time:` O(n)

32. [Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/)  
    `DS:` Tree | `Time:` O(n)

---

### 🧮 Others

33. [Merge Intervals](https://leetcode.com/problems/merge-intervals/)  
    `Pattern:` Sorting | `Time:` O(n log n)

34. [Add Two Numbers](https://leetcode.com/problems/add-two-numbers/)  
    `Pattern:` Linked List | `Time:` O(max(m,n))

35. [LRU Cache](https://leetcode.com/problems/lru-cache/)  
    `Pattern:` Design | `Time:` O(1)  
    `Note:` Use HashMap + Doubly Linked List

36. [Jump Game](https://leetcode.com/problems/jump-game/)  
    `Pattern:` Greedy | `Time:` O(n)

37. [Redundant Connection](https://leetcode.com/problems/redundant-connection/)  
    `Pattern:` Union-Find | `Time:` O(n)

38. [Implement Trie (Prefix Tree)](https://leetcode.com/problems/implement-trie-prefix-tree/)  
    `Pattern:` Trie | `Time:` O(n)

39. [Daily Temperatures](https://leetcode.com/problems/daily-temperatures/)  
    `Pattern:` Monotonic Stack | `Time:` O(n)

40. [Spiral Matrix](https://leetcode.com/problems/spiral-matrix/)  
    `Pattern:` Matrix Traversal | `Time:` O(m\*n)
