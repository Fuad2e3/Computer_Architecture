# Computer Architecture: Division Algorithms

<p align="center">
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Computer_Architecture-University_Project-blue?style=for-the-badge" alt="Project Type" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License" />
</p>

## 📌 Project Overview

This project implements two fundamental computer architecture algorithms for binary division: **Restoring Division** and **Non-Restoring Division**. Developed as part of the Computer Architecture course at **Green University of Bangladesh**, this tool provides a step-by-step trace of the division process, showing how the Accumulator (A), Dividend (Q), and Divisor (M) change during each step.

## 🚀 Features

- **Restoring Division Algorithm:** A detailed implementation that restores the accumulator if a subtraction result is negative.
- **Non-Restoring Division Algorithm:** An optimized approach that avoids the restoration step by adjusting the operation in the next cycle.
- **Decimal to Binary Conversion:** Automatically handles conversion and sign extension for division operations.
- **Interactive Menu:** Easy-to-use CLI for selecting algorithms and inputting decimal values.
- **Detailed Step-by-Step Trace:** Outputs the state of registers and operations at every iteration.

## 📁 Project Structure

The project is structured simply to focus on the algorithmic implementation:

```text
Computer_Architecture/
├── RestorigXnonRestoring.cpp  # Main source code containing both algorithms
├── .gitattributes             # Git configuration
└── .idea/                     # IDE configuration files
```

### Key Components in `RestorigXnonRestoring.cpp`:
- `restoringDivision()`: Implements the restoring division logic.
- `nonRestoringDivision()`: Implements the non-restoring division logic.
- `decimalToBinary()` & `binaryToDecimal()`: Utility functions for base conversion.
- `add()` & `complement()`: Binary arithmetic helpers.

## 🛠️ Getting Started

### Prerequisites
- A C++ compiler (GCC/MinGW recommended).
- A terminal or IDE (VS Code, Code::Blocks, CLion).

### Installation & Execution
1. Clone the repository:
   ```bash
   git clone https://github.com/fuadk/Computer_Architecture.git
   cd Computer_Architecture
   ```
2. Compile the code:
   ```bash
   g++ RestorigXnonRestoring.cpp -o DivisionAlgo
   ```
3. Run the executable:
   ```bash
   ./DivisionAlgo
   ```


## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="center">
  Developed with ❤️ by <b>Team Softece</b><br>
  <i>Computer Architecture | Green University of Bangladesh</i>
</p>
