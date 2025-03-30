# Collatz Conjecture Project

Welcome to the **Collatz Conjecture** project! This repository contains a PHP implementation that demonstrates the Collatz sequence (also known as the 3x+1 conjecture). The project includes functions to compute the sequence, analyze it, and perform various tests.

## Description

The Collatz conjecture is a mathematical sequence defined as follows:

1. Start with any positive integer \( n \).
2. If \( n \) is even, divide it by 2.
3. If \( n \) is odd, multiply it by 3 and add 1.
4. Repeat the process with the new value of \( n \) until \( n \) equals 1.

### Project Features:
- **PHP Implementation**: The core logic of the sequence is written in PHP.
- **HTML Forms**: User can input a number and view the sequence, maximum value, and iteration count.
- **Statistics**: The project includes analysis of the sequence for multiple values.

## Instructions

To use this project:
1. Clone the repository.
2. Open the PHP files in your preferred editor.
3. Run the PHP server to see the output.

### Example

```php
// Example code
$n = 6;
echo collatz($n);
