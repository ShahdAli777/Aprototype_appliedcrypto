# Unit 5a – Mini Project 1

## Web Cryptography Implementation Using JavaScript (WebCrypto API)

This project demonstrates how **modern cryptographic algorithms can be implemented directly in the browser using JavaScript** through the **WebCrypto API**.

The goal of this mini-project is to integrate multiple cryptographic functions into **one single web application**, allowing users to perform encryption, hashing, and digital signatures by clicking buttons.

---

# Project Objectives

The project integrates several cryptographic techniques into a **single web page interface**:

* Symmetric Encryption
* Hashing Algorithms
* Elliptic Curve Digital Signatures
* RSA Digital Signatures

All cryptographic operations are implemented using the **browser's built-in WebCrypto API**, which provides secure and efficient cryptographic functions.

---

# Features Implemented

## 1. Symmetric Encryption

The web page allows users to perform encryption using the following **AES modes**:

* AES-GCM
* AES-CBC
* AES-CTR

Each encryption mode is triggered using a **dedicated button**, allowing users to easily test and compare the different AES encryption schemes.

### Functions

* Encrypt message
* Decrypt ciphertext
* Generate encryption key
* Display encrypted output

---

## 2. Hashing Algorithms

The project includes hashing functionality using the following algorithms:

* SHA-1
* SHA-256
* SHA-384
* SHA-512

Instead of using a dropdown menu, the hashing algorithms are triggered using **individual buttons**, making it easier to test each hashing function directly.

### Functions

* Input message
* Generate hash
* Display hash output

---

## 3. ECC Digital Signatures

The system integrates **Elliptic Curve Cryptography (ECC)** signing methods using the WebCrypto API.

Supported options:

* P256 / SHA-1
* P256 / SHA-256

Users can generate signatures and verify them using buttons.

### Functions

* Generate ECC key pair
* Sign message
* Verify signature

---

## 4. RSA Digital Signatures

RSA-based digital signatures are also implemented.

Supported options:

* RSA-1024
* RSA-2048

Buttons allow users to generate keys and sign messages using RSA.

### Functions

* Generate RSA key pair
* Sign message
* Verify signature

---

# System Architecture

The project integrates all cryptographic methods into **one single web page**.

Main components:

```
Web Browser
     |
HTML Interface
     |
JavaScript (WebCrypto API)
     |
Cryptographic Operations
```

The WebCrypto API performs all cryptographic computations securely inside the browser.

---

# Project Structure

```
webcrypto-mini-project
│
├── index.html
├── style.css
├── crypto.js
└── README.md
```

### Files Description

**index.html**
Main webpage containing the user interface and buttons for all cryptographic operations.

**style.css**
Basic styling for the webpage interface.

**crypto.js**
JavaScript code implementing all cryptographic functions using the WebCrypto API.

**README.md**
Project documentation.

---

# Technologies Used

* HTML5
* CSS
* JavaScript
* WebCrypto API

---

# How to Run the Project

1. Download or clone the repository.

git clone https://github.com/ShahdAli777/webcrypto-mini-project.git](https://github.com/ShahdAli777/Aprototype_appliedcrypto.git
```

2. Open the project folder.

3. Double-click **index.html** or open it in a browser.

Supported browsers:

* Google Chrome
* Microsoft Edge
* Firefox
* Safari

The web page will load and display buttons for all cryptographic functions.

---

# Example Usage

1. Enter a message in the input field.
2. Click one of the cryptographic buttons:

Examples:

* AES-GCM Encrypt
* SHA-256 Hash
* ECC P256 Sign
* RSA-2048 Sign

3. The output will be displayed on the page.

---

# Learning Outcomes

This project demonstrates:

* How browser-based cryptography works
* Implementation of encryption algorithms
* Hashing techniques
* Digital signature creation and verification
* Integration of multiple cryptographic methods in one interface

---

# Security Note

This project is intended for **educational purposes only**.

While the WebCrypto API provides secure implementations of cryptographic algorithms, production systems should always follow strict security best practices and key management procedures.

---

# Author

Shahd Ali Mini-Project – Unit 5a
Web Cryptography Implementation using JavaScript and WebCrypto API


