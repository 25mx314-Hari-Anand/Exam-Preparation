# CO - 4 Backtracking
## 1. N-Queens Problem
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
