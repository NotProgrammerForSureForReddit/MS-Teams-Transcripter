# 📝 MS-Teams-Transcripter

Tampermonkey script that captures **live captions (CC)** from Microsoft Teams meetings, including **speaker names**, timestamps, and allows **easy download** of the transcript.

## 🚀 Features

- ✅ Automatically detects live captions (CC)
- 🧠 Extracts speaker name and spoken text with timestamps
- 💾 Download transcript manually with `Ctrl + Shift + S` or click `⬇️`
- 🛑 Auto-saves captions when you leave the meeting (on “Leave” button click)
- 🧩 Lightweight UI indicator (bottom-right) shows capture status
- 🛡️ Non-destructive: processes only caption content; no API hooks

## ⚠️ Limitations (Feel free to fix them and even commit to the code (I will test it before I add it to the main code) - I will work on improving as a hobby, but now feeling too lazy)

- Designed only for the **web version** of Microsoft Teams (script is working/listening only at links STARTING with`teams.microsoft.com` & ` https://teams.live.com/v2/`)
- Requires MS Teams in web browser and **Live Captions CC** to be enabled during the meeting
- Works best when used in an **active tab** (browser throttling may impact performance)


## 🔧 How to Use

1. Install [Tampermonkey](https://chromewebstore.google.com/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) browser extension (works on [Chrome/Firefox/Opera/Edge/Safari](https://www.tampermonkey.net/) — you need to enable developer settings for that extension (follow Tampermonkey guide or search on Google)
2. Create a new script and paste the contents of `MS-Teams-Scripter.js`
3. Join a Microsoft Teams meeting (web version)
4. Ensure **Live Captions CC** are turned on. You can enable them to be always on by default (HIGHLY RECOMMENDED). Other users doesn't see that you have it enabled/using it.
5. The logger will detect live captions CC window with text, and will start capturing automatically
6. Press `Ctrl + Shift + S` or click `⬇️` to download the `.txt` file at any time of a call (or download at the end by finishing a call by pressing "disconnect button")




## 📄 License

This code is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**.  
That means:
- ✅ You can use, modify, and share it freely
- ❌ **You may not use it for commercial purposes**  
- ℹ️ For commercial use — [contact me](NotProgrammerForSureForReddit) first.

Full license: [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)
