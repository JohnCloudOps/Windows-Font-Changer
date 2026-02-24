# 🖥️ Windows System Font Changer

A simple registry-based tweak that changes the default Windows system font from **Segoe UI** to another installed font (example: Segoe Script).

## 📌 Project Purpose

This project demonstrates:

- Windows Registry modification
- System customization
- Understanding of Windows font substitution
- Safe rollback configuration

## ⚙️ How It Works

The registry keys modified:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Fonts  
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\FontSubstitutes  

Segoe UI is removed and replaced with a chosen installed font.

## 🚀 How To Use

1. Backup your registry (recommended).
2. Ensure the new font (e.g., Segoe Script) is installed.
3. Right-click `ChangeFont.reg` → Run as Administrator.
4. Restart your computer.

## 🔄 Restore Default Font

To revert changes:

Right click the script `RestoreDefaultFont.reg`  
click edit
navigate to bottom part where "Segoe Script" is referenced
Replace Script with UI so it reads "Segoe UI"
Click file and save
Run the script as Administrator
Restart your computer.

############################
## ⚠️ Warning

- Editing the registry incorrectly can cause system instability.
- Only use fonts already installed on your system.
- Tested on Windows 10/11.


## 💡 Why This Project?

This repository is part of my Windows system administration and customization, it was inspired a company department that I saw running a differnt font from other departments as a phishing deterent.

############################
Here's a video demostrating the process: youtube.com/video/5ZA1PTdf3TU

👨‍💻 Author: John Munjoma
