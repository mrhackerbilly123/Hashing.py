# 🔐 Password Hasher with Salt (Python)

A simple Python script that hashes a password using a random salt and the SHA-512 algorithm.  
This shows how secure password storage works in real systems.

---

## 📌 Overview

This project uses Python’s built-in `hashlib` and `os` modules to:

- Generate a random salt
- Combine the salt with a password
- Hash the result using SHA-512

You use this to understand how passwords are protected in databases.

---

## ⚙️ Features

- Secure random salt generation
- Strong hashing with SHA-512
- Hex output for storage
- Simple and readable code

---

## 🛠️ How It Works

- You enter a password
- A random 16-byte salt is created using `os.urandom()`
- The salt is combined with the password
- The combined value is hashed using SHA-512
- Output shows:
  - Salt (hex format)
  - Hashed password (hex format)

---

## ▶️ Usage

### 1. Clone the repository
```bash
git clone https://github.com/mrhackerbilly123/password-hasher.git
cd password-hasher
