Functions & Modules in Python


## Task 1: Calculate Factorial Using a Function
### Description:
- This program defines a function called `factorial` that takes a **number** as an argument and calculates its factorial.
- The factorial is calculated recursively.
- The function is then called with a user-provided number, and the result is displayed.

### Code Explanation:
- The `factorial` function uses recursion to calculate the factorial.
- If `n == 0` or `n == 1`, it returns `1` (base case).
- Otherwise, it multiplies the number `n` with the factorial of `n-1`.

### How to Run:
1. Run `factorial.py` in any Python environment.
2. Enter a number when prompted.
3. The program will calculate and display the factorial of that number.

### Example Output:
Enter a number: 5
Factorial of 5 is: 120



## Task 2: Using the Math Module for Calculations
### Description:
- This program uses the **math module** to perform three calculations on a user-provided number:
  1. **Square root** of the number.
  2. **Natural logarithm** (log base `e`) of the number.
  3. **Sine** of the number (in radians).

### Code Explanation:
- The program imports the `math` module and uses its built-in functions:
  - `math.sqrt()` to calculate the square root.
  - `math.log()` to calculate the natural logarithm.
  - `math.sin()` to calculate the sine of the number (assuming the number is in radians).
- The program then displays the results of each calculation.

### How to Run:
1. Run `math_calculations.py` in any Python environment.
2. Enter a number when prompted.
3. The program will calculate and display the square root, logarithm, and sine of the number.

### Example Output:
Enter a number: 25
Square root is: 5.0 Natural logarithm is: 3.2188763188291306 Sine of is: -0.9589242746631385
