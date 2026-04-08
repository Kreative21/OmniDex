# OmniDex

**OmniDex** is a modern, AI-powered Pokédex-style Android app that uses your camera to scan real-world objects and generate rich, fun, Pokédex-inspired insights using Google Gemini.

Users provide their own Gemini API key, making the app lightweight, scalable, and cost-free for the developer.

---

## 🚀 Features

### 🧠 AI-Powered Scanning
- Scan real-world objects using your camera
- Get AI-generated:
  - Object name
  - Description
  - Fun facts
  - “Did you know?” trivia
  - Classification / category

---

### 📱 App Navigation
- **Explore (Home)** — default screen
- **Scan** — camera scanner
- **Collection** — saved scans
- **Settings** — API key & preferences

---

### 💾 Storage Efficient Design (Core Feature)

OmniDex is built to be extremely storage-efficient:

#### 📸 Images
- Converted to **WEBP (lossy)**
- Resized to **512 × 512**
- Target size: **~40KB per image**

#### 🧾 Text Data
- Only structured data is stored
- No raw API responses
- Minimal and optimized storage usage

#### 📂 Result
- Thousands of scans can be stored with very low space usage

---

### 🎨 UI / UX
- Dark mode by default
- Pokédex-inspired red theme
- Blue glowing scan button
- Smooth animations and transitions
- Clean, modern, professional design

---

## 📸 Screens

- Scanner View
- API Setup Screen
- Explore Categories
- Collection / History
- Scan Result
- Settings

---

## ⚙️ How OmniDex Works

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

1. Open **Settings** inside the app  
2. Tap **Manage Gemini API Key**  
3. Paste your API key  
4. Save it  
5. Start scanning  

### 🔒 Notes
- API key is stored locally on your device  
- Not shared with any external server (except Gemini API)  
- Required for scan functionality  

---

## 📥 Download APK

Download the latest version from GitHub Releases:

[Download Latest APK](https://github.com/your-username/omnidx/releases/latest)

---

## 📦 Installation (APK)

1. Download the APK from the Releases page  
2. Enable **Install from unknown sources** (if required)  
3. Open the APK file  
4. Install OmniDex  
5. Launch the app  
6. Enter your Gemini API key  
7. Start scanning  

---

## 🧱 Tech Stack

- Kotlin  
- Android Studio  
- CameraX  
- Google Gemini API  
- Room Database  
- SharedPreferences / DataStore  
- WebP Image Compression  
- Material Design  

---

## 🧠 Architecture

OmniDex follows clean architecture:

- **UI Layer** — Activities / Fragments  
- **ViewModel Layer** — State & logic  
- **Repository Layer** — Data handling  
- **Data Layer** — Room DB + API  

---

## 📂 Local Storage Strategy

### Images
- Stored as compressed WebP files  
- Downscaled to reduce memory usage  

### Data
- Structured storage (title, description, etc.)  
- No redundant data  
- Optimized for fast loading  

### History
- Stored locally  
- Lazy loaded for performance  

---

## 🔐 Permissions

- Camera — for scanning  
- Internet — for Gemini API  
- Storage — for saving scan results  

---

## 🧪 Troubleshooting

### ❌ Scan not working
- Check API key  
- Check internet connection  
- Ensure camera permission is enabled  

### ❌ No results from AI
- Verify Gemini API key  
- Ensure API quota is not exceeded  

### ❌ App crashes
- Restart app  
- Reinstall APK  
- Check device compatibility  

---

## 🛣️ Roadmap

- Offline viewing improvements  
- Favorites / bookmarks  
- Better category filtering  
- Performance optimizations  
- Export scan results  
- UI enhancements  

---

## 📸 Screenshots

_Add screenshots here_

Example:

![Scanner](assets/scanner.png)
![Explore](assets/explore.png)
![Result](assets/result.png)

---

## 🙌 Acknowledgments

- Google Gemini (AI engine)  
- Google Stitch (UI inspiration)  
- Android Studio  

---

## ⚠️ Disclaimer

OmniDex is inspired by the Pokédex concept but is not affiliated with Pokémon, Nintendo, or The Pokémon Company.

---

## 📄 License

MIT License

---

## 📬 Contact

- GitHub Issues: https://github.com/your-username/omnidx/issues  
- Email: your-email@example.com  
