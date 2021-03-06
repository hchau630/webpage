---
layout: page
title: Abstract Algebra and Real Analysis Self-Study Guide
permalink: /study_guide/
---

This is a self-study guide for introductory upper-division mathematics that I am currently compiling for my friend. 

Textbooks:
* Fraleigh – A First Course in Abstract Algebra, 7th edition
* Rudin - Principles of Mathematical Analysis, 3rd edition

How to use this study guide:

Each lesson covers the material of around one week of lecture for a typical course. The algebra sequence is easier than the analysis sequence. Under each lesson, the chapters covered are given, and for each chapter the most relevant reading material is given. 5.14, for example, means the reader should understand Definition/Theorem/Corollary 5.14; "Roots of Unity", for example, means the reader should understand the section "Roots of Unity" in the book. The suggested reading material aims to highlight the most important parts of the text so that a lazy person can read as few as possible while being able to grasp the main takeaways of the chapter. Doing the exercises, like all math courses, are important, so the reader should aim to do most, if not all, of them. For the abstract algebra section, I selected exercises that are more proof-based than computational as this study guide is designed for a person who has a rigorous background in proof-based mathematics.

Lessons or sections with an asterisk * means that while the topic is important in its own right, it is not essential to later discussion, and thus may be skipped if the reader inclines to do so. The algebra and analysis sequences can be studied independently.

## Abstract Algebra
<body>
<button type="button" class="collapsible">Lesson 1: Introduction to Group Theory</button>
<div class="content" markdown="1">
* Chapter 0: Sets and Relations
    1. 0.7 - 0.9
	2. Cardinality
	3. 0.16 - 0.18, 0.20, 0.22
	>Exercises: 18, 19, 29  
	>Extra exercise: Define a relation ~ on \\(\mathbb{Z}\\) by x ~ y iff x = y + n for n in \\(\mathbb{Z}\\). Show that ~ is an equivalence relation, and that there is a bijection between \\(\mathbb{Z}\\)/~, the set of all equivalence classes of \\(\mathbb{Z}\\) arising from ~, and the circle \\(S^1\\)
* Chapter 1: Introduction and Examples
	1. Roots of Unity
* Chapter 2: Binary Operations
	1. 2.1, 2.4
	2. Tables
	>Exercises: 37
* Chapter 3: Isomorphic Binary Structures
	1. Definition of Binary Structures
	2. 3.7
	3. How to Show that Binary Structures are Isomorphic
	>Exercises: 17
* Chapter 4: Groups
	1. 4.1, 4.2, 4.3, 4.6, 4.8, 4.10, 4.12, 4.13, the part about GL(n, R)
	2. 4.15 - 4.18, and the remarks following 4.18
	>Exercises: 2, 9, 20, 31, 32, 41
</div>
<button type="button" class="collapsible">Lesson 2: Subgroups, Cyclic Groups, and Generating Sets</button>
<div class="content" markdown="1">
* Chapter 5: Subgroups
	1. Notation and Terminology
	2. 5.3 - 5.5, 5.9 (and the subgroup diagram under it), 5.14, 5.16
	3. 5.17 - 5.21, 5.23
	>Exercises: 11, 12, 13 (this is the orthogonal group, \\(O(n)\\). Prove or disprove that this is same as the one in exercise 12), 45 (very useful!), 49, 52, 54
* Chapter 6: Cyclic Groups
	1. The stuff before 6.1, 6.1, 6.3, 6.6, 6.7, 6.8
	2. 6.10, 6.14, 6.16
	>Exercises: 44, 14, 15, 45, 56
* Chapter 7: Generating Sets and Cayley Digraphs
	1. Stuff before 7.1, 7.1, 7.3 - 7.6
	>Exercises: 19
</div>
<button type="button" class="collapsible">*Lesson 3: More examples of groups: Permutation Groups, Dihedral Groups, Alternating Groups, Direct Sum of Groups; Classification of Finitely Generated Abelian Groups</button>
<div class="content" markdown="1">
* Chapter 8: Groups of Permutations
	1. 8.3 - 8.6, stuff about dihedral group before 8.10
	2. 8.14 - 8.16
	>Exercises: 1, 46, 49, 52
* Chapter 9: Orbits, Cycles, and the Alternating Groups
	1. 9.1, 9.6, 9.8, 9.11, 9.12, 9.15 (proof 1 suffices and is far more elegant and illuminating than proof 2), 9.18, 9.20, 9.21
	>Exercises: 7, 23e, 29, 34, 36
* Chapter 11: Direct Products and Finitely Generated Abelian Groups
	1. 11.1 - 11.10, section following 11.11
	2. 11.12 - 11.17
	>Exercises: 9, 46, 50, 51, 52, 54
</div>
</body>

## Real Analysis
<body>
<button type="button" class="collapsible">Lesson 1: The Real Numbers and the Least Upper Bound Property; Complex Numbers</button>
<div class="content" markdown="1">
* Chapter 1: The Real and Complex Number Systems
	1. 1.5 - 1.11
	2. 1.12, 1.17 (I recommend not dwelling on the field axioms too much as the algebra sequence will introduce you to fields in great detail. Moreover, for the theorems about the properties of fields, it is not too important to read through the proofs as they are not very illuminating and not central to later discussion. Verify one or two of them, if you want, to gain a feel of the field axioms)
	3. 1.19, read construction of \\(\mathbb{R}\\) in the appendix at the end of chapter 1, and go through a few proofs of the properties of \\(\mathbb{R}\\) to understand why this construction works.
	4. 1.20 - 1.21 (Again, the proofs of the theorems are not that illuminating. The main point is to understand how the least upper bound property is used in the proofs.)
	5. 1.23
	6. 1.24, 1.25, 1.32, 1.35 (Again, the proofs for the various properties of complex numbers is not that important.)
	7. 1.36 - 1.38
	>Exercises: Rudin chapter 1: 3, 5, 6, 8, 13; Enderton chapter 5: 15, 16
</div>
<button type="button" class="collapsible">Lesson 2: Topological Spaces, Metric spaces, and Completenes</button>
<div class="content" markdown="1">

* Chapter 2
</body>