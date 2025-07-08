# 🛡️ CSOC_INFOSEC – My Infosec Journey (CSOC 2025)

Welcome to my personal walkthrough of the **CSOC 2025 Infosec Track**. This repository contains my writeups, scripts, challenges, and research notes week-by-week, as I explored various fields of cybersecurity — from Linux basics to cryptography, digital forensics, OSINT, and web vulnerabilities.

---

## 📁 Structure

Each week has its own subfolder (linked as Git submodules), making this a centralized collection of my work:

| Week | Topic                           | Repository Link                                                  |
|------|----------------------------------|------------------------------------------------------------------|
| 0    | 🐧 Basics of Hacking & Setup     | [Week_0_Infosec_CSOC](https://github.com/suryansh00001/Week_0_Infosec_CSOC) |
| 1    | 🕵️ Digital Forensics & OSINT    | [Week_1_Infosec_CSOC](https://github.com/suryansh00001/Week_1_Infosec_CSOC) |
| 2    | 🔐 Cryptography                  | [Week_2_Infosec_CSOC](https://github.com/suryansh00001/Week_2_Infosec_CSOC) |
| 3    | 🌐 Web Exploitation & Security   | [Week_3_Infosec_CSOC](https://github.com/suryansh00001/Week_3_Infosec_CSOC) |

> Each subrepo includes detailed writeups, resources I referred, solutions, and extra notes.

---

## ✨ Weekly Overview

### 🗓️ Week 0 – Baby Steps

- Set up Ubuntu (Dual Boot)
- Explored Linux CLI, Bash scripting
- Learned basics of:  
  - 🧠 C (Beej's Guide + BroCode)  
  - 🐍 Python (BroCode + practice scripts)  
  - 🔧 Bash  
  - 🌐 JavaScript (optional)
- Challenge: [Bandit Wargame](https://overthewire.org/wargames/bandit/)
- Mini-projects coded:
  - Russian Roulette
  - File-based To-Do List (multi-user support)
  - Simple sorting algorithm
  - ⭐ Custom language interpreter (basic syntax + operations)

---

### 🗓️ Week 1 – Digital Forensics & OSINT

- Learned about:
  - Image steganography
  - Metadata analysis
  - Hidden files and encodings
- Tools used: `exiftool`, `binwalk`, `strings`, `stegsolve`
- OSINT tasks done via:
  - Whois, Shodan, Google Dorking
  - TryHackMe and Gralhix exercises
- 📁 Notes on mindset and methodology for CTI

---

### 🗓️ Week 2 – Cryptography

- Explored:
  - Classic ciphers (ROT13, Vigenère, XOR, Rail-fence)
  - RSA basics and vulnerabilities
  - AES structure and symmetric crypto
- Platforms used:
  - [CryptoHack](https://cryptohack.org/)
  - [CyberChef](https://gchq.github.io/CyberChef/)
  - [DCode.fr](https://www.dcode.fr/en)
- Highlights:
  - RSA modular inverse in Python
  - XOR cipher crackers
  - Notes on entropy and OTP issues

---

### 🗓️ Week 3 – Web Security

- Studied common vulnerabilities:
  - ✅ XSS (Reflected & Stored)
  - ✅ SQL Injection
  - ✅ Open Redirect
  - ✅ CSRF & IDOR
  - ✅ LFI & SSTI
- Practiced on:
  - PicoCTF Web Challenges
  - Hands-on with Burp Suite
  - Cookie/Session manipulation
- Learned basics of:
  - HTML DOM exploitation
  - JavaScript obfuscation analysis

---

## 🛠️ Cloning With Submodules

If you want to explore the work in all weeks:

```bash
git clone --recurse-submodules https://github.com/suryansh00001/CSOC_INFOSEC.git
```

If already cloned:

```bash
git submodule update --init --recursive
```

---

## 📌 Notes

- This repo is purely for **learning purposes**.
- All challenges were solved independently or with proper citations.
- Writeups are documented in Markdown/PDF inside respective week folders.

---

## 🙋 About Me

**Suryansh Garg**  
1st-year Undergraduate | IIT BHU  
Roll No. - 24064029

##Exploring cybersecurity and system internals with curiosity and consistency.

GitHub: [@suryansh00001](https://github.com/suryansh00001)

---

> 🧠 _“Hacking is not always about breaking. It's about discovering.”_
