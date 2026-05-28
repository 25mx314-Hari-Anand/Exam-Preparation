# CO - 1 Trees
## 1. AVL Tree
An AVL tree is a self-balancing binary search tree where the height difference (balance factor) between the left and right subtrees of any node is at most 1
- Types of Rotation
  - LL Rotation
  - RR Rotation
  - LR Rotation
  - RL Rotation
- **Height:** log N

**Special Case: If Right <=0 LL Rotation else RL Rotation**

## 2. B Tree
A B-tree is a self-balancing tree data structure that allows for sorted data and efficient searching, insertion, and deletion operations
- Leaf Node:
  1. Borrow from Left Sibiling
  2. Borrow from Right Sibiling
  3. Merge with Head Node
- Internal Node
  1. Largest Element in Left
  2. Smallest Element in Right
  3. Merge
- Max Children : M
- Min Children : ⌈M/2⌉
- Height: h=O(log<sub>m​</sub>n)
### Special Case in B tree

<img width="1089" height="450" alt="image" src="https://github.com/user-attachments/assets/2de6ac57-71c9-44ac-8184-20d6af90ab07" />

## 3. B+ Tree
A B+ tree is an advanced, self-balancing search tree data structure primarily used in database systems (like MySQL) and file systems
- Same rules as B Tree but delete the element in the leap first
## 4. Trie
Trie is a tree-based data structure used to store and retrieve a dynamic set of strings

## 5. Algorithmic Complexity and Asymptotic Notation

---
# CO - 2 Divide & Conquer
## 1. Binary Search
| Algorithm          | Recurrence Relation | Time Complexity |
| ------------------ | ------------------- | --------------- |
| Binary Search      | (T(n)=T(n/2)+c)     | (O(\log n))     |


## 2. Maximum and Minimum
- Node Representation

| Start | End | Max | Min |
|-------|-----|-----|-----|

## 3. Merge Sort

Tabulation (Partition):
| Start | End |
|-------|-----|

Tabulation (Merge):
| Start | Mid | End |
|-------|-----|-----|

| Algorithm          | Recurrence Relation | Time Complexity |
| ------------------ | ------------------- | --------------- |
| Merge Sort         | (T(n)=2T(n/2)+cn)   | (O(n\log n))    |

## 4. Quick Sort

| Algorithm          | Recurrence Relation | Time Complexity |
| ------------------ | ------------------- | --------------- |
| Quick Sort (Best)  | (T(n)=2T(n/2)+cn)   | (O(n\log n))    |
| Quick Sort (Worst) | (T(n)=T(n-1)+cn)    | (O(n^2))        |

## 5. Knapsack Problem
1. Greedy About Profit (Select Max Profit)
2. Greedy about Weight (Select Min Weight)
3. Greedy about Object (Select 1/2 + 1/3 .. + 1/n)
4. Greedy about both Profit and Weight - Max(P/W)

## 6. Minimum Cost Spanning Tree

## 7. Prim's


## 8. Single Source Shortest Path
- Tabulation

| Select Vertex | 1 | 2 | 3 | 4 | 5 |
|---------------|---|---|---|---|---|
|      1        | 0 | @ | @ | @ | @ |

## 9. Optimal Storage Tapes

- Rules
  - Sort the values and place all the values in the vertical order
  - **Eg:** 1 2 3 = 1 + (1+2) + (1+2+3) = Total Retrival Time / N = MRT

## 10. Optimal Merge Pattern: Huffman Coding
- Left branch should be smaller and right should be greater
- **Left** - 0 **Right** - 1

---

# CO - 3 Dynamic Programming
## Principle of Optimality
An optimal solution to a problem contains optimal solutions to its subproblems

## 1. All Pairs shortest path
- If there is 4 Nodes find A1, A2, A3 and A4
1. Formula
<img width="441" height="48" alt="image" src="https://github.com/user-attachments/assets/ca9bb0cd-bc30-4a14-9374-a2e6a92728c4" />

2. Algorithm
<img width="572" height="288" alt="image" src="https://github.com/user-attachments/assets/35abca75-afae-490f-bc1a-519d301b84da" />

## 2. 0/1 Knapsack

## 3. Travelling Salesmsn
- To Find
- S = 0
  - G(2, %) = C21
  - G(3, %) = C31
  - G(4, %) = C41
- S = 1
  - G(2, {3}) = C23 + G(3, %)
  - G(2, {4}) = C24 + G(4, %)
  - G(3, {2}) = C32 + G(2, %)
  - G(3, {4}) = C34 + G(4, %)
  - G(4, {2}) = C42 + G(2, %)
  - G(4, {3}) = C43 + G(3, %)
- S = 2
  - G(2, {3,4}) = MIN{ C23 + G(3, {4}) , C24 + G(4, {3})}
  - G(3, {2,4}) = MIN{ C32 + G(2, {4}) , C34 + G(4, {2})}
  - G(4, {2,3}) = MIN{ C42 + G(2, {3}) , C43 + G(3, {2})}
- S = 3
  - G(1, {2,3,4}) = MIN{ C12 + G(2, {3,4}) , C13 + G(3, {2,4}) , C14 + G(4, {2,3})}
 
## 4. Multi Stage Decision Graph
- Tabulation

| Vertex      |
|-------------|
| Cost        |
| Destination |

- Algorithm
<img width="538" height="360" alt="image" src="https://github.com/user-attachments/assets/6a7fe2ad-f3d7-4b6a-85b0-21152e01725b" />


## 5.Single Source shortest path
- N Nodes means N-1 Iterations
  - 1st Iteration should always infinity  
1. Algorithm
<img width="522" height="291" alt="image" src="https://github.com/user-attachments/assets/b3d30378-7193-4a25-b6e8-058a6154c73e" />

## 6. String Editing

## 7. Flow Shop Scheduling

## 8. Longest Subsequence

---

# CO - 4 Backtracking
## 1. N-Queens Problem
- Total 65
- 24 Nodes at the End
- Solution 1:

|    | Q1 |    |    |
|----|----|----|----|
|    |    |    | Q2 |
| Q3 |    |    |    |
|    |    | Q4 |    |

- Solution 2:
  
|    |    | Q1 |    |
|----|----|----|----|
| Q2 |    |    |    |
|    |    |    | Q3 |
|    | Q4 |    |    |

## 2. Least Cost Branch and Bound
- Rules:
  - If C is greater than Upper means Kill the Node
  - If U is smaller than Upper means update the new Upper
  - U without Fraction
  - C with Fraction

## 3. Sum of Subsets

| Sum | Index | Total |
|-----|-------|-------|
- **Left:** S + W[K] == M -> Solution
- **Left:** S + W[K] + W[K + 1] <= M -> Increase Left Else Kill
- **Right:** S + W[K+1] <= M -> Increase Right Else Kill
