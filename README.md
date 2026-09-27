<div align="center">

# 🎂 Valentine Cake — Blow Out the Candles! 🎤

**Retro 8-bit pixel art Valentine cake with real microphone blow-detection.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Web Audio API](https://img.shields.io/badge/Web_Audio-API-FF69B4?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
[![Pixelify Sans](https://img.shields.io/badge/Font-Pixelify_Sans-8A2BE2?style=for-the-badge)](https://fonts.google.com/specimen/Pixelify+Sans)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

</div>

---

## 📖 About

**Valentine Cake** is an interactive, retro pixel-art celebration web app that connects physical action with digital celebration.

Using the browser's **Web Audio API** and microphone access (`navigator.mediaDevices.getUserMedia`), it detects when a user physically blows into their device's microphone, realistically extinguishing flickering birthday/Valentine candles one by one and displaying a joyful congratulatory celebration message!

---

## ✨ Features

- 🎤 **Real-Time Microphone Blow Detection**: Uses an `AudioContext` and `AnalyserNode` frequency spectrum ratio calculation to accurately distinguish blowing sounds.
- 🕯️ **Interactive Extinguishing Physics**: Candles extinguish with staggered, randomized realistic delays upon blowing.
- ⚙️ **URL Parameter Customization**: Easily configure recipient name and candle count via query params:
  - `?name=Adelia&candles=6` (supports between 1 and 30 candles)
- 👾 **Charming 8-Bit Pixel Art Style**: Handcrafted CSS pixel cake, multi-colored candles, and nostalgic [Pixelify Sans](https://fonts.google.com/specimen/Pixelify+Sans) typography.
- 📱 **Mobile & Laptop Friendly**: Works smoothly on mobile phones and laptops equipped with a microphone.

---

## 🛠️ Tech Stack

- **Markup**: [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML)
- **Styling**: [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS) (Pixel Art Grid & Keyframe Animations)
- **Audio Analysis**: [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API) (FFT AnalyserNode)
- **Typography**: [Pixelify Sans](https://fonts.google.com/specimen/Pixelify+Sans)

---

## 🚀 Quick Start

> **Note on Microphone Permissions**: The Web Audio microphone feature requires an HTTP or HTTPS localhost server to grant microphone permissions.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/kecrwn/ValentineAK.git
   cd ValentineAK
   ```

2. **Serve with a local web server:**
   ```bash
   # Using Python 3
   python3 -m http.server 8080

   # Or using Node
   npx serve .
   ```

3. **Open in browser:**
   Navigate to `http://localhost:8080?name=Adelia&candles=6`.
4. Allow microphone access, make a wish, and blow into your mic!

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
