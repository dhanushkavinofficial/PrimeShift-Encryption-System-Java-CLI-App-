# PrimeShift-Encryption-System-Java-CLI-App-
This is not production crypto (like AES), but it's mathematically structured and great for showcasing DSA + math thinking.
# 🔐 PrimeShift Encryption System (Java)

A mathematical encryption system built using prime numbers, modular arithmetic, and dynamic shifting logic.

This project demonstrates:

* Prime number validation
* Prime-based key generation
* Modular arithmetic encryption
* Reversible decryption algorithm
* Clean Java architecture (single code base)

---

## 🚀 Features

* Prime number validation
* Dynamic shift based on nearest prime
* Modular ASCII transformation
* Full encryption & decryption cycle
* CLI-based execution

---

## 🧠 Encryption Logic

1. User provides:

   * Message
   * Prime key

2. System:

   * Validates prime key
   * Finds next prime number
   * Uses formula:

   EncryptedChar = (ASCII + primeKey + nextPrime) % 256

3. Decryption reverses the process:

   OriginalChar = (EncryptedASCII - primeKey - nextPrime + 256) % 256

---
## 🛠 How to Run

```bash
javac PrimeShiftEncryption.java
java PrimeShiftEncryption
```
---

## 📌 Example

Input:
Message: HELLO
Prime Key: 11

Encrypted Output:
]bffl

Decrypted Output:
HELLO
---
## 📂 Project Structure

PrimeShiftEncryption.java

Single-file architecture.
---
## ⚠ Disclaimer

This is an educational encryption model.
Not suitable for production-level security.
---

## 👨‍💻 Author

Built for mathematical and algorithmic learning.
