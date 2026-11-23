# Tier 3 – Practical Exercise: Input → Processing → Output

## Project: The Simple Calculator

### 1. Introduction

The purpose of this exercise is to understand how a computer program receives information, processes it, and produces a result.

The three fundamental stages are:

1. Input
2. Processing
3. Output

### 2. Addition

**Input:**
- number_1 = 20
- number_2 = 5

**Processing:**

20 + 5

**Output:**

25

### 3. Subtraction

**Input:**
- number_1 = 20
- number_2 = 5

**Processing:**

20 - 5

**Output:**

15

### 4. Multiplication

**Input:**
- number_1 = 20
- number_2 = 5

**Processing:**

20 × 5

**Output:**

100

### 5. Division

**Input:**
- number_1 = 20
- number_2 = 5

**Processing:**

20 ÷ 5

**Output:**

4

### 6. Input → Processing → Output Model

The calculator follows this process:

**INPUT**
- Receive the first number (20).
- Receive the second number (5).

↓

**PROCESSING**
- Select the mathematical operation.
- Perform the selected calculation.

↓

**OUTPUT**
- Display the calculated result.

### 7. Reasoning Challenge: Division by Zero

Consider the following values:

- number_1 = 20
- number_2 = 0

**Processing:**

20 ÷ 0

**Problem:**

Division by zero is mathematically undefined. A program cannot perform this calculation normally.

**Expected behavior:**

1. Receive the two numbers.
2. Check whether the second number is zero.
3. If the second number is zero, display an error message.
4. Do not perform the division.
5. If the second number is not zero, perform the division and display the result.

**Expected output:**

```text
Error: Cannot divide by zero.
```

### 8. Conclusion

This exercise demonstrates the three fundamental stages of programming:

- **Input:** The program receives information from the user.
- **Processing:** The program performs an operation on the information.
- **Output:** The program displays the result.

A well-designed program should also handle invalid inputs and situations where an operation cannot be completed.

**Key Lesson:**

INPUT → PROCESSING → OUTPUT

Every basic computer program follows this fundamental model.