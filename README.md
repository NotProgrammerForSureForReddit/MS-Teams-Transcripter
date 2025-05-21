# 📝 MS-Teams-Transcripter

Tampermonkey script that captures **live captions (CC)** from Microsoft Teams meetings, including **speaker names**, timestamps, and allows **easy download** of the transcript.

## 🚀 Features

- ✅ Automatically detects live captions (CC)
- 🧠 Extracts speaker name and spoken text with timestamps
- 💾 Download transcript manually with `Ctrl + Shift + S` or click `⬇️`
- 🛑 Auto-saves captions when you leave the meeting (on “Leave” button click)
- 🧩 Lightweight UI indicator (bottom-right) shows capture status
- 🛡️ Non-destructive: processes only caption content; no API hooks

## 🔧 How to Use

1. Install [Tampermonkey](https://www.tampermonkey.net/) browser extension
2. Create a new script and paste the contents of `teams-caption-logger.user.js`
3. Join a Microsoft Teams meeting (web version)
4. Ensure **Live Captions** are turned on
5. The logger will detect captions and start capturing automatically
6. Press `Ctrl + Shift + S` or click `⬇️` to download the `.txt` file at any time

## 💡 Tip

If you forget to download manually, the script auto-saves the transcript **when you click “Leave”** in the call.
