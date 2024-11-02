# Password Encrypter 🔒

**Project Name:** `passwordEncrypter.py`  
**Created by:** Coderip & JBandzCode  
**License:** MIT License  

---

## 📖 Overview

`passwordEncrypter.py` is a simple yet powerful script designed to securely encrypt and decrypt passwords. This standalone Python file is ideal for anyone looking to protect sensitive data with minimal setup.

## 🔑 Key Features

- **AES-256 Encryption**: Uses AES encryption to secure passwords.
- **Password Hashing**: Adds an extra layer of security with hashing.
- **User-Friendly CLI**: Interact with the script via a command-line interface for encrypting and decrypting passwords.

## 🛠️ Installation

1. **Prerequisites**: Make sure Python 3.7+ is installed.
2. **Install Dependencies**: The script requires the `cryptography` library.

   ```bash
   pip install cryptography
   ```

3. **Download the Script**: Clone the repository or download the `passwordEncrypter.py` file.

---

## 🚀 Usage

### Basic Commands

1. **Encrypt a Password**

   To encrypt a password, run:

   ```bash
   python passwordEncrypter.py --encrypt
   ```

   You will be prompted to enter the password you want to encrypt. The script outputs the encrypted version.

2. **Decrypt a Password**

   To decrypt an encrypted password:

   ```bash
   python passwordEncrypter.py --decrypt
   ```

   Enter the encrypted password, and the script returns the original password if authenticated.

3. **Generate a Strong Password**

   Use the `--generate` option to create a random strong password.

   ```bash
   python passwordEncrypter.py --generate
   ```

---

## 🔐 How It Works

1. **AES Encryption**: The script uses AES-256 to securely encrypt passwords, ensuring they are safe from unauthorized access.
2. **Master Key**: Protects your passwords with a unique master key, allowing only you to decrypt stored information.
3. **Password Storage**: Encrypted passwords can be stored locally in your preferred file or environment.

---

## 📂 Example Usage

```bash
# Encrypting a password
python passwordEncrypter.py --encrypt

# Decrypting a password
python passwordEncrypter.py --decrypt

# Generating a random strong password
python passwordEncrypter.py --generate
```

---

## 📜 License

This project is licensed under the MIT License. See the LICENSE file for details.
