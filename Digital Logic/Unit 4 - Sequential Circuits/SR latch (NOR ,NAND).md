# SR Latch (Set-Reset Latch)

## Overview
An **SR Latch** (Set-Reset Latch) is a fundamental sequential logic circuit used to store a single bit of information. It has two primary inputs and outputs:

- **S (Set)** – Sets the output to **1**.
- **R (Reset)** – Resets the output to **0**.
- **Q** – The current state (output).
- **Q' (Q bar)** – The complement of **Q** (opposite state).

---

## Types of SR Latch

### 1. SR Latch using NOR Gates

| S | R | Q (Next State) | Q' (Next State) |
|---|---|--------------|--------------|
| 0 | 0 | No Change    | No Change    |
| 0 | 1 | 0           | 1            |
| 1 | 0 | 1           | 0            |
| 1 | 1 | **Invalid**  | **Invalid**  |

- **Implementation**: Constructed using two NOR gates, where each gate's output is connected to the other's input.
- **Invalid Condition**: When **S = 1** and **R = 1**, both outputs **Q** and **Q'** become **0**, violating the rule that they must always be complements.

[Click me for Diagram and conclusion](./assets/SR%20latch%20(using%20NOR%20gate).pdf)

---

### 2. SR Latch using NAND Gates

| S | R | Q (Next State) | Q' (Next State) |
|---|---|--------------|--------------|
| 1 | 1 | No Change    | No Change    |
| 1 | 0 | 0           | 1            |
| 0 | 1 | 1           | 0            |
| 0 | 0 | **Invalid**  | **Invalid**  |

- **Implementation**: Constructed using two NAND gates, where each gate's output is fed into the other's input.
- **Behavior**:
  - Unlike NOR-based latches, the **inactive** state is **S = 1, R = 1**, which results in no change in output.
  - The invalid condition happens when **S = 0** and **R = 0**, which forces **Q = 1** and **Q' = 1**, violating complementarity.

[Click me for Diagram and conclusion](./assets/SR%20latch%20(using%20NAND%20gate).pdf)
---

## Applications of SR Latch
- Used in **memory storage elements**.
- Forms the **basis of flip-flops** (e.g., D Flip-Flop, JK Flip-Flop).
- Applied in **control systems and sequential circuits**.

---

This document serves as a fundamental reference for understanding the **SR Latch**. Feel free to contribute and enhance this repository!

