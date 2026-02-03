![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
## Service.java Documentation

**1. Overview:**

This Java code defines a `Service` class that provides utility methods for basic numerical operations. It includes a method to check if a given integer is even and another method (`highComplexityMethod`) that performs a series of conditional checks based on the signs of three input integers. 

**2. Package/module name:**

org.example

**3. Class/file name:**

Service.java

**4. Detailed Documentation:**

   - **Class `Service`**:
     - **Description:**  A utility class containing methods for performing simple numerical checks and conditional logic operations.

     - **Methods:**
       - **Method `isEven(int input)`**:
         - **Description:** Checks if a given integer is even.
         - **Parameters:**
           - `input`: An integer to be checked.
         - **Return Values:**
           - A boolean value (`true` if the input is even, `false` otherwise).
         - **Important Logic:** Uses the modulo operator (%) to determine if the remainder of dividing the input by 2 is zero. If it is, the number is even and the method returns `true`; otherwise, it returns `false`.

       - **Method `highComplexityMethod(int a, int b, int c)`**:
         - **Description:**  Performs a series of nested conditional checks based on the signs of three input integers. It prints messages to the console indicating the sign of each integer and their combinations.
         - **Parameters:**
           - `a`: An integer.
           - `b`: An integer.
           - `c`: An integer.
         - **Return Values:** None (void method).
         - **Important Logic:** 
             - The method uses a series of `if` and `else if` statements to check the sign of each input (`a`, `b`, `c`).
             - It prints messages based on the combinations of positive and non-positive values.

**5. Pseudo Code:**



```
// Class: Service

// Method: isEven(input)
  1. Calculate the remainder when 'input' is divided by 2 using the modulo operator (%).
  2. If the remainder is equal to 0, return true (the number is even).
  3. Otherwise, return false (the number is odd).

// Method: highComplexityMethod(a, b, c)
  1. Check the sign of 'a':
    - If 'a' is positive:
      - Check the sign of 'b':
        - If 'b' is positive:
          - Check the sign of 'c':
            - If 'c' is positive, print "a, b, and c are positive".
            - Otherwise, print "a and b are positive, but c is non-positive".
        - Otherwise (b is non-positive):
          - Check the sign of 'c':
            - If 'c' is positive, print "a is positive, but b and c are non-positive".
            - Otherwise, print "a is positive, and b and c are non-positive".
    - If 'a' is non-positive:
      - Check the sign of 'b':
        - If 'b' is positive:
          - Check the sign of 'c':
            - If 'c' is positive, print "a is non-positive, but b and c are positive".
            - Otherwise, print "a is non-positive, but b is positive, and c is non-positive".
        - Otherwise (b is non-positive):
          - Check the sign of 'c':
            - If 'c' is positive, print "a and b are non-positive, but c is positive".
            - Otherwise, print "a and b are non-positive, and c is non-positive".



```

**Dependencies and Libraries:**


* **Standard Java Library:** The code relies on the standard Java library for basic operations like modulo (`%`) and printing to the console. No external libraries are explicitly used.




