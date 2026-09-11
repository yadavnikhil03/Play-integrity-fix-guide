# 👻 Specter Getting Started Guide

<p align="center">
  <img src="https://specter.dpejoh.com/ghost.svg" alt="Specter" width="120"/>
</p>

<p align="center">
  <strong>All-in-one Play Integrity module by <a href="https://github.com/dpejoh">dpejoh</a></strong><br/>
  Handles keybox, props, target.txt, and security patch automatically
</p>

**Specter** is an all-in-one Play Integrity module that automatically manages your keybox, device fingerprint (props), `target.txt`, and security patch on first boot. No extra keybox managers, props fixers, or vbmeta fixers needed — Specter does it all.

> 📄 Full official docs: [Getting Started](https://specter.dpejoh.com/getting-started.html) • [Best Setup](https://specter.dpejoh.com/guide/best-setup.html) • [WebUI Guide](https://specter.dpejoh.com/guide/webui.html)

---

## 📦 Prerequisites

1. **A rooted device** via **Magisk**, **KernelSU**, or **APatch**
2. **Tricky Store** ([Download](https://github.com/5ec1cff/TrickyStore/releases/latest)) — or one of its forks:
   - [TEESimulator](https://github.com/JingMatrix/TEESimulator/releases/latest)
   - [TEESimulator-RS](https://github.com/Enginex0/TEESimulator-RS/releases/latest)
   - > 💡 **Note:** Specter **auto-installs TEESimulator-RS** if none is detected
3. **A PIF fork (recommended):**
   - [Play Integrity Fix](https://github.com/KOWX712/PlayIntegrityFix/releases/latest)
   - [Play Integrity Fork](https://github.com/osm0sis/PlayIntegrityFork/releases/latest)

---

## 🛠️ Install

1. Download **`Specter-vX.X.X.zip`** from the [releases page](https://github.com/dpejoh/specter/releases/latest)
2. **Flash** it in **Magisk / KernelSU / APatch**
3. **Reboot** — first-boot setup runs automatically:
   - Backup originals
   - `target.txt`
   - Security patch
   - Keybox install

That's it. Specter configures everything on its own after the first reboot.

---

## 🔍 What's Next?

- [Best Setup Guide](specter_best_setup_guide.md) — recommended module combo + getting Strong integrity
- [Specter WebUI Guide](https://specter.dpejoh.com/guide/webui.html) — configure everything from the WebUI

---

<p align="center">
  <a href="../README.md">🏠 Back to Main Guide</a> |
  <a href="specter_best_setup_guide.md">⚙️ Specter Best Setup</a>
</p>