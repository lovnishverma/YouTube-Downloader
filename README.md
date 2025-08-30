# 🎥 YouTube URL Analyzer & Downloader (yt-dlp Command Generator)

[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-brightgreen?style=for-the-badge&logo=github)](https://lovnishverma.github.io/YouTube-Downloader/)  
[![yt-dlp](https://img.shields.io/badge/powered%20by-yt--dlp-blue?style=for-the-badge&logo=youtube)](https://github.com/yt-dlp/yt-dlp)

---

## 🌐 Live Demo  
👉 **[YouTube Downloader (Hosted on GitHub Pages)](https://lovnishverma.github.io/YouTube-Downloader/)**  

---

## 📌 About the Project
This project is a **YouTube URL Analyzer & yt-dlp Command Generator**, built as a **static web app** hosted on GitHub Pages.  
It helps users:
- Extract **Video IDs** and **Playlist IDs** from YouTube links.
- Generate **yt-dlp commands** for downloading in different qualities.
- Copy generated commands with **one click**.
- Access **external downloader links** like yt-dlp, youtube-dl, 4K Video Downloader, etc.  
- Analyze **multiple URLs in bulk** with a summary.

⚠️ **Note:**  
Due to GitHub Pages limitations, this site cannot download videos directly. Instead, it provides **ready-to-use commands** that you can run locally with [yt-dlp](https://github.com/yt-dlp/yt-dlp).

---

## 🚀 Features
✅ Extract Video & Playlist IDs  
✅ Support for **single & bulk URL analysis**  
✅ Generate **customizable yt-dlp commands**  
✅ Choose **video quality** (4K, 2K, 1080p, 720p, 480p, 360p, audio-only, MP3, etc.)  
✅ **Copy to clipboard** with notification  
✅ Quick-access **external downloader links**  
✅ Keyboard Shortcuts: `Ctrl + Enter` for quick analysis  
✅ Works **fully offline** (static HTML, CSS, JS)  

---

## 🛠️ How to Use
1. Open the [Live Demo](https://lovnishverma.github.io/YouTube-Downloader/).  
2. Paste a **single URL** or multiple YouTube URLs (one per line).  
3. Select your desired **video/audio quality**.  
4. Click **Analyze** → The tool will generate yt-dlp commands.  
5. Copy commands and run them locally:  

```bash
yt-dlp -f "bestvideo[height<=1080]+bestaudio/best" -o "downloads/%(title).80s.%(ext)s" "https://www.youtube.com/watch?v=VIDEO_ID"
````

---

## 📸 Screenshots

🔹 **Homepage (Analyzer UI)**
![Homepage Screenshot](https://github.com/user-attachments/assets/76b1e12d-870f-4347-b118-62caa967eb4d)

🔹 **Analysis Results Example**
![Results Screenshot](https://github.com/user-attachments/assets/bc62e4be-e38e-48bf-86c0-988ece250b0a)


🔹 **Downloading Video Example**
![Results Screenshot](https://github.com/user-attachments/assets/2aa2bdd3-848d-4bcc-aeaf-9d5802010dc5)

---

## 📂 Project Structure

```
YouTube-Downloader/
│── index.html        # Main web app (HTML + CSS + JS)
│── README.md         # Project documentation
│── 404.html           # (Optional) Not Found error page
```

---

## 🔗 External Tools

* [yt-dlp (Recommended)](https://github.com/yt-dlp/yt-dlp)
* [youtube-dl](https://ytdl-org.github.io/youtube-dl/)
* [4K Video Downloader](https://www.4kdownload.com/)
* [ClipGrab](https://clipgrab.org/)

---

## 📦 Run Locally

Clone and open in browser (no server required):

```bash
git clone https://github.com/lovnishverma/YouTube-Downloader.git
cd YouTube-Downloader
# Open index.html in browser
```

---

## 📜 License

This project is licensed under the **MIT License** – free to use, modify, and share.

---

## 🙌 Acknowledgements

* Built with ❤️ by [Lovnish Verma](https://github.com/lovnishverma)
* Inspired by [yt-dlp](https://github.com/yt-dlp/yt-dlp)

---

### ⭐ Support

If you find this project useful, consider **starring ⭐ the repo** to support!
