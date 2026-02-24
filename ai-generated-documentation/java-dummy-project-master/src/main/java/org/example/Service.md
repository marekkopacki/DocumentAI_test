![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---

1. Overview
The provided Java code defines a `Service` class with two methods: `isEven` and `highComplexityMethod`. The `isEven` method checks if an input integer is even, while the `highComplexityMethod` prints statements based on the signs of three input integers.

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
### Function/Method 1: isEven
- Description: Checks if the input integer is even.
- Parameters:
  - `input` (int): The integer to be checked.
- Return Values:
  - boolean: True if the input is even, false otherwise.
- Important Logic: The method uses the modulo operator (`%`) to check if the remainder of the division of the input by 2 is equal to 0.

### Function/Method 2: highComplexityMethod
- Description: Prints statements based on the signs of three input integers.
- Parameters:
  - `a` (int): The first integer.
  - `b` (int): The second integer.
  - `c` (int): The third integer.
- Return Values: None
- Important Logic: The method uses nested if-else statements to determine the signs of the input integers and prints corresponding messages.

5. Pseudo Code
```java
// Class: Service

// Method: isEven(int input)
  1. Check if the input is even by using the modulo operator (input % 2 == 0)
  2. Return true if the input is even, false otherwise

// Method: highComplexityMethod(int a, int b, int c)
  1. Check the sign of 'a'
    - If 'a' is positive, print "a is positive"
    - If 'a' is non-positive, print "a is non-positive"
  2. Check the sign of 'b'
    - If 'b' is positive, print "b is positive"
    - If 'b' is non-positive, print "b is non-positive"
  3. Check the sign of 'c'
    - If 'c' is positive, print "c is positive"
    - If 'c' is non-positive, print "c is non-positive"
```