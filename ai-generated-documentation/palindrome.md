![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
## palindrome.py Documentation

**1. Overview:**

This Python script determines if a given text string is a palindrome. A palindrome is a word, phrase, number, or other sequence of characters that reads the same backward as forward (ignoring spaces and capitalization). 

The script takes user input, processes it to remove spaces and convert it to lowercase, then compares the processed text with its reversed counterpart. Finally, it prints `True` if the text is a palindrome and `False` otherwise.

**2. Package/module name:** None (This is a standalone script)

**3. Class/file name:** palindrome.py

**4. Detailed Documentation:**

   - **Function: `check_palindrome()`**
     - **Description:** This function checks if the input text is a palindrome.
     - **Parameters:** 
       - None
     - **Return Values:** 
       - `True`: If the input text is a palindrome.
       - `False`: If the input text is not a palindrome.
     - **Important Logic:**
       1. Prompts the user to enter text using `input("Enter your text: ")`.
       2. Converts the input text to lowercase using `.lower()`.
       3. Removes all spaces from the text using `.replace(" ", "")`.
       4. Reverses the processed text using slicing (`[::-1]`).
       5. Compares the processed text with its reversed counterpart. If they are equal, it returns `True`; otherwise, it returns `False`.

   - **Function: `print(check_palindrome())`**
     - **Description:** This function calls the `check_palindrome()` function and prints the returned boolean value to the console.


**5. Pseudo Code:**

```
// Function: check_palindrome()

1. Prompt user for text input.
2. Convert the input text to lowercase.
3. Remove all spaces from the text.
4. Reverse the processed text.
5. Compare the processed text with its reversed counterpart.
6. If they are equal, return True (palindrome).
7. Otherwise, return False (not a palindrome).

// Function: print(check_palindrome())

1. Call the `check_palindrome()` function to get the result (True or False).
2. Print the returned result to the console. 



```


**6. Dependencies and Libraries:**

- **Python Standard Library:** This script utilizes built-in Python functions like `input()`, `.lower()`, `.replace()`, and slicing (`[::-1]`). No external libraries are required.

- **Equivalent Libraries in Other Languages:**
    -  Java: String manipulation methods (`.toLowerCase()`, `.replaceAll()`, substring reversal)
    -  C++: String class methods (`.tolower()`, `.replace()`, string reversal using iterators or algorithms)



