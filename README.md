# Arvik

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows%2010%2B-0078D4?style=for-the-badge&logo=windows11&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-Beta-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-Proprietary-333333?style=for-the-badge" />
</p>

<p align="center">
  <b>An AI-powered desktop assistant that actually controls your computer.</b><br/>
  Voice & text · Full desktop control · Browser automation · Multi-agent background tasks · Persistent memory
</p>

---

## What Arvik Does

Arvik is a Windows desktop assistant that goes beyond just answering questions. It can see your screen, control your mouse and keyboard, automate browsers, manage files, create documents, and run background agents for complex tasks — all through natural voice or text commands.

---

## ✨ Features

### 🖥️ Desktop Control
Arvik can operate your computer like a human would — open and close apps, click, type, scroll, press hotkeys, take screenshots, and analyze what's on screen using vision.

### 🎙️ Voice & Text
Talk to Arvik naturally or type commands in the chat. Conversations are context-aware and multi-turn — Arvik remembers what you said earlier in the conversation.

### 🌐 Browser Automation
A full headless browser runs invisibly in the background. Arvik can navigate websites, click elements, fill forms, upload files, handle dialogs, take page screenshots, and extract content — all without touching your visible browser.

### 🤖 Multi-Agent System
For complex tasks, Arvik spawns autonomous background agents. Each agent works independently — researching, creating files, browsing the web, running commands — then reports back when done. Multiple agents can run in parallel while you keep working.

### 📁 File & Document Operations
Create, read, edit, move, copy, delete, rename, and search files and folders. Read PDFs, Excel, PowerPoint, Word, CSV, and images (via AI vision). Create documents from scratch — PDFs, Excel workbooks, PowerPoint presentations, and Word documents.

### 🧠 Persistent Memory
Arvik remembers your preferences, facts about you, and key information across sessions. Memory is stored locally on your machine. Context is automatically recalled when relevant.

### 📅 Task Scheduler
Schedule commands to run at specific times or on recurring schedules. Set it up before bed and wake up to completed tasks.

### 🔍 Web Search
Search the web in real-time, synthesize results, and get current information with sources — all from a voice or text command.

---

## 📥 Download

**[Download Arvik for Windows →](https://arvik.in/download)**

Or grab the latest release from the [Releases](https://github.com/wonx2983/Arvik/releases/latest) page.

### Installation

1. Download `ArvikSetup.zip` from the latest release
2. Extract and run the installer (`ArvikSetup.exe`)
3. The setup wizard will ask for:
   - **Invite code** — received via email (Arvik is invite-only during beta)
   - **Display name** — how Arvik addresses you
4. Arvik starts automatically and lives in your system tray

---

## 💻 System Requirements

| Requirement | Details |
|------------|---------|
| **OS** | Windows 10 (64-bit) or later |
| **RAM** | 4 GB minimum |
| **Disk** | ~500 MB free space |
| **Internet** | Required |
| **Microphone** | Optional — needed for voice commands |

---

## 🏗️ How It Works

```
┌─────────────────────────────────────────┐
│         Arvik Desktop App               │
│   Chat UI · Agents · Scheduler · Tray   │
├─────────────────────────────────────────┤
│         Local Backend                   │
│   Desktop control · Browser engine      │
│   Memory · Voice · Privacy controls     │
├─────────────────────────────────────────┤
│         Arvik Cloud                     │
│   AI processing · Auth · Sync           │
└─────────────────────────────────────────┘
```

1. **You speak or type** → your message is sent securely to Arvik Cloud
2. **AI reasons** → the AI decides what to do and which tools to use
3. **Actions execute** → desktop actions run locally on your PC, other operations run server-side
4. **You get a response** → voice and/or text. Background agents notify you when they're done

---

## 🔐 Privacy & Security

- **Voice data** is processed for transcription and immediately discarded — never stored
- **Memory** stays on your machine — your data doesn't leave your PC
- **All communication** is encrypted (TLS/WSS)
- **Invite-only access** with token-based authentication
- **Privacy controls** let you define sensitive apps and windows that Arvik won't interact with
- **Desktop actions are local** — the server sends instructions, your PC executes them. No screen data leaves your machine unless you explicitly ask Arvik to analyze something on screen

---

## 📄 Legal

- [Privacy Policy](https://arvik.in/privacy)
- [Terms of Service](https://arvik.in/terms)

---

<p align="center">
  Built with ❤️ by the Arvik team<br/>
  <a href="https://arvik.in">arvik.in</a>
</p>
