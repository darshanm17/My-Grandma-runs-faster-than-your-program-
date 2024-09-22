# Time-Matters
# Time Complexities of Data Structures and Algorithms

This document provides an overview of the time complexities for common data structures, algorithms, graph algorithms, sorting algorithms, and both linear and non-linear data structures.

## 1. Linear Data Structures

### Arrays
| Operation       | Time Complexity |
|-----------------|-----------------|
| Access          | O(1)            |
| Search          | O(n)            |
| Insertion       | O(n)            |
| Deletion        | O(n)            |

### Linked Lists
#### Singly Linked List
| Operation       | Time Complexity |
|-----------------|-----------------|
| Access          | O(n)            |
| Search          | O(n)            |
| Insertion (Head)| O(1)            |
| Insertion (Tail)| O(n)            |
| Deletion (Head) | O(1)            |
| Deletion (Tail) | O(n)            |

#### Doubly Linked List
| Operation       | Time Complexity |
|-----------------|-----------------|
| Access          | O(n)            |
| Search          | O(n)            |
| Insertion       | O(1)            |
| Deletion        | O(1)            |

### Stacks
| Operation       | Time Complexity |
|-----------------|-----------------|
| Push            | O(1)            |
| Pop             | O(1)            |
| Peek            | O(1)            |
| Search          | O(n)            |

### Queues
| Operation       | Time Complexity |
|-----------------|-----------------|
| Enqueue         | O(1)            |
| Dequeue         | O(1)            |
| Peek            | O(1)            |
| Search          | O(n)            |

---

## 2. Non-Linear Data Structures

### Binary Search Tree (BST)
| Operation       | Time Complexity (Average) | Time Complexity (Worst) |
|-----------------|---------------------------|-------------------------|
| Access          | O(log n)                  | O(n)                    |
| Search          | O(log n)                  | O(n)                    |
| Insertion       | O(log n)                  | O(n)                    |
| Deletion        | O(log n)                  | O(n)                    |

### AVL Tree
| Operation       | Time Complexity |
|-----------------|-----------------|
| Access          | O(log n)        |
| Search          | O(log n)        |
| Insertion       | O(log n)        |
| Deletion        | O(log n)        |

### Heaps
#### Min/Max Heap
| Operation          | Time Complexity |
|--------------------|-----------------|
| Insert             | O(log n)        |
| Delete (Min/Max)   | O(log n)        |
| Find Min/Max       | O(1)            |

---

## 3. Graph Algorithms

### Graph Representations
| Representation     | Space Complexity |
|--------------------|------------------|
| Adjacency List     | O(V + E)         |
| Adjacency Matrix   | O(V^2)           |

### Breadth-First Search (BFS)
| Operation       | Time Complexity |
|-----------------|-----------------|
| BFS             | O(V + E)        |

### Depth-First Search (DFS)
| Operation       | Time Complexity |
|-----------------|-----------------|
| DFS             | O(V + E)        |

### Dijkstra’s Algorithm
| Operation       | Time Complexity |
|-----------------|-----------------|
| Dijkstra’s      | O((V + E) log V) |

### Bellman-Ford Algorithm
| Operation       | Time Complexity |
|-----------------|-----------------|
| Bellman-Ford    | O(V * E)        |

### Floyd-Warshall Algorithm
| Operation       | Time Complexity |
|-----------------|-----------------|
| Floyd-Warshall  | O(V^3)          |

### Prim’s Algorithm
| Operation       | Time Complexity |
|-----------------|-----------------|
| Prim’s          | O((V + E) log V) |

### Kruskal’s Algorithm
| Operation       | Time Complexity |
|-----------------|-----------------|
| Kruskal’s       | O(E log V)      |

---

## 4. Sorting Algorithms

| Algorithm           | Time Complexity (Best) | Time Complexity (Average) | Time Complexity (Worst) | Space Complexity |
|---------------------|------------------------|---------------------------|-------------------------|------------------|
| Bubble Sort         | O(n)                   | O(n^2)                    | O(n^2)                  | O(1)             |
| Selection Sort      | O(n^2)                 | O(n^2)                    | O(n^2)                  | O(1)             |
| Insertion Sort      | O(n)                   | O(n^2)                    | O(n^2)                  | O(1)             |
| Merge Sort          | O(n log n)             | O(n log n)                | O(n log n)              | O(n)             |
| Quick Sort          | O(n log n)             | O(n log n)                | O(n^2)                  | O(log n)         |
| Heap Sort           | O(n log n)             | O(n log n)                | O(n log n)              | O(1)             |
| Counting Sort       | O(n + k)               | O(n + k)                  | O(n + k)                | O(k)             |
| Radix Sort          | O(nk)                  | O(nk)                     | O(nk)                   | O(n + k)         |
| Bucket Sort         | O(n + k)               | O(n + k)                  | O(n^2)                  | O(n)             |

---

## 5. Hash Tables

| Operation       | Average Time Complexity | Worst Time Complexity |
|-----------------|-------------------------|-----------------------|
| Search          | O(1)                    | O(n)                  |
| Insertion       | O(1)                    | O(n)                  |
| Deletion        | O(1)                    | O(n)                  |

---

## 6. Trie (Prefix Tree)

| Operation       | Time Complexity |
|-----------------|-----------------|
| Insert          | O(L)            |
| Search          | O(L)            |
| Delete          | O(L)            |

Where `L` is the length of the word.

---

## Summary

This document provides an essential understanding of time complexities for the most commonly used data structures and algorithms. Optimizing time complexity is crucial for creating efficient applications, especially when dealing with large datasets or real-time processing requirements.
