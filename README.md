# Lab-Exercise---6---Pseudorandom-Number-Generation
## Aim
Implementation of Pseudorandom Number Generation Using Standard library

## Procedure
• Step 1: Import the secrets module: This module provides cryptographically secure random functions.
• Step 2: Generate a secure random integer: Use secrets.randbelow(n) to get a random integer between 0 and n-1.
• Step 3: Generate a secure random number with a specific bit length: Use secrets.randbits(bit_length) to generate a random number with a given number of bits.
• Step 4: Generate a secure random token (hexadecimal): Use secrets.token_hex(nbytes) to generate a secure random token in hex format. The nbytes parameter specifies the number of bytes, and the result will be a string with twice that number of hex characters.
• Step 5: Display or use the generated random values: Print or use the generated values for your cryptographic needs.
## Program
```
import random

minimum = int(input("Enter minimum value: "))
maximum = int(input("Enter maximum value: "))

numbers = list(range(minimum, maximum + 1))

random.shuffle(numbers)

print("Random numbers between", minimum, "and", maximum, "are:")

for num in numbers:
    print(num, end=" ")

```
## Output
<img width="1721" height="975" alt="Screenshot 2026-10-31 141104" src="https://github.com/user-attachments/assets/1ee7b654-62d8-4bed-864a-0a1912b5b101" />

## Result
Thus Pseudorandom Number Generation Using Standard library has been executed successfully.
