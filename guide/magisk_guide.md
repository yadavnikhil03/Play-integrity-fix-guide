<p align="center">
    <img src="https://raw.githubusercontent.com/yadavnikhil03/Play-integrity-fix-guide/main/assets/magisk.png" alt="Magisk Logo" width="200"/>
</p>

<h1 align="center">🔧 Magisk Guide – Play Integrity Fix</h1>

<p align="center">
    This guide is for users rooted with <strong>Magisk</strong>
</p>
---

## 📦 Required Files

| 🧩 Purpose             | 📂 Module Name             | 🔗 Download Link |
|------------------------|----------------------------|------------------|
| Core Integrity Fix     | Play Integrity Fix (Fork)  | [Download](https://github.com/osm0sis/PlayIntegrityFork/releases/) |
| Prop Injector Logic    | Integrity Fix Mod          | [Download](https://github.com/user-attachments/files/20530542/IntergrityFix2.4.zip) |
| Play Store Certification | TrickyStore              | [Download](https://github.com/5ec1cff/TrickyStore/releases/) |
| Add Target Packages    | Tricky Addon               | [Download](https://github.com/KOWX712/Tricky-Addon-Update-Target-List/releases) |
| Hide Root from Apps    | Shamiko                    | [Download](https://github.com/LSPosed/LSPosed.github.io/releases) |

---

## ⚙️ Setup Instructions

### 🔹 Step 1: Prepare Magisk

- Open the **Magisk app**
- Go to **Settings**
  - ✅ Turn ON `Zygisk`
- Tap `Hide the Magisk App`, and rename it (e.g., `Eren` or `Settings`)

---

### 🔹 Step 2: Flash Required Modules

> 📁 Open **Magisk > Modules** → Tap **Install from Storage**, and flash each of the following **one by one**:

- 🧩 `Play Integrity Fix (Fork)`
- 🧠 `Integrity Fix Mod v2.4`
- 🛍️ `TrickyStore`
- 🧩 `Tricky Addon`
- 🌀 `Shamiko` *(optional but recommended)*

✅ After flashing all, **reboot your phone**

---

### 🔹 Step 3: Configure TrickyStore (WebUI)

1. Go to **Magisk > Modules**
2. Tap **Action** on the **TrickyStore** module → allow root
3. The TrickyStore WebUI will open

Inside the WebUI:
- Tap `⋮`  (3-dots) → **Select All**
- Tap `Deselect unnecessary` 
- Tap `Set Security Patch` → **Get Security Patch**
- Tap **Save**

✅ Done? Now **reboot your device** again.

---

### 🔹 Step 4: Final Patch

- Go to **Magisk > Modules**
- Tap **Action** on the `Integrity Fix Mod` module
- It will patch required props

✅ Reboot after it's complete

---

## 🧪 Final Step: Check Play Integrity

> Install this app:  
> [✅ Play Integrity Checker](https://play.google.com/store/apps/details?id=gr.nikolasspyr.integritycheck&hl=en-US)

