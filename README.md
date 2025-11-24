Comprehensive Library of Number Theory & Computational Algorithms in
Python

Comprehensive Library of Number Theory & Computational Algorithms in
Python 💡 Overview of the Project This repository is an extensive
collection of Python implementations for algorithms across Number
Theory, Discrete Mathematics, and computational analysis. It provides
foundational and advanced functions for tasks ranging from primality
testing and factorization to sequence generation and various operations
on special number types. Each script is self-contained and demonstrates
its functionality, often including basic runtime and memory usage
metrics.

✨ Features The project's algorithms are organized into the following
major categories: 1. Primes, Factorization, and Modular Arithmetic
Miller-Rabin Test.py: Probabilistic primality test for efficiently
checking if a large number is prime. Fibonacci Prime Check.py: Checks if
a number is a Fibonacci number and a prime number. twin_prime.py: Finds
all twin prime pairs up to a specified limit. mersenne_prime.py: Checks
if a number of the form 2\^p - 1 is a Mersenne prime. Pollard Rho.py:
Implements Pollard's `\rho `{=tex}algorithm for fast integer
factorization. prime_factors: Returns the list of all prime factors of a
number. distinct_prime_no.py: Counts the number of distinct prime
factors of an integer. prime_pi: Approximates the Prime-Counting
function (`\pi`{=tex}(n)). Modular Multiplicative Inverse.py: Computes
the modular multiplicative inverse using the Extended Euclidean
Algorithm. mod_exp: Efficiently calculates Modular Exponentiation
`\left`{=tex}(`\text{base}`{=tex}\^{`\text{exponent}`{=tex}}
`\pmod{\text{modulus}}`{=tex}`\right`{=tex}). Order Mod.py: Calculates
the multiplicative order of a modulo n. Chinese Remainder Theorem
Solver.py: Solves a system of linear congruences using the CRT.
Carmichael Number Check.py: Checks if a composite number is a Carmichael
number. Quadratic Residue Check.py: Checks for quadratic residues using
Euler's Criterion. 2. Divisor and Multiplicative Functions
count_divisors.py: Efficiently counts the number of divisors of an
integer n. divisor_sum: Calculates the Divisor Sum function
(`\sigma`{=tex}(n)). aliquot_sum: Returns the sum of all proper divisors
(divisors less than n). euler_phi: Calculates Euler's Totient Function
(`\varphi`{=tex}(n)). mobius: Calculates the Möbius function
(`\mu`{=tex}(n)). 3. Special Number Types & Properties Perfect Powers
Check.py: Determines if n is a perfect power. prime_power.py: Checks if
an integer n is a prime power (n = p\^k). is_highly_composite: Checks if
n is a highly composite number. is_abundant: Checks for abundant
numbers. is_deficient: Checks for deficient numbers. are_amicable:
Checks for amicable numbers. is_pronic: Checks for pronic (oblong)
numbers (n = i(i+1)). is_automorphic: Checks if a number's square ends
with the number itself (Automorphic numbers). is_harshad: Checks for
Harshad (Niven) numbers. 4. Sequences and Digit Operations Lucas Numbers
Generator.py: Generates the Lucas sequence. Collatz Sequence Length.py:
Computes the length of the Collatz sequence. Partition Function.py:
Calculates the value of the Partition Function p(n). Polygonal
Numbers.py: Computes the n-th Polygonal Number. factorial: Calculates
the factorial (n!). is_palindrome: Checks if a number is a palindrome.
mean_of_digits: Calculates the average of all digits in a number.
digital_root: Calculates the digital root. multiplicative_persistence:
Counts the steps until a number's digits multiply to a single digit.
Zeta Approx.py: Approximates the Riemann Zeta function `\zeta`{=tex}(s).

🛠️ Technologies/Tools Used

⚙️ Steps to Install & Run the Project Prerequisites Python 3.x: Ensure
you have a recent version of Python installed. psutil (Required for
memory monitoring in some files): Bash pip install psutil Installation &
Setup Clone the repository or gather files: Place all the provided .py
files into a single project directory. Navigate to the project
directory: Bash cd \[your-project-name\] Running a Script To execute any
of the algorithms, run the corresponding Python file from your terminal:
Bash python "prime_power.py" \# Or python "digital_root.py" Many scripts
contain an internal test case or prompt for user input. The script will
execute and output the result, along with performance metrics where
included.

✅ Instructions for Testing Each script includes a built-in test case or
uses a basic input() function for testing. Run the scripts: Execute the
individual Python files. Verify the output: Check the printed Result
against the known correct mathematical output for the test case
provided. For example, running factorial.py with input 5 should output
FACTORIAL: 120. Modify and Test: For thorough testing, change the input
variables inside the scripts (e.g., change result = order_mod(2, 7) to
result = order_mod(3, 10) in Order Mod.py) to test different values.
