# Steganography
Secure Data Hiding in Images using Steganography (Python)
This project presents an image steganography technique that allows users to securely embed and retrieve hidden messages within images. Built using Python and OpenCV, the application ensures lossless data hiding while maintaining image integrity. A Tkinter-based GUI makes the encryption and decryption process user-friendly and accessible.

## Features
- Data Embedding (Encryption)
  - Securely hides a text message inside an image without altering its visible quality.
  - Each character's ASCII value is embedded diagonally within pixel data for effective concealment.
  - Saves the modified image in PNG format to maintain data integrity.
- Message Extraction (Decryption)
  - Extracts the hidden message from the modified image.
  - Requires the correct passcode and message length for secure retrieval.
- User-Friendly GUI
A Tkinter-based graphical interface simplifies the entire process:
  - Select a Cover Image – Upload an image for embedding the message.
  - Enter Secret Message & Passcode – Protect the hidden text with a passcode.
  - Encrypt & Save Image – Securely embed the message within the image.
  - Upload Encrypted Image – Select an image containing a hidden message.
  - Decrypt & Retrieve Message – Extract and display the hidden text.

## Requirements
- Python 3.x
- [OpenCV](https://pypi.org/project/opencv-python/)
  ##### Install via pip:
    ```sh
    pip install opencv-python


