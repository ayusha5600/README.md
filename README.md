# Collatz Conjecture Project
The Collatz Conjecture project This repository contains a PHP implementation that demonstrates the Collatz sequence.
## Description
The Collatz conjecture is a mathematical sequence defined as follows:
1. Start with any positive integer \( n \).
2. If \( n \) is even, divide it by 2.
3. If \( n \) is odd, multiply it by 3 and add 1.
4. Repeat the process with the new value of \( n \) until \( n \) equals 1.
### Example
```php
// Example code
$n = 6;
echo collatz($n);
