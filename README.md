<!-- HERO BANNER -->
<p align="center">
  <img src="https://i.ibb.co/TM9k36n5/banner.png" alt="OmniDex Banner" width="100%">
</p>

<h1 align="center">OmniDex</h1>

<p align="center">
  AI-powered Pokédex-style scanner for the real world
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/Kreative21/OmniDex?style=for-the-badge" />
  <img src="https://img.shields.io/github/downloads/Kreative21/OmniDex/total?style=for-the-badge" />
  <img src="https://img.shields.io/github/v/release/Kreative21/OmniDex?style=for-the-badge" />
  <img src="https://img.shields.io/github/license/Kreative21/OmniDex?style=for-the-badge" />
</p>

---

## 🚀 Overview

**OmniDex** is a modern Pokédex-style Android app that uses your camera to scan real-world objects and generate rich, fun, Pokédex-inspired insights using Google Gemini.

---

## 🧠 Features

### 🔍 AI-Powered Scanning
- Scan real-world objects using your camera  
- Get AI-generated:
  - Object name  
  - Description  
  - Fun facts  
  - “Did you know?” trivia  
  - Classification / category  

---

### 🔄 Smart Updates
- Automatically **checks for updates on every app startup**
- Keeps users informed about the latest version
- Seamless and non-intrusive update experience

---

### 💾 Backup & Restore System
- Create **compressed backups** of your app data  
- Efficient storage using optimized file handling  
- Restore backups **directly without manual extraction**  
- Ensures data safety and easy migration  

---

### 📱 App Navigation
- **Explore (Home)** — default screen  
- **Scan** — camera scanner  
- **Collection** — saved scans  
- **Settings** — API key & preferences  

---

### 💾 Storage Efficient Design

OmniDex is built to be extremely storage-efficient:

#### 📸 Images
- Stored in **WEBP (lossy)**  
- Resized to **512 × 512**  
- Target size: **~40KB per image**  

#### 🧾 Text
- Only structured data stored  
- No raw API responses  
- Minimal storage footprint  

---

### 🎨 UI / UX
- Dark mode by default  
- Pokédex-inspired red theme  
- Blue glowing scan button  
- Smooth animations and transitions  
- Clean, modern, professional interface  

---

## 📸 Screens

- Scanner View  
- API Setup Screen  
- Explore Categories  
- Collection / History  
- Scan Result  
- Settings  

---

## ⚙️ How It Works

1. Open the app  
2. Go to **Settings**  
3. Enter your Gemini API key  
4. Go to **Scan**  
5. Capture an image  
6. App sends image to Gemini  
7. Receive AI-generated result  
8. View and save scan locally  

---

## 🔑 Gemini API Setup

OmniDex requires a **Google Gemini API key**.

### Setup Steps

1. Open **Settings**  
2. Tap **Manage Gemini API Key**  
3. Paste your API key  
4. Save it  
5. Start scanning  

### 🔒 Notes
- API key is stored locally  
- Only used for Gemini API requests  
- Required for scanning  

---

## 📦 Installation (APK)

1. Download the APK  
2. Enable **Install from unknown sources**  
3. Open the APK  
4. Install OmniDex  
5. Launch the app  
6. Enter your API key  
7. Start scanning  

---

## 🧱 Tech Stack

- Kotlin  
- Android Studio  
- CameraX  
- Google Gemini API  
- Room Database  
- SharedPreferences / DataStore  
- WebP Compression  
- Material Design  

---

## 🧠 Architecture

- **UI Layer** — Activities / Fragments  
- **ViewModel Layer** — Logic  
- **Repository Layer** — Data handling  
- **Data Layer** — Room + API  

---

## 📂 Local Storage Strategy

### Images
- Compressed WebP format  
- Downscaled to reduce memory  

### Data
- Structured minimal storage  
- No redundancy  

### History
- Stored locally  
- Lazy loaded  

---

## 🔐 Permissions

- Camera — scanning  
- Internet — Gemini API  
- Storage — saving results  

---

## 🧪 Troubleshooting

### ❌ Scan not working
- Check API key  
- Check internet  
- Enable camera permission  

### ❌ No results
- Verify API key  
- Check API quota  

### ❌ App crashes
- Restart app  
- Reinstall APK  

---

## 🛣️ Roadmap

- Favorites / bookmarks  
- Better filtering  
- Performance improvements  
- Export scan data  
- UI polish  

---

## 📸 Screenshots

<p align="center">
  <img src="assets/scanner.jpg" width="250"/>
  <img src="assets/explore.jpg" width="250"/>
  <img src="assets/result.jpg" width="250"/>
</p>

---

## 🙌 Acknowledgments

- Google Gemini (AI engine)  
- Google Stitch (UI inspiration)  
- Android Studio  

---

## ⚠️ Disclaimer

OmniDex is inspired by the Pokédex concept and is not affiliated with Pokémon, Nintendo, or The Pokémon Company.

---

## 📄 License

MIT License
