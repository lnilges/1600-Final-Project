[Home](README.md) | [Back](BinaryToHex.md) | [Next](BinaryMath.md)

# Binary to Octal Conversion

To convert from binary to octal values, the base is changed from 2 to 8. Start by separating the binary digits into groups of 3, starting from the right side and going towards the left. Then use the following forumla, Octal = (n * 4) + (n * 2) + (n * 1).

### Examples:

>Binary: 11101011\
>Split: 011 101 011\
>Use formula:\
>011 = (0 * 4) + (1 * 2) + (1 * 1) = 3\
>101 = (1 * 4) + (0 * 2) + (1 * 1) = 5\
>011 = (0 * 4) + (1 * 2) + (1 * 1) = 3\
>Octal Value: 353\

>Binary: 11101100101001\
>Split: 011 101 100 101 001\
>Use formula:\
>011 = (0 * 4) + (1 * 2) + (1 * 1) = 3\
>101 = (1 * 4) + (0 * 2) + (1 * 1) = 5\
>100 = (1 * 4) + (0 * 2) + (0 * 1) = 4\
>101 = (1 * 4) + (0 * 2) + (1 * 1) = 5\
>001 = (0 * 4) + (0 * 2) + (1 * 1) = 1\
>Octal Value: 35451

# Octal to Binary Conversion

To convert from octal to binary, use the same formula as before but backwards to get the binary version. 

### Examples:

>Octal: 627\
>6 = (1 * 4) + (1 * 2) + (0 * 1) = 110\
>2 = (0 * 4) + (1 * 2) + (0 * 1) = 010\
>7 = (1 * 4) + (1 * 2) + (1 * 1) = 111\
>Binary Value = 110010111

>Octal: 1453\
>1 = (0 * 4) + (0 * 2) + (1 * 1) = 001\
>4 = (1 * 4) + (0 * 2) + (0 * 1) = 100\
>5 = (1 * 4) + (0 * 2) + (1 * 1) = 101\
>3 = (0 * 4) + (1 * 2) + (1 * 1) = 011\
>Binary Value = 001100101011