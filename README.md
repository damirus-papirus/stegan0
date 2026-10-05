# stegan0

[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)]()
[![Made with](https://img.shields.io/badge/made%20with-Python-1f425f.svg)](https://www.python.org/)

[![Download for Windows](https://img.shields.io/badge/download-Windows-blue?logo=windows&style=for-the-badge)](https://github.com/damirus-papirus/stegan0/releases/latest/download/stegan0.exe)
[![Download for Windows (CLI)](https://img.shields.io/badge/download-Windows_(CLI)-blue?logo=windows&style=for-the-badge)](https://github.com/damirus-papirus/stegan0/releases/latest/download/stegan0-cli.exe)

---

**PNG steganography with AES-GCM encryption.**

`stegan0` hides arbitrary files inside PNG images so that visually they remain unchanged. Before embedding, data is encrypted with a password, and bits are scattered across the entire image in a pseudorandom order — without the password, extraction is impossible.

<p align="center">
  <img src="docs/demo.gif" alt="stegan0 demo" width="640">
</p>

---

## ✨ Features

- 🔐 **AES-GCM** — authenticated encryption, catches any bit tampering
- 🔑 **PBKDF2-HMAC-SHA256, 300,000 iterations** — slows down password brute-forcing
- 🎲 **Pseudorandom pixel order** — positions depend on the password
- 📦 **Hides any file** — text, archives, documents, images
- 🖥 **Tkinter GUI** — simple and intuitive
- ⌨️ **CLI** — for scripting and automation
- 📊 **Capacity display** — see immediately whether a file fits
- 🎯 **Integrity check** — corrupted data won't decrypt

---

## 📋 Requirements

- **OS:** Windows only
- **PNG only** for the container (JPEG and other lossy formats will destroy the data)

## Files

- **Windows:** 

