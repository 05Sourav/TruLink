# 🛡️ Safe Link Detector - Chrome Extension

A Chrome extension that helps detect trusted vs. potentially malicious links using both a built-in trusted domain list and the VirusTotal API.

## 🔧 Features

- ✅ Detects and marks **trusted domains**
- ⚠️ Warns against **external/unverified links**
- 🧠 Checks link safety using **VirusTotal API**
- 🧪 Built-in page scanner and safety badge
- 🌐 Right-click context menu for **link safety checks**
- 🎨 Sleek and responsive popup interface

---

## 🚀 Usage Manual

### 1. Load the Extension in Chrome

1. Open Chrome and visit:  
   `chrome://extensions/`

2. Enable **Developer mode** (top-right corner)

3. Click **“Load unpacked”**

4. Select the folder where this extension is located  
   (The folder must include `manifest.json`)

---

### 2. Set Your VirusTotal API Key

To enable live scanning of unknown links:

1. Click the extension icon (🛡️) from your browser toolbar

2. In the popup, click **⚙️ Settings**

3. Paste your **VirusTotal API key**  
   _(You can get one free by signing up at [https://www.virustotal.com](https://www.virustotal.com))_

4. Click **Save**

> ✅ Your key is stored securely in your browser using `chrome.storage.sync`.

---

### 3. How to Use the Extension

- **Hover over links** on any webpage  
  → You'll see a tooltip indicating whether the link is trusted or external.

- **Right-click** on any link or empty page space  
  → Select **“Check link safety”** or **“Check current page”** from the context menu.

- **Open the extension popup**  
  → Paste any URL and click **"Check Link"**  
  → Or click **“🔍 Scan This Page”** to check the active tab’s URL.

---

### 4. Badge Indicators

- ✅ `✓` – Trusted domain  
- ⚠️ `?` – Unknown or external (not on trusted list)

---

### 5. Notes

- VirusTotal link checking requires a valid personal API key.
- Never share or hardcode your API key in the codebase.
- This extension does not send your key anywhere other than the VirusTotal API itself.

---
