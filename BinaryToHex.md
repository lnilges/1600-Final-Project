[Home](README.md) | [Back](BinaryToDecminal.md) | [Next](BinaryToOctal.md)

# Binary to Hexadecimal Conversion

To convert from a binary value into a hexadecimal value, group the binary number into groups of four digits. This is done because binary is base-2 while hexadecimal is base-16. Once they are in groups of four, convert each into binary. Since there are only four numbers in the group, use the formula - D = (n * 8) + (n * 4) + (n * 2) + (n * 1). If the number is 1-9, then that is the hexadecimal character for that group. If the number is 10-15 then the character is A-F.

This table can be used for faster conversions:
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

>Binary: 11101000\
>Split: 1110 1000\
>Convert to decimal:\
>1110 = (1 * 8) + (1 * 4) + (1 * 2) + (1 * 1) = 14\
>1000 = (1 * 8) + (0 * 4) + (0 * 2) + (0 * 1) = 8\
>Convert to hexadecimal: E8

>Binary: 1110101101101\
>Split: 0001 1101 0110 1101\
>Convert to decimal:\
>0001 = (0 * 8) + (0 * 4) + (0 * 2) + (1 * 1) = 1\
>1101 = (1 * 8) + (1 * 4) + (0 * 2) + (1 * 1) = 13\
>0110 = (0 * 8) + (1 * 4) + (1 * 2) (0 * 1) = 6\
>1101 = (1 * 8) + (1 * 4) + (0 * 2) + (1 * 1) = 13\
>Convert to hexadecimal: 1D6D

### Hexadecimal to Binary Conversion

To convert from hexadecimal to binary, you must first convert each character to a decimal value. Then convert each decimal value to a binary as discussed in the [binary to decimal page](BinaryToDecminal.md).

### Examples

>Hexadecimal: B7C2\
>Convert each character into a decimal value:\
>B = 11, 7 = 7, C = 12, 2 = 2\
>Then convert each into binary using table:\
>11 = 1011\
>7 = 0111\
>12 = 1100\
>2 = 0010\
>Binary Value: 1011011111000010

>Hexadecimal: AF3C\
>Convert to decimal values:\
>A = 10, F = 15, 3 = 3, C = 12\
>Then convert each into binary using table:\
>10 = 0101\
>15 = 1111\
>3 = 0011\
>12 = 1100\
Binary Value: 0101111100111100
