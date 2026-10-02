# ENC

<!-- ═══════════════════════════════════════════════════════════════════════ -->
<!--                        ENC - README.md                                  -->
<!--              Professional Payload Encoder Documentation                 -->
<!-- ═══════════════════════════════════════════════════════════════════════ -->

<div align="center">

<!-- Animated Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:FF0000,100:000000&height=220&section=header&text=ENC&fontSize=90&fontColor=00FF00&animation=fadeIn&fontAlignY=35&desc=Encode%20%7C%20Obfuscate%20%7C%20Bypass&descAlignY=58&descSize=18&descColor=00FF00" width="100%" />

<!-- Typing Animation -->
<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=800&size=24&duration=2500&pause=700&color=00FF00&center=true&vCenter=true&multiline=true&width=750&height=110&lines=%5B%2B%5D+Initializing+ENC...;%5B%2B%5D+Loading+encoder+modules...;%5B%2B%5D+Encoding+payload...;%5B%2B%5D+Encoding+Complete+%5B%E2%9C%94%5D" alt="Typing SVG" />

<br>

<!-- Status Badges -->
<p>
<img src="https://img.shields.io/badge/VERSION-1.0.0-FF0000?style=for-the-badge&labelColor=000000&logo=gitbook&logoColor=00FF00" />
<img src="https://img.shields.io/badge/PYTHON-3.8%2B-FF0000?style=for-the-badge&labelColor=000000&logo=python&logoColor=00FF00" />
<img src="https://img.shields.io/badge/LICENSE-MIT-FF0000?style=for-the-badge&labelColor=000000&logo=opensourceinitiative&logoColor=00FF00" />
<img src="https://img.shields.io/badge/STATUS-ACTIVE-FF0000?style=for-the-badge&labelColor=000000&logo=statuspage&logoColor=00FF00" />
</p>

<p>
<img src="https://img.shields.io/badge/PLATFORM-LINUX%20%7C%20WIN%20%7C%20MAC-FF0000?style=for-the-badge&labelColor=000000&logo=linux&logoColor=00FF00" />
<img src="https://img.shields.io/badge/ENCODING-MULTI--LAYER-FF0000?style=for-the-badge&labelColor=000000&logo=hackaday&logoColor=00FF00" />
<img src="https://img.shields.io/badge/PAYLOAD-OBFUSCATION-FF0000?style=for-the-badge&labelColor=000000&logo=target&logoColor=00FF00" />
</p>

<br>

<!-- Matrix Rain GIF -->
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" />

</div>

---

<div align="center">

<img width="686" height="850" alt="Image" src="https://github.com/user-attachments/assets/eaa38e96-18e9-437d-897f-459ba20f854a" />



                [ Encode | Obfuscate | Bypass ]
```

</div>

---

## ⚠️ Legal Disclaimer

<div align="center">

```
╔══════════════════════════════════════════════════════════════════════╗
║                                                                      ║
║   ENC (MAX OD) is a payload encoder and obfuscation tool built for   ║
║   EDUCATIONAL and AUTHORIZED testing purposes only.                  ║
║                                                                      ║
║   ▸ Use ONLY on systems you own or have permission to test.          ║
║   ▸ Unauthorized use of encoded payloads is ILLEGAL.                 ║
║   ▸ The author is NOT responsible for any misuse or damage.          ║
║                                                                      ║
║   Hack responsibly. Learn ethically. Report responsibly.             ║
║                                                                      ║
╚══════════════════════════════════════════════════════════════════════╝
```

</div>

---

## 🎯 Overview

> **ENC (MAX OD)** is a Python-based **payload encoder and obfuscation tool** designed for **security researchers, red teamers, and penetration testers**. It allows you to encode payloads using multiple layers of **Marshal, Zlib, Base16, Base32, and Base64** — making them harder to detect by signature-based scanners.

Whether you're testing antivirus evasion or studying obfuscation techniques — ENC gives you the **flexibility and power** you need.

---

## ✨ Encoding Options

<div align="center">

| Option | Encoding Type |
|:------:|:-------------|
| `[01]` | Encode Marshal |
| `[02]` | Encode Zlib |
| `[03]` | Encode Base16 |
| `[04]` | Encode Base32 |
| `[05]` | Encode Base64 |
| `[06]` | Encode Zlib, Base16 |
| `[07]` | Encode Zlib, Base32 |
| `[08]` | Encode Zlib, Base64 |
| `[09]` | Encode Marshal, Zlib |
| `[10]` | Encode Marshal, Base16 |
| `[11]` | Encode Marshal, Base32 |
| `[12]` | Encode Marshal, Base64 |
| `[13]` | Encode Marshal, Zlib, B16 |
| `[14]` | Encode Marshal, Zlib, B32 |
| `[15]` | Encode Marshal, Zlib, B64 |
| `[16]` | Simple Encode |
| `[17]` | Exit |

</div>

---

## 🚀 Installation

<div align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=18&duration=2000&pause=500&color=00FF00&center=true&vCenter=true&width=500&lines=%5B%2B%5D+Installing+ENC...;%5B%2B%5D+Almost+there...;%5B%E2%9C%94%5D+Ready+to+encode." alt="Installing" />
</div>

### ⚡ One-Line Install

```bash
git clone https://github.com/anonmoty/ENC.git && cd ENC && python ENCODE.py
```

### 🐧 Linux / 🍎 macOS

```bash
# Step 1 — Clone the repo
git clone https://github.com/anonmoty/ENC.git

# Step 2 — Enter the directory
cd ENC

# Step 3 — Run the encoder
python ENCODE.py
```

### 🪟 Windows (PowerShell)

```powershell
git clone https://github.com/anonmoty/ENC.git
cd ENC
python ENCODE.py
```

---

## 🎯 Usage

```bash
# Run the tool
python Enc.py

# Then select an encoding option from the menu
[+] Option : 9
```

### Example

```
[01] Encode Marshal
[02] Encode Zlib
...
[09] Encode Marshal, Zlib
...
[17] Exit

[-] Option : 9
```

---

## 🧠 How It Works

```mermaid
graph TD
    A[Input Payload] --> B{Select Encoding}
    B -->|Marshal| C[Marshal Encode]
    B -->|Zlib| D[Zlib Compress]
    B -->|Base64| E[Base64 Encode]
    C --> F[Combine Layers]
    D --> F
    E --> F
    F --> G[Output Encoded Payload]
    G --> H[Done]

    style A fill:#1a0000,stroke:#FF0000,color:#00FF00
    style G fill:#1a0000,stroke:#FF0000,color:#00FF00
    style H fill:#1a0000,stroke:#FF0000,color:#00FF00
```

1. **Input** — Takes raw payload
2. **Select** — Choose encoding method
3. **Encode** — Apply one or more layers
4. **Output** — Generates obfuscated payload

---

## 📁 Project Structure

```
ENC/
├── Enc.py                    # Main entry point
├── core/
│   ├── __init__.py
│   ├── encoder.py            # Encoding engine
│   └── marshal.py            # Marshal wrapper
├── payloads/                 # Sample payloads
├── output/                   # Encoded output
├── requirements.txt
├── LICENSE
└── README.md
```

---

## 📸 Demo

<div align="center">

```
╔═════════════════════════════════════════════════════════════╗
║  ███╗   ███╗ █████╗ ██╗  ██╗    ██████╗ ██████╗              ║
║  ████╗ ████║██╔══██╗╚██╗██╔╝   ██╔═══██╗██╔══██╗             ║
║  ██╔████╔██║███████║ ╚███╔╝    ██║   ██║██║  ██║             ║
║  ██║╚██╔╝██║██╔══██║ ██╔██╗    ██║   ██║██║  ██║             ║
║  ██║ ╚═╝ ██║██║  ██║██╔╝ ██╗   ╚██████╔╝██████╔╝             ║
║  ╚═╝     ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝    ╚═════╝ ╚═════╝              ║
╚═════════════════════════════════════════════════════════════╝

[✓] Payload Loaded
[✓] Encoding Method: Marshal + Zlib
[→] Encoding...

[████████████████████████░░░░░░] 80% | Encoding...
[✓] Encoded Successfully
[✓] Output: output/payload_encoded.txt

        Happy Hacking! 🎯
```

</div>

---

## 🛠️ Requirements

```txt
colorama>=0.4.6
```

Install:

```bash
pip install -r requirements.txt
```

---

## 🎨 Hacker Terminal Theme

ENC uses a **red + green** theme by default:

```python
THEME = {
    "primary":   "\033[38;5;196m",  # Bright Red
    "secondary": "\033[38;5;46m",   # Matrix Green
    "accent":    "\033[38;5;214m",  # Amber
    "error":     "\033[38;5;196m",  # Red
    "warning":   "\033[38;5;220m",  # Yellow
    "info":      "\033[38;5;51m",   # Cyan
    "reset":     "\033[0m",         # Reset
}
```

---

## 🔥 Use Cases

- 🧪 **Payload obfuscation** for red team engagements
- 🛡️ **AV evasion testing** in controlled labs
- 📚 **Learning encoding layers** in Python
- 🔍 **Understanding signature bypass** techniques
- 🎯 **CTF challenges** and security research

---

## 🗺️ Roadmap

- [x] Marshal encoding
- [x] Zlib compression
- [x] Base16/32/64 encoding
- [x] Multi-layer combinations
- [ ] AES encryption layer
- [ ] XOR encoding
- [ ] Custom key support
- [ ] Batch encoding
- [ ] CLI arguments
- [ ] pip package

---

## 🤝 Contributing

Contributions are welcome. Please follow these steps:

1. Fork the repository
2. Create your branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for more information.

---

## 🙏 Credits

- **Author:** MAX OD
- **GitHub:** [@anonmoty](https://github.com/anonmoty)
- **Telegram:** [@MAXOD0](https://t.me/MAXOD0)
- **WhatsApp:** +91 9710569549857
- **Built with:** Python, caffeine, and curiosity ☕

---

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=800&size=22&duration=3000&pause=1000&color=00FF00&center=true&vCenter=true&width=600&lines=Stay+Curious.;Encode+Ethically.;Report+Responsibly!+%F0%9F%8E%AF" alt="Footer" />

<br><br>

### ⭐ If this tool helped you, drop a star!

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:FF0000,100:000000&height=120&section=footer" width="100%" />

</div>
