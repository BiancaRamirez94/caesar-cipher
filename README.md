# caesar-cipher

This is a Python program that implements the Caesar cipher, a simple encryption technique that involves shifting the letters of the alphabet by a certain amount.

# How to Use
Run the program in a Python environment.
The program will display the ASCII art of the logo from art.py.
The program will then prompt the user to choose whether to encrypt or decrypt a message.
The user will be prompted to enter the message they wish to encrypt/decrypt and the shift amount to use.
The program will apply the Caesar cipher to the message and display the result.
The program will then ask the user if they want to restart the cipher program. If the user enters 'yes', they will be prompted again to choose whether to encrypt or decrypt a message and to enter a message and shift amount. If the user enters 'no', the program will end.

# Notes
The program uses the English alphabet, with the letters wrapped around to the beginning of the alphabet if necessary (e.g. shifting 'z' by 1 gives 'a').
Non-alphabetic characters (such as spaces and symbols) are preserved in the output.
The program handles shifts greater than 26 by taking the modulus of the shift amount with 26.
The program uses the art.py module to display the logo at the start of the program. This file must be in the same directory as the program file for the logo to display properly.
