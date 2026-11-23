# Tier 4 – Conceptual Challenge: Data Translator

## Project: Understanding Computer Data Representation

### 1. Introduction

Computers need information to be represented in a format they can understand, store, and process.

In this exercise, we will identify different types of customer information and explain how computers represent them.

### 2. Identify the Data

Consider the following customer information:

- Customer name: Victor
- Age: 30
- Account balance: 150000.50
- Account active: Yes

| Information | Value | Data Type |
|---|---|---|
| Customer name | Victor | String (Text) |
| Age | 30 | Integer (Whole number) |
| Account balance | 150000.50 | Float (Decimal number) |
| Account active | Yes | Boolean (True/False) |

### 3. Why Does Each Piece Need a Representation?

**A. Customer Name – Victor**

- The name is text.
- The computer represents it using characters.
- Each character has a digital representation.

**B. Age – 30**

- Age is a whole number.
- The computer represents it as a numerical value.
- It can be used for calculations and comparisons.

**C. Account Balance – 150000.50**

- The account balance is a decimal quantity.
- It represents the amount of money in the customer's account.
- The computer must store and interpret the value correctly to avoid financial errors.

**D. Account Active – Yes**

- This represents a condition.
- The computer can represent it using a Boolean value.
- True means the account is active.
- False means the account is inactive.

### 4. How Is Information Represented Digitally?

Real-world information goes through different stages before a computer can process it.

**REAL-WORLD INFORMATION**

Customer name, age, account balance and account status.

↓

**DATA REPRESENTATION**

Text, integers, decimal numbers and Boolean values.

↓

**DIGITAL REPRESENTATION**

The information is encoded into digital data.

↓

**BINARY DATA**

The computer ultimately represents and processes data using binary digits (0 and 1).

↓

**COMPUTER STORAGE**

The represented information is stored and made available for processing.

### 5. Reasoning Challenge: Incorrect Account Balance

Imagine the customer's actual account balance is:

150000.50

But the computer mistakenly interprets it as:

15000.50

**What could happen?**

1. The customer's account balance would be incorrect.
2. The customer might be prevented from withdrawing money they actually have.
3. The bank could display inaccurate financial information.
4. Transactions and financial reports could become incorrect.
5. The customer could lose trust in the banking system.

**How can this problem be prevented?**

- Use appropriate data types.
- Validate information before storing it.
- Use accurate numerical representations for money, such as decimal or integer-based monetary storage.
- Test calculations and transactions.
- Check stored values for errors.

### 6. Conclusion

This exercise demonstrates that computers need information to be represented in specific formats before they can store and process it.

Different kinds of information require different representations:

- Text represents names and words.
- Integers represent whole numbers.
- Decimal numbers represent quantities with fractional parts.
- Boolean values represent True or False conditions.

**Key Lesson:**

Data is information represented in a form that a computer can store, process, and communicate.

REAL-WORLD INFORMATION → DATA REPRESENTATION → BINARY DATA → COMPUTER STORAGE