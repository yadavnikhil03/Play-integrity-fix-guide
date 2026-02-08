<p align="center">
  <img src="https://raw.githubusercontent.com/yadavnikhil03/Play-integrity-fix-guide/main/assets/adv.png" width="120"/>
</p>

<h1 align="center">Advanced TrickyStore Method</h1>

<p align="center">
  Root Required
</p>

## 📋 Prerequisites

- **Rooted device** with Magisk or KernelSU
---

## ⚠️ Important Notes

This is an **advanced method** that combines multiple modules for maximum compatibility and security. This method will:
- ✅ **Pass all Play Integrity checks** (BASIC, DEVICE, STRONG)
- ✅ **Show bootloader as locked** in key attestation
- ✅ **Provide strong hardware attestation spoofing**

> 🚨 **WARNING:** Uses third-party/imported keyboxes and a spoof provider to produce forged attestation — not OEM hardware-backed; will often fail with Google Wallet, other security-sensitive apps.

> 🚨 **WARNING:** Follow the exact order of installation and configuration. Skipping steps may cause the method to fail.

---

## 📦 Required Downloads

Download the following files from their respective GitHub releases:

1. **[ReZygisk](https://github.com/PerformanC/ReZygisk/releases)** 
2. **[PlayIntegrityFix v4.3-inject-s](https://github.com/KOWX712/PlayIntegrityFix/releases/tag/v4.3-inject-s)**
3. **[TrickyStore](https://github.com/5ec1cff/TrickyStore/releases)** 
4. **[Tricky Addon Update Target List](https://github.com/KOWX712/Tricky-Addon-Update-Target-List/releases)**
5. **[KsuWebUI Standalone](https://github.com/5ec1cff/KsuWebUIStandalone/releases)**

---

## 🛠️ Installation Steps

> **Note:** Use your root manager (Magisk Manager or KernelSU) to flash all modules below.

### Step 1: Install All Required Modules

1. **Flash ReZygisk module**
2. **Flash PlayIntegrityFix v4.3-inject-s module**
3. **Flash TrickyStore module**
4. **Flash Tricky Addon Update Target List module**
5. **⚠️ IMPORTANT:** Do **NOT** turn on the default Zygisk from Magisk settings
6. **Reboot your device** once after installing all modules

---

### Step 2: Install & Configure KsuWebUI App

1. **Install the KsuWebUI Standalone APK** on your device
2. **Open the KsuWebUI app**
3. Navigate to **Advanced** settings
4. **Configure the following options** (leave everything else as default):
   - ✅ **Turn ON:** Spoof Build
   - ✅ **Turn ON:** Spoof Provider  
   - ✅ **Turn ON:** Spoof Signature
5. **Click "Fetch"** to apply the configuration

---

### Step 3: Configure TrickyStore

1. **Open TrickyStore app**
2. **Click on the hamburger menu (☰)**
3. **Click "Select All"** 
4. **Deselect unnecessary apps** (keep only apps that need Play Integrity)
5. **Select "Set Security Patch"** at the bottom
6. **Click "Auto"** to automatically set the security patch

### Step 4: Set Valid Keybox

1. **Go back to hamburger menu (☰)**
2. **Click "Set Valid Keybox"**
3. **Click "Save"** to apply all settings

---

## ✅ Verification

⚠️ **WARNING:** Do NOT check integrity via third-party apps on custom ROMs, as it may lead to loss of integrity certification. Use only the Play Store app.

### Check Play Integrity:
1. Open the **Play Store APP**
2. Tap on your **Profile Picture**
3. Tap on **'Settings'**, then tap **'About'**
4. Verify it shows Play Protection certification **"Device is certified"**

---

<p align="center">
  <strong>🎉 Success! You should now have full Play Integrity bypass with locked bootloader attestation.</strong>
</p>

---

<p align="center">
  <a href="../README.md">🏠 Back to Main Guide</a> | 
  <a href="full_guide.md">📋 All Methods</a>
</p>
