![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
 1. Overview
The provided Python script checks if a given input text is a palindrome (reads the same forwards and backwards). It takes user input, converts it to lowercase, removes spaces, and compares it with its reverse. If both are equal, it returns True; otherwise, it returns False.

2. Package/module name
- The script is not part of a specific package or module as it's a standalone Python file.

3. Class/file name
- palindrome.py

4. Detailed Documentation
   - Function: check_palindrome()
     - Description: Checks if the given input text is a palindrome (reads the same forwards and backwards).
     - Parameters: None (takes user input through the `input` function)
     - Return Values: Boolean value indicating whether the input text is a palindrome or not.
     - Important Logic: Converts the input to lowercase, removes spaces, compares it with its reverse, and returns the result.

5. Pseudo Code
```
// Function: check_palindrome()
  1. Get user input (text)
  2. Convert text to lowercase
  3. Remove spaces from text
  4. Initialize reversed_text with the reverse of text
  5. Compare text and reversed_text for equality
      - If equal, return True
      - Else, return False
```