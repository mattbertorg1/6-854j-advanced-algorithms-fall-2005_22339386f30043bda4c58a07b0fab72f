---
course_id: 6-854j-advanced-algorithms-fall-2005
layout: course_section
menu:
  leftnav:
    identifier: 04e4324493580cc17a3574a2b6151c59
    name: Syllabus
    weight: 10
title: Syllabus
type: course
uid: 04e4324493580cc17a3574a2b6151c59

---

Course Meeting Times
--------------------

Lectures: 3 sessions / week, 1 hour / session

Course Description
------------------

The need for efficient algorithms arises in nearly every area of computer science. But the type of problem to be solved, the notion of what algorithms are "efficient,'' and even the model of computation can vary widely from area to area. In this second class in algorithms, we will survey many of the techniques that apply broadly in the design of efficient algorithms, and study their application in a wide range of application domains and computational models.

The goal is for the class to be broad rather than deep. Our plan is to touch upon the following areas. This is a tentative list of topics that might be covered in the class; we will select material adaptively based on the background, interests, and rate of progress of the students.

### Data Structures

More Advanced Solutions to Basic Data Structuring Problems: Fibonacci Heaps. Van Emde Boas Priority Queues. Dynamic Data Structures for Graph Connectivity/Reachability.

### Bit Tricks

Word-level Parallelism. Transdichotomous Model. o(n \\log n) Integer Sorting.

### String Algorithms

Rabin-Karp Fingerprinting Algorithm. Suffix Trees.

### Maximum Flows

Augmenting Paths and Push-Relabel Methods. Minimum Cost Flows. Bipartite Matching.

### Linear Programming

Formulation of Problems as Linear Programs. Duality. Simplex, Interior Point, and Ellipsoid Algorithms.

### Online Algorithms

Ski Rental. River Search Problem. Paging. The k-Server Problem. List Ordering and Move-to-Front.

### Approximation Algorithms

One Way of Coping with NP-Hardness. Greedy Approximation Algorithms. Dynamic Programming and Weakly Polynomial-Time Algorithms. Linear Programming Relaxations. Randomized Rounding. Vertex Cover, Wiring, and TSP.

### Fixed-Parameter Algorithms

Another Way of Coping with NP-Hardness. Parameterized Complexity. Kernelization. Vertex Cover. Connections to Approximation.

### Parallel Algorithms

PRAM. Pointer Jumping and Parallel Prefix. Tree Contraction. Divide and Conquer. Randomized Symmetry Breaking. Maximal Independent Set.

### External-Memory Algorithms

Accounting for the Cost of Accessing Data from Slow Memory. Sorting. B-trees. Buffer Trees. Cache-oblivious Algorithms for Matrix Multiplication and Binary Search.

### Computational Geometry

Convex Hull. Line-segment Intersection. Sweep Lines. Voronoi Diagrams. Range Trees. Seidel's Low-dimensional LP Algorithm.

### Streaming Algorithms

Sketching. Distinct and Frequent Elements.

Course Objectives
-----------------

Our hope is that this class will confer:

*   Some familiarity with several of the main thrusts of work in algorithms-sufficient to give you some context for formulating and seeking known solutions to an algorithmic problem.
*   Sufficient background and facility to let you read current research publications in the area of algorithms.
*   A set of tools for design and analysis of new algorithms for new problems that you encounter.

Prerequisites
-------------

We assume that the reader has had an undergraduate class in Algorithms ([6.046J](/courses/6-046j-introduction-to-algorithms-sma-5503-fall-2005)) and some exposure to probability ([6.041](/courses/6-041-probabilistic-systems-analysis-and-applied-probability-spring-2006/) or [6.042J](/courses/6-042j-mathematics-for-computer-science-spring-2015/) are more than sufficient). Complexity Theory ([6.045J](/courses/6-045j-automata-computability-and-complexity-spring-2011)) is a bonus.

Textbook
--------

There are no textbooks covering a majority portion of the material we will be studying in this class. Roughly 20% of the material is covered in the lecture notes from another version of this course, by Prof. Michel Goemans. For a list of other readings, see the [readings]({{< baseurl >}}/sections/readings) section.

Student Grading and Scribing
----------------------------

Students are expected to help scribe a lecture in LaTeX and/or help grade a problem set. This work amounts to 5% of the grade for this course.

Assignments
-----------

There will be weekly problem sets worth a total of 70% of the grade, with collaboration usually allowed.

Exams
-----

There will be no exams in this course.

Project
-------

You will read a new (not yet textbook) algorithm from the recent research literature, and improve upon it via some mixture of the following:

*   Write a description of greater clarity than the original publication, or
*   Devise an improved solution to the problem under consideration, and write up your improvement (with appropriate discussion of the original algorithm).
*   Implement the algorithm in order to study its performance in practice. Considerations include choice of algorithm, design of good tests, interpretation of results, and design and analysis of heuristics for improving performance in practice.

Ideally, the algorithm you choose will be motivated by a computational problem you need to solve. If the project is large, it may be tackled by a group. This project is worth 25% of the grade in the course.

Collaboration Policy
--------------------

Collaboration is encouraged on all aspects of the class, except where explicitly forbidden. Note:

1.  All collaboration (who and what) must be clearly indicated in writing on anything turned in.
2.  Homeworks may be solved collaboratively except as explicitly forbidden, but solutions must be written up independently. Groups should be small enough that each member plays a significant role.
3.  For projects every collaborator must contribute significantly to reading, implementation, and writeup. To allow this, groups should limit their size to 3 unless the project is unusually large.

Grading
-------

| ACTIVITIES | PERCENTAGES |
| --- | --- |
| Problem Sets | 70% |
| Project | 25% |
| Scribing or Grading | 5%