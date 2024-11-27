
---

# 🌐 **WiFi Profile Scanner** 🚀

This tool extracts and saves WiFi network credentials stored on a Windows machine. It uses the `netsh` command to retrieve WiFi profiles and passwords, saving the results in a sequentially named text file. Designed for system administrators and network professionals, it simplifies managing and documenting WiFi network credentials.

---

## ✨ **Features**
- 🔍 **Profile Retrieval**: Extracts all WiFi profiles stored on the system.
- 🔑 **Password Extraction**: Retrieves passwords for secured networks (if available).
- 🛠️ **Error Handling**: Implements fallback mechanisms for handling command failures.
- 📂 **Sequential File Saving**: Automatically creates uniquely named text files (`keylogsX.txt`).
- ⏳ **Progress Indicator**: Displays a progress bar with `tqdm` for better task visualization.

---

## 📋 **Requirements**
- **Operating System**: Windows (Run as Administrator)
- **Python**: Pre-installed (if not using the EXE)
- **Dependencies**: `tqdm`

---

## 📦 **Installation (Dependencies)**

If you're running the Python script (not the EXE), you'll need to install the required dependencies. Use the Bash script below to set everything up:

```bash
#!/bin/bash

echo "Installing dependencies..."
pip install tqdm
echo "All dependencies installed successfully!"
```

---

## ⚙️ **How to Use**
1. 🖥️ **For EXE Users**:
   - Download the EXE file .
   - Run the EXE with administrative privileges.
   - The tool will scan all available WiFi profiles, retrieve their credentials, and save the data in a text file named `keylogsX.txt`, where `X` is the next available number.

2. 🐍 **For Python Users**:
   - Clone the repository:
     ```bash
     git clone https://github.com/your-repo.git](https://github.com/janitha479/Wifi-Scanner.git
     cd your-repo
     ```
   - Install dependencies:
     ```bash
     bash install_dependencies.sh
     ```
   - Run the script with admin privileges:
     ```bash
     python wifi_profile_scanner.py
     ```

---

## ⚠️ **Disclaimer**
- Ensure you have appropriate permissions to access and use this tool.
- Use responsibly and only for legitimate purposes, such as network management or troubleshooting.
- Unauthorized use of this tool may violate privacy or security laws.

---

## 🛠️ **Built With**
- Python
- PyInstaller (for generating EXE)

---
##This script support only if the running pc has a wifi adapter.


