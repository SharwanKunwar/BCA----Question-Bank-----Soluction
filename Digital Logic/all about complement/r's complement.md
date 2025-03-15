# r's Complement

## Definition
The **r's complement** of a number in base **r** is obtained by subtracting the number from the smallest power of **r** that is greater than the number.

## Formula
For an **n-digit** number **N** in base **r**:

```
r’s complement = rⁿ - N
```

## Example : find the 10's complement where, N = 725.

**N = 725** (3-digit number)
<br>
**n = 3**
<br>
**r = 10**
<br>
```
We know that,

  rⁿ - N
= 10³ - 725
= 1000 - 725 
= 275
```
So, the **10’s complement of 725 is 275**.

## Example: find the 2's complement of 0101
In **binary (Base 2)**, the **2’s complement** is commonly used for representing signed numbers. It is found by:
1. Inverting the bits.
2. Adding 1 to the result.

Example for **N = 0101 (5 in decimal)**:
```
Step 1: Invert bits → 1010
Step 2: Add 1 → 1011 (2's complement of 0101)
