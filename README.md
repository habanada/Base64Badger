<p align="center">
  <img src="https://raw.githubusercontent.com/habanada/Base64Badger/refs/heads/main/base64badger.png" alt="Base64Badger Logo" width="300">
</p>
#  Base64Badger 
### Image ⇄ Base64 Converter Tool

**Version:** 1.2 
**Author:** [Selahattin Erkoc](https://github.com/habanada) 
**Year:** 2025 

---

##  Overview

**Base64Badger** is a lightweight, fully client-side tool for converting **images to Base64** and vice versa. 
It runs entirely in the browser, stores nothing on a server, and can be used **offline**. 

Built with **Vanilla JavaScript**, **Tailwind CSS**, and designed with full **accessibility (A11y)** in mind. 
It is an enhanced successor of *ByteBadger*.

---

##  Features

###  General
- No installation required - just open and use 
- 100% client-side (no server communication) 
- Supported formats: **JPG** and **PNG** 
- Supports **Drag & Drop**, **File Picker**, and **Clipboard** 
- Multilingual: 🇩🇪 German, 🇬🇧 English, 🇹🇷 Turkish 
- **Dark / Light Theme** with automatic system detection 
- Fully **accessible** and keyboard navigable (ARIA-compliant)

---

### ️ Image → Base64
- Upload via file picker or drag & drop 
- Live image preview 
- Generates complete `<img>` tag with Base64 data automatically 
- **Copy to clipboard** button (Clipboard API with fallback) 
- **File size limit (5 MB)** prevents performance issues 
- Enhanced security checks:
 - MIME type validation 
 - File extension validation 
 - File size validation 

---

###  Base64 → Image
- Accepts either plain Base64 strings or full `<img>` tags 
- Automatically detects format (JPG / PNG) 
- Real-time image preview 
- Export options:
 - **Download as PNG** 
 - **Download as JPG** 
- Canvas-based rendering (auto white background for JPGs)

---

###  UI / UX Highlights
- Modern responsive interface built with **Tailwind CSS** 
- Smooth **Dark/Light Theme** transitions 
- Animated drag-and-drop indicator (pulse effect) 
- Toast notifications for all actions and errors 
- Fully localized texts and messages 
- Automatically saves language and theme preferences via **localStorage**

---

## ️ Technical Details

| Component | Technology |
|------------|-------------|
| Framework | None (Vanilla JS + HTML5 + Tailwind CSS) |
| CSS | Tailwind CSS (via CDN) |
| Language | JavaScript (ES6) |
| License | CC BY-NC 4.0 |
| Dependencies | None |
| Compatibility | Chrome, Edge, Firefox, Safari, Opera |
| Offline Support |  Yes |
| Platform | Browser (Desktop & Mobile) |

---

##  Security

**Base64Badger v1.2** includes a multi-layered upload validation system:

1. **`accept` filter** on the file input element 
2. **MIME type check** via `file.type` 
3. **File extension check** (`.jpg`, `.jpeg`, `.png`) 
4. **File size limit (5 MB)** 
5. Fully client-side (no data sent anywhere)

Together, these prevent tampered or malicious uploads and ensure only real images are processed.

---

## ️ How to Use

1. Open `Base64Badger.html` in your browser 
2. Drag an image into the window or select it via file picker 
3. Click **Copy** to copy the Base64 `<img>` tag 
4. Or paste a Base64 string to see the decoded image 
5. Use **Download as PNG/JPG** to save the converted image 

---

##  Languages

| Language | Supported | Auto Detection |
|-----------|------------|----------------|
| 🇩🇪 German |  | Yes |
| 🇬🇧 English |  | Yes |
| 🇹🇷 Turkish |  | Yes |

---

##  License

**Base64Badger - Image to Base64 Converter Tool** 
Copyright  2025 **Selahattin Erkoc**

**License:** 
[Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/)

>  You may **use, share, and modify** this software for **non-commercial** purposes only. 
> Proper **attribution** is required (e.g., *"Base64Badger by Selahattin Erkoc"*). 
> 
> For any **commercial use**, explicit permission from the author is required.

---

##  Folder Structure

```bash
 base64badger/
├── Base64Badger.html # Main application file
├── base64badger.png # Logo
├── README.md # This documentation
└── LICENSE.txt # License (CC BY-NC 4.0)
````

---

##  Developer Notes

* Built with a focus on **clarity, stability, and performance**
* No external servers, trackers, or analytics
* 100% **open source** for non-commercial use
* Uses only browser-native APIs - no build step required

---

## ️ Credits

> **Base64Badger** by [Selahattin Erkoc](https://github.com/habanada)
> Based on the concept of *ByteBadger*
>  2025 - All rights reserved.



