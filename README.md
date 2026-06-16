# HACKIG - Instagram Password Testing Tool

**Version:** 2.0  
**Author:** Pentest Tool  
**License:** For authorized security testing only

---

## ⚠️ LEGAL DISCLAIMER

This tool is designed **ONLY** for authorized penetration testing on accounts you own or have **explicit written permission** to test. Unauthorized use against any account is illegal and violates:

- Computer Fraud and Abuse Act (CFAA) – US
- Computer Misuse Act – UK
- Similar laws worldwide

**The author assumes NO liability for misuse of this tool.**

---

## 📋 REQUIREMENTS

### Hardware Requirements
- Android device with Termux (minimum 2GB RAM recommended)
- OR Linux/MacOS system
- Storage: ~200MB for dependencies + wordlists

### Software Requirements

#### Termux (Android)
```bash
# Core packages
pkg update && pkg upgrade -y
pkg install python git curl wget -y

# Python package manager
pkg install python-pip -y

# Optional: for better performance
pkg install openssl -y
