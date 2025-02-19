# Cyber-Security
This is final Project of IBM edunet cybersecurity internship

## Project Title: Secure Data Hiding In Images Using Steganography

---

### Overview

This project is a part of the IBM Edunet Foundation Cybersecurity internship, which lasted for six Weeks. Throughout this internship, I gained practical knowledge about various cybersecurity tools and techniques, including VeraCrypt and setting up Kali Linux. The main focus of this project is to develop a steganography system to securely hide text messages within digital images.

---

### Repository Name: Deepakkhulve-Cyber-Security-Project

---

### Files in the Repository:

- `stego.py`: Script for encoding secret messages into images and Script for decoding hidden messages from images.
- `Deepak Khulve PPT of Cyber Security Steganography Project.pptx`: PowerPoint presentation detailing the project.
- `encryptedImage.jpg`: Sample encrypted image with a hidden message.

---

### Project Description

**SECURE DATA HIDING IN IMAGES USING STEGANOGRAPHY:**

This project involves creating a steganographic system to embed confidential text messages into digital images using advanced encryption techniques. The project ensures that the hidden data remains imperceptible to unauthorized users while maintaining the image quality.

---

### Project Components

1. **Encryption Script (`stego.py`):**
   - Reads an input image.
   - Prompts the user for a secret message and password.
   - Embeds the secret message into the image pixels.
   - Saves the encrypted image.

2. **Decryption Script (`stego.py`):**
   - Reads the encrypted image.
   - Prompts the user for the password.
   - Extracts and decodes the hidden message from the image.
   - Displays the decoded message.
   
---   

### How to Use

1. **Encryption:**
   - Ensure `stego.py` is in the same directory as your input image.
   - Run the script and follow the prompts to input your secret message and password.
   - The script will generate an `encryptedImage.jpg` file with the hidden message.

2. **Decryption:**
   - Ensure `stego.py` is in the same directory as your encrypted image.
   - Run the script and follow the prompts to input your password.
   - The script will display the hidden message.

---

## Tools and Libraries

- Python
- Open cv2
- string
- OS
- Hardware Requirements: Decent CPU, Ample RAM, Fast storage (SSD).

---

### Cloning the Repository

To copy or clone this repository to your local machine, use the following commands:

```bash
# Clone the repository
git clone https://github.com/Deepak14Khulve/Deepakkhulve-Cyber-Security-Project.git

# Change directory to the cloned repository
cd Deepakkhulve-Cyber-Security-Project
