# Data Representation

Computers run on electricity. "On" is 1, "Off" is 0. This is **Binary**.

## Number Systems

### Binary (Base 2)
Uses only `0` and `1`.
* **Bit:** A single 0 or 1.
* **Byte:** 8 bits (e.g., `10110011`).
* **Calculating:** $101_2 = (1 \times 4) + (0 \times 2) + (1 \times 1) = 5_{10}$

### Hexadecimal (Base 16)
Uses `0-9` and `A-F`. Used to simplify binary representation (like color codes `#FF5733`).
* $A = 10, B = 11 ... F = 15$
* One Hex digit = 4 Binary bits (a "Nibble").

## Character Encoding
How do numbers become text?

1.  **ASCII:** 7-bit code. Only English (e.g., 'A' = 65).
2.  **Unicode (UTF-8):** The standard today. Covers all languages + Emojis (e.g., '🙂').