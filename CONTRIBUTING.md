# Contributing to Lagoon Frenzy: Gone Fishing

First off, thank you for considering contributing to **Lagoon Frenzy: Gone Fishing**! It's people like you that make open-source games fun, accessible, and durable for generations to come.

---

## 📜 Code of Conduct

This project and everyone participating in it is governed by our Code of Conduct. By participating, you are expected to uphold this code. Please report unacceptable behavior to project maintainers.

---

## 🛠️ Project Philosophy & Technical Pillars

1. **Zero External Runtime Engines:** The game runs on standard HTML5 Canvas 2D and the native Web Audio API. Do not introduce Phaser, Pixi, Three.js, or heavy bundlers unless discussed in an issue first.
2. **Zero Backend Database Dependency:** The game must remain playable 100% offline and statically hostable on GitHub Pages / Vercel with zero server or DB costs. All saves must persist cleanly in `localStorage` with exportable Base64/JSON codes.
3. **Clean-Room & 100% Original Assets:** Never import copyrighted game assets, decompiled sprites, or third-party proprietary artwork. All visual assets must be original or under permissive licenses (CC0 / MIT).

---

## 🚀 Development Workflow

### 1. Fork & Clone

```bash
git clone https://github.com/avartan007/Lagoon-Frenzy-Gone-Fishing.git
cd Lagoon-Frenzy-Gone-Fishing
```

### 2. Run Locally

No build step is required! Simply serve the directory with any static server:

```bash
# Using Python
python3 -m http.server 3000

# Or using Node.js
npx serve .
```

Visit `http://localhost:3000` in your browser. To test mobile or iPad touch controls, open your computer's local network IP on your mobile browser.

### 3. Making Changes

* Create a topic branch: `git checkout -b feature/my-new-feature`
* Keep canvas simulation logic deterministic.
* Test responsiveness across desktop viewports, tablet (768px–1024px), and mobile (<768px).
* Ensure touch swipe-to-collect and swipe-to-cage remain smooth at 60 FPS.

---

## 🐛 Reporting Bugs & Submitting Features

* **Bug Reports:** Open an issue describing your browser (Safari, Chrome, Firefox), device (Mac, iPad, iPhone, Android, Windows), and exact reproduction steps.
* **Feature Requests:** Open an issue with a pitch for new islands, aquatic animals, factory recipes, or accessibility improvements.
* **Pull Requests:** Ensure PR titles follow standard conventional commit naming (`feat: ...`, `fix: ...`, `docs: ...`).

---

## ⚖️ License

By contributing to **Lagoon Frenzy: Gone Fishing**, you agree that your contributions will be licensed under the project's [MIT License](./LICENSE).
