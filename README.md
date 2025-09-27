# Cipher Implementation Showcase

[![Live Demo](https://img.shields.io/badge/🔗%20Live%20Demo-0a0a0a?style=for-the-badge&logo=google-chrome&logoColor=white)](https://anukriti2306.github.io/cryptography/)  
![Made with HTML5](https://img.shields.io/badge/Made%20with-HTML5-orange?style=for-the-badge&logo=html5)  
![Made with JavaScript](https://img.shields.io/badge/Made%20with-JavaScript-yellow?style=for-the-badge&logo=javascript)  
![Status](https://img.shields.io/badge/Status-Research%20Demo-lightgrey?style=for-the-badge)  

---

## Purpose

The project aims to provide a **didactic and experimental tool** that enables students, researchers, and educators to:

- Explore the working of **classical substitution ciphers** (Caesar and Vigenère).  
- Understand the principles of **public-key cryptography** through RSA.  
- Experiment with encryption, decryption, and key generation in real time.  
- Compare the **strengths and weaknesses** of classical and modern ciphers.  

---

## Implementation Details

- **Language & Frameworks:** Implemented in **HTML5**, **Tailwind CSS**, and **vanilla JavaScript**.  
- **Portability:** Distributed as a single `index.html` file. No dependencies or installation required.  
- **Execution:** Runs entirely in-browser, ensuring reproducibility and ease of deployment.  
- **RSA Implementation:** Simplified for demonstration purposes. Key generation uses user-provided primes; real-world cryptography requires large primes and secure padding schemes.  

---

## Features

- **Multiple Cipher Support** – Caesar, Vigenère, and RSA within one interface.  
- **Interactive Demonstration** – Users can input plaintext, ciphertext, and keys to observe transformations in real time.  
- **RSA Key Generation** – Generates public and private key pairs from user-specified primes.  
- **Responsive Design** – Interface adapts to desktops, tablets, and mobile devices.  
- **Lightweight and Accessible** – Requires only a modern web browser.  

---

## Educational Notes

- **Caesar Cipher:** Demonstrates a simple monoalphabetic substitution cipher; vulnerable to frequency analysis.  
- **Vigenère Cipher:** Introduces polyalphabetic substitution; more complex but still breakable with modern techniques.  
- **RSA:** Illustrates the principles of asymmetric encryption; demonstrates modular exponentiation and key pair generation.  

⚠️ **Disclaimer:** The implementations are intended for **educational and research demonstration** only and are **not suitable for production cryptography**.

---

## Usage

1. Download or clone the repository.  
2. Open `index.html` in a modern browser.  
3. Select a cipher tab and enter the required parameters (plaintext, key, primes, etc.).  
4. View encryption/decryption results in real time.  

Alternatively, access the [![Live Demo](https://img.shields.io/badge/🔗%20Live%20Demo-0a0a0a?style=for-the-badge&logo=google-chrome&logoColor=white)](https://anukriti2306.github.io/cryptography/).  

---

## Deployment (Optional)

To host this tool independently:  
1. Fork or clone this repository.  
2. Ensure the main file is named `index.html`.  
3. Enable GitHub Pages in repository settings.  

---

## Citation

If you use this project as part of your research or teaching, please cite it appropriately.

