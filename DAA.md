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

Recursive Method

<img width="979" height="736" alt="image" src="https://github.com/user-attachments/assets/f7706743-bc39-43c3-9d1b-7b0504ca786d" />

Iterative Method

<img width="1071" height="639" alt="image" src="https://github.com/user-attachments/assets/cda199f1-5ce0-4123-9e7b-069482075c01" />


## 2. Maximum and Minimum
- Node Representation

| Start | End | Max | Min |
|-------|-----|-----|-----|

<img width="1026" height="1097" alt="image" src="https://github.com/user-attachments/assets/3bbdc141-6380-446b-9a59-fdda63aa8fad" />


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

Merge Sort:

<img width="1073" height="635" alt="image" src="https://github.com/user-attachments/assets/0daf8f4d-f819-441b-8200-2e61e2e10304" />

Merge:

<img width="1106" height="1163" alt="image" src="https://github.com/user-attachments/assets/f6b8f187-257a-4653-bf17-bcef911087af" />


## 4. Quick Sort

| Algorithm          | Recurrence Relation | Time Complexity |
| ------------------ | ------------------- | --------------- |
| Quick Sort (Best)  | (T(n)=2T(n/2)+cn)   | (O(n\log n))    |
| Quick Sort (Worst) | (T(n)=T(n-1)+cn)    | (O(n^2))        |

- Partition
<img width="954" height="1141" alt="image" src="https://github.com/user-attachments/assets/c6c3fcd0-5151-4751-9ce5-a74a1218915b" />

- Sort
<img width="1054" height="615" alt="image" src="https://github.com/user-attachments/assets/bbcb8ce8-98bc-4feb-931e-8eea00978946" />


## 5. Knapsack Problem
1. Greedy About Profit (Select Max Profit)
2. Greedy about Weight (Select Min Weight)
3. Greedy about Object (Select 1/2 + 1/3 .. + 1/n)
4. Greedy about both Profit and Weight - Max(P/W)

## 6. Minimum Cost Spanning Tree

## 7. Prim's
<img width="1142" height="1044" alt="image" src="https://github.com/user-attachments/assets/4b6757c4-48e4-43b1-a0eb-83627c725027" />


## 8. Single Source Shortest Path
- Tabulation

| Select Vertex | 1 | 2 | 3 | 4 | 5 |
|---------------|---|---|---|---|---|
|      1        | 0 | @ | @ | @ | @ |

<img width="1014" height="859" alt="image" src="https://github.com/user-attachments/assets/f8cf8c54-8127-46e9-9e8c-3a3f7f5c535a" />


## 9. Optimal Storage Tapes

- Rules
  - Sort the values and place all the values in the vertical order
  - **Eg:** 1 2 3 = 1 + (1+2) + (1+2+3) = Total Retrival Time / N = MRT
 
<img width="1099" height="441" alt="image" src="https://github.com/user-attachments/assets/1292c315-38b4-4019-ac92-2e351b3a4683" />


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
<img width="1128" height="643" alt="image" src="https://github.com/user-attachments/assets/8331da97-5d00-4515-a1b9-76f8c6068d94" />

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
- Not Match
  - Minimum of UP + 1, LEFT + 1, DIAGANOL + 2

| D | UP |
|---|----|
| L |    |

- Match
  - Diaganol 

## 7. Flow Shop Scheduling

## 8. Longest Subsequence
- Not Match
  - Max of UP, LEFT

|   | UP |
|---|----|
| L |    |

- Match
  - Diaganol + 1
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

<img width="1111" height="543" alt="image" src="https://github.com/user-attachments/assets/0c3e92e3-0af0-4d59-a8ec-3d79d550a602" />

<img width="951" height="576" alt="image" src="https://github.com/user-attachments/assets/bd7dd570-c685-44ca-95ee-0303b848bb6d" />


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

<img width="1162" height="748" alt="image" src="https://github.com/user-attachments/assets/f9e0a254-92fb-4e74-98e3-e7325223e325" />



---

# E-Node, Live Node, Dead Node

These terms are commonly used in Branch and Bound and State Space Tree searching.

---

# 1. E-Node (Expansion Node)

An **E-node** (Expansion Node) is the node currently being expanded in the state-space tree.

- Its children are generated.
- The algorithm explores possible solutions from this node.

## Definition

An E-node is the live node selected for expansion.

---

## Example

If a node represents a partial solution and we generate all next possible choices from it, that node becomes the E-node.

---

# 2. Live Node

A **Live Node** is a generated node that has not yet been expanded.

- It is still eligible for exploration.
- It may lead to the final solution.

## Definition

A live node is a generated node whose children have not yet been created.

---

## Characteristics

- Waiting for expansion
- Stored in queue/stack/priority queue
- Promising node

---

# 3. Dead Node

A **Dead Node** is a node that will not be expanded further.

This happens when:

- It cannot produce a better solution
- It violates constraints
- It has already been explored

## Definition

A dead node is a node that is discarded and not considered for further expansion.

---

## Characteristics

- Non-promising
- Pruned from search space
- No children generated

---

# Simple State Flow

Live Node → E-Node → Dead Node

### Explanation

1. Node is first generated → Live Node
2. Selected for expansion → E-node
3. Fully explored/discarded → Dead Node

---

# Example in Branch and Bound

Consider solving a knapsack problem:

- Generated states → Live nodes
- Current node being processed → E-node
- Nodes exceeding weight limit → Dead nodes

---

# Comparison Table

| Term | Meaning |
|---|---|
| E-node | Node currently expanded |
| Live Node | Generated but not expanded |
| Dead Node | Discarded node not expanded further |


# Subset Paradigm and Ordered Paradigm in Greedy Method

In Greedy Algorithms, problems are solved using different strategies called paradigms.

Two important paradigms are:

1. Subset Paradigm
2. Ordered Paradigm

---

# 1. Subset Paradigm

The **Subset Paradigm** constructs a solution by selecting a subset of items from a given set.

At each step:

- Choose the best available item using a greedy choice.
- Add it to the solution if it satisfies the constraints.

The final solution is a subset of all available elements.

---

## Working

Given a set:

S = {x1, x2, x3, ..., xn}

The algorithm repeatedly:

1. Selects the best candidate.
2. Checks feasibility.
3. Adds it to the solution subset.

---

## Examples

- Minimum Spanning Tree
- Knapsack Problem
- Job Sequencing Problem

---

## Example (Knapsack Problem)

Items are selected based on maximum profit/weight ratio.

Selected items form a subset of all items.

---

# 2. Ordered Paradigm

The **Ordered Paradigm** constructs the solution step-by-step in a specific order.

Instead of selecting arbitrary subsets:

- Elements are processed in sorted or sequential order.
- Decisions depend on the order.

---

## Working

1. Arrange elements according to some criterion:
   - Smallest first
   - Largest first
   - Earliest deadline
   - Shortest duration

2. Process them one by one greedily.

---

## Examples

- Huffman Coding
- Activity Selection Problem
- Dijkstra’s Algorithm

---

## Example (Activity Selection Problem)

Activities are sorted by finishing time.

Then activities are selected in that order.

---

# Difference Between Subset and Ordered Paradigm

| Feature | Subset Paradigm | Ordered Paradigm |
|---|---|---|
| Main Idea | Select best subset | Process elements in order |
| Selection | Based on feasibility | Based on arranged order |
| Output | Subset of elements | Ordered sequence |
| Examples | Knapsack, MST | Activity Selection, Huffman |

---

# Short Definitions

## Subset Paradigm

Constructs the solution by selecting a feasible subset of elements using greedy choices.

## Ordered Paradigm

Constructs the solution by processing elements in a specific greedy order.


# Implicit Constraint and Explicit Constraint

These terms are commonly used in Backtracking, Branch and Bound, and Constraint Satisfaction Problems.

---

# 1. Explicit Constraint

An **Explicit Constraint** directly defines all possible values that a solution component can take.

It specifies the allowable set of values for variables.

---

## Definition

An explicit constraint restricts each variable to take values from a predefined set or domain.

---

## Example

If a variable x can take values only from:

x ∈ {1, 2, 3, 4}

then this is an explicit constraint.

---

## Characteristics

- Directly stated
- Defines the solution space
- Easy to check

---

## Example Problems

- N-Queens
- Graph Coloring
- Sudoku

---

# 2. Implicit Constraint

An **Implicit Constraint** restricts which combinations of values are allowed.

It defines relationships between variables.

---

## Definition

An implicit constraint limits feasible solutions by specifying conditions among variables.

---

## Example

In the 4-Queens problem:

No two queens can attack each other.

This is an implicit constraint because it restricts combinations of queen positions.

---

## Characteristics

- Not directly listed
- Applied during solution construction
- Removes invalid solutions

---

# Example in N-Queens Problem

## Explicit Constraints

Each queen must be placed:

- In a valid row
- In a valid column

Example:

Qi ∈ {1,2,3,4}

---

## Implicit Constraints

- No two queens in same row
- No two queens in same column
- No two queens on same diagonal

---

# Difference Between Explicit and Implicit Constraints

| Feature | Explicit Constraint | Implicit Constraint |
|---|---|---|
| Meaning | Defines possible values | Defines relationships between values |
| Purpose | Limits domain | Limits valid combinations |
| Applied On | Individual variables | Combination of variables |
| Example | x ∈ {1,2,3} | x ≠ y |

---

# Short Definitions

## Explicit Constraint

A constraint that directly specifies the possible values of variables.

## Implicit Constraint

A constraint that restricts valid combinations of variable assignments.
