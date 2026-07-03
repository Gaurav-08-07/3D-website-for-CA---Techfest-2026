[README-3d.md](https://github.com/user-attachments/files/29629767/README-3d.md)
# Techfest 2026 · Campus Ambassador Program — 3D Interactive Edition

The Techfest, IIT Bombay College Ambassador Program landing page, rebuilt around a real 3D scene rather than flat graphics.

> ⚠️ **Disclaimer:** This is an unofficial concept/portfolio design, not affiliated with or endorsed by Techfest or IIT Bombay. For official information and registration, visit [ca.techfest.org](https://ca.techfest.org/).

---

## 🔗 Live Demo

`https://<your-username>.github.io/<repo-name>/3D_Website_for_Techfest_.html`

*(Update this once GitHub Pages is enabled — see [Deployment](#-deployment) below.)*

---

## ✨ Features

- The Techfest "TF" mark modeled as a real extruded, beveled 3D object — metallic violet with a glowing amber edge outline
- A hero scene built from a slowly drifting particle field, standing in for the ambassador network
- **Drag to rotate** the 3D logo by hand
- Mouse-driven camera parallax
- Scroll-driven camera dolly, with the 3D layer fading into the page content below
- Reward cards, stat cells, and the vitals panel respond to cursor position with real CSS 3D tilt
- A soft glow that follows the pointer across the page
- Motion disabled for users with reduced-motion preferences, with a graceful fallback if WebGL isn't available

---

## 🛠️ Tech Stack

- **HTML5 / CSS3** — no build step, no framework
- **Vanilla JavaScript** — drag interactions, parallax, tilt effects
- **[Three.js](https://threejs.org/)** (r128, via CDN) — 3D logo geometry, lighting, and particle scene
- **Google Fonts** — [Rajdhani](https://fonts.google.com/specimen/Rajdhani), [Inter](https://fonts.google.com/specimen/Inter), [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono)

---

## 📁 File Structure

```
.
├── 3D_Website_for_Techfest_.html   # This page — 3D interactive CA program landing page
└── README.md
```

Fully self-contained — HTML, CSS, and JS in one file, nothing to build or bundle.

---

## 🖥️ Running Locally

No installation or dependencies required.

**Option 1 — just open it:**
Double-click `3D_Website_for_Techfest_.html`, or drag it into your browser.

**Option 2 — serve it (recommended, avoids some browser file-access restrictions):**
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
python3 -m http.server 8000
```
Then visit `http://localhost:8000/3D_Website_for_Techfest_.html`.

> Note: this page loads Three.js and fonts from a CDN, so an internet connection is needed even when running locally. A GPU with WebGL support gives the smoothest experience.

---

## 🚀 Deployment

To publish this on GitHub Pages:

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under "Branch," select `main` and `/ (root)`, then **Save**
4. Your page will be live at `https://<your-username>.github.io/<repo-name>/3D_Website_for_Techfest_.html`

*(Optional: rename the file to `index.html` if you want it at the repo root, or to something simpler like `techfest-3d.html`.)*

---

## 📝 Notes on Content

Program figures (footfall, network size, reward tiers, etc.) are drawn from Techfest's publicly published materials at the time of writing and may change with each edition — check `ca.techfest.org` for current figures before using this content anywhere official.

---

## 🙏 Credits

- Techfest branding, name, and program facts — [Techfest, IIT Bombay](https://techfest.org/)
- 3D rendering — [Three.js](https://threejs.org/)
- Typefaces — [Google Fonts](https://fonts.google.com/)

---

## 📄 License

Concept/portfolio project — free to reference or fork for learning purposes. Not for use as an official Techfest property.

---

## 👤 Author

**Gaurav Shrikant Khole**
[GitHub](https://github.com/Gaurav-08-07) · [LinkedIn](https://linkedin.com/in/gaurav-shrikant-khole-616b8b334)
