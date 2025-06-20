
# Tamper-Proof Digital Credential Verification Using Blockchain and Capsule Siamese Networks

## 📜 Overview

This project aims to modernize and secure digital credential management by leveraging Blockchain Technology, Capsule Siamese Networks, and One-Time Symmetric Key Encryption. It addresses the growing concerns around certificate forgery and inefficient manual verification processes by offering a robust, scalable, and tamper-proof solution for issuing and verifying educational certificates.

## 🧠 Key Features

🔒 Tamper-proof storage using Blockchain with cryptographic hash functions

🤖 Forgery detection via Capsule Siamese Neural Networks

🗝️ Secure data transmission using One-Time Symmetric Key encryption

🌐 Role-based web interface for Issuers, Holders, and Verifiers

⚠️ Real-time fraud alerts and tampering notifications

🔄 Blockchain immutability with decentralized trust

📲 Certificate locker web app for secure access and sharing

🧪 Rigorous testing including black-box and white-box methodologies

## 📁 Project Structure

<pre lang="bash"> 
/certificate-verification/
│
├── /static/                  # Static files (CSS, JS, encrypted files)
├── /templates/               # HTML templates (Jinja2 with Flask)
├── /upload/                  # Certificate upload directory
├── /decrypted/               # Decrypted certificate files
├── app.py                    # Flask application entry point
├── blockchain.py             # Blockchain logic and structure
├── siamese_model.py          # Capsule Siamese Network for forgery detection
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation </pre>

## 🔧 Tech Stack
* Frontend: HTML5, CSS3, Bootstrap 4

* Backend: Python 3.7.4, Flask 1.1.1

* Blockchain: Custom implementation with JSON structure

* AI/ML: Capsule Siamese Networks (PyTorch, TensorFlow, Pillow)

* Database: MySQL

* Security: One-Time Symmetric Key Encryption (Fernet, PBKDF2, AES)

* Server: WampServer 2i

## 👨‍💼 User Roles
 * Certificate Issuer
    - Generates and uploads verified certificates
    - Issues hard/soft copies and stores hash on blockchain

* Certificate Holder
  - Uploads certificates

  - Receives UCIC & key

  - Verifies integrity and shares verification link

* Certificate Verifier
  Requests and verifies certificate authenticity using blockchain and AI tamper detection

## 🛡️ Security Modules
 * Blockchain Layer: Stores hashes of certificates and tracks their transactions

 * Capsule Siamese Networks: Locates and identifies tampered certificate content

 * Symmetric Encryption: One-time key encryption for secure certificate exchange

## 🚀 How to Run

 ### 📥 Clone the Repository 
 ```bash 
 git clone https://github.com/Seshwarbabu19/certificate-verification.git
 cd certificate-verification 
 ```
 ### 📦 Install Dependencies 
 ```bash 
 pip install -r requirements.txt
```
 ### ▶️ Run the App 
 ```bash 
 python app.py
```
 ### 🌐 Access via Browser 
 ```bash 
 http://127.0.0.1:5000
```
