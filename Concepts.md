# Caesar Cipher: Encryption & Decryption

## Overview

The Caesar Cipher is one of the most basic and widely known encryption methods. It works by shifting each letter in a given text by a fixed number of positions in the alphabet, making it a simple yet effective way to obscure information.

### Encryption Process

1. **Shifting Characters**: Each letter in the plaintext is moved forward by a specified number of positions in the alphabet.
2. **Wrapping Around**: If shifting a letter goes beyond 'z', it loops back to the beginning of the alphabet.
3. **Case Sensitivity**: The case (uppercase or lowercase) of each letter is maintained.

### Decryption Process

1. **Reversing the Shift**: Each letter in the ciphertext is moved backward by the same number of positions to retrieve the original plaintext.
2. **Handling Letter Wrapping**: If shifting a letter moves past 'a', it loops back to 'z'.

### Implementation Approach

1. **Alphabet Representation**: The alphabet is stored as a string for easy reference.
2. **Encryption Function**: Uses modular arithmetic to shift each letter forward according to the key.
3. **Decryption Function**: Reverses the shift using the same key to reconstruct the original text.

This method, while simple, demonstrates fundamental principles of cryptography and is a great starting point for understanding encryption techniques.

