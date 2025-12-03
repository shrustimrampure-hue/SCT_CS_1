# Caesar Cipher Program
A classic and foundational substitution cipher implemented for educational purposes.

# 💻Task 1: Caesar Cipher Program Features
This program enables the encoding and decoding of messages using the Caesar Cipher, which shifts each letter of the message by a fixed number of positions (the key) up or down the alphabet.

# 🔑 Features

# Dual Mode Functionality: 
Supports both Encryption (e) and Decryption (d) using the same core logic.
# Reversible Logic:
Decryption is handled efficiently by applying a negative key shift, effectively reversing the encryption process. The relationship is:
Decryption Key = - Encryption Key
# Modular Arithmetic (Wraparound):
The most critical feature is the correct handling of the alphabet's beginning and end. The program ensures that:
• Shifting past 'z' wraps back to 'a'. 

• Shifting before 'a' wraps back to 'z'.
# Non-Alphabetic Preservation: 
Any characters that are not letters (like spaces, numbers, or punctuation) are left untouched in the output.
# Case Handling: 
All input text is uniformly processed as lowercase for consistency.

# 🧠 What I Learned (Skillcraft Technology)
This project, developed as part of Skillcraft Technology, reinforced several key programming concepts essential for algorithmic development and data processing.

# 🎯 Key Technical Learnings
# 1. Algorithmic Indexing and Retrieval:
• Learned how to use indexing methods to convert a character (like 'a') into a numerical position (like 0) and vice-versa, which is fundamental to substitution ciphers.
• Understood how to identify and handle non-alphabetic characters by checking for    non-existent indices.
# 2. Advanced Conditional Logic and Modulo Simulation:
• Mastered the use of complex if/elif blocks to manage the program's primary mode (encryption vs. decryption) and, most importantly, to implement the wraparound logic. This logic mimics the mathematical modulo operation ((mod 26))to ensure the resulting index always falls within the valid range of the 26-letter alphabet.
# 3. Function Abstraction and Reusability:
Gained experience in designing a single, highly reusable function that accepts different parameters (text, mode, key) to perform two distinct, yet related, operations. This promotes code efficiency and maintainability.
# 4. Input Validation and Data Type Management:
Practiced gathering raw user input and converting it to the appropriate data type (e.g., ensuring the shift key is treated as an integer) before it is used in calculations.
This project provided a practical demonstration of how to apply basic cryptography principles and modular arithmetic in a programming context.

# 🚀 How to Run
# 1. Prerequisite: 
Ensure you have Python installed.
# 2. Execution: 
Run the script file (e.g., caesar_cipher.py) using your system's Python interpreter.
# 3. Interaction: 
The program will prompt you to:
• Select the mode: e (encrypt) or d (decrypt).
• Enter the key (a number from 1 to 26).
• Provide the text to be processed.
