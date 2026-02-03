![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
## palindrome.py Documentation

**1. Overview:**

This Python script determines if a given text string is a palindrome. A palindrome is a word, phrase, number, or other sequence of characters that reads the same backward as forward (ignoring spaces and capitalization). 

**2. Package/module name:** None (script runs directly)

**3. Class/file name:** palindrome.py

**4. Detailed Documentation:**

   - **`check_palindrome()` Function:**
     - **Description:** This function takes user input, processes it to remove spaces and convert it to lowercase, and then checks if the processed text is equal to its reverse. It returns `True` if it's a palindrome, `False` otherwise.
     - **Parameters:** None
     - **Return Values:** A boolean value (`True` or `False`) indicating whether the input text is a palindrome.
     - **Important Logic:** 
       - The function first prompts the user to enter text using `input("Enter your text: ")`.
       - It then cleans the input by converting it to lowercase using `.lower()` and removing spaces using `.replace(" ", "")`.
       - Finally, it compares the cleaned text with its reversed version (`text[::-1]`). If they are equal, it returns `True`; otherwise, it returns `False`.

   - **`print(check_palindrome())`:**
     - **Description:** This line calls the `check_palindrome()` function and prints the returned boolean value to the console.


**5. Pseudo Code:**

```
// Function: check_palindrome()

  1. Prompt user to enter text: "Enter your text: "
  2. Read user input as 'text'.
  3. Convert 'text' to lowercase: 'text.lower()'.
  4. Remove spaces from 'text': 'text.replace(" ", "")'.
  5. Reverse the processed 'text': 'text[::-1]'.
  6. Compare the processed 'text' with its reversed version:
     - If they are equal, return True (palindrome).
     - Otherwise, return False (not a palindrome).

// Main Execution

  1. Call the 'check_palindrome()' function.
  2. Print the returned boolean value to the console. 



```


**6. Dependencies and Libraries:**

* **Python Standard Library:** This script uses built-in Python functions like `input()`, `.lower()`, `.replace()`, and slicing (`[::-1]`). No external libraries are required.
* **Equivalent Libraries in Other Languages:**
    - **Java:**  Similar functionality can be achieved using Java's `Scanner` class for input, string manipulation methods like `toLowerCase()` and `replaceAll()`, and string reversal techniques.
    - **C++:** Use `std::cin` for input, `std::string` for strings, and the `reverse()` function or manual iteration to reverse a string.



