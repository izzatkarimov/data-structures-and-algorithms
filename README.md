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

> What is a Data Structure?

A data structure is a systematic way of organizing, managing, and storing data to enable efficient processing and retrieval. It defines how data elements relate, how they are accessed, and what operations can be performed on them, and how efficient these operations are.

It can be compared to a container—just as different containers hold items in various ways, a data structure organizes and stores data in a specific manner according to our needs.

> What are the types of data structures?

Data structures are classified into primitive and non-primitive types.
- Primitive Data Structures:
  - Integer, Float, Character, Boolean.
- Non-Primitive Data Structures:
  - Linear: Arrays, Linked Lists, Stacks, Queues.
  - Non-Linear: Trees, Graphs.
  - Hash-Based: Hash Tables.

> What are Primitive Data Structures?

Primitive Data Structures are the fundamental types of data directly supported by a programming language. They store a single value and are the building blocks for more complex data structures.

The core four primitive types are: (int, float, char, bool) and are universal across most languages, but some languages extend the list with types like string, byte, short, long, double, and unsigned int. Whether they are considered primitive depends on the language.

> What are Non-Primitive Data Structures?

Non-primitive data structures are complex structures that store multiple values and are derived from primitive data types. They can store homogeneous or heterogeneous elements, support dynamic size, and perform complex operations.

Common Types of Non-Primitive Data Structures:
- Arrays: Fixed-size collections of homogeneous elements.
- Linked Lists: Chain of nodes, each pointing to the next.
- Stacks: Follow LIFO (Last In First Out) principle.
- Queues: Follow FIFO (First In First Out) principle.
- Trees: Hierarchical structure of nodes (e.g., binary tree, AVL tree).
- Graphs: Non-linear, consisting of vertices and edges.
- Hash Tables: Key-value pairs with constant time access.
- Heaps: Tree-based structures with heap property (max or min).

> What is a Linear Data Structure?

Data structure in which data elements are arranged sequentially or linearly, where each element is attached to its previous and next adjacent elements, is called a linear data structure.

Examples of linear data structures are array, stack, queue, linked list, etc.

> What is a Non-Linear Data Structure?

A non-linear data structure is one where elements do not have a sequential relationship. Instead, elements can have multiple connections to other elements. Non-linear structures are used to represent hierarchical or graph-based relationships, such as trees or graphs.
 
Examples of non-linear data structures are trees and graphs.

> What is a Hash-Based Data Structure?

A hash-based data structure uses a hash function to map keys to indices or addresses, enabling fast retrieval, insertion, and deletion of data. The hash function transforms the key into an integer index, which is used to store the corresponding value. Key examples include hash tables and hash sets.

Simpler Analogy:
A hash-based data structure is like a library system. Imagine each book in the library has a unique ID (the key), and the hash function is like the system that turns that ID into a specific shelf number (the index). When you want to find or add a book, the system quickly tells you the exact shelf number where it is located. This way, you can easily retrieve, add, or remove books without having to search through all the shelves.

Based on this analogy, hash tables would be where books are stored with their details and hash sets would be where only the books themselves are stored without extra details.

> What is a Static Data Structure?

A static data structure has a fixed size at the time of creation and cannot be resized during the program's execution. Memory allocation is predetermined, making it memory-efficient, but lack of flexibility is its key limitation.

An example:
Arrays: Fixed-size, contiguous collection of elements.

*(Note: Arrays can be dynamic in some contexts, but as a static structure, their size is fixed at creation.)*

> What is Dynamic Data Structure?

A dynamic data structure can grow or shrink in size during the program’s execution. Memory is allocated and deallocated as needed, allowing for flexibility in managing elements. This structure is ideal when the number of elements is not fixed.

Examples:
- Linked Lists: Collection of nodes that can grow or shrink dynamically.
- Dynamic Stacks: Stack that resizes as elements are added or removed.
- Dynamic Queues: Queue that resizes dynamically with elements being added/removed.
- Hash Tables: Resizes automatically when a capacity threshold is reached.
