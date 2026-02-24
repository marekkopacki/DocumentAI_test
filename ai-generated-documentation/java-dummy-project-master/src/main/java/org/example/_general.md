![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---

## General Documentation for example package
Description generated based on the provided Markdown files. The `example` package consists of two main classes, `Client` and `Service`, which work together to provide personalized greetings based on the length of input names. The `Client` class interacts with the `Service` object to determine whether the name length is even or odd and returns the appropriate greeting. The `Service` class contains methods for checking if an integer is even and printing statements based on the signs of three input integers.

## Table of Contents
- [Client.md](Client.md)
  - **Description:** The `Client` class interacts with a `Service` object to generate personalized greetings based on the length of the input name. It checks if the name is not null or empty and determines whether the length is even or odd, returning the greeting in uppercase or original case accordingly.
- [Service.md](Service.md)
  - **Description:** The `Service` class provides two methods: `isEven`, which checks if an input integer is even, and `highComplexityMethod`, which prints statements based on the signs of three input integers. It assists the `Client` class in determining the appropriate greeting format.