# PRODIGY_CS_01
#Python program that can encrypt and decrypt text using the Caesar Cipher algorithm. Allow users to input a message and a shift value to perform encryption and decryption.
How the Program Works:

    caesar_cipher_encrypt(text, shift):
        This function takes a string text and an integer shift as input.
        It iterates through each character in the string. If the character is a letter, it shifts it by the specified amount. The shift wraps around the alphabet if necessary.
        Non-letter characters are added to the result without change.

    caesar_cipher_decrypt(text, shift):
        This function simply calls caesar_cipher_encrypt with the negative shift value to reverse the encryption.

    main():
        This function serves as the user interface.
        It prompts the user to choose whether to encrypt or decrypt a message.
        It then asks for the text and the shift value.
        Depending on the choice, it calls the appropriate function and prints the result.

To run the program, simply copy the code into a Python environment and execute it. You will be prompted to input whether you want to encrypt or decrypt, followed by the text and the shift value. The program will then output the encrypted or decrypted text accordingly.
