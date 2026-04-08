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

## 📦 Installation

### Option 1: Install APK

1. Download APK from Releases page  
2. Enable **Install from unknown sources** (if required)  
3. Open APK and install OmniDex  
4. Launch the app  
5. Enter your Gemini API key  
6. Start scanning  

---

### Option 2: Run from Source

1. Clone the repository:
```bash
git clone https://github.com/your-username/omnidx.git
