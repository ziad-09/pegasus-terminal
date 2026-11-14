# 🐎 Pegasus Terminal

Android terminal app with AI chat, proot Ubuntu sandbox, and real root (KernelSU/Magisk) support.

## ✨ Features

- **Full terminal** with ExtraKeys, fonts, themes, scrollback
- **Ubuntu via proot** — full container with apt, git, python…
- **AI chat** (DeepSeek) built into the terminal
- **Real root (su)** — KernelSU / Magisk / SuperSU for host shells
- **File manager** with SAF access
- **Session backup** — export/import chats and settings
- **Update checker** — find newer APKs in Download

## 📥 Download

Grab the latest **APK** from the [Releases](../../releases) page.

| | |
|---|---|
| Min SDK | 26 (Android 8.0) |
| Target SDK | 34 |
| Version | 1.1 (versionCode 2) |

## 📦 Install

1. Download `pegasus-update.apk` from Releases
2. Open the APK → allow **Install from unknown sources** if prompted
3. Grant **All files access** when asked (Settings → Apps → Pegasus → All files access)

## 🔐 Root (optional)

Pegasus can start Android-side shells as real root:

1. Grant Superuser to Pegasus in KernelSU / Magisk
2. Enable **Real root (su)** in Pegasus → Settings → System
3. Restart sessions (or open a failsafe session)

> Root applies to host Android shells only — the Ubuntu proot container keeps its own fake root.

## 💾 Backup

**Settings → User data:**
- **Backup / Restore** — settings JSON
- **Backup sessions / Restore sessions** — chats, notes, session names, command history

## 🛠️ Build from source

Source code is not published in this repository.

```sh
ANDROID_HOME=/path/to/android-sdk sh gradlew assembleDebug
```

Requires JDK 17+, Android SDK (compileSdk 36), Gradle 9.0.

## 📄 License

All rights reserved — © Hevan09
