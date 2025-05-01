# 🪄 FlashCopy Prank Script (Old Archive)

> ⚠️ This script is intended **for educational and prank purposes only**. Do not use it on someone else's computer without **explicit permission**.

## 🧠 About

This is an **old Python script** I wrote about 4 years ago — back when I was just having fun experimenting with how file systems work.

The idea?  
Whenever a USB flash drive is plugged into a machine, the script walks through the directories and copies various document types (like `.pdf`, `.docx`, `.txt`) into a shared folder on the system. It also attempts to delete images and video files afterward, just for prank purposes.

**I repeat: this was a joke. Don't take it seriously.**

## ❗ What it does

- Detects all available drives (e.g., C:, D:, E:)
- Picks a specific drive (`drives[2]`) to scan
- Copies files with the following extensions:
  - `.txt`, `.pdf`, `.doc`, `.docx`, `.odt`, `.ott`, `.rtf`, `.uot`, `.dic`
- Places them into: `C:/Users/Public/ortak/...`
- Then tries to delete:
  - `.jpg`, `.jpeg`, `.png`, `.bmp`, `.mp4`
- If any error occurs, it waits 15 seconds and retries again in a loop.

## ⚠️ Disclaimer

- ❌ **Do NOT use this script on any system you do not own or have permission to test.**
- ⚖️ Unauthorized access to or manipulation of files can be illegal.
- 🎓 This script is kept here as an archive to reflect my learning journey as a developer.

## 📁 Why keep it?

Because every developer starts somewhere — and sometimes, we start with chaotic code, bad indentation, and ambitious pranks.  
This is one of those moments.

## 🛑 Again: Don't use this for real.

Seriously. I mean it.

---

> [https://github.com/foxyscat](https://github.com/foxyscat)
