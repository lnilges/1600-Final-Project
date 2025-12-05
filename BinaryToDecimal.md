[Home](README.md) | [Back](Basics.md) | [Next](BinaryToHex.md)

## Binary to Decimal Conversion

Converting a binary to a decimal number is done by multiplying each digit of the binary numbers 1 or 0 to the corresponding to the power of 2 according to the place value. In binary, each position represents a power of 2. The digit on the far right represents 2<sup>0</sup>, then the next digit represents 2<sup>1</sup>, and the power on each digit is increased by 1 from the previous digit. 

Instructions:
1. Write out the binary number
2. Label each digit with its power of 2
3. Multiply each bit (0 or 1) by its power of 2
4. Add the results

**Formula:** D = (n * 2<sup>7</sup>) + (n * 2<sup>6</sup>) + (n * 2<sup>5</sup>) + (n * 2<sup>4</sup>) + (n * 2<sup>3</sup>) + (n * 2<sup>2</sup>) + (n * 2<sup>1</sup>) + (n * 2<sup>0</sup>)

### Examples:

- Binary: 11101011
- Decimal Value = (1 * 2<sup>7</sup>) + (1 * 2<sup>6</sup>) + (1 * 2<sup>5</sup>) + (0 * 2<sup>4</sup>) + (1 * 2<sup>3</sup>) + (0 * 2<sup>2</sup>) + (1 * 2<sup>1</sup>) + (1 * 2<sup>0</sup>)
- Decimal Value = 128 + 64 + 32 + 0 + 8 + 0 + 2 + 1
- Decimal Value = 235
--- 
- Binary: 10111
- 10111 = 00010111
- Decimal Value = (0 * 2<sup>7</sup>) + (0 * 2<sup>6</sup>) + (0 * 2<sup>5</sup>) + (1 * 2<sup>4</sup>) + (0 * 2<sup>3</sup>) + (1 * 2<sup>2</sup>) + (1 * 2<sup>1</sup>) + (1 * 2<sup>0</sup>)
- Decimal Value = 0 + 0 + 0 + 16 + 0 + 4 + 2 + 1
- Decimal Value = 23


## Decimal to Binary Conversion

Converting a decimal value to a binary value is done by dividing the decimal value by 2 and keeping track of the remainders.

Instructions:
1. Divide the number by 2
2. Keep track of the remainder, it will always be 0 or 1
3. Divide the quotient by 2 again
4. Repeat until the quotient is 0
5. Write down the remainder values (bottom to top - the last remainder is the first bit on the left)

### Examples

- Decimal: 156
- 156 / 2 = 78, remainder 0
- 78 / 2 = 39, remainder 0
- 39 / 2 = 19, remainder 1
- 19 / 2 = 9, remainder 1
- 9 / 2 = 4, remainder 1
- 4 / 2 = 2, remainder 0
- 2 / 2 = 1 remainder 0
- 1 / 2 = 0, remainder 1
- Binary Value = 10011100
--- 
- Decimal: 17
- 17 / 2 = 8, remainder 1
- 8 / 2 = 4, remainder 0
- 4 / 2 = 2, remainder 0
- 2 / 2 = 1, remainder 0
- 1 / 2 = 0, remainder 1
- Binary Value = 10001