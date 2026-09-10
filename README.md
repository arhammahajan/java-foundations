# java-foundations

A retrospective archive of Java source code and BlueJ projects developed during 9th and 10th grade (ICSE Computer Applications curriculum).

This repository documents early programming milestones—from initial procedural logic, conditional branching, and number theory to object-oriented programming (OOP), data structures (1D arrays, sorting, searching), and ICSE board examination preparation.

---

## 📂 Repository Layout

```
java-foundations/
├── arham_grd-9/     # Grade 9 introductory Java programs & BlueJ package
└── arham_grd-10/    # Grade 10 advanced topics, array algorithms & ICSE Board prep
```

Both directories are structured as standalone **BlueJ** packages containing `package.bluej` configuration files, compiled bytecode, BlueJ context files (`.ctxt`), and original `.java` source files.

---

## 📚 Topic & Code Reference

### 1. Object-Oriented Programming (OOP) & Class Design
Core concepts of encapsulation, constructors, method overloading, access modifiers, and parameter passing:
- [arham_grd-10/Employee.java](arham_grd-10/Employee.java) — Class design featuring parameterized constructors, conditional bonus calculations, and encapsulated display methods.
- [arham_grd-10/Pay.java](arham_grd-10/Pay.java) — Salary computation class managing basic pay, tax deductions, and net computation.
- [arham_grd-10/Atransport.java](arham_grd-10/Atransport.java) — Parcel logistics class calculating tiered slab rates and applying surcharges.
- [arham_grd-10/cuboid.java](arham_grd-10/cuboid.java) — Geometric modeling class evaluating surface areas and volume with instance state.
- [arham_grd-10/cbyR.java](arham_grd-10/cbyR.java) — Demonstration of Call-by-Reference object semantics in Java.
- [arham_grd-9/employee.java](arham_grd-9/employee.java) & [arham_grd-9/employee2.java](arham_grd-9/employee2.java) — Early Grade 9 implementations of class-level state and behaviors.

### 2. Data Structures, Searching & Sorting
Fundamental algorithms for array manipulation, traversal, and ordering:
- [arham_grd-10/sort.java](arham_grd-10/sort.java) — Bubble sort implementation for ascending numerical ordering.
- [arham_grd-10/searching_programs.java](arham_grd-10/searching_programs.java) — Search algorithms exploring linear and binary search techniques.
- [arham_grd-10/arrays.java](arham_grd-10/arrays.java) — 1D array operations: mean, median, min/max element detection, and aggregations.
- [arham_grd-10/arrdataops1.java](arham_grd-10/arrdataops1.java) & [arham_grd-10/arrayops3.java](arham_grd-10/arrayops3.java) — Multi-operation array processing suites.
- [arham_grd-10/ascendingOrder.java](arham_grd-10/ascendingOrder.java) — Array sorting and sequence validation.

### 3. String Processing & Character Logic
Techniques for tokenization, ASCII manipulation, and character analysis:
- [arham_grd-10/string_ops_1.java](arham_grd-10/string_ops_1.java) — Parsing strings for embedded digits, computing digit sums (`sumOfDigitsInString`), and multi-digit number extraction.
- [arham_grd-10/ascii.java](arham_grd-10/ascii.java) — Character encoding manipulation, case conversions, and ASCII code evaluation.

### 4. Mathematical Algorithms & Number Theory
Classic computer science numerical challenges:
- [arham_grd-9/Armstrong.java](arham_grd-9/Armstrong.java) — Digit extraction and Armstrong number validation ($n = \sum d_i^3$).
- [arham_grd-9/Palindrome.java](arham_grd-9/Palindrome.java) — Digit reversal and palindrome verification.
- [arham_grd-9/PrimeNumber.java](arham_grd-9/PrimeNumber.java) — Prime number testing via divisibility bounds.
- [arham_grd-10/factorial.java](arham_grd-10/factorial.java) & [arham_grd-10/binomial.java](arham_grd-10/binomial.java) — Factorial evaluations and binomial coefficient computations.
- [arham_grd-10/oswaal_programs.java](arham_grd-10/oswaal_programs.java) — Solutions to special number problems (e.g., special two-digit numbers where sum + product equals the number).
- [arham_grd-10/series.java](arham_grd-10/series.java) & [arham_grd-10/newSeries.java](arham_grd-10/newSeries.java) — Mathematical series summations and sequences.
- [arham_grd-10/swapNumber.java](arham_grd-10/swapNumber.java) — Variable value swapping logic.

### 5. Loop Patterns & Control Structures
Nested looping constructs and formatted console output:
- [arham_grd-10/loopPatternsRev.java](arham_grd-10/loopPatternsRev.java) — Triangular and matrix pattern generation using nested `for` loops.
- [arham_grd-10/pre2_finsl.java](arham_grd-10/pre2_finsl.java) — Board examination pattern questions combining alternating character sequences (`*`, `#`) and inverted numerical pyramids.
- [arham_grd-9/pg103.java](arham_grd-9/pg103.java) & [arham_grd-9/Bill.java](arham_grd-9/Bill.java) — Tiered conditional logic, discount calculations, and commercial billing rules.

### 6. ICSE Board Examination Projects & Revisions
Comprehensive revision sets, past board exam question solutions, and coursework submissions:
- [arham_grd-10/ArhamPriojectPDFA.java](arham_grd-10/ArhamPriojectPDFA.java) — Complete Grade 10 ICSE Computer Applications project assignment encompassing electricity billing slabs, mathematical series, number properties, and string utilities.
- [arham_grd-10/prelim_1_1st_rev.java](arham_grd-10/prelim_1_1st_rev.java) & [arham_grd-10/prelim_2_prep.java](arham_grd-10/prelim_2_prep.java) — Prelim revision suites covering common factors, common multiples, and digit transformations.
- [arham_grd-10/sir_codes.java](arham_grd-10/sir_codes.java) & [arham_grd-10/sirSts4.java](arham_grd-10/sirSts4.java) — Classroom challenge exercises and school test practice.

---

## 🛠️ Environment & Tools

- **Language:** Java (JDK 8 / 11+)
- **IDE:** [BlueJ](https://www.bluej.org/) (Interactive Java environment designed for teaching OOP)
- **Standard Libraries:** `java.util.Scanner`, `java.lang.Math`

### Running the Code

#### Via BlueJ (Recommended):
1. Launch BlueJ.
2. Select **Project** > **Open Project...**
3. Open either `arham_grd-9` or `arham_grd-10`.
4. Right-click on any class rectangle to invoke static methods or instantiate class objects interactively.

#### Via CLI:
Compile and run any standalone class with standard JDK tools:
```bash
# Example: Running ArhamPriojectPDFA
cd arham_grd-10
javac ArhamPriojectPDFA.java
java ArhamPriojectPDFA
```

---

## 📜 Historical Note

This repository reflects foundational coursework written between 9th and 10th grade during school ICSE Computer Applications studies. The code illustrates early problem-solving exploration, BlueJ's direct-method invocation workflows, and progression toward structured object-oriented programming.
