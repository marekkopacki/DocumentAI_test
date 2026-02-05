![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
 1. Overview
The provided Java code defines a `Service` class that contains two methods: `isEven(int input)` and `highComplexityMethod(int a, int b, int c)`. The `isEven` method checks if an integer is even by determining whether it has a remainder of 0 when divided by 2. The `highComplexityMethod` prints out the signs of three integers (a, b, and c) to indicate their relationship with zero.

2. Package/module name
The code belongs to the package `org.example`.

3. Class/file name
- Class: Service
- File: Service.java

4. Detailed Documentation
   - Function/Method 1 (isEven)
     - Description: Checks if an integer is even by determining whether it has a remainder of 0 when divided by 2.
     - Parameters:
       - input (int): The integer to be checked for evenness.
     - Return Values: A boolean value indicating whether the input integer is even or odd.
     - Important Logic: Uses the modulus operator (%).
   - Function/Method 2 (highComplexityMethod)
     - Description: Prints out the signs of three integers (a, b, and c) to indicate their relationship with zero.
     - Parameters:
       - a (int): The first integer to be checked for its sign.
       - b (int): The second integer to be checked for its sign.
       - c (int): The third integer to be checked for its sign.
     - Return Values: None.
     - Important Logic: Checks the signs of a, b, and c using conditional statements.
   - Key Variables: None.
   - Assumptions or Dependencies: No external dependencies are assumed or required.

5. Pseudo Code
```
// Class: Service

// Method: isEven(int input)
  1. Initialize variables
  2. Check if input is valid
    - If not, throw an exception
  3. Determine if the input is even using modulus operator
  4. Return the result

// Method: highComplexityMethod(int a, int b, int c)
  1. Initialize variables
  2. Check if a is valid
    - If not, throw an exception
  3. Determine the sign of a
  4. Check if b is valid
    - If not, throw an exception
  5. Determine the sign of b
  6. Check if c is valid
    - If not, throw an exception
  7. Determine the sign of c
  8. Print out the signs of a, b, and c
```