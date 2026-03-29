# Mht2html — MHTML → HTML Converter

<p align="center">
  <a href="#"><img alt="Status" src="https://img.shields.io/badge/status-working-22c55e?style=for-the-badge"></a>
  <a href="#"><img alt="Client Side" src="https://img.shields.io/badge/runs-100%25%20in%20browser-0ea5e9?style=for-the-badge"></a>
  <a href="#"><img alt="No Upload" src="https://img.shields.io/badge/privacy-no%20uploads-6366f1?style=for-the-badge"></a>
  <a href="#"><img alt="Built With" src="https://img.shields.io/badge/built%20with-vanilla%20js-f59e0b?style=for-the-badge"></a>
  <a href="./LICENSE"><img alt="License" src="https://img.shields.io/badge/license-MIT-64748b?style=for-the-badge"></a>
</p>

A stylish, browser-only converter for `.mht` / `.mhtml` files.
Drop in a saved web page and export it as:

- **Single self-contained `.html`** (assets embedded as data URIs), or
- **`index.html` + `assets/` ZIP** (smaller for large pages).

---

## ✨ Features

- 🧠 **100% client-side** conversion (your file never leaves your machine)
- 📦 **Two output modes**: embedded single-file HTML or ZIP package
- 🖼️ **Asset rewriting** for `src`, `srcset`, CSS `url(...)`, inline styles, and linked stylesheets
- ⚡ **Progress UI** with clear processing steps
- 👀 **Preview + download** right from the browser
- 📱 **Responsive dark UI**
- 📲 **Installable PWA** with install prompt + offline shell caching

---

## 🚀 Quick Start

1. Serve the project root over HTTP (for service-worker support), e.g. `python -m http.server 8080`.
2. Open `http://localhost:8080/` in your browser.
3. Drag-and-drop an `.mht` / `.mhtml` file (or click **Browse Files**).
4. Pick output format.
5. Click **Convert →**.
6. Download your converted result.

> No backend and no build step required.

For installation prompts, open the app over `http://` or `https://` (not directly via `file://`).

---

## 🧩 Supported Inputs

- Browser-saved web archives (`.mht`, `.mhtml`)
- Many MIME multipart variants using:
  - `base64`
  - `quoted-printable`
  - `7bit` / `8bit`

---

## 🛠️ Tech

- HTML
- CSS
- Vanilla JavaScript
- [JSZip](https://stuk.github.io/jszip/) for ZIP output

---

## 📄 License

MIT — feel free to use and modify.


---

## 👨‍💻 Development & Repo

- Developer: **BR1JM0H4N**
- Repository: https://github.com/BR1JM0H4N/Mht2html.git
