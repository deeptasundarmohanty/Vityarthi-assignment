 Project Statement: Computational Number Theory Library

1. ❓ Problem Statement

The field of Number Theory and Discrete Mathematics often requires specialized, efficient, and mathematically accurate algorithms for computation, verification, and analysis (e.g., primality testing, factorization, modular arithmetic, and classifying special numbers). Existing general-purpose libraries may lack specific, clear implementations for these diverse concepts, making educational validation and dedicated computational tasks cumbersome. The challenge is to consolidate these fragmented mathematical tools into a single, accessible, and well-documented Python library.

2. 🎯 Scope of the Project

The scope of this project is to create a comprehensive library of mathematical functions in Python, primarily focused on Number Theory and algorithmic Discrete Mathematics. The project aims to provide:

Foundational Implementations: Clear, direct code for core concepts like Modular Inverse, CRT, and Divisor Sums.

Advanced Algorithms: Functionality for complex tasks such as Pollard's Rho factorization, Miller-Rabin primality testing, and Partition Function calculation.

Special Number Classification: Tools to test properties of integers (e.g., Harshad, Automorphic, Abundant, Perfect Powers).

Performance Inclusion: Built-in logging of runtime and memory usage to compare algorithm efficiency.

The project is limited to Python scripts using only standard or commonly available mathematical libraries (math, random, psutil) and does not include external web integrations or advanced UI.

3. 🧑‍💻 Target Users

The primary users of this computational library include:

Students and Educators: For learning and verifying mathematical concepts through runnable code examples.

Researchers/Mathematicians: To quickly implement and test fundamental numerical algorithms for theoretical work.

Software Developers: For incorporating specific Number Theory utilities into larger computational or cryptographic applications.

Hobbyists/Data Scientists: Anyone needing fast, precise mathematical functions for numerical experiments or challenges.

4. ✨ High-Level Features

Core Arithmetic & Modulo Operations: Modular exponentiation, multiplicative inverse, and solutions to systems of congruences (CRT).

Primality Testing & Factorization: Efficient, robust primality tests (Miller-Rabin) and integer factorization (Pollard Rho), alongside specialized prime checks (Twin, Mersenne).

Mathematical Function Library: Implementations of classic functions like Euler's Totient ($\varphi$), Möbius ($\mu$), Divisor Sum ($\sigma$), and the Prime-Counting Function ($\pi$).

Sequence Generation & Analysis: Tools for generating and analyzing known integer sequences (Lucas, Collatz, Partition function, Polygonal numbers).

Number Property Classifiers: Functions to identify and classify special numbers based on their divisor and digit properties (e.g., Perfect, Amicable, Harshad, Abundant).

Performance Benchmarking: Built-in boilerplate to log execution time and memory consumption for easy algorithm comparison.
