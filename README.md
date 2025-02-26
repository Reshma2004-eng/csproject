Secure Data Hiding in Images Using Steganography
Overview
This project implements a simple yet effective steganographic technique to hide secret messages within images using pixel manipulation. The message can only be retrieved with the correct passcode, ensuring secure and confidential data transmission.

Features
✅ Hide text messages inside an image without noticeable changes.
✅ Password-protected decryption for added security.
✅ Lightweight and fast execution.
✅ Works offline for complete privacy.
✅ Simple and easy-to-use implementation with OpenCV.

Technologies Used
Python
OpenCV (cv2) for image processing
OS Module for system commands
Installation & Setup
Clone the Repository:
  git clone https://github.com/Reshma2004-eng/csproject.git
cd your-repository;
   Install Dependencies
pip install opencv-python:
    Run the Program
python steganography.py
How It Works
The user inputs a secret message and a passcode.
The message is embedded into the image using pixel value modifications.
The modified image is saved as encryptedImage.jpg.
For decryption, the user enters the correct passcode to retrieve the hidden message.
Usage Example
Encoding a Message:
Provide a secret message and a passcode.
The program modifies the image and saves it.
Decoding a Message:
Enter the passcode to extract the hidden message.
Future Improvements
🔹 Stronger encryption before embedding messages
Contributing
We welcome contributions! Feel free to open issues or submit pull requests.
License
This project is open-source.

