# 🔍 PortScanner Pro

A multi-threaded TCP/UDP port scanner with banner grabbing and detailed service insights. Built with Python, this tool is designed for network reconnaissance and enumeration with flexible scanning modes.

---

## ✨ Features

- 🔧 **Protocol Support**: Scan both **TCP** and **UDP** ports.
- 🚀 **Multi-threaded Scanning**: Lightning-fast scans with **200 concurrent threads**.
- 🎛️ **Custom Modes**:
  - Mode 1: Top 1024 ports
  - Mode 2: Top 10000 ports
  - Mode 3: Common/Custom (to be improved)
  - Mode 4: Manual port list input
  - Mode 69: All ports (1-65535, ⚠️ use with caution)
- 📌 **Port Info Lookup**: Displays known service name, protocol, and descriptions for popular ports.
- 📡 **Banner Grabbing**: Attempts to grab HTTP or other banners on open ports.
- 🎨 **Colorized Output**: Clear console feedback using `colorama`.

---

## 🛠️ Requirements

Make sure Python 3.x is installed. Then install dependencies:

```bash
pip install colorama requests
```
---
## 🚀 Usage
Run the script using:

```bash
python portscanner.py
```
Then follow the interactive prompts:

Enter the target IP/domain

Choose protocol:

1: TCP

2: UDP

Select scanning mode:

1: First 1024 ports

2: First 10000 ports

3: Common ports (to be defined)

69: All ports (⚠️ slow)

4: Custom ports input

---
## 📌 Notes
Port descriptions are sourced from a predefined dictionary. They may not reflect custom or non-standard services.

UDP scanning is less reliable due to the nature of the protocol.

Banner grabbing is implemented for TCP only (HTTP by default).

---

## 🛡️ Disclaimer
This tool is intended for educational and authorized use only. Scanning networks without permission is illegal.

