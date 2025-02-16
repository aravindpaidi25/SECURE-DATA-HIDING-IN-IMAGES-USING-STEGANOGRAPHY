# SECURE-DATA-HIDING-IN-IMAGES-USING-STEGANOGRAPHY

## 📌 Project Overview  
This project implements a simple **steganography technique** to hide secret messages within images by modifying pixel values based on ASCII mappings. It also includes a **password-protected decryption process** to retrieve hidden messages.  

## Features  
✔️ Hide secret messages within an image using pixel manipulation  
✔️ Password-protected decryption for restricted access  
✔️ Simple and lightweight implementation using Python  
✔️ Works with any image format supported by OpenCV  
✔️ Beginner-friendly code for learning steganography  

## Technologies Used  
- **Python** – Programming language  
- **OpenCV (`cv2`)** – Image processing and manipulation  
- **OS Module** – Handling system operations  

## Installation & Usage  

###  Prerequisites  
Make sure you have **Python 3.x** installed along with the required libraries:  
```sh
pip install opencv-python
```

###  How to Run  

1. Clone this repository:  
   ```sh
   git clone https://github.com/your-username/steganography.git
   cd steganography
   ```
2. Place your **image** inside the project folder and update the script with its path.  
3. Run the script:  
   ```sh
   python stego.py
   ```
4. Enter the secret message and a password for encryption.  
5. The script generates an **encrypted image** containing the hidden message.  
6. Run the script again and enter the correct password to **decrypt** the hidden message.  

##  Limitations & Future Enhancements  
🔴 **No encryption** – Direct ASCII mapping makes it vulnerable to attacks.  
🔴 **Hardcoded image path** – Needs manual updates for different images.  
🔴 **Basic pixel allocation** – Can lead to data loss in large messages.  

**Future Improvements:**  
- Implement **AES encryption** for secure message encoding.  
- Use **randomized pixel mapping** to improve security.  
- Support **larger message sizes** with optimized storage techniques.  

##  End Users  
This project is useful for **cybersecurity enthusiasts, students, forensic analysts, and privacy-conscious individuals** interested in data hiding techniques.  


