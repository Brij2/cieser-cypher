# Caesar Cipher Program

<video width="600" autoplay loop muted>
  <source src="VIDEO_URL_HERE" type="video/mp4">
  Your browser does not support the video tag.
</video>

This is a Python program that implements a menu-driven Caesar cipher algorithm with the following operations:

## Encrypt Plain Text
## Decrypt Cipher Text
## Show All Combinations
## Show Meaningful Decryptions
### Exit
The program allows you to perform encryption, decryption, and analysis of text using the Caesar cipher. It provides options to interactively choose the operation you want to perform.

## Prerequisites
Make sure you have Python installed on your system. You can download Python from the official website: https://www.python.org/downloads/

To use the nltk library for checking meaningful English words, you need to install it. You can install it using the following command:

```bash
pip install nltk
```
## How to Use
Clone or download this repository to your local machine.

Open a terminal or command prompt and navigate to the directory containing the downloaded files.

## Run the program:

```bash
python caesar_cipher.py
```
The program will display a menu with different options. Choose an option by entering the corresponding number and follow the prompts.

## Features
1. **Encrypt Plain Text**
This option allows you to encrypt plain text using the Caesar cipher. Enter the plain text and a key to perform the encryption.

2. **Decrypt Cipher Text**
Use this option to decrypt cipher text using the Caesar cipher. Enter the cipher text and the corresponding key to reveal the original message.

3. **Show All Combinations**
This option displays all 26 possible combinations of decrypting a given cipher text. It shows the decrypted text for each key.

4. **Show Meaningful Decryptions**
Choose this option to display meaningful decryptions of a cipher text. The program uses the nltk library to check if words in the decrypted text are meaningful English words. It shows the decrypted text, key, and the probability of meaningful words.

5. **Exit**
Select this option to exit the program.

## Customization
You can modify the is_english_word function in the caesar_cipher.py file to use a more advanced English word checking mechanism if needed.

## Credits
This program was created by Brijesh Kumar.
