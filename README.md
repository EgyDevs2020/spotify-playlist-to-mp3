# 🎵 Spotify Playlist to MP3 Downloader - PRO

Download Spotify playlists as MP3s — no setup, no Python, no stress.  
Built for creators, casual listeners, and developers who want clean, offline music.

---

## 📥 For Users

### ✨ Features

- Paste a Spotify playlist link
- Fetch all tracks with album art
- Select the songs you want
- Download high-quality MP3s (192kbps)
- Built-in FFmpeg: No extra installation required
- Beautiful, modern dark UI
- Remembers your download folder & recent playlists
- Works offline after first setup
- No Python or installation needed

---

### 🚀 How to Use

1. **[⬇️ Download the app (.RAR)](https://github.com/EgyDevs2020/spotify-playlist-to-mp3/releases/download/v1.0.0/Spotify.Playlist.to.MP3.rar)**
2. Extract the folder:
3. Open `Spotify Playlist to MP3.exe`
4. On first launch:
- Enter your **Spotify API Client ID and Secret**
- [Get them for free here](https://developer.spotify.com/dashboard)
5. Paste a Spotify playlist link
6. Fetch → Select → Download 🎶
7. All songs will be saved inside the `Downloaded/` folder

✅ Simple as that — no terminal, no setup, no fluff.

---

## 🛠 For Developers

You’ll find the full source code inside `/source/` (see the release assets).

### 📁 Folder Structure


---

### 📦 Dependencies

Install these with pip:

```bash
pip install customtkinter==5.2.1
pip install spotipy==2.19.0
pip install yt-dlp==2024.04.09
pip install pillow==10.3.0
pip install requests==2.31.0

🔧 FFmpeg used:
https://www.gyan.dev/ffmpeg/builds/ffmpeg-release-essentials.zip  
→ Only `ffmpeg.exe` and `ffprobe.exe` were included
