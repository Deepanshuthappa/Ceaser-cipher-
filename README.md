# PRODIGY_CS_01

Encryption/Decryption program

# Objective
The objective of this project is to implement the Caesar Cipher encryption and decryption algorithm in Java. The program allows users to input text and a shift value to either encrypt or decrypt the text using the Caesar Cipher technique.

# Description
The Caesar Cipher is a simple substitution cipher where each letter in the plaintext is shifted a certain number of places down or up the alphabet. The shift value determines the number of positions each character in the plaintext is shifted.

This program provides two main functionalities:

Encrypt: Shifts each letter in the input text by the given shift value.
Decrypt: Shifts each letter in the input text backwards by the given shift value.
The program also handles both uppercase and lowercase letters, maintaining their case, and leaves non-alphabet characters unchanged.

# Usage
Prerequisites
Java Development Kit (JDK) installed on your system.
A text editor or an Integrated Development Environment (IDE) for Java.
Installation
Clone the repository or copy the code:
Save the provided Java code in a file named CaesarCipher.java.

Compile the code:
Open your terminal or command prompt and navigate to the directory where the CaesarCipher.java file is located. Run the following command to compile the Java file:
javac CaesarCipher.java
Run the program:
After successful compilation, run the program using the following command:
java CaesarCipher

## How to Use
Select Operation:

When prompted, type encrypt to encrypt a text or decrypt to decrypt a text.

Enter Text:
Input the text you wish to encrypt or decrypt.

Enter Shift Value:
Input the shift value (an integer). The shift value determines how many positions each character in the text will be shifted.



## Example

Do you want to encrypt or decrypt the text? (Type 'encrypt' or 'decrypt'): encrypt
Enter the text: Hello, World!
Enter the shift value: 3
Encrypted text: Khoor, Zruog!

Do you want to encrypt or decrypt the text? (Type 'encrypt' or 'decrypt'): decrypt
Enter the text: Khoor, Zruog!
Enter the shift value: 3
Decrypted text: Hello, World!
Code Explanation
The program consists of the following main parts:

## Encrypt Method:

Shifts each letter in the input text by the shift value.
Handles both uppercase and lowercase letters.
Leaves non-alphabet characters unchanged.
## Decrypt Method:

Shifts each letter in the input text backwards by the shift value.
Handles both uppercase and lowercase letters.
Leaves non-alphabet characters unchanged.

## Main Method:

Takes user input for operation type, text, and shift value.
Calls the appropriate method (encrypt or decrypt) based on the user input.
Outputs the result.

## OUTPUT : 
![Screenshot 2024-08-19 114454](https://github.com/user-attachments/assets/b078d06d-b60d-43db-afc5-0ae38d936211)


## Contact
For any questions or suggestions, please contact [Deepanshu thappa] at [deepanshuthappa51@gmail.com].

