# Propositional Logic Expression Analyzer 🧮

> **CS-101 Discrete Mathematics Project** > **University of Engineering and Technology, Lahore**

[cite_start]An automated C++ tool designed to generate truth tables, evaluate complex logical expressions, and verify logical equivalence between statements[cite: 1, 10, 14, 16].

---

## 📖 About The Project

This program bridges the gap between Discrete Mathematics theory and practical computer science application. [cite_start]It automates the tedious process of manually creating truth tables, allowing users to instantly visualize how different logical inputs affect the final result of an expression[cite: 22, 97, 98].

### Key Capabilities
* [cite_start]**Truth Table Generation:** Automatically calculates $2^n$ rows for up to `N` variables[cite: 31, 105].
* [cite_start]**Logic Evaluation:** Uses a custom evaluation engine (Shunting Yard Algorithm) to solve complex boolean algebra[cite: 32, 102].
* [cite_start]**Equivalence Checker:** Compares two separate expressions side-by-side to prove if they are logically identical[cite: 37, 108].
* [cite_start]**Status Detection:** Identifies if an expression is a **Tautology** (Always True), **Contradiction** (Always False), or **Contingency** (Mixed)[cite: 38].

---

## ⚙️ Features

* [cite_start]**Dual Modes:** Support for **Single Expression** analysis and **Double Expression** comparison[cite: 17].
* [cite_start]**Smart Variable Detection:** Automatically scans input strings and identifies unique variables (e.g., A, B, C)[cite: 30, 56].
* [cite_start]**GUI-like Console:** Features a structured User Interface with ASCII art headers, borders, and centered text using `windows.h`[cite: 39, 111].
* [cite_start]**Robust Validation:** Checks for balanced parentheses and invalid characters before processing[cite: 44].

---

## ⌨️ Supported Syntax & Operators

[cite_start]The analyzer supports standard discrete math operators mapped to keyboard characters[cite: 35]:

| Operator Name | Math Symbol | Input Syntax |
| :--- | :---: | :---: |
| **Negation (NOT)** | $\neg p$ | `!` or `~` |
| **Conjunction (AND)** | $p \land q$ | `&` |
| **Disjunction (OR)** | $p \lor q$ | `\|` |
| **Exclusive OR (XOR)** | $p \oplus q$ | `^` |
| **Implication** | $p \rightarrow q$ | `>` |
| **Biconditional** | $p \leftrightarrow q$ | `=` |
| **Grouping** | $(p \land q)$ | `( )` |

> [cite_start]**Note:** The program treats Implication ($P \rightarrow Q$) as logically equivalent to $\neg P \lor Q$[cite: 103].

---

## 🚀 How to Run

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/RehanIlyas-dev/Logic-Analyzer.git](https://github.com/RehanIlyas-dev/Logic-Analyzer.git)
    ```
2.  **Compile the Code:**
    Ensure you have a C++ compiler (like g++).
    ```bash
    g++ main.cpp -o logic_analyzer
    ```
3.  **Run the Executable:**
    ```bash
    ./logic_analyzer
    ```
4.  **Usage:**
    * Select **Option 1** for Single Expression Analysis.
    * Select **Option 2** for Equivalence Checking.
    * [cite_start]Select **Option 3** for the User Manual[cite: 46].

---

## 📸 Screenshots

**Single Expression Analysis:**
*Generates a full truth table and identifies the logical state (e.g., Contingency).*
![Single Expression Mode](https://via.placeholder.com/800x400?text=Place+Your+Single+Expression+Screenshot+Here)

**Double Expression Mode:**
*Compares R1 and R2 columns to verify equivalence.*
![Double Expression Mode](https://via.placeholder.com/800x400?text=Place+Your+Double+Expression+Screenshot+Here)

---

## 🔮 Future Enhancements
[cite_start]We plan to improve this project with the following features[cite: 124]:
* [cite_start][ ] **GUI Development:** Moving from Console to a Windows Form/Qt application[cite: 126].
* [cite_start][ ] **Karnaugh Maps:** Automated K-Map generation for simplification[cite: 127].
* [cite_start][ ] **File Export:** Saving generated tables to `.csv` or `.txt` files[cite: 129].
* [cite_start][ ] **Step-by-Step Solver:** Displaying intermediate evaluation steps[cite: 127].

---

## 👥 Authors

* [cite_start]**Muhammad Rehan Ilyas** (2025-CS-65) - *Developer* [cite: 5]
* [cite_start]**Muhammad Hassan Rauf** (2025-CS-106) - *Developer* [cite: 6]

[cite_start]**Submitted To:** Sir Waqas Ali [cite: 8]

---

## 📚 References
* [cite_start]*Discrete Mathematics and Its Applications*, 8th Edition - K. H. Rosen[cite: 114].
* [cite_start]Microsoft Documentation (Windows Console Functions)[cite: 117].
* [cite_start]C++ Standard Library Documentation[cite: 119].
