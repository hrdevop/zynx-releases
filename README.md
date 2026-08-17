<div align="center">

# ⚡ ZynxTerminal

**The terminal workspace built for how you actually ship.**

[![Latest Release](https://img.shields.io/github/v/release/hrdevop/zynx-releases?color=6366f1&label=Release&logo=github&style=flat-square)](https://github.com/hrdevop/zynx-releases/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011%20(x64)-blue?style=flat-square&logo=windows)](https://github.com/hrdevop/zynx-releases/releases/latest)
[![License](https://img.shields.io/badge/License-Apache%202.0-green?style=flat-square)](./LICENSE)
[![Website](https://img.shields.io/badge/Website-usezynx.com-orange?style=flat-square)](https://usezynx.com)
[![Issues](https://img.shields.io/badge/Issue%20Tracker-GitHub%20Issues-purple?style=flat-square&logo=github)](https://github.com/hrdevop/ZynxTerminal-issues)

<br />

[**Official Website**](https://usezynx.com) • [**Download Installer**](#-downloads-v100) • [**Release Notes**](https://github.com/hrdevop/zynx-releases/releases) • [**Report an Issue**](https://github.com/hrdevop/ZynxTerminal-issues/issues/new/choose)

</div>

---

## 📦 Downloads (v1.0.0)

| Asset | Package Type | Architecture | Size | Checksum (SHA-256) | Download |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **`ZynxTerminal_1.0.0_x64-setup.exe`** | NSIS Setup (Recommended) | `Windows x64` | `9.27 MB` | `fe70503a939a87a7e39b90e000b022e3ba5a2bb8572047510a27e4127f15659c` | [⬇️ **Download .exe**](https://github.com/hrdevop/zynx-releases/releases/download/v1.0.0/ZynxTerminal_1.0.0_x64-setup.exe) |
| **`ZynxTerminal_1.0.0_x64_en-US.msi`** | MSI Enterprise Installer | `Windows x64` | `11.58 MB` | `9847804afcf6f7ba4eed6efc9c980b834462aace60d6c83f04bbbc8d2a12b8eb` | [⬇️ **Download .msi**](https://github.com/hrdevop/zynx-releases/releases/download/v1.0.0/ZynxTerminal_1.0.0_x64_en-US.msi) |

> [!NOTE]
> **Windows SmartScreen Notice**: During early access, code signing certificates are being provisioned. If Windows SmartScreen displays a prompt on first launch, click **"More info" → "Run anyway"**.

---

## 🚀 Quick Install

### Method 1: Graphical Setup (Recommended)
1. Download [**`ZynxTerminal_1.0.0_x64-setup.exe`**](https://github.com/hrdevop/zynx-releases/releases/download/v1.0.0/ZynxTerminal_1.0.0_x64-setup.exe).
2. Run the installer and follow the quick setup wizard.
3. Launch **ZynxTerminal** from your Start Menu or Desktop.

### Method 2: PowerShell One-Liner
Open PowerShell and run:
```powershell
Invoke-WebRequest -Uri "https://github.com/hrdevop/zynx-releases/releases/download/v1.0.0/ZynxTerminal_1.0.0_x64-setup.exe" -OutFile "$env:TEMP\ZynxTerminal-setup.exe"; Start-Process "$env:TEMP\ZynxTerminal-setup.exe"
```

---

## ✨ Key Capabilities

- **🤖 Native AI CLI Context**: Deep detection and acceleration for Claude Code, OpenAI Codex, Gemini CLI, and Aider. Commands are inserted (never auto-run) with safety guard protection against destructive commands (`rm -rf`, `git push --force`).
- **📑 OSC 133 Structured Command Blocks**: Transforms unstructured terminal stream into copyable, collapsible, structured command cards with execution duration, working directory, and exit codes.
- **🔄 Crash-Recoverable Workspaces**: Automatic debounced snapshots restore split-panes, profiles, tabs, and commands across crashes or reboots.
- **🎨 17 Curated Terminal Schemes**: Built-in Tokyo Night, Catppuccin Mocha, Dracula, Nord, One Dark Pro, Monokai Pro, Rosé Pine, Night Owl, and more.
- **⚡ High-Throughput Engine**: WebGL-accelerated 60 FPS rendering with zero dropped frames under heavy PTY output bursts.
- **🔒 First-Class SSH & SFTP**: OS credential manager isolation (DPAPI), ED25519 fingerprint review, and remote port forwarding.

---

## 💻 System Requirements

| Specification | Requirement |
| :--- | :--- |
| **Operating System** | Windows 10 (version 1809+) or Windows 11 |
| **Architecture** | 64-bit (`x64` / `AMD64`) |
| **Runtime** | Microsoft Edge WebView2 (pre-installed on Windows 10/11) |
| **Supported Shells** | PowerShell 7 / 5.1, Command Prompt (`cmd.exe`), Git Bash, WSL2 (Ubuntu, Debian, Arch) |

---

## 🔐 Verify Binary Integrity

You can verify the authenticity and integrity of downloaded binaries using PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 "path\to\ZynxTerminal_1.0.0_x64-setup.exe"
# Hash: 1A52569562AD79F9697006C2B4FE6B753DDF5983E87916E7B942089F94694578

Get-FileHash -Algorithm SHA256 "path\to\ZynxTerminal_1.0.0_x64_en-US.msi"
# Hash: 10584F3090964D96D992D6C9A3342C536B04583A0A13C6196478AD91382AC072
```

---

## 🤝 Community & Support

- **Bug Reports & Feature Requests**: [ZynxTerminal Issue Tracker](https://github.com/hrdevop/ZynxTerminal-issues)
- **Security Vulnerabilities**: See [SECURITY.md](./SECURITY.md) or email `security@usezynx.com`
- **Documentation & Website**: [https://usezynx.com](https://usezynx.com)

---

<div align="center">
  <sub>Built with Tauri, Rust, React & xterm.js · Copyright © 2026 ZynxTerminal. All rights reserved.</sub>
</div>
