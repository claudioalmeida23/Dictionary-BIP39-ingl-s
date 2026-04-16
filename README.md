# Dictionary BIP39

A lightweight, responsive, and high-performance web tool for browsing and exploring the BIP-39 mnemonic dictionary. Designed to assist developers and cryptography enthusiasts in quickly and accurately verifying word indices and entries.

## 🚀 Features

- **Dual Search:** Find words by their text or numerical index.  
- **Zero-Based Indexing:** Aligned with programming logic (0–2047), making integration with Python scripts and other languages easier.  
- **Dark Mode Interface:** Modern design with orange accents, optimized for long working sessions.  
- **Fully Responsive:** Automatically adapts to desktops, tablets, and smartphones.  
- **Zero Dependencies:** Built purely with HTML, CSS, and Vanilla JavaScript to ensure maximum security and performance.  

## 🛠️ Technical Specifications

The project uses the **BIP-39 (Bitcoin Improvement Proposal 39)** standard, which consists of a list of 2048 carefully selected words used to generate seed phrases for cryptocurrency wallets.

### The Zero Index Logic
Unlike typical text lists opened in simple editors, this explorer uses indexing starting at **0**.  
- **First Word (`abandon`):** Index 0  
- **Last Word (`zoo`):** Index 2047  

This approach eliminates the need for manual offset calculations when mapping indices into recovery or key derivation algorithms.

## 📂 Repository Structure

- `index.html`: Main file containing structure, styles, and search logic.  
- `README.md`: Project documentation and guide.  

## 🌐 Acessar o Site Versão DEMO

Você pode usar a aplicação diretamente pelo link abaixo:

🔎 **:**
(https://dictionarybip39.netlify.app/)



## 🖥️ How to Use

1. Download or clone this repository.  
2. Open the `index.html` file in any modern browser.  
3. Use the search bar at the top to instantly filter the list by name or number.  

---

## ✒️ Credits

Developed by **Claudio Almeida.CAAS**.

---

### ⚠️ Security Notice
*This tool is strictly for educational and reference purposes. Never enter your real seed phrase (your 12 or 24 words) on third-party websites or in any internet-connected environment that you do not fully trust and control.*
