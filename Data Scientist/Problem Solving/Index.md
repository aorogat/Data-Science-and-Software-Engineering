# Problem Solving (Coding Interview)

---

<details>
<summary><strong>1- Sliding Window Problems</strong></summary>

Sliding window problems involve solving problems by maintaining a "window" of elements within the input (like an array or string) and sliding it over the input to find the solution efficiently.
<p align="center">
  <img src="https://github.com/user-attachments/assets/cef5d7a2-c682-49ee-84b0-4902f45625ba" alt="Sliding Window - Copy" style="width: 60%;">
</p>



### 1.1- Fixed Length Window Problems
Content here.

### 1.2- Minimum Length Window Problems
Content here.

### 1.3- Maximum Length Window Problems
Content here.

</details>


---

<details>
<summary><strong>2- Dynamic Programming Problems</strong></summary>

Dynamic Programming (DP) is a powerful optimization technique used to solve problems by breaking them into smaller overlapping subproblems, storing intermediate results, and reusing them to solve the larger problem efficiently.

### Subcategories of Dynamic Programming Problems:

#### 2.1- Knapsack-Type Problems
Knapsack problems involve selecting items or subsets to optimize a given objective while satisfying certain constraints.

- **2.1.1- 0/1 Knapsack Problems (Subset Selection)**
  In these problems, each item can be included at most once, and the goal is to find a subset of items that satisfies a condition.
  
  Examples:
  - Subset Sum
  - Partition Equal Subset Sum

- **2.1.2- Unbounded Knapsack Problems (0-k Items per Element)**
  Items can be selected multiple times, and the task is to determine the number of times each item is required to satisfy a condition.

  Examples:
  - Coin Change Problem
  - Rod Cutting Problem

#### 2.2- Range-Based Problems
These problems focus on solving tasks based on ranges of elements, often using intervals or windows.

- **2.2.1- Consecutive Ranges**
  Tasks involve checking or optimizing values over consecutive ranges.
  - **Leetcode 139: Word Break Problem** (Medium): Determine if a string can be segmented into valid words from a dictionary.

- **2.2.2- Nested Ranges**
  Problems where ranges overlap or are nested within other ranges.

- **2.2.3- In-Out Ranges**
  These involve solving problems where information flows inward and outward from a range or point.
  - **Leetcode: Longest Palindromic Substring** (Medium): Find the longest palindrome in a given string.

- **2.2.4- Out-In Ranges**
  Problems where information propagates outward first and then inward.
  - **Leetcode: Minimum Number of Operations to Make a Palindrome** (Hard): Compute the minimum changes needed to transform a string into a palindrome.

</details>

---

<details>
<summary><strong>3- Graph Problems (DFS, BFS, Topological Sort-DAG, Union-Find)</strong></summary>

Graph problems involve understanding and solving tasks that can be represented as a network of nodes and edges.

## Algorithms Used in Graph Problems
1. **Depth-First Search (DFS)**: Explores as far as possible along each branch before backtracking. [Explanation Video Link Placeholder]
2. **Breadth-First Search (BFS)**: Explores all neighbors of a node level by level. [Explanation Video Link Placeholder]
3. **Topological Sort (Directed Acyclic Graph - DAG)**: Linear ordering of vertices such that for every directed edge `u -> v`, `u` comes before `v`. [Explanation Video Link Placeholder]
4. **Union-Find (Disjoint Set Union)**: Efficiently tracks connected components and detects cycles in undirected graphs. [Explanation Video Link Placeholder]

### 3.1- Connected Nodes (Pointers) Problems
In these problems, the nodes are connected using explicit pointers. The goal is to explore and clone, connect, or find relationships between the nodes.
- **Leetcode: 133. Clone Graph**: (Medium)

### 3.2- Grid Problems
These problems involve grids, where each cell can be treated as a graph node connected to its neighbors.

#### 3.2.1- Grid Problems (Try All Nodes)
<p align="center">
  <img src="[https://github.com/user-attachments/assets/cef5d7a2-c682-49ee-84b0-4902f45625ba](https://github.com/user-attachments/assets/20d53c0c-1866-4a1b-89dc-a497f2cff402)" style="width: 30%;">
</p>

- **Leetcode: 79. Word Search**: (Medium)
- **Leetcode: 200. Number of Islands**:  (Medium)

#### 3.2.2- Grid Problems (Simultaneous Start)
- **Leetcode: 286. Walls and Gates**: (Medium)
- **Leetcode: 994. Rotting Oranges**:  (Medium)

#### 3.3- Word Problems (Need to Construct Graph from the Problem Statement)
These problems require constructing a graph from the given data before applying algorithms.

##### Word Problems - BFS
- **Leetcode: 127. Word Ladder**: (Hard)
- 
##### Word Problems - Topological Sort (DAG)
These problems typically involve tasks that depend on one another, making topological sorting essential.
- **Leetcode: 207. Course Schedule**: (Medium)  
- **Leetcode: 269. Alien Dictionary**: (Hard)

</details>



---


<details>
<summary><strong>4- Data Structure Building Problems</strong></summary>

This category of problems requires designing and implementing new data structures to meet specific requirements. These problems often involve combining or modifying basic data structures such as arrays, hash maps, linked lists, heaps, or queues to achieve the desired functionality.

### Characteristics of Data Structure Building Problems:
- Require a clear understanding of the underlying data structures.
- Focus on combining multiple data structures to optimize performance (e.g., O(1) operations for specific tasks).
- Test problem-solving and design skills to handle edge cases and constraints effectively.

### Example Problems:
- **Leetcode 146: LRU Cache** (Medium):  
</details>

