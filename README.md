# 🔹 Promptify – AI Prompt Generator for Chrome

**Promptify** is a lightweight Chrome extension powered by **Gemini Nano**, designed to convert any on-screen selected text into a high-quality AI prompt for optimal responses.

- ⚡ Works offline using Gemini Nano’s on-device inference  
- 🎯 Converts selected screen text into optimized prompts in a click  
- 🌙 Sleek, responsive UI with minimal overhead  
- 🛠️ Fully client-side – no servers, no data sent

---

## 📝Note

> 📦 This extension is not on the Chrome Web Store. You’ll install it manually by cloning this repo.
</br>

> 🔑 The `.js` files have been encrypted in a manner that Chrome can read them, but they make no sense to humans.
---
## 🚀 How to Install

### 1. Clone this repository

```bash
git clone https://github.com/electro-glitch/promptify.git
````

### 2. Enable Required Chrome Flags for Gemini Nano

In **Google Chrome**:

* Visit: `chrome://flags/#optimization-guide-on-device-model`
  → Set to: **Enable BypassPerfRequirement**

* Visit: `chrome://flags/#prompt-api-for-gemini-nano`
  → Set to: **Enabled**

* Then go to: `chrome://components`
  → Look for **Optimization Guide On Device Model**
  → Click **Check for Update**
  → Wait a few minutes until it shows "Up to date"

### 3. Load the Extension

1. Open Chrome and go to `chrome://extensions/`
2. Enable **Developer Mode** (top-right)
3. Click **Load Unpacked**
4. Select the cloned `promptify` folder _(make sure to delete the README.md and LICENSE files before doing so)_

✅ Promptify is now installed and ready to use.

---

## 🧪 How to Use

1. **Select any text** on a webpage
2. **Right-click**
3. Choose **“Promptify”**

A prompt will be generated and shown in a clean popup, ready to copy and use.

---

## 💡 Example Use Cases

* Rewriting vague or unclear prompts
* Helping students, professionals, and creatives craft better queries
* Enhancing productivity for day-to-day AI use

---

## 🛡️ Privacy

Promptify is completely local:

* No data leaves your browser
* No server dependencies
* No tracking or analytics

---

## 🧩 Built With

* Chrome Manifest V3
* JavaScript
* Gemini Nano APIs (on-device)
