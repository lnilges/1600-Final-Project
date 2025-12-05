[Home](README.md) | [Back](BinaryToOctal.md)

# Binary Math

There are various operations that can be performed using binary numbers, including addition, subtraction, multiplication, and division.

## Binary Addition
When adding binary values, use the following table to determine the solution:

| First Number | Second Number | Addition | Carry |
| ----- | ----- | ----- | ----- |
| 0 | 0 | 0 | 0 |
| 0 | 1 | 1 | 0 |
| 1 | 0 | 1 | 0 |
| 1 | 1 | 0 | 1 |

Instructions:
1. Line up the numbers like in normal addition
2. Add from right to left
3. Use the table above to complete the problem
4. If you get 1 + 1 + 1 (carried 1), place a 1 and carry a 1

### Example:

![Binary Addition Example](Images/BinaryAddition.png)

## Binary Subtraction
Use the table below when doing a binary subtraction problem:

| First Number | Second Number | Subtraction | Borrow |
| --- | --- | --- | --- |
| 0 | 0 | 0 | 0 |
| 1 | 0 | 1 | 0 |
| 0 | 1 | 1 | 1 |
| 1 | 1 | 0 | 0 |

Instructions:
1. Line up the numbers
2. Subtract from right to left
3. If the subtraction is 0 - 1, borrow from the next 1

### Example:

![Binary Subtraction Example](Images/BinarySubtraction.png)

## Binary Multiplication
Use the table below when doing a binary multiplication problem:

| First Number | Second Number | Result |
| --- | --- | --- |
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

Instructions:
1. Line up the numbers
2. Multiply the right digit on the first number with all of the digits in the second number
3. Add a placeholder of 0 or X before multiplying the next digit of the first number with all of the digits of the second number
4. Repeat the process for all of the digits in the first number
5. Add the results of multiplying each digit to get the final result

### Example:

![Binary Multiplication Example](Images/BinaryMultiplication.png)


## Binary Division
Use the table below when completing a binary division problem:

| First Number | Second Number | Result |
| --- | --- | --- |
| 0 | 1 | 0 |
| 1 | 1 | 1 |


Instructions:
1. Compare the left bits of the dividend with the divisor
2. Determine the quotient bit, write a 1 if it fit or a 0 if it does not fit
3. Multiply the divisor by the quotient bit and write the result under the selected dividend bits
4. Subtract the product from the selected dividend bits to get the remainder
5. Bring down the next bit of the dividend to the remainder
6. Repeat until all bits have been divided

### Example:

![Binary Division Example](Images/BinaryDivision.png)