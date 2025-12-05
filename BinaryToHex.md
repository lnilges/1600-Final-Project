[Home](README.md) | [Back](BinaryToDecminal.md) | [Next](BinaryToOctal.md)

## Binary to Hexadecimal Conversion

Each hexadecimal digit represents 4 binary numbers. This makes it easy to convert between binary and hexadecimal. 

Instructions:
1. Group the binary number into 4-bit groups, starting from the right side.
2. If the last group has less than 4 bits, add 0s to the front to get 4 bits
3. Convert each group into its decimal value using D = (n * 2<sup>3</sup>) + (n * 2<sup>2</sup>) + (n * 2<sup>1</sup>) + (n * 2<sup>0</sup>)
4. Convert each decimal value to hexadecimal: 0-9 = 0-9, 10-15 = A - F


Quick Reference Table:
| Binary | Decimal | Hexadecimal|
| ------- | ------ | ------|
| 0000 | 0 | 0 |
| 0001 | 1 | 1 |
| 0010 | 2 | 2 |
| 0011 | 3 | 3 |
| 0100 | 4 | 4 |
| 0101 | 5 | 5 |
| 0110 | 6 | 6 |
| 0111 | 7 | 7 |
| 1000 | 8 | 8 |
| 1001 | 9 | 9 |
| 1010 | 10 | A |
| 1011 | 11 | B |
| 1100 | 12 | C |
| 1101 | 13 | D |
| 1110 | 14 | E |
| 1111 | 15 | F |

### Examples:

- Binary: 11101000
- Split: 1110 1000
- 1110 = (1 * 2<sup>3</sup>) + (1 * 2<sup>2</sup>) + (1 * 2<sup>1</sup>) + (0 * 2<sup>0</sup>) = 14
- 1000 = (1 * 2<sup>3</sup>) + (0 * 2<sup>2</sup>) + (0 * 2<sup>1</sup>) + (0 * 2<sup>0</sup>) = 8
- Hexadecimal Value: E8
--- 
- Binary: 1110101101101
- Split: 0001 1101 0110 1101
- 0001 = (0 * 2<sup>3</sup>) + (0 * 2<sup>2</sup>) + (0 * 2<sup>1</sup>) + (1 * 2<sup>0</sup>) = 1
- 1101 = (1 * 2<sup>3</sup>) + (1 * 2<sup>2</sup>) + (0 * 2<sup>1</sup>) + (1 * 2<sup>0</sup>) = 13
- 0110 = (0 * 2<sup>3</sup>) + (1 * 2<sup>2</sup>) + (1 * 2<sup>1</sup>) + (0 * 2<sup>0</sup>) = 6
- 1101 = (1 * 2<sup>3</sup>) + (1 * 2<sup>2</sup>) + (0 * 2<sup>1</sup>) + (1 * 2<sup>0</sup>) = 13
- Hexadecimal Value: 1D6D

## Hexadecimal to Binary Conversion

Instructions:
1. Separate each character in the hexadecimal
2. Convert each character into a decimal value
3. Convert the decimal values into 4-bit binary values
4. Put the 4-bit values together to get the binary value

### Examples

- Hexadecimal: B7C2
- B = 11 = 1011
- 7 = 7 = 0111
- C = 12 = 1100
- 2 = 2 = 0010
- Binary Value: 1011011111000010
---
- Hexadecimal: AF3C
- A = 10 = 1010 
- F = 15 = 1111
- 3 = 3 = 0011
- C = 12 = 1100
- Binary Value: 0101111100111100
