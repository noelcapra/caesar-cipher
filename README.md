# Caesar Cipher Python Program

This guide explains how to run a simple Caesar Cipher program in Python and the concepts demonstrated in the code.

---

## How to Run

1. Ensure you have Python installed.
2. Download the Python file (e.g., `caesar_cipher.py`).
3. Run the program from the terminal using the command:

   ```bash
   python caesar_cipher.py

## What I Learned / Concepts Demonstrated

Function definition and parameters – Creating reusable functions (caesar, encrypt, decrypt) with default arguments (encrypt=True).

Input validation – Checking if the shift is an integer and within the allowed range (1–25).

String translation – Using str.maketrans() and .translate() for character substitution.

Handling uppercase and lowercase letters – Mapping both lower and upper case letters in the translation table.

Conditional logic – Adjusting the shift for encryption vs decryption using if not encrypt:.

Modular design – Separating encryption and decryption into dedicated functions for clarity and reuse.
