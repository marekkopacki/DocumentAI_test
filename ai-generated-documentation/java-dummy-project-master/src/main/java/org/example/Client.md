![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
 1. Overview
The provided Java code defines a `Client` class that takes a `Service` object as a constructor argument and provides a method called `greeting(String name)`. The `greeting` method checks if the input string `name` is not null or empty, then determines whether the length of the name is even using the `Service` object's `isEven` method. If the length of the name is even, it returns the greeting in uppercase; otherwise, it returns the greeting as is.

2. Package/module name
The code belongs to the package `org.example`.

3. Detailed Documentation
- Class/file name: Client.java

   - Constructor (Client)
     - Description: Initializes a new instance of the `Client` class with the provided `Service` object.
     - Parameters:
       - service (Service): The `Service` object to be used by the client.
     - Return Values: None.
     - Important Logic: Assigns the provided `Service` object to the private instance variable `service`.

   - Method (greeting)
     - Description: Generates a greeting message for the given name and returns it in either uppercase or lowercase depending on whether the length of the name is even.
     - Parameters:
       - name (String): The name to generate a greeting for.
     - Return Values: A `String` containing the generated greeting.
     - Important Logic:
       - Checks if the input string is null or empty and throws an exception if it is.
       - Determines whether the length of the name is even using the `Service` object's `isEven` method.
       - If the length of the name is even, converts the greeting to uppercase; otherwise, leaves it as is.

4. Pseudo Code
```
// Class: Client

// Method: Client(Service service)
  1. Initialize client instance with provided service
  2. Assign service to private variable

// Method: greeting(String name)
  1. Initialize variables
  2. Check if name is null or empty
    - If yes, throw an exception
  3. Determine if the length of name is even using Service's isEven method
  4. Convert greeting to uppercase if length is even; otherwise, leave it as is
  5. Return the generated greeting
```