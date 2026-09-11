# AutoSkipper ⏩

> A lightweight, platform-compliant browser extension that ensures uninterrupted video playback by automatically clearing pop-ups and bypassing "Continue watching?" prompts.

[![Live Website](https://img.shields.io/badge/Website-autoskipper.app-blue)](https://autoskipper.app)
[![Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-Live-green)](#) 

## 🚀 Overview

AutoSkipper is designed to improve the video viewing experience without triggering platform ad-blocker warnings. Instead of blocking network requests, it utilizes DOM manipulation via modern WebExtension APIs to detect and automatically clear viewing interruptions within seconds of them appearing.

### 🎥 Demo

<video src="./autoskipper-demo.mp4" width="600" controls="controls"></video>

*(Note: GitHub natively supports rendering MP4 files in the README. Ensure `autoskipper-demo.mp4` is pushed to your main branch.)*

## ✨ Key Features

*   **Zero Network Blocking:** Operates entirely strictly within the DOM, ensuring 100% compliance with platform policies and avoiding "ad-blocker detected" warnings.
*   **Performance Optimized:** Extremely lightweight footprint that only executes scripts on targeted video domains to preserve browser memory and battery life.
*   **Privacy First:** Collects zero user data. All processing happens locally on the user's machine.

## 🛠️ Architecture & Tech Stack

*   **Extension Core:** JavaScript (ES6+), HTML5, CSS3
*   **API:** Chrome WebExtension API (Manifest V3)
*   **Landing Page Hosting:** GitHub Pages 
*   **DNS & Security:** Cloudflare (Custom Domain Management, Edge SSL/TLS, Email Routing)

## 🌐 Browser Compatibility

AutoSkipper is built on the modern WebExtensions standard, ensuring native compatibility across the Chromium ecosystem.

*   ✅ **Google Chrome:** Native support via the Chrome Web Store.
*   ✅ **Microsoft Edge:** Native support (Enable "Allow extensions from other stores").
*   ✅ **Brave Browser:** Native support.
*   ✅ **Opera / Vivaldi:** Native support.
*   ⏳ **Mozilla Firefox:** Architecture is fully compatible; official Mozilla Add-ons port planned.

## 💻 Local Development & Installation

To run this extension locally for development or testing:

1. Clone this repository:
   ```bash
   git clone [https://github.com/yourusername/autoskipper.git](https://github.com/yourusername/autoskipper.git)
