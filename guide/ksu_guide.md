<p align="center">
    <img src="https://raw.githubusercontent.com/yadavnikhil03/Play-integrity-fix-guide/main/assets/ksu.png" alt="KSU Logo" width="200"/>
</p>

<h1 align="center"> KernelSU Guide – Play Integrity Fix</h1>

<p align="center">
   This guide is for users rooted with <strong>KernelSU</strong><br>
</p>
---

## 📦 Required Files

| 🧩 Purpose               | 📂 Module Name             | 🔗 Download Link |
|--------------------------|----------------------------|------------------|
| Enable Zygisk-like Patching | ReZygisk (KSU only)     | [Download](https://github.com/PerformanC/ReZygisk/releases) |
| Core Integrity Fix       | Play Integrity Fix (Fork)  | [Download](https://github.com/osm0sis/PlayIntegrityFork/releases/) |
| Prop Injector Logic      | Integrity Fix Mod          | [Download](https://github.com/user-attachments/files/20530542/IntergrityFix2.4.zip) |
| Play Store Certification | TrickyStore                | [Download](https://github.com/5ec1cff/TrickyStore/releases/) |
| Add Target Packages      | Tricky Addon               | [Download](https://github.com/KOWX712/Tricky-Addon-Update-Target-List/releases) |

---

## ⚙️ Setup Instructions

### 🔹 Step 1: Flash ReZygisk via KernelSU

- Open the **KernelSU Manager app**
- Flash the module: **ReZygisk**
- ✅ Reboot your phone

---

### 🔹 Step 2: Flash Required Modules

> 📁 Open **KernelSU > Modules**, and flash the following **one by one**:

- 🧩 `Play Integrity Fix (Fork)`
- 🧠 `Integrity Fix Mod`
- 🛍️ `TrickyStore`
- 🧩 `Tricky Addon`

✅ Once done, **reboot your device**

---

### 🔹 Step 3: Configure TrickyStore (WebUI)

1. Open the **TrickyStore** app (or tap “Action” from KSU module section)
2. WebUI will open in your browser

Inside the WebUI:
- Tap `Select All`
- Tap `Deselect unnecessary` 
- Tap `Security Patch` → **Get Patch**
- Tap **Save**

✅ After saving, **reboot your device** again

---

### 🔹 Step 4: Final Patch

- Open **KernelSU > Modules**
- Tap **Action** on the `Integrity Fix Mod` module
- It will patch required props

✅ Reboot once it finishes

---

## 🧪 Final Step: Check Play Integrity

> Install this app:  
> [✅ Play Integrity Checker](https://play.google.com/store/apps/details?id=gr.nikolasspyr.integritycheck&hl=en-US)

