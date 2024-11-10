# 🔐 File Encryption Tool

A simple and secure file encryption solution that uses **AES** encryption to protect your sensitive files. This tool allows you to easily **encrypt** and **decrypt** files using a **password-based key**, ensuring that only authorized users can access the contents. The program hashes the password with **SHA-512** and encrypts the file using **AES in CBC mode**, offering strong protection for your data. It also provides a straightforward **command-line interface** for both encryption and decryption operations.

## ✨ Features

- 🔒 Encrypt files using **AES** with a password-based key.
- 🔑 Decrypt encrypted files with the correct password.
- 🧩 Uses **SHA-512** to hash passwords for added security.
- 🖥️ Command-line interface for easy file encryption and decryption.

## 🛠️ Requirements

- Python 3.x
- Install the required dependencies with `pip`:

```bash
pip install -r requirements.txt
```

## 🚀 Installation

1. Clone this repository:

```bash
git clone https://github.com/arieg88/FileCryptor.git
```

2. Navigate to the project directory:

```bash
cd file-encryption-tool
```

3. Install the dependencies:

```bash
pip install -r requirements.txt
```

## ⚙️ Usage

### 🔒 Encrypt a file

To encrypt a file, run the following command:

```bash
python file_encryption.py lock [filename]
```

You will be prompted to enter a password. The file will be encrypted and saved with a `.encr` extension.  
💡 *Note*: The original file will **not** be deleted—only the encrypted version will be created.

### 🔓 Decrypt a file

To decrypt an encrypted file, run the following command:

```bash
python file_encryption.py unlock [filename]
```

You will be prompted to enter the password. If the correct password is provided, the file will be decrypted.

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
