<div align="center">

# ⚡ ZynxTerminal

**The terminal workspace built for how you actually ship.**

[![Latest Release](https://img.shields.io/github/v/release/hrdevop/zynx-releases?color=6366f1&label=Release&logo=github&style=flat-square)](https://github.com/hrdevop/zynx-releases/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011%20(x64)-blue?style=flat-square&logo=windows)](https://github.com/hrdevop/zynx-releases/releases/latest)
[![License](https://img.shields.io/badge/License-Apache%202.0-green?style=flat-square)](./LICENSE)
[![Website](https://img.shields.io/badge/Website-usezynx.com-orange?style=flat-square)](https://usezynx.com)
[![Issues](https://img.shields.io/badge/Issue%20Tracker-GitHub%20Issues-purple?style=flat-square&logo=github)](https://github.com/hrdevop/ZynxTerminal-issues)

<br />

[**Official Website**](https://usezynx.com) • [**Download Installer**](#-downloads) • [**Release Notes**](https://github.com/hrdevop/zynx-releases/releases) • [**Report an Issue**](https://github.com/hrdevop/ZynxTerminal-issues/issues/new/choose)

</div>

---

## 📦 Downloads (v0.1.0 Early Access)

| Asset | Architecture | Size | Checksum (SHA-256) | Download |
| :--- | :--- | :--- | :--- | :--- |
| **`ZynxTerminal-0.1.0-x64-setup.exe`** | `Windows x64` | `~2.8 MB` | `c09808fa57b4f7532d3125a2a5e9a9ba4fe7e5b9a2ca26e2201145cd8d3a15d6` | [⬇️ **Download .exe**](https://github.com/hrdevop/zynx-releases/releases/download/v0.1.0/ZynxTerminal-0.1.0-x64-setup.exe) |

> [!NOTE]
> **Windows SmartScreen Notice**: During early access, code signing certificates are being provisioned. If Windows SmartScreen displays a prompt on first launch, click **"More info" → "Run anyway"**.

---

## 🚀 Quick Install

### Method 1: Graphical Setup (Recommended)
1. Download [**`ZynxTerminal-0.1.0-x64-setup.exe`**](https://github.com/hrdevop/zynx-releases/releases/download/v0.1.0/ZynxTerminal-0.1.0-x64-setup.exe).
2. Run the executable and follow the quick setup wizard.
3. Launch **ZynxTerminal** from your Start Menu or Desktop.

### Method 2: PowerShell One-Liner
Open PowerShell and run:
```powershell
Invoke-WebRequest -Uri "https://github.com/hrdevop/zynx-releases/releases/download/v0.1.0/ZynxTerminal-0.1.0-x64-setup.exe" -OutFile "$env:TEMP\ZynxTerminal-setup.exe"; Start-Process "$env:TEMP\ZynxTerminal-setup.exe"
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
Get-FileHash -Algorithm SHA256 "path\to\ZynxTerminal-0.1.0-x64-setup.exe"
```

Expected Output:
```
Algorithm       Hash
---------       ----
SHA256          C09808FA57B4F7532D3125A2A5E9A9BA4FE7E5B9A2CA26E2201145CD8D3A15D6
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
