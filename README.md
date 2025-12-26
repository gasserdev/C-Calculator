# Simple C Calculator

A basic **calculator program in C** that performs the following operations:  

- Addition (+)  
- Subtraction (-)  
- Multiplication (*)  
- Division (/)  

---

## How It Works

1. The program asks the user to **enter an operator** (`+`, `-`, `*`, `/`).  
2. Then it asks for **two numbers**.  
3. It performs the calculation based on the chosen operator.  
4. If the operator is invalid or if dividing by zero, it shows an **error message**.  
5. Finally, it prints the **result** with two decimal places.

---

## Example

Welcome to Simple C Calculator!
Enter an operator (+, -, *, /): *
Enter first number: 5
Enter second number: 3
Result: 15.00

yaml
Copy code

---

## How to Run

1. Save the code in a file called `calculator.c`.  
2. Compile using:  
   ```bash
   gcc calculator.c -o calculator
Run the program:

bash
Copy code
./calculator
