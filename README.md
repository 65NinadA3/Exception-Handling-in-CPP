# Exception Handling  

**Name:** Ninad Phatak  
**PRN:** 24070123065  
**Batch:** ENTC A3  

---

## Overview  

In C++, **exception handling** is a mechanism used to handle runtime errors, ensuring that the program can continue executing instead of abruptly terminating.  
It uses the keywords `try`, `catch`, and `throw`.  

- **try** block: Contains the code that may cause an exception.  
- **throw** statement: Used to signal (raise) an exception when an error occurs.  
- **catch** block: Handles the exception by catching the thrown error.  

This mechanism is useful to build reliable, robust, and fault-tolerant applications, as it separates normal execution from error-handling logic.  

---

## 1. Access Code  

### Algorithm  
1. Start the program.  
2. Prompt the user to enter the private code.  
3. Read the input from the user.  
4. Inside a `try` block:  
   - If the entered code is **not equal** to `9762`, throw the code.  
   - Else, display **“Access Granted”**.  
5. In the `catch` block, display **“ERROR: Entered wrong code”** if the exception is thrown.  
6. End the program.  

### Theory  
This program demonstrates exception handling by validating a secret numeric code.  
- The user is asked to enter a private code.  
- If the entered code matches the correct value (`9762`), access is granted.  
- If the code does not match, an exception is thrown, and an error message is displayed.  

### Output  
Enter the private code:9762
Access Granted

markdown
Copy code

---

## 2. Divide by 0 Error  

### Algorithm  
1. Start the program.  
2. Prompt the user to enter two numbers.  
3. Read the two inputs (`n1` and `n2`).  
4. Inside a `try` block:  
   - If `n2` is **equal to 0**, throw `n2`.  
   - Else, calculate `ans = n1 / n2` and display the result.  
5. In the `catch` block, display **“ERROR: Division by 0”** if the exception is thrown.  
6. End the program.  

### Theory  
This program shows how exceptions can prevent runtime crashes such as division by zero.  
- The user enters two numbers.  
- If the second number (`n2`) is zero, the program throws an exception.  
- The catch block then handles the situation by displaying an error message.  
- Otherwise, the division result is calculated and displayed.  

### Output  
Enter values of numbers 1 & 2:3
0

ERROR: Division by0
