![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
## palindrome.py Documentation

**1. Overview:**

This Python script determines if a given input string is a palindrome. A palindrome is a word, phrase, number, or other sequence of characters that reads the same backward as forward (e.g., "racecar", "madam"). The script takes user input, processes it to remove spaces and convert it to lowercase, and then compares the processed text with its reversed counterpart. Finally, it prints True if the input is a palindrome and False otherwise.

**2. Package/module name:** None (This is a standalone script)

**3. Class/file name:** palindrome.py

**4. Detailed Documentation:**

   - **Function `check_palindrome()`:**
     - **Description:** This function checks if the input text is a palindrome.
     - **Parameters:** 
       - None (It takes user input directly)
     - **Return Values:** 
       - `True`: If the input text is a palindrome.
       - `False`: If the input text is not a palindrome.
     - **Important Logic:**
       1.  **Input:** Prompts the user to enter text using `input("Enter your text: ")`.
       2.  **Preprocessing:** 
           - Converts the input text to lowercase using `.lower()`.
           - Removes all spaces from the text using `.replace(" ", "")`.
       3. **Palindrome Check:** Compares the processed text with its reversed version (`text[::-1]`). If they are equal, it returns `True`; otherwise, it returns `False`.

   - **`print(check_palindrome())`:**
     - **Description:** Calls the `check_palindrome()` function and prints the returned boolean value (True or False) to the console.


**5. Pseudo Code:**

```
// Function: check_palindrome()

1. Prompt user for text input: "Enter your text: ".
2. Store the entered text in a variable named 'text'.
3. Convert 'text' to lowercase: 'text.lower()'.
4. Remove all spaces from 'text': 'text.replace(" ", "")'.
5. Reverse the processed 'text': 'text[::-1]'.
6. Compare the processed 'text' with its reversed version:
   - If they are equal, return True (palindrome).
   - Otherwise, return False (not a palindrome).

// Main Execution

1. Call the `check_palindrome()` function.
2. Print the returned value (True or False) to the console.



```


**6. Dependencies and Libraries:**

* **Python Standard Library:** This script relies on built-in Python functionalities like input(), string manipulation methods (lower(), replace()), and comparison operators. No external libraries are required. 

* **Equivalent Libraries in Other Languages:**
    - **Java:**  Similar functionality can be achieved using the `Scanner` class for input, string methods like `toLowerCase()` and `replaceAll()`, and comparison operators.
    - **JavaScript:** Use `prompt()` for user input, `.toLowerCase()` and `.replace()` for string manipulation, and comparison operators.



