# Optimization-linear-programming Assignment 2
In this project we try to solve classical optimization tasks and realize Simplex and Interior-point algorithms. \
You can test our code in Live on replit platform: 

# Manual
1. git clone https://github.com/IVproger/Optimization-linear-programming-Assignment2.git
2. cd Optimization-linear-programming-Assignment2
3. javac Main.java
4. java Main

# Tests

## Test 1

### Minimization Problem
- Number of Variables: 6
- Number of Constraints: 3
- Coefficients of Objective Function (c): 9 10 16 0 0 0
- Coefficients of Constraint Function (A):
  - 18 15 12 1 0 0
  - 6 4 8 0 1 0
  - 5 3 3 0 0 1
- Right-hand Side Numbers (b): 360 192 180
- Approximation Accuracy (epsilon): 0.0001
- Starting Point for Interior Point Algorithm: 1 1 1 315 174 169

**Simplex Method Algorithm:**
- Solution:
  - Decision Variables (x*): { 0.0000 0.0000 0.0000 360.0000 192.0000 180.0000 }
- Minimum Value of the Objective Function: 0.0000

**Interior Point Algorithms:**
- Solution with alpha1 = 0.5 (Last Iteration 20):
  - Decision Variables (x*): { 0.0000 0.0000 0.0000 359.9999 192.0000 180.0000 }
  - Minimum Value of the Objective Function: -0.0000

- Solution with alpha = 0.9 (Last Iteration 11):
  - Decision Variables (x*): { 0.0000 0.0000 0.0000 360.0000 192.0000 180.0000 }
  - Minimum Value of the Objective Function: -0.0000

### Maximization Problem
- Number of Variables: 6
- Number of Constraints: 3
- Coefficients of Objective Function (c): 9 10 16 0 0 0
- Coefficients of Constraint Function (A):
  - 18 15 12 1 0 0
  - 6 4 8 0 1 0
  - 5 3 3 0 0 1
- Right-hand Side Numbers (b): 360 192 180
- Approximation Accuracy (epsilon): 0.0001
- Starting Point for Interior Point Algorithm: 1 7.1 19.6 1 1 94.9

**Simplex Method Algorithm:**
- Solution:
  - Decision Variables (x*): { 0.0000 8.0000 20.0000 0.0000 0.0000 96.0000 }
- Maximum Value of the Objective Function: 400.0000

**Interior Point Algorithms:**
- Solution with alpha1 = 0.5 (Last Iteration 18):
  - Decision Variables (x*): { 0.0000 8.0444 20.0028 0.0001 0.0000 95.8583 }
  - Maximum Value of the Objective Function: 400.4888

- Solution with alpha = 0.9 (Last Iteration 9):
  - Decision Variables (x*): { 0.0000 8.0444 20.0028 0.0001 0.0000 95.8583 }
  - Maximum Value of the Objective Function: 400.4888

## Test 2

**Maximization Problem**
- Need to maximize the function.
- Number of variables: 4
- Number of constraints: 2
- Coefficients of the objective function (c): 1 1 0 0
- Coefficients of the constraint function (A):
  - 2 4 1 0
  - 1 3 0 -1
- Right-hand side numbers (b): 16 9
- Approximation accuracy (epsilon): 0.0001
- Starting point for Interior Point Algorithm: 1 3.25 1 1.75

**Simplex Method Algorithm Result:**
- The method is not applicable!

**Interior Point Algorithm Results:**
- Solution with alpha1 = 0.5:
  - In the last iteration 18, we have x* = { 6.0000 1.0000 0.0000 0.0000 }
  - Maximum value of the objective function: 7.0000

- Solution with alpha = 0.9:
  - In the last iteration 10, we have x* = { 6.0000 1.0000 0.0000 0.0000 }
  - Maximum value of the objective function: 7.0000

## Test 3

**Maximization Problem**
- Need to maximize the function.
- Number of variables: 6
- Number of constraints: 3
- Coefficients of the objective function (c): 3 5 4 0 0 0
- Coefficients of the constraint function (A):
  - 2 -3 0 1 0 0
  - 0 2 5 0 1 0
  - 3 2 4 0 0 1
- Right-hand side numbers (b): 8 10 15
- Approximation accuracy (epsilon): 0.001
- Starting point for Interior Point Algorithm: 1 1.3 1.28 10 1 4.28

**Simplex Method Algorithm Result:**
- Solution:
  - Decision Variables (x*): { 1.667 5.000 0.000 19.667 0.000 0.000 }
- Maximum value of the objective function: 30.000

**Interior Point Algorithm Results:**
- Solution with alpha1 = 0.5:
  - In the last iteration 15, we have x* = { 1.667 5.000 0.000 19.766 0.000 0.000 }
  - Maximum value of the objective function: 29.999

- Solution with alpha = 0.9:
  - In the last iteration 9, we have x* = { 1.667 5.000 0.000 19.767 0.000 0.000 }
  - Maximum value of the objective function: 30.000

## Test 4

**Maximization Problem**
- Need to maximize the function.
- Number of variables: 3
- Number of constraints: 1
- Coefficients of the objective function (c): 25 40 0
- Coefficients of the constraint function (A):
  - 1 -1 1
- Right-hand side number (b): 0
- Approximation accuracy (epsilon): 0.001
- Starting point for Interior Point Algorithm: 1 2 1

**Simplex Method Algorithm Result:**
- The method is not applicable!

**Interior Point Algorithm Result:**
- The problem does not have a solution, or the starting point is incorrect!

## Test 5

**Minimization Problem**
- Need to minimize the function.
- Number of variables: 5
- Number of constraints: 3
- Coefficients of the objective function (c): 0 0 0 0 0
- Coefficients of the constraint function (A):
  - 3 2 1 0 0
  - 2 1 0 1 0
  - 5 3 0 0 1
- Right-hand side numbers (b): 30 40 50
- Approximation accuracy (epsilon): 0.001
- Starting point for Interior Point Algorithm: 1 13 1 25 6

**Simplex Method Algorithm Result:**
- The method is not applicable!

**Interior Point Algorithm Result:**
- The method is not applicable!

