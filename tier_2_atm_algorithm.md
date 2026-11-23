# Tier 2 – Field Exercise: Algorithm Thinking

## Project: ATM Withdrawal Algorithm

### 1. Problem Description

The problem is to design an algorithm that allows a customer to withdraw money from an ATM safely and correctly.

The ATM must verify the customer's card, validate the PIN, check the account balance, confirm cash availability, dispense money, and update the account.

### 2. Step-by-Step Algorithm

**Goal: Withdraw Money**

1. Start the ATM.
2. Display a welcome message.
3. Ask the customer to insert their ATM card.
4. Read and verify the card.
5. If the card cannot be read or is invalid, display an error message and return the card.
6. If the card is valid, ask the customer to enter their PIN.
7. Validate the PIN.
8. If the PIN is incorrect, allow the customer to try again.
9. If the customer enters an incorrect PIN three times, block the transaction and retain or return the card according to the bank's security policy.
10. If the PIN is correct, display the ATM menu.
11. Ask the customer to select the withdrawal option.
12. Ask the customer to enter the amount they want to withdraw.
13. Check whether the amount is greater than zero and meets the ATM's withdrawal rules.
14. If the amount is invalid, display an error message and ask the customer to enter another amount.
15. Check the customer's available account balance.
16. If the requested amount is greater than the available balance, display an insufficient balance message.
17. Check whether the ATM has enough cash.
18. If the ATM does not have enough cash, display a message and ask the customer to enter a smaller amount or cancel the transaction.
19. Confirm that the transaction can be completed.
20. Deduct the withdrawal amount from the customer's account.
21. Dispense the requested cash.
22. Confirm that the cash was successfully dispensed.
23. Print or display the transaction receipt if requested.
24. Return the ATM card.
25. Display a successful transaction message.
26. End the transaction.

### 3. Handling Possible Failures

**A. Card cannot be read**
- Display an invalid card error.
- Return the card if possible.
- End the transaction.

**B. Incorrect PIN**
- Display an incorrect PIN message.
- Allow another attempt.
- After three incorrect attempts, block the transaction and follow the bank's card security policy.

**C. Insufficient account balance**
- Display an insufficient balance message.
- Ask the customer to enter a smaller amount or cancel.

**D. ATM has insufficient cash**
- Display a message that the ATM cannot dispense the requested amount.
- Ask the customer to enter a smaller amount or cancel.

**E. Transaction cannot be completed**
- Do not treat the withdrawal as successful.
- Do not permanently deduct money without confirming the cash dispense.
- If money was deducted but cash was not dispensed, initiate a transaction reversal or recovery process.
- Display an error message.
- Return the card when safe.

### 4. Algorithm Flow

Start  
↓  
Insert ATM card  
↓  
Verify card  
↓  
Enter PIN  
↓  
Validate PIN  
↓  
Select withdrawal  
↓  
Enter withdrawal amount  
↓  
Validate amount  
↓  
Check account balance  
↓  
Check ATM cash availability  
↓  
Complete transaction  
↓  
Dispense cash  
↓  
Confirm cash dispensing  
↓  
Update account  
↓  
Print receipt if requested  
↓  
Return card  
↓  
End

### 5. Reasoning Challenge: Why Are These Steps Necessary?

1. **Card verification:** Ensures that the ATM can identify and accept the card.
2. **PIN validation:** Protects the customer's account from unauthorized access.
3. **Amount validation:** Prevents invalid withdrawal requests.
4. **Balance checking:** Prevents customers from withdrawing more money than they have available.
5. **Cash availability:** Ensures the ATM can provide the requested amount.
6. **Transaction confirmation:** Helps prevent incorrect account deductions.
7. **Account updating:** Ensures the customer's balance reflects a successful withdrawal.
8. **Card return:** Allows the customer to safely retrieve their card.

### 6. Key Distinction

**Problem:** Withdraw money from an ATM.

**Algorithm:** A sequence of ordered instructions explaining how to withdraw money safely.

**Program:** Python or another programming language used to implement the algorithm.

### 7. Conclusion

This exercise demonstrates that solving a problem requires more than simply stating what we want to achieve.

An algorithm breaks a problem into smaller, logical steps and considers what should happen when something goes wrong.

A good algorithm must be clear, ordered, and precise enough for a computer program to follow.

**Problem → Algorithm → Program**