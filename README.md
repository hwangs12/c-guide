# MY WHY JOURNEY

> Ask questions then try to answer. Please ping me if you see anything incorrect. 

## Why does C programming language have float and double to represent decimals?

> double stores high-precision floating-point data or numbers in computer memory. double has size of 8 bits while float has size of 4 bits.

## What differences are there between double and floating-point data?

> Single precision (float) gives you 23 bits of significand, 8 bits of exponent, and 1 sign bit.
> Double precision (double) gives you 52 bits of significand, 11 bits of exponent, and 1 sign bit.

## What is significand, exponent and sign bit?

## What are the format specifiers and do they work on any type of data?

> No, first of all there are following format specifiers in c:

| Specifier   | Description                                       |
| ----------- | ------------------------------------------------- |
| %c          | a single character                                |
| %s          | a string                                          |
| %hi         | short (signed)                                    |
| %hu         | short (unsigned)                                  |
| %Lf         | long double                                       |
| %n          | prints nothing                                    |
| %d          | a decimal integer (assumes base 10)               |
| %i          | a decimal integer (detects the base automatically)|
| %o          | an octal (base 8) integer                         |    
| %x          | a hexadecimal (base 16) integer                   |
| %p          | an address (or pointer)                           |
| %f          | a floating point number for floats                |
| %u          | int unsigned decimal                              |
| %e          | a floating point number in scientific notation    |
| %E          | a floating point number in scientific notation    |
| %%          | the % symbol                                      |

## What are the order of operations in C?

| Priority    | Operation                 |
| ----------- | ------------------------- |
| 1           | ++                        |
| 1           | – (negative)              |
| 1           | ()                        |
| 2           | !                         | 
| 2           | (typecast)                |
| 3           | *                         |
| 3           | /                         |
| 3           | %                         |
| 4           | +                         |
| 4           | - (minus)                 |
| 5           | <, <=                     |
| 5           | >, >=                     |
| 6           | ==, !=                    |
| 7           | &&                        |
| 8           | \|\|                      |
| 9           | all assignment operators  |
