# Problem Solving (Coding Interview)

---

<details>
<summary><strong>1- Sliding Window Problems</strong></summary>

Sliding window problems involve solving problems by maintaining a "window" of elements within the input (like an array or string) and sliding it over the input to find the solution efficiently.

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

Dynamic Programming (DP) is an optimization technique used to solve problems by breaking them into smaller overlapping subproblems and solving each subproblem only once, storing its results.

Content here.

</details>

---

<details>
<summary><strong>3- Graph Problems (DFS, BFS, Topological Sort-DAG, Union-Find)</strong></summary>

Graph problems involve understanding and solving tasks that can be represented as a network of nodes and edges.

## Algorithms Used in Graph Problems
1. **Depth-First Search (DFS)**: Explores as far as possible along each branch before backtracking.
   - [Explanation Video Link Placeholder]
2. **Breadth-First Search (BFS)**: Explores all neighbors of a node level by level.
   - [Explanation Video Link Placeholder]
3. **Topological Sort (Directed Acyclic Graph - DAG)**: Linear ordering of vertices such that for every directed edge `u -> v`, `u` comes before `v`.
   - [Explanation Video Link Placeholder]
4. **Union-Find (Disjoint Set Union)**: Efficiently tracks connected components and detects cycles in undirected graphs.
   - [Explanation Video Link Placeholder]

### 3.1- Connected Nodes (Pointers) Problems
In these problems, the nodes are connected using explicit pointers. The goal is to explore and clone, connect, or find relationships between the nodes.
- **Leetcode: 133. Clone Graph**: (Medium)

### 3.2- Grid Problems
These problems involve grids, where each cell can be treated as a graph node connected to its neighbors.

#### 3.2.1- Grid Problems (Try All Nodes)
- **Leetcode: 79. Word Search**: (Medium)
- **Leetcode: 200. Number of Islands**:  (Medium)

#### 3.2.2- Grid Problems (Simultaneous Start)
- **Leetcode: 286. Walls and Gates**: (Medium)
- **Leetcode: 994. Rotting Oranges**:  (Medium)

#### 3.3- Word Problems (Need to Construct Graph from the Problem Statement)
These problems require constructing a graph from the given data before applying algorithms.

##### 3.3.1- Word Problems - Topological Sort (DAG)
These problems typically involve tasks that depend on one another, making topological sorting essential.
- **Leetcode: 207. Course Schedule**: (Medium)  
- **Leetcode: 269. Alien Dictionary**: (Hard)

</details>
