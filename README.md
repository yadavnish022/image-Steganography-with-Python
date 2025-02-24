## **Image Steganography: Encryption & Decryption**

This project implements **image steganography**, allowing users to hide secret messages inside images and retrieve them using encryption and decryption techniques.

### **Features**
- Encrypts a secret message into an image.
- Requires a passcode for security.
- Extracts the hidden message from an image.
- Uses **OpenCV** and **Tkinter** for image processing and file selection.

---

## **Installation**
Ensure you have **Python 3.x** installed along with the required dependencies.

### **Install Dependencies**
```bash
pip install opencv-python tkinter
```

---

## **Usage**

### **Encryption**
1. Run the encryption script:
   ```bash
   python encryption.py
   ```
2. Select an image file.
3. Enter a **secret message** to hide.
4. Set a **passcode** for security.
5. The script generates:
   - `encryptedImage.jpg` (image containing the hidden message)
   - `password.txt` (stores the passcode)

### **Decryption**
1. Run the decryption script:
   ```bash
   python decryption.py
   ```
2. Select the **encrypted image**.
3. Select the **password file**.
4. Enter the passcode.
5. If the passcode is correct, the message is extracted and saved as `decrypted_message.txt`.

---

## **Files Overview**
- **`encryption.py`** → Encrypts a message into an image.
- **`decryption.py`** → Extracts the hidden message from an image.
- **`stego.py`** → Experimental version of encryption & decryption (simplified).

---

## **Notes**
- The **image should not be resized or modified** after encryption, as it may corrupt the hidden message.
- Ensure the **correct password** is used during decryption.

---

## **License**
This project is **open-source** and free to use.
