# Caesar Cipher Program
A classic and foundational substitution cipher implemented for educational purposes.

# 💻Task 1: Caesar Cipher Program Features
This program enables the encoding and decoding of messages using the Caesar Cipher, which shifts each letter of the message by a fixed number of positions (the key) up or down the alphabet.

# 🔑 Features
# Dual Mode Functionality: 
Supports both Encryption (e) and Decryption (d) using the same core logic.

# Reversible Logic:
Decryption is handled efficiently by applying a negative key shift, effectively reversing the encryption process. The relationship is:
# Decryption Key = - Encryption Key
# Modular Arithmetic (Wraparound):
The most critical feature is the correct handling of the alphabet's beginning and end. The program ensures that:
• Shifting past 'z' wraps back to 'a'.
• Shifting before 'a' wraps back to 'z'.

# Non-Alphabetic Preservation: 
Any characters that are not letters (like spaces, numbers, or punctuation) are left untouched in the output.

# Case Handling: All input text is uniformly processed as lowercase for consistency.
