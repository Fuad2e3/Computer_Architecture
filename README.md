<div align="center">

# 💻 Computer Architecture: Binary Division Algorithms
### **Hardware ALU Simulation: Restoring & Non-Restoring Division**

[![Language](https://img.shields.io/badge/Language-C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)](https://isocpp.org/)
[![Course](https://img.shields.io/badge/Course-Computer_Architecture-blue?style=for-the-badge)](https://green.edu.bd)
[![Focus](https://img.shields.io/badge/Focus-ALU_Arithmetic-orange?style=for-the-badge)](RestorigXnonRestoring.cpp)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

**Low-level ALU arithmetic simulation tracing binary register states (Accumulator A, Dividend Q, Divisor M).**

---

[Explore Algorithms](#-features) • [Code Architecture](#-project-structure) • [License](#-license)

</div>

---

## 📌 Project Overview
Developed as part of the Computer Architecture coursework at **Green University of Bangladesh**, this project implements two fundamental hardware-level binary integer division algorithms: **Restoring Division** and **Non-Restoring Division**. It provides a cycle-by-cycle hardware trace of how the Accumulator register ($A$), Dividend register ($Q$), and Divisor register ($M$) mutate during each ALU clock cycle.

---

## 🚀 Key Features

- ⚙️ **Restoring Division Algorithm:** Hardware trace that evaluates partial remainders and executes an automatic accumulator restoration step when intermediate subtraction yields a negative result.
- ⚡ **Non-Restoring Division Algorithm:** Optimized high-speed arithmetic eliminating the restoration penalty cycle by shifting the partial remainder and adding/subtracting conditionally.
- 🔢 **Binary & 2's Complement Converters:** End-to-end base-10 to signed binary converters handling register bit-width alignment.
- 🖥️ **Interactive Terminal CLI:** Clean prompt allowing users to enter arbitrary dividend and divisor pairs and inspect step-by-step register states.

---

## 📁 Project Structure

```text
Computer_Architecture/
├── RestorigXnonRestoring.cpp   # Core C++ implementation of division routines
├── LICENSE                     # MIT License
└── README.md                   # System documentation & usage guide
```

### Key Modules in `RestorigXnonRestoring.cpp`:
- `restoringDivision()`: Implements cycle-level restoring logic with register state dumps.
- `nonRestoringDivision()`: Implements cycle-level non-restoring conditional addition/subtraction.
- `decimalToBinary()` & `binaryToDecimal()`: Bit-vector conversion utilities.
- `add()` & `complement()`: Binary ripple-carry addition and two's complement generators.

---

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.

<div align="center">

**Developed ❤️ by Softece**

</div>
