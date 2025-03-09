# Data Structures and Algorithms Notes

![dsa-banner](https://github.com/izzatkarimov/DSA-Notes/assets/108251704/44dda9d8-a66b-45c8-a602-6487ff6fa762)

## Overview
This repository contains my personal notes on Data Structures and Algorithms, with links to websites, courses, books, and other valuable materials.

## Table of Contents

- [Resources](#resources)
  - [Websites](#websites)
  - [Courses](#courses)
  - [YouTube Channels / Playlists / Videos](#youtube-channels--playlists--videos)
  - [Github Repositories](#github-repositories)
  - [Books](#books)
  - [Practice](#practice)
- [Notes](#notes)
  - [Getting Started](#getting-started)
    - [What is a Data Structure](#what-is-a-data-structure)
    - [What are the types of Data Structures?](#what-are-the-types-of-data-structures)
    - [What are Primitive Data Structures?](#what-are-primitive-data-structures)
    - [What are Non-Primitive Data Structures?](#what-are-non-primitive-data-structures)
    - [What is a Linear Data Strcuture?](#what-is-a-linear-data-structure)
    - [What is a Non-Linear Data Structure?](#what-is-a-non-linear-data-structure)
    - [What is a Hash-Based Data Structure](#what-is-a-hash-based-data-structure)
    - [What is a Static Data Structure?](#what-is-a-static-data-structure)
    - [What is a Dynamic Data Structure?](#what-is-dynamic-data-structure)
    - [What is Big O Notation?](#what-is-big-o-notation)
    - [Common Big O Notations](#common-big-o-notations)
    - [Common Big O Notations Summary](#common-big-o-notations-summary)
    - [Additional Big O Notations](#additional-big-o-notations)
  - [Data Structures](#data-structures)
    - [Arrays](#arrays)
    - [Linked Lists](#linked-lists)
    - [Stacks](#stacks)
    - [Queues](#queues)
    - [Trees](#trees)
    - [Hash Tables](#hash-tables)
    - [Heaps / Priority Queues](#heaps--priority-queues)
    - [Graphs](#graphs)
    - [Tries](#tries)
  - [Algorithms](#algorithms)

## Resources
> The following is a list of online courses, YouTube videos, and websites to help learn Data Structures & Algorithms. Note that these are not in order of completion.

| All Resources | Type | Links |
| --- | --- | --- |
| LeetCode | `website`| [Website Link](https://leetcode.com) |
| NeetCode| `website`| [Website Link](https://neetcode.io/practice) |
| AlgoMap | `website` | [Website Link](https://algomap.io/) |
| TopSWE | `website`| [Website Link](https://topswe.com/) |
| LeetCode Patterns | `website` | [Website Link](https://seanprashad.com/leetcode-patterns/) |
| NeetCode Roadmap | `website` | [Website Link](https://neetcode.io/roadmap) |
| VisuAlgo | `website` | [Website Link](https://visualgo.net/en) |
| Data Structure Visualizations | `website` | [Website Link](https://www.cs.usfca.edu/~galles/visualization/Algorithms.html) |
| Big-O CheatSheet | `website` | [Website Link](https://www.bigocheatsheet.com/) |
| Data Structure Visualization | `website` | [Website Link](https://www.cs.usfca.edu/~galles/visualization/Algorithms.html) |
| NeetCode Courses | `course` | [Course Link](https://neetcode.io/courses) |
| C++ Data Structures & Algorithms + LEETCODE Exercises | `course` | [Course Link](https://www.udemy.com/course/data-structures-algorithms-python/?couponCode=ACCAGE0923) |
| The Last Algorithms Course You'll Need | `course` | [Course Link](https://frontendmasters.com/courses/algorithms/) |
| Algorithms and Data Structures Tutorial - Full Course for Beginners | `youtube-video` | [Video Link](https://youtu.be/8hly31xKli0?si=HmAgr-2AlG3hcRZp) | |
| A & DS English Course - Pavel Mavrin| `youtube-playlist` | [Playlist Link](https://youtube.com/playlist?list=PLrS21S1jm43igE57Ye_edwds_iL7ZOAG4&si=F9wl4QuTwXjn4VbS) | |
| NeetCode YouTube Videos | `youtube-channel` | [Channel Link](https://www.youtube.com/@NeetCode) |
| Coding Interview University | `github-repo` | [Repository Link](https://github.com/jwasham/coding-interview-university) |
| Awesome Algorithms | `github-repo` | [Repository Link](https://github.com/tayllan/awesome-algorithms) |

### Websites
- [Roadmap to learn DSA by Neetcode](https://neetcode.io/roadmap)
- [AlgoMap](https://algomap.io/)
- [VisuAlgo](https://visualgo.net/en)
- [Data Structure Visualization](https://www.cs.usfca.edu/~galles/visualization/Algorithms.html)

### Courses
- [Neetcode Courses](https://neetcode.io/courses)
- [C++ Data Structures & Algorithms + LEETCODE Exercises](https://www.udemy.com/course/data-structures-algorithms-cpp/)
- [The Last Algorithms Course You'll Need](https://frontendmasters.com/courses/algorithms/)

### YouTube Channels / Playlists / Videos
- 
- [Algorithms and Data Structures Tutorial - Full Course for Beginners - FreeCodeCamp](https://youtu.be/8hly31xKli0?si=HmAgr-2AlG3hcRZp)
- [A & DS English Course - Pavel Mavrin](https://youtube.com/playlist?list=PLrS21S1jm43igE57Ye_edwds_iL7ZOAG4&si=F9wl4QuTwXjn4VbS)
- [Neetcode Videos on YouTube](https://www.youtube.com/@NeetCode)

### Github Repositories
- [Coding Interview University](https://github.com/jwasham/coding-interview-university)
- [Awesome Algorithms](https://github.com/tayllan/awesome-algorithms)

### Books
- [Cracking the Coding Interview](https://www.crackingthecodinginterview.com)
- [Introduction to Algorithms](https://shorturl.at/rahhl)
- [Competitive Programmer's Handbook](https://cses.fi/book/book.pdf)

### Practice
- [Leetcode](https://leetcode.com/)
- [Codeforces](https://codeforces.com)
- [Neetcode](https://neetcode.io/practice)
- [TopSWE](https://topswe.com/)
- [LeetCode Patterns](https://seanprashad.com/leetcode-patterns/)

## Notes

### Getting Started

> #### What is a Data Structure?

A data structure is a systematic way of organizing, managing, and storing data to enable efficient processing and retrieval. It defines how data elements relate, how they are accessed, and what operations can be performed on them, and how efficient these operations are.

It can be compared to a container—just as different containers hold items in various ways, a data structure organizes and stores data in a specific manner according to our needs.

> #### What are the types of data structures?

Data structures are classified into primitive and non-primitive types.
- **Primitive Data Structures**:
  - Integer, Float, Character, Boolean.
- **Non-Primitive Data Structures**:
  - Linear: Arrays, Linked Lists, Stacks, Queues.
  - Non-Linear: Trees, Graphs.
  - Hash-Based: Hash Tables.

> #### What are Primitive Data Structures?

Primitive Data Structures are the fundamental types of data directly supported by a programming language. They store a single value and are the building blocks for more complex data structures.

The core four primitive types are: (int, float, char, bool) and are universal across most languages, but some languages extend the list with types like string, byte, short, long, double, and unsigned int. Whether they are considered primitive depends on the language.

> #### What are Non-Primitive Data Structures?

Non-primitive data structures are complex structures that store multiple values and are derived from primitive data types. They can store homogeneous or heterogeneous elements, support dynamic size, and perform complex operations.

**Common Types of Non-Primitive Data Structures**:
- Arrays: Fixed-size collections of homogeneous elements.
- Linked Lists: Chain of nodes, each pointing to the next.
- Stacks: Follow LIFO (Last In First Out) principle.
- Queues: Follow FIFO (First In First Out) principle.
- Trees: Hierarchical structure of nodes (e.g., binary tree, AVL tree).
- Graphs: Non-linear, consisting of vertices and edges.
- Hash Tables: Key-value pairs with constant time access.
- Heaps: Tree-based structures with heap property (max or min).

> #### What is a Linear Data Structure?

Data structure in which data elements are arranged sequentially or linearly, where each element is attached to its previous and next adjacent elements, is called a linear data structure.

Examples of linear data structures are array, stack, queue, linked list, etc.

> #### What is a Non-Linear Data Structure?

A non-linear data structure is one where elements do not have a sequential relationship. Instead, elements can have multiple connections to other elements. Non-linear structures are used to represent hierarchical or graph-based relationships, such as trees or graphs.
 
Examples of non-linear data structures are trees and graphs.

> #### What is a Hash-Based Data Structure?

A hash-based data structure uses a hash function to map keys to indices or addresses, enabling fast retrieval, insertion, and deletion of data. The hash function transforms the key into an integer index, which is used to store the corresponding value. Key examples include hash tables and hash sets.

**Simpler Analogy**:
A hash-based data structure is like a library system. Imagine each book in the library has a unique ID (the key), and the hash function is like the system that turns that ID into a specific shelf number (the index). When you want to find or add a book, the system quickly tells you the exact shelf number where it is located. This way, you can easily retrieve, add, or remove books without having to search through all the shelves.

Based on this analogy, hash tables would be where books are stored with their details and hash sets would be where only the books themselves are stored without extra details.

> #### What is a Static Data Structure?

A static data structure has a fixed size at the time of creation and cannot be resized during the program's execution. Memory allocation is predetermined, making it memory-efficient, but lack of flexibility is its key limitation.

**An example**:
Arrays: Fixed-size, contiguous collection of elements.

*(Note: Arrays can be dynamic in some contexts, but as a static structure, their size is fixed at creation.)*

> #### What is Dynamic Data Structure?

A dynamic data structure can grow or shrink in size during the program’s execution. Memory is allocated and deallocated as needed, allowing for flexibility in managing elements. This structure is ideal when the number of elements is not fixed.

**Examples**:
- Linked Lists: Collection of nodes that can grow or shrink dynamically.
- Dynamic Stacks: Stack that resizes as elements are added or removed.
- Dynamic Queues: Queue that resizes dynamically with elements being added/removed.
- Hash Tables: Resizes automatically when a capacity threshold is reached.

> #### What is Big O Notation?

Big O notation is a mathematical concept used to describe the efficiency of algorithms in terms of time complexity and space complexity. It is a measure of how the runtime of an algorithm or memory usage of an algorithm grows as the input size (usually denoted as n) grows.

To reiterate, Big O can be categorized into two types:

- **Time Complexity:** Measures how the runtime of an algorithm grows as the input size grows.
- **Space Complexity:** Measures how memory usage increases as input size grows.

![Image](https://github.com/user-attachments/assets/2c6341a2-4a77-468e-a47d-541d91e39ebe)

![big-o-complexity-chart](https://github.com/user-attachments/assets/74fb77a6-3436-4630-a451-1ebf0009301f)

> #### Common Big O Notations

![Image](https://github.com/user-attachments/assets/91abc84b-77d5-4db1-9afe-8c4cb90e6251)

[<ins>**O(1): Constant Time**</ins>](https://en.wikipedia.org/wiki/Big_O_notation#:~:text=%5B15%5D-,Orders%20of%20common%20functions,-%5Bedit%5D)

An algorithm has O(1) complexity if its execution time does not depend on the input size (n). It always takes a constant number of operations, regardless of how large the input is.

_Short description: Time does not depend on input size - always takes the same time._

**Examples:**

![Image](https://github.com/user-attachments/assets/299da2f9-6a76-4735-aab9-ba7f61945e8f)

[<ins>**O(log n): Logarithmic Time**</ins>](https://en.wikipedia.org/wiki/Big_O_notation#:~:text=%5B15%5D-,Orders%20of%20common%20functions,-%5Bedit%5D)

An algorithm has **O(log n) complexity** if the number of operations **decreases exponentially** as the input size (**n**) increases. Instead of processing each element one by one, the algorithm **repeatedly divides the problem into smaller parts**, typically by a factor of 2 (or another base). 

This means that the time required to complete the algorithm grows much more slowly compared to linear time complexities, such as O(n). Logarithmic time complexity is particularly efficient for large data sets, making it a desirable characteristic in algorithm design.

_Short Description: Reduces problem size each step._

**Examples:**

![Image](https://github.com/user-attachments/assets/6c38081b-4313-4bdf-97db-528f74ba2ecf)

[<ins>**O(n): Linear Time**</ins>](https://en.wikipedia.org/wiki/Big_O_notation#:~:text=%5B15%5D-,Orders%20of%20common%20functions,-%5Bedit%5D)

An algorithm has O(n) complexity if its execution time increases linearly with the input size (n). This means that if the input size doubles, the time taken by the algorithm also roughly doubles.

_Short Description: Time increases linearly with the input size._

**Examples:**

![Image](https://github.com/user-attachments/assets/fae1ad13-80b9-4c40-bf93-1e0c27dde005)

[<ins>**O(n log n): Linearithmic Time**</ins>](https://en.wikipedia.org/wiki/Big_O_notation#:~:text=%5B15%5D-,Orders%20of%20common%20functions,-%5Bedit%5D)

O(n log n), or **linearithmic time complexity**, represents an algorithm whose execution time grows in proportion to the **product of the size of the input data set, denoted as *n*, and the logarithm of that size**.

This means that as the input size increases, the time required to complete the algorithm increases at a rate that is faster than linear (O(n)) but slower than quadratic (O(n²)). Linearithmic time complexity is particularly significant in algorithms that involve both linear iterations and logarithmic divisions.

_Short Description: The runtime of the algorithm grows linearly with the input AND with the logarithm of the input size. Common in Sorting Algorithms._

**Examples:**

![Image](https://github.com/user-attachments/assets/f921bef5-5fc9-44f2-8e47-2a12af3b331f)

[<ins>**O(n^2): Quadratic Time**</ins>](https://en.wikipedia.org/wiki/Big_O_notation#:~:text=%5B15%5D-,Orders%20of%20common%20functions,-%5Bedit%5D)

O(n²), or **quadratic time complexity**, describes an algorithm whose execution time grows proportionally to the square of the size of the input data set, denoted as *n*.

**This means that if the input size doubles, the execution time increases by a factor of four (since 2² = 4)**. Quadratic time complexity is commonly associated with algorithms that involve nested iterations over the input data, where each element is compared or processed with every other element.

_Short Description: Typical in Algorithms with Nested Loops._

**Examples:**

![Image](https://github.com/user-attachments/assets/7334f8e4-590a-4544-b3de-b699a9f9cfd9)

[<ins>**O(2^n): Exponential Time**</ins>](https://en.wikipedia.org/wiki/Big_O_notation#:~:text=%5B15%5D-,Orders%20of%20common%20functions,-%5Bedit%5D)

An algorithm has **O(2ⁿ) complexity** if its execution time **doubles with each additional input element (n).** This means that **if the input size increases by 1, the number of operations doubles.**

Exponential time complexity typically arises in problems that involve **combinatorial growth**, such as recursion with multiple branching paths, brute-force approaches, and exhaustive searches. These algorithms become **extremely slow for large inputs** and are generally impractical beyond small values of **n**.

_Short Description: Doubles with each additional input._

**Examples:**

![Image](https://github.com/user-attachments/assets/08573051-4c72-4218-ade8-825bdd024b90)

[<ins>**O(n!): Factorial Time**</ins>](https://en.wikipedia.org/wiki/Big_O_notation#:~:text=%5B15%5D-,Orders%20of%20common%20functions,-%5Bedit%5D)

Factorial growth is **extremely fast**—even faster than **exponential growth (O(2ⁿ))**. As a result, **O(n!) algorithms become impractical very quickly** beyond small values of **n**.

_Short Description: Extremely inefficient! Runtime grows extremely fast!_

**Examples:**

![Image](https://github.com/user-attachments/assets/5acd4d08-3a02-434b-9080-9ab78f17c55a)

> #### Common Big O Notations Summary

![big-o-summary](https://github.com/user-attachments/assets/effd5871-71d0-4be3-8877-8950666fe0fd)

> #### Additional Big O Notations

[<ins>**O (n * m): Bilinear Time**</ins>](https://en.wikipedia.org/wiki/Big_O_notation#:~:text=%5B15%5D-,Orders%20of%20common%20functions,-%5Bedit%5D)

An algorithm has **O(n * m)** complexity when its execution time is **proportional to the product of two independent input sizes, n and m**. This typically occurs when processing **two separate data structures** or **iterating over a 2D matrix** where n represents the number of rows and m represents the number of columns.

Unlike **O(n²), where n and m are equal**, in **O(n * m), n and m can be different**, making it more general than quadratic complexity.

_Short Description: This is the time complexity of a nested loop where the inner loop runs m times for each iteration of the outer loop._

**Examples:**

![Screenshot 2025-02-03 at 3 02 54 AM](https://github.com/user-attachments/assets/f98aae80-fad3-4d5e-ab4e-1c9cf2a044cb)

[<ins>**O(n^3): Cubic Time**</ins>](https://en.wikipedia.org/wiki/Big_O_notation#:~:text=%5B15%5D-,Orders%20of%20common%20functions,-%5Bedit%5D)

An algorithm has **O(n³) complexity** when its execution time **grows proportionally to the cube of the input size**. This typically happens when three nested loops iterate over the input, processing each combination of elements.

This means that if the input size increases, the execution time increases at a rate that is proportional to *n* × *n* × *n*, or n3. This type of complexity is typically seen in algorithms that involve three nested loops, where each loop iterates over the input data.

_Short Description: The runtime of the algorithm grows cubically with the input size._

**Examples:**

![Screenshot 2025-02-03 at 3 06 55 AM](https://github.com/user-attachments/assets/15095d8d-7a56-4768-a597-7c7c27ab6aec)

[<ins>**O(c^n) : Exponential Time Complexity**</ins>](https://en.wikipedia.org/wiki/Big_O_notation#:~:text=%5B15%5D-,Orders%20of%20common%20functions,-%5Bedit%5D)

An algorithm has **O(cⁿ)** complexity when its execution time **grows exponentially with the size of the input**, where **c** is a constant greater than 1, and **n** is the size of the input. This type of growth is **extremely fast**, making the algorithm impractical for even relatively small values of **n** (typically, when **n > 20**).

In this case, for each additional unit of **n**, the time taken to execute the algorithm grows **by a constant factor** (c).

The growth rate of **O(c^n)** is extremely steep. For instance, if c=2, then for an input size of 10, the number of operations would be **2^10=1024**. If the input size increases to **20**, it jumps to **2^20=1,048,576**.

_Short Description: The runtime of the algorithm grows exponentially with the input size._

**Examples:**

![Screenshot 2025-02-03 at 3 26 46 AM](https://github.com/user-attachments/assets/7d88de22-fade-4610-8aed-08644efca686)

[<ins>**O(sqrt(n)): Square Root Time Complexity**</ins>](https://en.wikipedia.org/wiki/Big_O_notation#:~:text=%5B15%5D-,Orders%20of%20common%20functions,-%5Bedit%5D)

O(√n), or **square root time complexity**, describes an algorithm whose execution time grows proportionally to the square root of the size of the input data set, denoted as *n*. 

This means that as the input size increases, the time required to complete the algorithm increases at a rate proportional to n^1/2 . Square root time complexity is relatively efficient compared to linear or quadratic complexities, making it suitable for certain types of problems.

_Short Description: The runtime of the algorithm grows as the square root of the input size._

**Examples:**

![Screenshot 2025-02-03 at 3 27 54 AM](https://github.com/user-attachments/assets/03bf69ee-f337-4467-9ca5-f568b9ce5002)

### Data Structures

> #### Arrays

> #### Linked Lists

> #### Stacks

> #### Queues

> #### Trees

> #### Hash Tables

> #### Heaps / Priority Queues

> #### Graphs

> #### Tries

### Algorithms

[🔼 Back to Top](#table-of-contents)
