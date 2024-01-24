---
markmap:
  colorFreezeLevel: 2
  initialExpandLevel: 2
---

# Algorithms Cheatsheet

## Data Structures

### Arrays

- Common terms
  - Sub array
  - Sub sequence
- Time Complexity
  - Access: O(1)
  - Search: O(n)
  - Search Sorted: O(log n)
  - Insertion: O(n)
  - Deletion: O(n)
  - Sorting: O(n log n)
  - Remove at the end: O(1)
  - Remove at the beginning: O(n)
  - Remove in the middle: O(n)
  - Insert at the end: O(1)
- Corner Cases
  - Empty sequence
  - Sequence with 1 or 2 elements
  - Sequence with repeated elements
  - Duplicated values in the sequence
- Techniques
  - Sliding window
  - Two pointers
  - Traversing from the right
  - Sorting array
  - Precomputation
  - Traversing the array more than once
- Problems to practice
  - Two Sum
  - Best Time to Buy and Sell Stock
  - Product of Array Except Self
  - Maximum Subarray
  - Contains Duplicate
  - Maximum Product Subarray
  - Search in Rotated Sorted Array
  - 3Sum
  - Container With Most Water
  - Sliding Window Maximum

### Strings

- Can apply many approaches from arrays
- Common data structures for looking up strings
  - Trie/Prefix Tree
  - Suffix Tree
- Common strings algorithms
  - Rabin-Karp (rolling hash)
  - KMP (Knuth-Morris-Pratt)
  - Boyer-Moore (bad character rule, good suffix rule)
  - Longest Common Substring
  - Longest Common Subsequence
- Time Complexity
  - Access: O(1)
  - Search: O(n)
  - Search Sorted: O(log n)
  - Insertion: O(n)
  - Deletion: O(n)
  - Concatenate 2 strings: O(a + b)
  - Find substring: O(a.b)
- Corner Cases
  - Empty string
  - String with 1 or 2 characters
  - String with repeated characters
  - Duplicated values in the string
- Techniques
  - Counting characters with hash map
  - String of unique characters
  - Anagrams
    - Sort and compare: O(n.log(n)) time and O(log(n)) space
    - Frequency table and compare: O(n) time and O(1) space
    - Prime product and compare: O(n) time and O(1) space
  - Palindrome
    - Reverse and compare: O(n) time and O(n) space
    - Two pointers: O(n) time and O(1) space
- Problems to practice
  - Valid Anagram
  - Valid Palindrome
  - Longest Substring Without Repeating Characters
  - Longest Repeating Character Replacement
  - Find All Anagrams in a String
  - Minimum Window Substring
  - Group Anagrams
  - Longest Palindromic Substring
  - Encode and Decode Strings (LeetCode Premium)

### Hash Tables

- Hashing is the most common example of a space-time tradeoff
- Collision resolution
  - Separate chaining
  - Open addressing
- Time Complexity
  - Access: O(1)
  - Search: O(1)
  - Insertion: O(1)
  - Deletion: O(1)
- Corner Cases
- Techniques
- Problems to practice
  - Two Sum
  - Ransom Note
  - Group Anagrams
  - Insert Delete GetRandom O(1)
  - First Missing Positive
  - LRU Cache
  - All O one Data Structure

### Linked Lists

- Each element contains a connection to another element
- Types of linked lists
  - Singly linked list
  - Doubly linked list
  - Circular linked list
- Advantages
  - Dynamic size
  - Ease of insertion/deletion
- Disadvantages
  - No random access
  - Extra memory space for pointers
  - Not cache friendly
- Common terms
  - Head
  - Tail
  - Node
  - Pointer
- Corner Cases
  - Empty linked list (head is null)
  - Single node
  - Two nodes
  - Linked list has cycles
- Time Complexity
  - Access: O(n)
  - Search: O(n)
  - Insertion: O(1)
  - Deletion: O(1)
- Corner Cases
  - Empty sequence
  - Sequence with 1 or 2 elements
  - Sequence with repeated elements
  - Duplicated values in the sequence
- Techniques
  - Sentinel/dummy nodes
  - Two pointers
    - Getting the Kth element from the end
    - Detecting cycles
    - Reversing a linked list
    - Finding the middle node
  - Using space
  - Elegant modification operations
- Problems to practice
  - Reverse Linked List
  - Merge Two Sorted Lists
  - Merge k Sorted Lists
  - Remove Nth Node From End of List
  - Swap Nodes in Pairs
  - Linked List Cycle
  - Linked List Cycle II
  - Reverse Nodes in k-Group
  - Reorder List

### Stacks

- LIFO (Last In First Out)
- Time Complexity
  - Access: O(n)
  - Search: O(n)
  - Insertion: O(1)
  - Deletion: O(1)
  - Peek: O(1)
  - Push: O(1)
  - Pop: O(1)
  - Size: O(1)
- Corner Cases
  - Empty stack
  - Stack with one item
  - Stack with two items
- Algorithms that use stacks
  - Depth First Search
  - Backtracking
- Techniques
- Problems to practice
  - Implement Stack using Queues
  - Min Stack
  - Asteroid Collision
  - Evaluate Reverse Polish Notation
  - Basic Calculator
  - Basic Calculator II
  - Daily Temperatures
  - Trapping Rain Water
  - Largest Rectangle in Histogram

### Queues

- FIFO (First In First Out)
- Time Complexity
  - Access: O(n)
  - Search: O(n)
  - Insertion: O(1)
  - Deletion: O(1)
  - Peek: O(1)
  - Enqueue: O(1)
  - Dequeue: O(1)
- Corner Cases
  - Empty queue
  - Queue with one item
  - Queue with two items
- Algorithms that use queues
  - Breadth First Search
- Techniques
- Problems to practice
  - Implement Queue using Stacks
  - Design Circular Queue

### Trees

- Tree is a data structure that consists of nodes in a parent/child relationship
- A tree is an undirected and connected acyclic graph
- There are no cycles or loops
- Types of trees
  - Binary tree
  - Binary search tree
  - AVL tree
  - Red-black tree
  - Segment tree
  - Trie
  - N-ary tree
  - B-tree
  - B+ tree
- Common terms
  - Leaf: Node without children
  - Edge: Connection between one node and another
  - Neighbor: Parent or child of a node
  - Ancestor: A node reachable by traversing its - parent chain
  - Descendant: A node in the node's subtree
  - Degree: Number of children of a node
  - Degree of a tree: Maximum degree of nodes in the tree
  - Distance: Number of edges along the shortest path between two nodes
  - Level/Depth: Number of edges along the unique path between a node and the root node
  - Width: Number of nodes in a level
- Binary Tree
  - Perfect Binary Tree: All leaf nodes are at the same level and all internal nodes have two children
  - Complete Binary Tree: All levels are completely filled except possibly the last level and the last level has all keys as left as possible
  - Full Binary Tree: Every node has 0 or 2 children
  - Balanced Binary Tree: The difference between heights of left and right subtrees cannot be more than one for all nodes
  - Degenerate/Pathological Tree: Every internal node has one child
- Binary Tree traversal
  - in-order: left, root, right
  - pre-order: root, left, right
  - post-order: left, right, root
- Corner Cases
  - Empty tree
  - Tree with one node
  - Tree with two nodes
  - Tree with three nodes
  - Tree with repeated values
- Algorithms that use trees
  - Depth First Search
  - Breadth First Search
  - Binary Search
- Techniques
  - Use recursion
  - Traversing by level: Breadth First Search
  - Summation of nodes
- Problems to practice
  - Binary Tree
    - Maximum Depth of Binary Tree
    - Invert/Flip Binary Tree
    - Same Tree
    - Binary Tree Maximum Path Sum
    - Binary Tree Level Order Traversal
    - Lowest Common Ancestor of a Binary Tree
    - Binary Tree Right Side View
    - Subtree of Another Tree
    - Construct Binary Tree from Preorder and Inorder - Traversal
    - Serialize and Deserialize Binary Tree
  - Binary Search Tree
    - Lowest Common Ancestor of a Binary Search Tree
    - Validate Binary Search Tree
    - Kth Smallest Element in a BST

### Graphs

- A graph is a structure containing a set of objects (nodes or vertices)
- Corners Cases
  - Empty graph
  - Graph with one node
  - Graph with two nodes
  - Graph with three nodes
  - Graph with repeated values
  - Disconnected graphs
  - Graph with cycles
- Time Complexity
  - Depth-first search: O(V + E)
  - Breadth-first search: O(V + E)
  - Topological sort: O(V + E)
- Graph representations
  - Adjacency matrix
  - Adjacency list
  - Hash table of hash tables
- Graph search algorithms
  - Common - Breadth-first Search, Depth-first Search
  - Uncommon - Topological Sort, Dijkstra's algorithm
  - Almost never - Bellman-Ford algorithm, Floyd-Warshall algorithm, Prim's algorithm, Kruskal's algorithm. Your interviewer likely doesn't know them either.
- Problems to practice
  - Breadth-first search
    - Rotting Oranges
    - Minimum Knight Moves (LeetCode Premium)
  - Either search
    - Clone Graph
    - Pacific Atlantic Water Flow
    - Number of Connected Components in an Undirected Graph - (LeetCode Premium)
    - Graph Valid Tree (LeetCode Premium)
  - Topological sorting
    - Course Schedule
    - Alien Dictionary (LeetCode Premium)

### Heaps

- A heap is a specialized tree-based data structure which is essentially an almost complete tree that satisfies the heap property
- Also known as a priority queue
- Used in questions where you need to find the `k` smallest/largest elements
- Types of heaps
  - Min heap
  - Max heap
- Time Complexity
  - Access: O(n)
  - Search: O(n)
  - Insertion: O(log n)
  - Deletion: O(log n)
  - Peek: O(1)
  - Enqueue: O(log n)
  - Dequeue: O(log n)
- Corner Cases
  - Empty heap
  - Heap with one item
  - Heap with two items
- Algorithms that use heaps
  - Heap Sort
  - Priority Queue
- Problems to practice
  - Merge k Sorted Lists
  - Top K Frequent Elements
  - Find Median from Data Stream
  - Sliding Window Maximum

### Trie

- Tries are special trees (prefix trees) that make searching and storing strings more efficient
- Practical applicationes for tries
  - Autocomplete
  - Spell checker
  - IP routing (Longest prefix matching)
  - T9 predictive text
  - Solving word games
- Time Complexity
  - Access: O(n)
  - Search: O(n)
  - Insertion: O(n)
  - Deletion: O(n)
- Corner Cases
  - Empty trie
  - Trie with one item
  - Trie with two items
  - Insert empty string into a trie
- Algorithms that use tries
  - Autocomplete
  - Spell checker
- Problems to practice
  - Implement Trie (Prefix Tree)
  - Add and Search Word
  - Word Break
  - Word Search II

## Algorithms

### Recursion

- All recursive functions contains two parts
  - Base case (or cases)
  - Recursive case (smaller subproblem)
- Aspects to consider
  - Recursion is useful for permutation
  - Recursion implicitly uses a stack. Be aware of stack overflow
  - Number of base cases
- Algorithms that user recursion
  - Binary Search
  - Merge Sort
  - Quick Sort
  - Tree Traversal
  - Graph Traversal
  - Dynamic Programming
- Corner Cases
  - Empty sequence
  - Sequence with 1 or 2 elements
  - Sequence with repeated elements
  - Duplicated values in the sequence
- Techniques
  - Memoization
  - Dynamic Programming
- Problems to practice
  - Generate Parentheses
  - Combinations
  - Subsets
  - Letter Combinations of a Phone Number
  - Subsets II
  - Permutations
  - Sudoku Solver

### Sorting

- Types of sorting
  - Numerical
  - Lexicographical
  - Ascending and descending
- Aspects to consider
  - Check time and complexity for default sorting algorithm in your language
- Time Complexity
  - Bubble Sort: Time: O(n^2), Space: O(1)
  - Selection Sort: Time: O(n^2), Space: O(1)
  - Insertion Sort: Time: O(n^2), Space: O(1)
  - Merge Sort: Time: O(n.log(n)), Space: O(n)
  - Quick Sort: Time: O(n.log(n)), Space: O(log(n))
  - Heap Sort: Time: O(n.log(n)), Space: O(1)
  - Bucket Sort: Time: O(n + k), Space: O(n + k)
  - Counting Sort: Time: O(n + k), Space: O(k)
  - Radix Sort: Time: O(n.k), Space: O(n + k)
  - Timsort: Time: O(n.log(n)), Space: O(n)
  - Dual-Pivot Quicksort: Time: O(n.log(n)), Space: O(log(n))
  - Binary Search: O(log(n))
- Techniques
  - Divide and conquer
  - Sorting in place
  - Stable sorting
  - Comparison based sorting
  - Non-comparison based sorting
- Problems to practice
  - Binary Search
  - Search in Rotated Sorted Array
  - Kth Smallest Element in a Sorted Matrix
  - Search a 2D Matrix
  - Kth Largest Element in an Array
  - Find Minimum in Rotated Sorted Array
  - Median of Two Sorted Arrays

### Matrix

- Matrix is a 2-dimensional array
- Used in
  - Image processing
  - Dynamic programming
  - Graphs representation
- Corner Cases
  - Empty matrix
  - Matrix with 1 or 2 elements
  - Matrix with repeated elements
  - Duplicated values in the matrix
- Techniques
  - Creating an empty N x M matrix
  - Transposing a matrix
- Problems to practice
  - Set Matrix Zeroes
  - Spiral Matrix
  - Rotate Image
  - Word Search
  - Valid Sudoku

### Interval

- Interval questions are a subset of array questions where you are given an array of two-element arrays (an interval) and the two values represent a start and an end value
- Things to look for
  - Overlapping intervals
  - Merging intervals
  - Sorting intervals
- Corner cases
  - No intervals
  - Single interval
  - Two intervals
  - Non-overlapping intervals
  - An interval totally consumed within another interval
  - Duplicate intervals (exactly the same start and end)
  - Intervals which start right where another interval - ends - [[1, 2], [2, 3]]
- Techniques
  - Sort the array of intervals by its starting point
  - Checking if two intervals overlap
  - Merging two intervals
- Problems to practice
  - Insert Interval
  - Merge Intervals
  - Non-overlapping Intervals
  - Meeting Rooms
  - Meeting Rooms II

### Dynamic Programming

- Dynamic programming is a technique for solving problems with overlapping subproblems
- It takes some amount of practice to be able to recognize that a problem can be solved by DP
- Techniques
  - Top-down approach (memoization)
  - Bottom-up approach (tabulation)
- All dynamic programming problems have two properties
  - Overlapping subproblems
  - Optimal substructure
- Problems to practice
  - Climbing Stairs
  - Coin Change
  - House Robber
  - Longest Increasing Subsequence
  - 0/1 Knapsack or Partition Equal Subset Sum
  - Longest Common Subsequence
  - Word Break Problem
  - Combination Sum
  - House Robber II
  - Decode Ways
  - Unique Paths
  - Jump Game

### Binary conversions

- More commonly used when dealing with lower level systems and programming languages
- Corner Cases
  - Negative numbers
  - Zero
  - Positive numbers
  - Overflow/underflow
- Techniques
  - Test kth bit is set : `n & (1 << k)`
  - Set kth bit : `n |= (1 << k)`
  - Turn off kth bit : `n &= ~(1 << k)`
  - Toggle the kth bit : `n ^= (1 << k)`
  - Multiply by 2k : `n << k`
  - Divide by 2k : `n >> k`
  - Check if a number is a power of 2: `n & (n - 1) == 0`
  - Swapping two variables: `a ^= b; b ^= a; a ^= b;`
- Problems to practice
  - Sum of Two Integers
  - Number of 1 Bits
  - Counting Bits
  - Missing Number
  - Reverse Bits
  - Single Number

### Math

- Some basic math techniques is helpful to know as you may be asked to implement mathematical operations
- Corner Cases
  - Division by zero
  - Multiplication by 1
  - Negative Numbers
  - Floats
- Common formulas
  - Sum of first n natural numbers: `n * (n + 1) / 2`
  - Sum of 1 to N: `n * (n + 1) / 2`
  - Sum of Geometric Progression: `a * (1 - r^n) / (1 - r)`
  - Permutations of N: `n!`
  - Combinations of N: `n! / (k! * (n - k)!)`
- Problems to practice:
  - Pow(x, n)
  - Sqrt(x)

### Geometry

- Geometry is a branch of mathematics that is concerned with properties of space that are related with distance, shape, size, and relative position of figures
- Corner Cases
  - Negative numbers
  - Zero values
- Techniques
  - Distance from 2 points: `sqrt((x1 - x2)^2 + (y1 - y2)^2)`
  - Overlapping circles: `sqrt((x1 - x2)^2 + (y1 - y2)^2) < r1 + r2`
  - Overlapping rectangles: `x1 < x4 && x3 < x2 && y1 < y4 && y3 < y2`
- Problems to practice:
  - Rectangle Overlap
  - K Closest Points to Origin
  - Rectangle Area
