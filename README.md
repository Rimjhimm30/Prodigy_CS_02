# Prodigy_CS_02
PixelCrypt is a command-line tool for encrypting and decrypting data using pixel manipulation in images. It utilizes the least significant bits (LSBs) of pixel values to hide and retrieve encrypted data.

Features:
1. Encrypts data using pixel manipulation in images
2. Decrypts encrypted data from images
3. Supports various image formats (e.g., PNG, JPEG, BMP)
4. Cross-platform compatibility (Windows and Linux)
5. Command-line interface for easy automation

Encryption Process:
1. Convert input data to binary
2. Hide binary data in the LSBs of pixel values
3. Save the modified image

Decryption Process:

1. Extract LSBs from pixel values
2. Convert extracted bits to binary data
3. Save decrypted data to output file

