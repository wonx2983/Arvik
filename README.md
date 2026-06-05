# Arvik

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows-blue?style=for-the-badge&logo=windows" />
  <img src="https://img.shields.io/badge/Version-1.0.0-purple?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge" />
</p>

<p align="center">
  <b>Your AI-powered desktop assistant for Windows.</b><br/>
  Voice & text control · Smart memory · Browser automation · Multi-agent tasks
</p>

---

## ✨ Features

- **🎙️ Voice & Text Control** — Talk to Arvik or type commands naturally
- **🧠 Persistent Memory** — Remembers your preferences, past conversations, and context
- **🌐 Browser Automation** — Automates web tasks in the background using a headless browser
- **🤖 Multi-Agent System** — Spawns specialized agents for complex tasks
- **📅 Task Scheduler** — Schedule commands to run at specific times
- **🔒 Secure** — End-to-end encrypted communication, local-first data storage

## 📥 Download

**[Download Arvik for Windows →](https://arvik.in/download)**

Or grab the latest release from the [Releases](https://github.com/wonx2983/Arvik/releases/latest) page.

## 🚀 Getting Started

1. Download `ArvikSetup.zip` from the latest release
2. Extract the zip and run `ArvikSetup-1.0.0.exe`
3. Follow the setup wizard:
   - Enter your **invite code** (received via email)
   - Set your **display name**
4. Start using Arvik!

## 💻 System Requirements

| Requirement | Minimum |
|------------|---------|
| OS | Windows 10 (64-bit) or later |
| RAM | 4 GB |
| Disk | 500 MB free space |
| Internet | Required for AI processing |

## 🏗️ Architecture

```
┌─────────────────────────────────────────┐
│           Electron (Frontend)           │
│  React UI · Custom Titlebar · HUD      │
├─────────────────────────────────────────┤
│        WebSocket Bridge (9147)          │
├─────────────────────────────────────────┤
│         Python Backend (bridge.exe)     │
│  Memory · Agents · Browser · Scheduler  │
├─────────────────────────────────────────┤
│          Arvik Cloud Server             │
│    AI Processing · Auth · Sync          │
└─────────────────────────────────────────┘
```

## 🔐 Privacy & Security

- Voice data is processed and discarded — never stored on servers
- Local memory database stays on your machine (`%APPDATA%\Arvik\`)
- All server communication uses TLS encryption
- Invite-only access with JWT authentication

## 📄 Legal

- [Privacy Policy](https://arvik.in/privacy)
- [Terms of Service](https://arvik.in/terms)

---

<p align="center">
  Built with ❤️ by the Arvik team<br/>
  <a href="https://arvik.in">arvik.in</a>
</p>
