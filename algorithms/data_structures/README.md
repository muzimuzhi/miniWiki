---
title: 数据结构与算法
---

# 学习资源

## 教程

### Princeton

- Textbooks:
  - [Algorithms, 4th Edition](https://algs4.cs.princeton.edu/home/)
  - [An Introduction to the Analysis of Algorithms, 2nd Edition](https://aofa.cs.princeton.edu/home/)
- Courses:
  - [Algorithms, Part 1](https://www.coursera.org/learn/algorithms-part1)
  - [Algorithms, Part 2](https://www.coursera.org/learn/algorithms-part2)
  - [Analysis of Algorithms](https://www.coursera.org/learn/analysis-of-algorithms)

### MIT

- Textbook:
  - [Introduction to Algorithms, Third Edition](https://mitpress.mit.edu/books/introduction-algorithms-third-edition)
- Courses:
  - [Introduction to Algorithms](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/) taught by *Prof. Erik Demaine* and *Prof. Srini Devadas* in Fall 2011.
  - [Design and Analysis of Algorithms](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-046j-design-and-analysis-of-algorithms-spring-2015/) taught by *Prof. Erik Demaine* and *Prof. Srini Devadas* and *Prof. Nancy Lynch* in Spring 2015.

## 网站

### 学习

- [VisuAlgo](https://visualgo.net/en): visualising data structures and algorithms through animation.

### 刷题

- [LeetCode](https://leetcode.com/): the world's leading online programming learning platform.
- [PAT](https://www.patest.cn/): Programming Ability Test.

# Computational Complexity

## Mathematical (Theoretical) Method

- MIT
  - Text:
    - Chap-3  Growth of Functions
    - Chap-5  Probabilistic Analysis and Randomized Algorithms

## Scientific (Experimental) Method

- Princeton
  - Text: [Sect-1.4  Analysis of Algorithms](https://algs4.cs.princeton.edu/14analysis/)
  - Video: [Analysis of Algorithms](https://www.coursera.org/learn/algorithms-part1/supplement/mpK20/lecture-slides)

> 1. *Observe* some feature of the natural world, generally with precise measurements.
> 2. *Hypothesize* a model that is consistent with the observations.
> 3. *Predict* events using the hypothesis.
> 4. *Verify* the predictions by making further observations.
> 5. *Validate* by repeating until the hypothesis and observations agree.

# Arrays & Vectors

## Sorting

- VisuAlgo
  - [Sorting](https://visualgo.net/en/sorting)

### Quadratic Sorts

- Princeton
  - Text: [Sect-2.1  Elementary Sorts](https://algs4.cs.princeton.edu/21elementary)
  - Video: [Elementary Sorts](https://www.coursera.org/learn/algorithms-part1/supplement/erHuw/lecture-slides)

#### Bubble Sort

#### Selection Sort

#### Insertion Sort

### Shellsort

### Mergesort

- Princeton
  - Text: [Sect-2.2  Mergesort](https://algs4.cs.princeton.edu/22mergesort)
  - Video: [Mergesort](https://www.coursera.org/learn/algorithms-part1/supplement/4E9fa/lecture-slides)

#### [Timsort](https://en.wikipedia.org/wiki/Timsort)

- Libraries
  - C++: [`std::stable_sort`](https://en.cppreference.com/w/cpp/algorithm/stable_sort) in `<algorithm>`
  - Java8: [`java.util.Arrays.sort(Object[] a)`](https://docs.oracle.com/javase/8/docs/api/java/util/Arrays.html#sort-java.lang.Object:A-)
  - Python:
    - [`list.sort(*, key=None, reverse=False)`](https://docs.python.org/3/library/stdtypes.html#list.sort) stably sorts the list in place.
    - [`sorted(iterable, *, key=None, reverse=False)`](https://docs.python.org/3/library/functions.html#sorted) returns a new stably sorted list from the items in `iterable`.

### Quicksort

- Princeton
  - Text: [Sect-2.3  Quicksort](https://algs4.cs.princeton.edu/23quicksort)
  - Video: [Quicksort](https://www.coursera.org/learn/algorithms-part1/supplement/efbDN/lecture-slides)
- Libraries
  - C: [`qsort`](https://en.cppreference.com/w/c/algorithm/qsort) in `<stdlib.h>`
  - C++: [`std::sort`](https://en.cppreference.com/w/cpp/algorithm/sort) in `<algorithm>`
  - Java8: [`java.util.Arrays.sort(int[] a)`](https://docs.oracle.com/javase/8/docs/api/java/util/Arrays.html#sort-int:A-)

### Application: [Convex Hull](https://www.coursera.org/learn/algorithms-part1/lecture/KHJ1t/convex-hull)

### Application: [Collinear Points](https://www.coursera.org/learn/algorithms-part1/programming/prXiW/collinear-points)

## Searching

### Binary Search

## Union--Find

- VisuAlgo
  - [Union--Find DS](https://visualgo.net/en/ufds)
- Princeton
  - Text: [Sect-1.5  Union--Find](https://algs4.cs.princeton.edu/15uf/)
  - Video: [Union--Find](https://www.coursera.org/learn/algorithms-part1/supplement/bcelg/lecture-slides)
  - Assignment: [Percolation](https://www.coursera.org/learn/algorithms-part1/programming/Lhp5z/percolation)

## Vectors (Resizing Arrays)

- Princeton
  - Text: [Sect-1.3  Bags, Queues, and Stacks](https://algs4.cs.princeton.edu/13stacks/)
  - Video: [Resizing Arrays](https://www.coursera.org/learn/algorithms-part1/lecture/WTFO7/resizing-arrays)

# Lists, Stacks & Queues

## Linked Lists

- VisuAlgo
  - [Linked List](https://visualgo.net/en/list)
    - Linked List
    - Doubly Linked List
- Princeton
  - Text: [Sect-1.3  Bags, Queues, and Stacks](https://algs4.cs.princeton.edu/13stacks/)
  - Video: [Stacks](https://algs4.cs.princeton.edu/13stacks/)

## Stacks

- VisuAlgo
  - [Linked List](https://visualgo.net/en/list)
    - Stack
- Princeton
  - Text: [Sect-1.3  Bags, Queues, and Stacks](https://algs4.cs.princeton.edu/13stacks/)
  - Video: [Stacks](https://algs4.cs.princeton.edu/13stacks/)

## Queues

- VisuAlgo
  - [Linked List](https://visualgo.net/en/list)
    - Queue
    - Deque
- Princeton
  - Text: [Sect-1.3  Bags, Queues, and Stacks](https://algs4.cs.princeton.edu/13stacks/)
  - Video: [Queues](https://www.coursera.org/learn/algorithms-part1/lecture/5vgrm/queues)
  - Programming Assignment: [Deques and Randomized Queues](https://www.coursera.org/learn/algorithms-part1/programming/zamjZ/deques-and-randomized-queues)

# Priority Queues

## Binary Heap

- Princeton
  - Section: [Sect-2.4 Priority Queues](https://algs4.cs.princeton.edu/24pq)
  - Video: [Priority Queues](https://www.coursera.org/learn/algorithms-part1/supplement/eHe3d/lecture-slides)
  - Programming Assignment: [8 Puzzle](https://www.coursera.org/learn/algorithms-part1/programming/iqOQi/8-puzzle)

### Event-Driven Simulation

- Princeton
  - Text: [Sect-6.1  Event Driven Simulation](https://algs4.cs.princeton.edu/61event)
  - Video: [Event-Driven Simulation](https://www.coursera.org/learn/algorithms-part1/lecture/QVhGs/event-driven-simulation-optional)

## Fibonacci Heap

## Van Emde Boas Tree

# Hash Tables

- VisuAlgo
  - [Hash Table](https://visualgo.net/en/hashtable)

## Open Addressing

## Seperate Chaining

## Universal Hashing

# Trees

## Binary Search Trees

- Princeton
  - Text: [Sect-3.2 Elementary Symbol Tables](https://algs4.cs.princeton.edu/33balanced)
  - Video: [Elementary Symbol Tables](https://www.coursera.org/learn/algorithms-part1/supplement/2kwpU/lecture-slides)

## Balanced Search Trees

- Princeton
  - Text: [Sect-3.3 Balanced Search Trees](https://algs4.cs.princeton.edu/33balanced), [Sect-6.2 B-trees](https://algs4.cs.princeton.edu/62btree)
  - Video: [Balanced Search Trees](https://www.coursera.org/learn/algorithms-part1/supplement/zQXMd/lecture-slides)

## Geometric Search Trees

### Kd-Trees

- Princeton
  - Video: [Geometric Applications of BSTs](https://www.coursera.org/learn/algorithms-part1/supplement/yelcJ/lecture-slides)
  - Programming Assignment: [Kd-Trees](https://www.coursera.org/learn/algorithms-part1/programming/wuF0a/kd-trees)

### Range Trees

# Graphs

## Undirected Graphs

## Directed Graphs

### Application: [WordNet](https://www.coursera.org/learn/algorithms-part2/programming/BCNsp/wordnet)

## Minimum Spanning Trees

## Shortest Paths

### Application: [Seam Carving](https://www.coursera.org/learn/algorithms-part2/programming/cOdkz/seam-carving)

## Maximum Flow and Minimum Cut

### Application: [Baseball Elimination](https://www.coursera.org/learn/algorithms-part2/programming/hmYRI/baseball-elimination)

# Strings

## String Implementations

## Radix Sorts

### LSD Radix Sort

### MSD Radix Sort

### 3-way Radix Quicksort

## Suffix Arrays

## Tries

## Substring Search

### Brute-Force

### Knuth--Morris--Pratt

### Boyer--More

### Rabin--Karp

### Application: [Boggle](https://www.coursera.org/learn/algorithms-part2/programming/9GqJs/boggle)

## Regular Expressions

## Data Compression

### Application: [Burrows Wheeler](https://www.coursera.org/learn/algorithms-part2/programming/3nmSB/burrows-wheeler)

# Computation Theory

## Reductions

## Linear Programming

## Intractability