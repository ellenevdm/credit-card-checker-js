# Credit Card Checker Project

This project involves implementing the Luhn algorithm in JavaScript to determine the validity of credit card numbers. The primary objective is to create a backend logic that checks the authenticity of credit card digits using JavaScript functions.

## Project Overview

The "Credit Card Checker" project, as part of the Codecademy course, focuses on verifying the legitimacy of credit card numbers using the Luhn algorithm. By employing JavaScript functions, the project aims to build an essential backend logic that assesses the validity of provided credit card arrays.

## Project Goals

In the context of this project, you'll assume the role of a clerk entrusted with the task of validating credit card numbers. Unlike other clerks who manually verify these numbers, your role is to optimize the verification process using functions and loops to handle multiple credit card validations simultaneously. Your progress can be monitored using terminal outputs and `console.log()` statements.

## Project Requirements

1. Review the starter code provided. This includes 15 arrays, each containing digits of separate credit card numbers. These arrays are labeled with prefixes like "valid," "invalid," and "mystery" to denote their status. Additionally, there's a `batch` array storing all provided credit card numbers.

2. Develop a `validateCred()` function that accepts an array as a parameter. The purpose of this function is to determine whether the array contains digits of a valid credit card number. The function must adhere to the Luhn algorithm. Follow the provided steps to implement the Luhn algorithm logic.

3. Create a `findInvalidCards()` function that accepts a nested array of credit card numbers as a parameter. This function should identify invalid numbers within the nested array and return another nested array containing those invalid card numbers.

4. Implement an `idInvalidCardCompanies()` function with a parameter for a nested array of invalid numbers. This function should identify the credit card companies that may have issued these invalid numbers. Based on the unique starting digits, associate each company with its corresponding number and name.

## Code Sample

```javascript
// Add your functions below:

// (Code sample provided in your message)
```

## Instructions

1. To verify the validity of the credit card numbers, utilize the `validateCred()` function.
2. Identify the invalid credit card numbers using the `findInvalidCards()` function.
3. Employ the `idInvalidCardCompanies()` function to determine the credit card companies associated with the invalid numbers.

Please note that this project doesn't involve a frontend interface. You can explore the implementation details by reviewing the provided JavaScript code available on the associated GitHub repository.
