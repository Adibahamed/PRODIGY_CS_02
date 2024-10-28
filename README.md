PIXEL MANIPULATION FOR IMAGE ENCRYPTION

This project is a basic image encryption and decryption tool that uses pixel manipulation to modify images, making them unrecognizable until decrypted.

Features
Encrypts images by modifying pixel values based on a key.
Decrypts images by reversing the pixel modification to restore the original image.
Note: This encryption method is educational and not secure for sensitive data.

Requirements
Python 3.x
Pillow and NumPy libraries

Install the required libraries with:
pip install Pillow numpy

Usage
1. Clone the Repository
Clone this repository to your local machine and navigate to the project folder.
2. Prepare an Image
Save the image you want to encrypt in the project folder and note its file path.
3. Encrypt the Image
Use the encrypt_image function to apply encryption by providing:
The input image path
The output path for saving the encrypted image
An optional integer key (used for both encryption and decryption)
4. Decrypt the Image
Use the decrypt_image function to restore the original image by providing:

The encrypted image path
The output path for saving the decrypted image
The same key used during encryption
Notes
Ensure the same key is used for both encryption and decryption.
This tool is a demonstration of basic pixel manipulation, not intended for real-world security.
License
This project is licensed under the MIT License.
