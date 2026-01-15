How to Run

Ensure you have Python installed.

Download the Python file (e.g., caesar_cipher.py).

Run the program from the terminal using the command:

python caesar_cipher.py


The program will encrypt the sample text 'freeCodeCamp' with a shift of 3 and print the result.

You can also use the encrypt(text, shift) and decrypt(text, shift) functions in your own code.

What I Learned / Concepts Demonstrated

Function definition and parameters – Creating reusable functions (caesar, encrypt, decrypt) with default arguments (encrypt=True).

Input validation – Checking if the shift is an integer and within the allowed range (1–25).

String translation – Using str.maketrans() and .translate() for character substitution.

Handling uppercase and lowercase letters – Mapping both lower and upper case letters in the translation table.

Conditional logic – Adjusting the shift for encryption vs decryption using if not encrypt:.

Modular design – Separating encryption and decryption into dedicated functions for clarity and reuse.

Simple encryption logic – Understanding the Caesar Cipher and how to shift letters in the alphabet.
