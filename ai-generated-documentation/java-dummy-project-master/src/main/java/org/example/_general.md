![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---

## General Documentation for example package
The `example` package consists of two main classes, `Client` and `Service`, which work together to provide personalized greetings based on the length of the input name. The `Client` class interacts with the `Service` object to determine if the name length is even or odd and generates the appropriate greeting.

## Table of Contents
- [Client.md](Client.md)
  - **Description:** This file documents the `Client` class, which interacts with a `Service` object to generate personalized greetings based on the length of the input name. The `greeting` method checks if the name is not null or empty and determines whether the length of the name is even or odd. If the length is even, it returns the greeting in uppercase; otherwise, it returns the greeting in the original case.
- [Service.md](Service.md)
  - **Description:** This document outlines the `Service` class, which provides two methods: `isEven` and `highComplexityMethod`. The `isEven` method checks if an input integer is even, while the `highComplexityMethod` prints statements based on the signs of three input integers.
- [model/_general.md](model/_general.md)
  - **Description:** This general documentation file provides an overview of the child packages within the example package. It includes common information and shared functionalities that apply to all child packages.