# Caesar Cipher: Simple Text Encryption & Decryption  

This Python program is a personal project I built to easily encrypt and decrypt messages using the Caesar Cipher method. Just input your text and a shift value, and the script takes care of the rest!

## How It Works  

The program asks whether you want to **encrypt** or **decrypt** a message. Once you enter your text and shift key, it scrambles the message based on the shift value for encryption or reverses the process for decryption.  

## Features  

- Encrypt messages with a shift key.  
- Decrypt messages using the same key to restore the original text.  

## Installation  

1. Clone this repository to your local machine.  
2. Ensure Python is installed.  
3. Run the script using Python.  

## Running the Script  

1. **Open a terminal or command prompt.**  
2. **Navigate to the folder where `caesar_cipher.py` is saved.**  
3. **Run the script:**  
   ```bash
   python caesar_cipher.py
$ python caesar_cipher.py
Do you want to encrypt or decrypt? (e/d): e

ENCRYPTION MODE SELECTED

Enter the key: 3  
Enter the text to encrypt: hello world  
CIPHERTEXT: khoor zruog

$ python caesar_cipher.py
Do you want to encrypt or decrypt? (e/d): d

DECRYPTION MODE SELECTED

Enter the key: 3  
Enter the text to decrypt: khoor zruog  
PLAINTEXT: hello world
