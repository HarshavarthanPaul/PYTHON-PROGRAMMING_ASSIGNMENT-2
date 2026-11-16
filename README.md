# Python Programming Assignments - Day 1 to Day 4 Design Challenge

This repository contains Python solutions and analyses for a series of programming tasks ranging from basic conditional logic and loops to data validation, string performance optimization, scope/parameter debugging, recursion vs. iteration, and algorithmic redesigns.

---

## Table of Contents
* [Q1: Decisions with Many Boundaries](#q1-decisions-with-many-boundaries)
* [Q2: Loops that Count Attempts](#q2-loops-that-count-attempts)
* [Q3: Engineer a Vehicle Registration Number Validator](#q3-engineer-a-vehicle-registration-number-validator)
* [Q4: Building Long Text: + vs join()](#q4-building-long-text--vs-join)
* [Q5: Functions, Parameters and Scope](#q5-functions-parameters-and-scope)
* [Q6: Recursion and Its Limits](#q6-recursion-and-its-limits)
* [Q7: Diagnose, Redesign and Validate (Design Challenge)](#q7-diagnose-redesign-and-validate-design-challenge)

---

### Q1: Decisions with Many Boundaries
* **Objective:** Analyse subsidy eligibility rules using separate `if` statements versus an `if-elif-else` chain.
* **Key Concepts:** Boundary conditions, chained comparisons, mutual exclusivity.
* **Files:** Included in the codebase under Q1.

---

### Q2: Loops that Count Attempts
* **Objective:** Implement an OTP verification mechanism allowing up to 3 failed attempts while ignoring blank entries using `while` and `for` loops.
* **Key Concepts:** `break`, `continue`, `pass`, and loop-`else` clauses.

---

### Q3: Engineer a Vehicle Registration Number Validator
* **Objective:** Clean, validate, and format vehicle registration numbers using strict string operations and slicing without regular expressions.
* **Key Concepts:** String immutability, slicing, string methods (`isalpha`, `isdigit`, `upper`, `replace`).

---

### Q4: Building Long Text: + vs join()
* **Objective:** Compare the performance of repeated string concatenation (`+=`) versus `str.join()` for large text generation.
* **Key Concepts:** Time complexity ($O(n^2)$ vs $O(n)$), memory overhead, string immutability in CPython.

---

### Q5: Functions, Parameters and Scope
* **Objective:** Diagnose the mutable default argument trap (`order=[]`) in Python functions and explore proper parameter design.
* **Key Concepts:** Default argument evaluation timing, scope rules (local, global, nonlocal), and closures.

---

### Q6: Recursion and Its Limits
* **Objective:** Compute temple step climbing paths using naive recursion and memoisation (`functools.lru_cache`).
* **Key Concepts:** Call trees, redundant work, recursion limits (`sys.setrecursionlimit`), space-time trade-offs.

---

### Q7: Diagnose, Redesign and Validate (Design Challenge)
* **Objective:** Redesign the naive recursive step-climbing solution from Q6 into an optimized iterative approach.
* **Key Concepts:** Bottleneck diagnosis, design objectives, iterative bottom-up dynamic programming ($O(n)$ time, $O(1)$ space).

---

## Usage
Clone the repository and run any script using Python 3.10+:
```bash
python script_name.py
