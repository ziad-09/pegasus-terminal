<div align="center">

# 🐎 Pegasus Terminal

**An Android terminal that feels like a workstation — AI chat, Ubuntu, real root, and more.**

[![Release](https://img.shields.io/github/v/release/ziad-09/pegasus-terminal?style=flat-square&color=blue)](https://github.com/ziad-09/pegasus-terminal/releases)
[![Download](https://img.shields.io/badge/download-APK-blue?style=flat-square&logo=android)](https://github.com/ziad-09/pegasus-terminal/releases/download/v1.1/Pegasus_Terminal_1.1.apk)
[![Min SDK](https://img.shields.io/badge/Min%20SDK-26%20(8.0)-green?style=flat-square)](#-install)
[![Size](https://img.shields.io/badge/APK-22.8%20MB-orange?style=flat-square)](https://github.com/ziad-09/pegasus-terminal/releases/download/v1.1/Pegasus_Terminal_1.1.apk)

[📥 **Download APK**](https://github.com/ziad-09/pegasus-terminal/releases/download/v1.1/Pegasus_Terminal_1.1.apk) ·
[📦 **All Releases**](../../releases) ·
[⭐ **Star**](../../stargazers)

</div>

---

## ✨ Features

### ⌨️ Terminal Core
| Feature | Description |
|---|---|
| 🖥️ **Full terminal emulator** | xterm-256color, truecolor, scrollback up to 100k lines |
| ⌨️ **Extra keys bar** | ESC, CTRL, ALT, arrows, PGUP/PGDN — fully customizable layout |
| 🎨 **Live theming** | Dark / light / dynamic / custom hue+sat, background gradients, wallpaper |
| 🔤 **Premium fonts** | FiraCode, JetBrains Mono, JetBrains, Source Code Pro, Inter, Roboto… |
| 📝 **Command input bar** | Type commands with a modern input field + history |
| 💡 **Smart suggestions** | Context-aware command suggestions you can dismiss permanently |
| 📋 **Clipboard keybindings** | CTRL+C/V/X style copy-paste with visual feedback |
| 🔔 **Bell notifications** | Optional notification on terminal bell |
| 🌐 **Multi-session tabs** | Multiple parallel sessions with swipe/switch navigation |

### 🐧 Ubuntu Sandbox (proot)
| Feature | Description |
|---|---|
| 📦 **Full Ubuntu container** | Complete rootfs with apt, dpkg, systemd-less environment |
| 🔧 **apt package manager** | Install anything: git, python3, node, vim, htop, docker… |
| 🛡️ **PRoot isolation** | Sandboxed filesystem — no risk to your device |
| ⚙️ **Seccomp modes** | Auto / on / off — tune performance vs. compatibility |
| 🔒 **Failsafe mode** | Raw Android shell for maintenance when things break |
| 📂 **Project workdir** | Optional auto-cd to `/sdcard/AndroidIDEProjects` |
| 🖼️ **X11 support** | Optional Termux:X11 bridge for GUI apps (tkinter, etc.) |

### 🤖 AI Integration
| Feature | Description |
|---|---|
| 💬 **DeepSeek chat** | Built-in AI assistant streamed directly in the terminal |
| 🧠 **PoW auto-solver** | Handles DeepSeek's proof-of-work challenge automatically |
| 🎨 **Chat UI** | Slide-up sheet with markdown rendering, code highlighting |
| 📜 **Chat history** | Persistent conversations — resume anytime |
| 📝 **AI notes** | Quick notes panel tied to your sessions |
| 🤖 **Codex PS1** | Optional fancy shell prompt with git chips, logos, ASCII art |

### 🛠️ ASCII Art Studio
| Feature | Description |
|---|---|
| ✨ **332+ Figlet fonts** | Full figlet library — classic, 3D, script, banner… |
| 🔤 **TDF engine** | The Drawille / TDF font format with color cells |
| 🎭 **Live preview** | Generate art, copy to clipboard, inject into terminal |
| 🖼️ **Welcome banner** | Customizable startup art with ANSI colors |

### 📁 File Manager
| Feature | Description |
|---|---|
| 📂 **Dual-pane browse** | Navigate phone storage, app data, and Ubuntu home |
| 📋 **Full file ops** | Copy, move, rename, delete, zip, checksum |
| 🔍 **Search** | Find files by name across roots |
| 📤 **SAF integration** | Storage Access Framework for scoped storage |
| 🔐 **All files access** | Full-storage permission with one-tap grant |

### 🔐 Root & System
| Feature | Description |
|---|---|
| 🌳 **Real root (su)** | KernelSU / Magisk / SuperSU — start host shells as real root |
| 🩺 **Health dashboard** | Diagnostics: PRoot, shell, root, storage, Ubuntu, network, temp |
| 📊 **Process control** | Foreground service keeps sessions alive in background |
| 🔔 **Notification actions** | Wake lock toggle, exit, session info from the notification |

### 💾 Backup & Sync
| Feature | Description |
|---|---|
| ⚙️ **Settings export** | Full settings backup as portable JSON |
| 💬 **Session backup** | Chats, notes, session names, command history → one file |
| 🔄 **One-tap restore** | Import on any device — everything comes back |
| 🎨 **Theme presets** | Save, share, and apply named theme presets |

### 🔄 Updates & Distribution
| Feature | Description |
|---|---|
| 🔍 **Update checker** | Scan Download/ for newer APKs + optional remote manifest |
| 📲 **In-app install** | One-tap system installer for new builds |
| 🌍 **Bilingual UI** | Full Arabic + English (RTL-aware) |

### ⚡ Under the Hood
| Feature | Description |
|---|---|
| 🚀 **Kotlin + Jetpack Compose** | Modern Material 3 UI |
| 🧩 **JNI native layer** | proot, loader, link2symlink, termux-terminal JNI |
| 📱 **4 ABI support** | arm64-v8a, armeabi-v7a, x86, x86_64 |
| 🧪 **17 unit tests** | Golden tests for Figlet, TDF, Codex PS1, ASCII art |
| 🌐 **RTL native** | Arabic-first design with proper layout mirroring |

---

## 📥 Download

| | |
|---|---|
| **Latest** | **[v1.1](https://github.com/ziad-09/pegasus-terminal/releases/tag/v1.1)** |
| **APK** | [Pegasus_Terminal_1.1.apk](https://github.com/ziad-09/pegasus-terminal/releases/download/v1.1/Pegasus_Terminal_1.1.apk) (22.8 MB) |
| **Min Android** | 8.0 (API 26) |
| **Target** | Android 14 (API 34) |

---

## 📦 Install

1. **Download** the APK from [Releases](../../releases)
2. **Open** it → allow **Install from unknown sources** if prompted
3. **Grant** *All files access*: Settings → Apps → Pegasus → All files access

---

## 🌳 Root Setup (optional)

Pegasus can start Android-side shells with **real root**:

1. Grant **Superuser** to Pegasus in **KernelSU / Magisk**
2. Open Pegasus → **Settings → System → Real root (su)** → ON
3. Restart sessions (or open a failsafe session)

> Root applies to **host Android shells** only — the Ubuntu proot container keeps its own sandboxed fake root.

---

## 💾 Backup

**Settings → User data:**

| Action | What it saves |
|---|---|
| **Backup** | All settings → `pegasus-settings-backup.json` |
| **Restore** | Re-import settings on any device |
| **Backup sessions** | Chats + notes + session names + cmd history → `pegasus-sessions-backup.json` |
| **Restore sessions** | Bring everything back in one tap |


- 🐧 `apt install git python3 nodejs` — full Ubuntu packages
- 🌳 `su -c id` — real root when enabled
- ✨ `figlet -f slant "HELLO"` — 332 fonts ready
- 🤖 Slide up for AI chat — DeepSeek, streaming, markdown
- 💾 Backup everything before you switch phones

---

## 📄 License

All rights reserved — © ziad-09

---

<div align="center">

**Made with ❤️ for the terminal community**

[⬆ Back to top](#-pegasus-terminal)

</div>
