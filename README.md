#  EncryptEase

EncryptEase is a secure encryption application with a graphical user interface, built using Python and Tkinter. It enables users to safely encrypt text and files, verify digital signatures, and manage user authentication — all in one easy-to-use platform.

---

##  Features

-  **Text & File Encryption**
  - Encrypts text and files using a custom shifting key algorithm.
  - Key evolves per character to strengthen encryption.

-  **User Login & Registration**
  - Secure login system with password hashing.
  - Uses bcrypt for hashing and salting passwords to prevent brute-force and rainbow table attacks.

-  **Digital Signature Verification (RSA)**
  - Verifies message authenticity and integrity.
  - Generates RSA key pair (private/public) for signing and verification.
  - Ensures decryption is only allowed after successful signature verification.

-  **Data Integrity Check (SHA-256)**
  - Hashes data before signing using SHA-256.
  - Even small changes result in a different hash, ensuring data wasn’t tampered.

-  **Educational Focus**
  - Demonstrates real-world cryptographic concepts.
  - Ideal for students or beginners learning about encryption, hashing, digital signatures, and secure GUI design.


## 🛠️ Tech Stack

- **Language**: Python 3  
- **GUI**: Tkinter  
- **Cryptography**: RSA, SHA-256, bcrypt  
- **Libraries Used**:
  - `bcrypt`
  - `hashlib`
  - `tkinter`
  - `rsa` (if using an RSA lib)
  - `os`, `base64`, and standard Python modules
