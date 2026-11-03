# Java Programming Lab (BCS-553) - Repository README

> **Institution:** Invertis University, Bareilly
> 
> 
> **Course:** B.Tech CSE (5th Semester)
> 
> 
> **Subject:** Java Programming Lab / Applied Data Structure & Algorithms Lab (BCS-553)
> 
> 
> **Submitted To:** Mr. Manish Sir
> 
> 
> **Submitted By:** Haseen Babu
> 
> 

---

## 📖 About This Repository

This repository contains all laboratory assignments, practical programs, and tasks completed as part of the **Java Programming Lab (BCS-553)** course. The programs focus on fundamental data structures, sorting and searching algorithms, object-oriented programming (OOP) principles, recursion, and backtracking implemented in **Java**.

---

## 🗂️ Index / Table of Contents

| S.N. | Experiment Title | Key Concepts / Topics Covered |
| --- | --- | --- |
| **1** | [Reading Array Values](https://www.google.com/search?q=%23experiment-01--reading-array-values) | Array indexing, loop traversal, aggregation (`sum`)[cite: 3] |
| **2** | [Largest, Smallest and Count](https://www.google.com/search?q=%23experiment-02--largest-smallest-and-count) | Extremum search, conditional filtering tallies[cite: 5] |
| **3** | [Bubble Sort](https://www.google.com/search?q=%23experiment-03--bubble-sort) | Adjacent element comparison and swapping[cite: 6] |
| **4** | [Selection Sort](https://www.google.com/search?q=%23experiment-04--selection-sort) | Minimum selection and placement in unsorted regions[cite: 8] |
| **5** | [Linear Search](https://www.google.com/search?q=%23experiment-05--linear-search) | Sequential scanning, occurrence counting[cite: 10] |
| **6** | [Binary Search on a Sorted Array](https://www.google.com/search?q=%23experiment-06--binary-search-on-a-sorted-array) | Divide-and-conquer on sorted datasets, `mid` calculation[cite: 11] |
| **7** | [Practice Set](https://www.google.com/search?q=%23experiment-07--practice-set) | Consolidation of loops, arrays, searches, and modulo filters[cite: 13] |
| **8** | [Classes and Objects](https://www.google.com/search?q=%23experiment-08--classes-and-objects) | Blueprints, state, behavior, heap allocation, dot operator[cite: 14] |
| **9** | [Constructors and Field Initialization](https://www.google.com/search?q=%23experiment-09--constructors-and-field-initialization) | No-arg & parameterized constructors, `this` keyword[cite: 15] |
| **10** | [Parent and Child Classes (Inheritance)](https://www.google.com/search?q=%23experiment-10--parent-and-child-classes) | Single-level inheritance, `extends`, `super()` delegation[cite: 17] |
| **11** | [Method Overriding & Polymorphism](https://www.google.com/search?q=%23experiment-11--method-overriding--polymorphism) | Runtime polymorphism, dynamic method dispatch[cite: 19] |
| **12** | [Recursive Factorial, Sum and Power](https://www.google.com/search?q=%23experiment-12--recursive-factorial-sum-and-power) | Base cases, call stack management, mathematical recursion[cite: 20] |
| **13** | [Recursion on Arrays](https://www.google.com/search?q=%23experiment-13--recursion-on-arrays) | Recursive traversal, array max, reverse printing[cite: 22] |
| **14** | [Sorted Check, Search and Fibonacci](https://www.google.com/search?q=%23experiment-14--sorted-check-search-and-fibonacci) | Multi-step relational invariants, sequence generation[cite: 23] |
| **15** | [Subsets and Arrangements (Backtracking)](https://www.google.com/search?q=%23experiment-15--subsets-and-arrangements-backtracking) | Incremental exploration, state marking, undo choices[cite: 25] |

---

## ⚙️ Requirements & Environment Setup

* **Java Development Kit (JDK):** Version 8 or higher[cite: 3]
* **IDE / Text Editor:** Eclipse, IntelliJ IDEA, or Visual Studio Code[cite: 3]
* **Terminal / Command Prompt** for compilation and execution via CLI[cite: 3]

---

## 📝 Experiment Summaries & Quick Code Reference

### Experiment 01: Reading Array Values

* **Aim:** Read values from an array using indices and loops[cite: 3].
* **Key Takeaway:** Understanding zero-based indexing (`0` to `length-1`) and avoiding `ArrayIndexOutOfBoundsException`[cite: 3, 5].

### Experiment 02: Largest, Smallest and Count

* **Aim:** Find extreme values and count elements matching specific conditions[cite: 5].
* **Key Takeaway:** Initializing trackers with the first array element (`marks[0]`) rather than `0` to safely handle negative values[cite: 6].

### Experiment 03: Bubble Sort

* **Aim:** Sort an array by comparing neighboring elements and swapping out-of-order values[cite: 6].
* **Key Takeaway:** Quadratic time complexity $O(n^2)$ and early-exit optimization using swap tracking flags[cite: 6, 8].

### Experiment 04: Selection Sort

* **Aim:** Divide lists into sorted/unsorted regions and repeatedly move minimum elements to the front[cite: 8].
* **Key Takeaway:** Minimizing memory writes to $O(n)$ swaps[cite: 9].

### Experiment 05: Linear Search

* **Aim:** Sequentially scan arrays to find target keys or frequencies[cite: 10].
* **Key Takeaway:** Works on both sorted and unsorted data with an $O(n)$ worst-case scenario[cite: 10, 11].

### Experiment 06: Binary Search on a Sorted Array

* **Aim:** Utilize divide-and-conquer to locate elements in logarithmic time $O(\log n)$[cite: 11].
* **Key Takeaway:** Using `low + (high - low) / 2` to prevent integer overflow compared to `(low + high) / 2`[cite: 13].

### Experiment 07: Practice Set

* **Aim:** Combine array traversals, sorting passes, product aggregations, and even-number modulo checks (`% 2 == 0`)[cite: 13].

### Experiment 08: Classes and Objects

* **Aim:** Define blueprints with fields and methods, and instantiate objects on the Heap memory[cite: 14, 16].

### Experiment 09: Constructors

* **Aim:** Automate state initialization upon object creation using default and parameterized constructors (`this`)[cite: 15, 16].

### Experiment 10: Parent and Child Classes

* **Aim:** Implement single inheritance using `extends` and propagate superclass constructors via `super()`[cite: 17, 18].

### Experiment 11: Method Overriding

* **Aim:** Achieve runtime polymorphism and dynamic method dispatch by redefining parent methods in subclasses[cite: 19].

### Experiment 12: Recursive Factorial, Sum and Power

* **Aim:** Solve self-similar mathematical problems with strict base cases to prevent `StackOverflowError`[cite: 20, 21].

### Experiment 13: Recursion on Arrays

* **Aim:** Traverse arrays recursively via explicit index shifting for summation, finding maximums, and reverse printing[cite: 22, 23].

### Experiment 14: Sorted Check, Search and Fibonacci

* **Aim:** Validate sorted array properties, perform recursive searches, and compute Fibonacci terms[cite: 23, 24].

### Experiment 15: Subsets and Arrangements (Backtracking)

* **Aim:** Systematically generate power sets ($2^N$) and permutations ($N!$) by making choices and backtracking[cite: 25, 26].

---

## 🚀 How to Compile and Run

Open your terminal or command prompt in the respective directory and run the following commands:

```bash
# Compile a specific task/class
javac Task1.java

# Run the compiled Java class
java Task1

```

---

## 🛡️ License

This project is developed for academic submission under Invertis University's B.Tech Computer Science curriculum.

## Auther:
   HASEEN BABU
