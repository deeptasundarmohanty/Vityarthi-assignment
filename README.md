# 🧮 Number Theory and Mathematical Algorithms Collection

## Project Title: Mathematical Algorithms and Number Theory Explorations

---

## 💡 Overview of the Project

This repository is a collection of Python scripts implementing various fundamental algorithms and concepts from **Number Theory**, **Discrete Mathematics**, and **Elementary Arithmetic**. The project serves as a comprehensive toolkit for classifying numbers, solving modular arithmetic problems, computing number-theoretic functions, and implementing classic sequence generators and factorization methods.

Many scripts include built-in timing and memory checks, allowing for direct performance comparison of different mathematical implementations.

---

## ✨ Features (Implemented Algorithms)

The collection includes implementations for the following mathematical concepts, categorized by function:

### I. Primality and Factorization
* **Primality Testing:** Miller-Rabin probabilistic test.
* **Prime Classification:** Mersenne Prime Check, Fibonacci Prime Check.
* **Factorization:** Pollard's Rho algorithm for finding factors, Prime Factorization list, Counting Distinct Prime Factors.
* **Divisor Functions:** Counting the number of divisors $\tau(n)$, Sum of Divisors $\sigma(n)$.

### II. Modular Arithmetic
* **Congruence Solver:** Chinese Remainder Theorem (CRT) Solver.
* **Inverses:** Modular Multiplicative Inverse using the Extended Euclidean Algorithm.
* **Properties:** Quadratic Residue Check, Order Modulo $n$.
* **Exponentiation:** Efficient Modular Exponentiation (Binary Exponentiation).

### III. Number Classification & Sequences
* **Classification:** Checks for Harshad (Niven), Automorphic, Pronic, Abundant, Deficient, Perfect Power, Highly Composite, and Carmichael numbers.
* **Number Pairs:** Checks for Twin Primes and Amicable Numbers.
* **Sequences:** Lucas Numbers Generator, Collatz Sequence Length, Polygonal Numbers.

### IV. Number Theoretic Functions
* **Euler's Totient Function** ($\phi(n)$).
* **Möbius Function** ($\mu(n)$).
* **Partition Function** ($p(n)$).
* **Prime-Counting Function** ($\pi(n)$) approximation.
* **Aliquot Sum** (Sum of proper divisors).

### V. Digit Arithmetic
* **Digit Operations:** Factorial, Palindrome Check, Mean of Digits, Digital Root, Multiplicative Persistence.

---

## 🛠️ Technologies/Tools Used

* **Language:** Python 3.x
* **Libraries:** `time`, `sys`, `resource`, `math`, `random` (Standard Python Library Modules)
* **External Tools (in some scripts):** `os`, `psutil` (for advanced memory usage reporting)

---

## ⚙️ Steps to Install & Run the Project

Since this project consists of individual Python files using only standard libraries, no formal installation is required.

1.  **Clone or Download:** Download the desired Python file (e.g., `Pollard Rho.py`).
2.  **Ensure Python is Installed:** Make sure you have Python 3.x installed on your system.
3.  **Run from Terminal:** Execute the script using the Python interpreter:

    ```bash
    python <filename>.py
    ```
    *Example:*
    ```bash
    python Chinese\ Remainder\ Theorem\ Solver.py
    ```

---

## 🧪 Instructions for Testing

1.  **Identify Input:** Open the desired script. Most files contain a `# Test` section or `input()` prompts near the end defining the default test case (e.g., `result = is_quadratic_residue(2, 7)` in `Quadratic Residue Check.py`).
2.  **Run Tests:** Execute the script.
3.  **Verify Output:** Compare the printed **Result** against known mathematical values for the given input. The scripts also report:
    * **Runtime:** The execution time in seconds.
    * **Memory:** The memory usage in bytes.

*Example Test Case Verification:*
| Script | Test Input | Expected Output | Actual Result (from screenshots) |
| :--- | :--- | :--- | :--- |
| `Partition Function.py` | $n=10$ | $p(10) = 42$ | 42 |
| `Modular Multiplicative Inverse.py` | $3 \pmod{26}$ | 9 | 9 |
| `Collatz Sequence Length.py` | $n=27$ | 112 | 112 |
| `Carmichael Number Check.py` | 561 | True | True |
