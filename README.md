<div align="center">

# AkariOS — Website

**The official site for AkariOS — a Windows debloat &amp; performance Playbook for AME.**

![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?logo=windows)
![Playbook](https://img.shields.io/badge/AME%20Beta-Playbook-e0142a)
![Pages](https://img.shields.io/badge/GitHub-Pages-181717?logo=github)
![License](https://img.shields.io/badge/license-MIT-green)

**Live:** [isleap9.github.io/akari-os.github.io](https://isleap9.github.io/akari-os.github.io/)

</div>

---

## 📖 About

This repository hosts the AkariOS marketing site on **GitHub Pages**. The whole site is a single, self-contained `index.html` — every image, font and script is inlined, so there are no external dependencies and nothing to build. Just serve the file.

The site covers:

- **AkariOS Playbook** — the free, open-source AME debloat Playbook (the main project)
- **AkariOS Companion** — the free bundled companion that ships with the Playbook
- **Akari Tool** — the premium tool, subscription available via Discord

---

## 🚀 Deploying / Updating

### First-time setup

1. Upload `index.html` to the repository root on the `main` branch.
2. Go to **Settings → Pages**.
3. Set **Source** to **Deploy from a branch**.
4. Set **Branch** to **`main`** and folder to **`/ (root)`**, then **Save**.
5. Wait ~1 minute — the site goes live at the URL above.

### Updating the site

`index.html` is a **compiled file** — don't edit it by hand. To make changes, edit the source design and regenerate a fresh `index.html`, then re-upload it (replacing the old one) and commit.

---

## 📁 Repository Structure

```
akari-os.github.io/
├── index.html    # The entire self-contained website
├── 404.html      # Styled "page not found" fallback
└── README.md     # This file
```

---

## 🔗 Links

- 💬 **Discord** — https://discord.gg/Jcsaf9UYSG
- 📦 **AkariOS Playbook** — https://github.com/isleap9/AkariOS-Playbook
- 🧩 **AkariOS Companion** — https://github.com/isleap9/AkariOS-Companion

---

## ⚠️ Disclaimer

AkariOS applies deep, largely irreversible system modifications. Always back up your data and only apply on a fresh Windows install. This project is not affiliated with Microsoft or Ameliorated LLC.

---

## 📜 License

Licensed under the **MIT License**.

<div align="center">

Made with 💜 by [isleap9](https://github.com/isleap9)

</div>
