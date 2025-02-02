# 📥 Google Drive View-Only Files Downloader (Colab-Based)  

This script helps you **download view-only files** from Google Drive on **Google Colab**.  
It supports **PDFs** (as images) and **videos** (via yt-dlp and ffmpeg).  

## 📝 How It Works  

### 📄 For PDFs:  
- Downloads individual **high-resolution page images** from Google Drive.  
- Merges them using `img2pdf` for **lossless** quality.  
- The resulting PDF **will not be text-searchable**, but you can **OCR** it later.  

### 🎥 For Videos:  
- Uses `yt-dlp` to fetch video/audio streams.  
- Downloads them using `aria2` for speed.  

## 🚀 Features  
✅ **Highest quality** PDF (lossless merging)  
✅ **Parallel downloads** using `aria2` (faster speeds)  
❌ **PDFs will be image-based**, so they need OCR for searchable text.  

---

✨ **Enjoy high-quality downloads!** 🚀  
