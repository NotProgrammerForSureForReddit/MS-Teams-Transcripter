# 📝 MS-Teams-Transcripter

Javascript script, executed in TamperMonkey that captures **live captions (CC)** from Microsoft Teams meetings, including **speaker names**, timestamps, and allows **easy download** of the transcript.

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
- Works best when used in an **active tab** (browser throttling may impact performance) - otherwise, when the tab will unfreeze, big amount of text will go at the same second, making it look like everything was being said at the same time


## 🔧 How to Use

1. Install [Tampermonkey](https://chromewebstore.google.com/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) browser extension (works on [Chrome/Firefox/Opera/Edge/Safari](https://www.tampermonkey.net/) — you need to enable developer settings for that extension (follow Tampermonkey guide or search on Google)
2. Create a new script and paste the contents of [`MS-Teams-Scripter`](https://github.com/NotProgrammerForSureForReddit/MS-Teams-Transcripter/blob/main/MS-Teams-Transcripter)
3. Join a Microsoft Teams meeting (web version)
4. Ensure **Live Captions CC** are turned on. You can enable them to be always on by default (HIGHLY RECOMMENDED). Other users doesn't see that you have it enabled/using it.
5. The logger will detect live captions CC window with text, and will start capturing automatically
6. Press `Ctrl + Shift + S` or click `⬇️` to download the `.txt` file at any time of a call (or download at the end by finishing a call by pressing "disconnect button")

## 🤝 Contributions & Feedback

Feel free to suggest your own improvements — via pull requests, issues or discussions.  
Even small changes are welcome, whether it's fixing a bug, cleaning up the code or making something more readable.

> I'm still learning how GitHub works myself, so please be patient 😅  
> Once I test your changes and see that they work, I’ll be happy to merge them into `main`.

You can also open a [discussion](../../discussions) if you just want to ask a question, leave a comment, or share an idea.


## 📄 License

This code is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**.  
That means:
- ✅ You can use, modify, and share it freely
- ❌ **You may not use it for commercial purposes**  

Full license: [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)
