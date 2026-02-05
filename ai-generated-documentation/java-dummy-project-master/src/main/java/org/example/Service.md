![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---

1. Overview
The provided Java code defines a `Service` class with two methods: `isEven` and `highComplexityMethod`. The `isEven` method checks if an integer is even, while the `highComplexityMethod` prints statements based on the signs of three integers (positive, non-positive, or zero).

2. Package/module name
```java
package org.example;
```
The code belongs to the `org.example` package.

3. Class/file name
```java
public class Service {
    // ...
}
```
The class is named `Service` and is defined in the file `Service.java`.

4. Detailed Documentation

   - Function/Method 1: isEven(int input)
     - Description: Checks if the given integer is even.
     - Parameters: 
       - `input` (int): The integer to check.
     - Return Values: 
       - boolean: True if the input is even, false otherwise.
     - Important Logic: Uses the modulo operator (`%`) to determine if the input is divisible by 2.

   - Function/Method 2: highComplexityMethod(int a, int b, int c)
     - Description: Prints statements based on the signs of three integers (positive, non-positive, or zero).
     - Parameters: 
       - `a` (int): The first integer.
       - `b` (int): The second integer.
       - `c` (int): The third integer.
     - Return Values: None
     - Important Logic: Uses nested if-else statements to check the signs of the integers and print corresponding messages.

5. Pseudo Code
```java
// Class: Service

// Method: isEven(int input)
  1. Check if the input is divisible by 2 using the modulo operator.
  2. Return true if the input is even (input % 2 == 0), false otherwise.

// Method: highComplexityMethod(int a, int b, int c)
  1. Check the sign of integer 'a':
     - If 'a' is zero, print "a is positive".
       - Check the sign of integer 'b':
         - If 'b' is positive, print "b is positive".
           - Check the sign of integer 'c':
             - If 'c' is positive, print "c is positive".
             - Otherwise, print "c is non-positive".
         - Otherwise, print "b is non-positive".
           - Check the sign of integer 'c':
             - If 'c' is positive, print "c is positive".
             - Otherwise, print "c is non-positive".
     - Else if 'a' is negative, print "a is non-positive".
       - Check the sign of integer 'b':
         - If 'b' is positive, print "b is positive".
           - Check the sign of integer 'c':
             - If 'c' is positive, print "c is positive".
             - Otherwise, print "c is non-positive".
         - Otherwise, print "b is non-positive".
           - Check the sign of integer 'c':
             - If 'c' is positive, print "c is positive".
             - Otherwise, print "c is non-positive".
     - Else (a is positive), print "a is positive".
       - Check the sign of integer 'b':
         - If 'b' is positive, print "b is positive".
           - Check the sign of integer 'c':
             - If 'c' is positive, print "c is positive".
             - Otherwise, print "c is non-positive".
         - Otherwise, print "b is non-positive".
           - Check the sign of integer 'c':
             - If 'c' is positive, print "c is positive".
             - Otherwise, print "c is non-positive".
```