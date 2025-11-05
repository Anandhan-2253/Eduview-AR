# 🎓 Educational Keylogger - Cybersecurity Awareness Demonstration Tool

## 📌 Overview
**Educational Keylogger** is a Python-based security demonstration tool designed to showcase how keyloggers operate and raise awareness about cybersecurity threats.  
This tool captures keystrokes and sends them to a Telegram bot at configurable intervals, serving as an **educational demonstration** of how malicious software can compromise personal information.

Built using Python with keyboard monitoring capabilities, this project helps students and security professionals understand the importance of downloading software from trusted sources and implementing proper security measures.

---

## 🚀 Key Features

### ⌨️ Advanced Key Capture
Accurately captures all keystrokes including special keys, function keys, and modifier combinations with enhanced accuracy.

### 🤖 Telegram Integration
Automatically sends captured data to a Telegram bot at configurable intervals with formatted reports.

### ⏰ Flexible Timing Options
Configurable auto-send intervals (default: **20 seconds**) and manual trigger capability using hotkeys.

### 📊 Detailed Logging System
Comprehensive logging with timestamps, key details, session information, and local JSON backups.

### 🔧 Manual Control
Instant manual data transmission using **Ctrl + Alt + M** hotkey for on-demand demonstrations.

### 💾 Local Data Backup
Automatic local backup of all captured data in structured **JSON** format for analysis.

---

## 🛠️ Tech Stack

| Component | Technology |
|------------|-------------|
| **Language** | Python 3.6+ |
| **Key Monitoring** | `keyboard` library |
| **Data Transmission** | `requests` (Telegram Bot API) |
| **Data Format** | JSON for local storage |
| **Multithreading** | `threading` module |
| **Platform** | Cross-platform (Windows, Linux, macOS) |

---

## 🎯 Educational Purpose & Impact

**Educational Keylogger** is designed to demonstrate real-world cybersecurity threats in a **controlled environment**. It helps:

- 🧠 **Understand Malware Operations:** Show how keyloggers capture sensitive information  
- 🔐 **Raise Security Awareness:** Demonstrate the importance of software source verification  
- 🛡️ **Teach Prevention Methods:** Highlight antivirus and monitoring solutions  
- 👨‍🏫 **Support Cybersecurity Education:** Provide hands-on demonstration for security courses  

**Ideal for:**
- Cybersecurity students and educators  
- Penetration testers (with authorization)  
- Security awareness training workshops  
- Ethical hacking demonstrations  

---

## ⚠️ Legal & Ethical Disclaimer

### 🔒 IMPORTANT NOTICE:
This tool is created **STRICTLY FOR EDUCATIONAL PURPOSES ONLY**.  
Unauthorized use is **illegal and unethical**.

#### ✅ Permitted Uses:
- Educational demonstrations in academic settings  
- Authorized penetration testing with written consent  
- Cybersecurity awareness training  
- Personal systems you own  

#### ❌ Prohibited Uses:
- Unauthorized surveillance  
- Installing on systems without explicit permission  
- Malicious or unethical activity  
- Violating privacy laws  

> Users must ensure:  
> - Proper authorization is obtained before testing  
> - Compliance with local laws and regulations  
> - Use only in controlled, educational environments  
> - Responsible disclosure and ethical handling  

---

## 📋 Quick Start

### 🔧 Prerequisites
- Python 3.6 or higher  
- Telegram account (for bot creation)  
- Required packages: `keyboard`, `requests`

---

### 💻 Installation

```bash
git clone https://github.com/yourusername/educational-keylogger.git
cd educational-keylogger
pip install -r requirements.txt
