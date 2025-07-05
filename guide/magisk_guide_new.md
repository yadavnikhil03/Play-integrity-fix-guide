<p align="center">
    <img src="https://raw.githubusercontent.com/yadavnikhil03/Play-integrity-fix-guide/main/assets/magisk.png" alt="Alternative Method Logo" width="200"/>
</p>

<h1 align="center">🚀 Alternative Method – Play Integrity Fix</h1>

<p align="center">
    Advanced setup using ZygiskNext + AutoKeybox + KSUWebUI for enhanced compatibility
</p>

---

## 📦 Required Files

| 🧩 Purpose                    | 📂 Module Name                | 🔗 Download Link |
|-------------------------------|-------------------------------|------------------|
| Zygisk Framework              | ZygiskNext                    | [Download](https://github.com/Dr-TSNG/ZygiskNext/releases) |
| Core Integrity Fix            | Play Integrity Fix (Fork)     | [Download](https://github.com/osm0sis/PlayIntegrityFork/releases/) |
| Store Certification           | TrickyStore                   | [Download](https://github.com/5ec1cff/TrickyStore/releases/) |
| Target Package Support       | TrickyStore Addon             | [Download](https://github.com/KOWX712/Tricky-Addon-Update-Target-List/releases) |
| Automatic Keybox Setup       | AutoKeybox Installer          | [Download](https://github.com/user-attachments/files/21082319/AutoKeyboxInstaller.zip) |
| WebUI Interface               | KSUWebUI Application          | [Download](https://github.com/5ec1cff/KsuWebUIStandalone/releases/tag/v1.0) |
| Root Hiding (Optional)        | Shamiko                       | [Download](https://github.com/LSPosed/LSPosed.github.io/releases) |

> ⚠️ **Important:** Do NOT enable Zygisk in Magisk settings when using this method

---

## ⚙️ Installation Steps

### 🔹 Step 1: Flash Required Modules

Flash the following modules in **Magisk** in this exact order:

1. 🧬 **ZygiskNext** *(Do not enable Zygisk in Magisk settings)*
2. 🛡️ **Play Integrity Fix (Fork)**
3. 🧩 **TrickyStore Addon**
4. 🛍️ **TrickyStore**
5. 🔑 **AutoKeybox Installer**

✅ After flashing all modules, **reboot your device**

---

### 🔹 Step 2: Install KSUWebUI Application

1. Install the **KSUWebUI** application on your device
2. **Reboot** your device after installation

---

### 🔹 Step 3: Configure Play Integrity Fix

1. Open **Magisk > Modules**
2. Tap **Action** on the **Play Integrity Fix (Fork)** module
3. Wait for the process to complete
4. Tap **Close** when finished

---

### 🔹 Step 4: Configure TrickyStore via KSUWebUI

#### 🔸 Open KSUWebUI:
1. Launch the **KSUWebUI** application
2. Grant **root access** when prompted
3. You'll see two options: **ZygiskNext** and **TrickyStore**

#### 🔸 Configure TrickyStore:
1. Tap on **TrickyStore**
2. Tap the **☰** (hamburger menu) icon
3. Tap **Select All**
4. Tap **Deselect Unnecessary**
5. Tap **Set Valid Keybox**
   - ✅ Green: "Valid keybox found" 
   - ❌ Red: "No valid keybox found"
   - *Either result is fine - proceed to next step*
6. Tap **SAVE**

#### 🔸 Set Security Patch:
1. Again tap **☰** (hamburger menu)
2. Select **Set Security Patch**
3. Tap **Get Security Patch**
4. Tap **Save**
5. You should see: 🟢 "Security patch saved successfully"
6. Tap **Save** again to confirm

---

### 🔹 Step 5: Clear Google Services Data

1. Go to **Settings > Apps**
2. Enable **Show System Apps**
3. Clear app data for the following:
   - 📱 **Google Play Store**
   - ⚙️ **Google Play Services**
   - 🔧 **Google Services Framework**

✅ **Reboot** your device after clearing data

---

## 🧪 Verify Play Integrity

Install and run the verification app:  
➡️ [Play Integrity API Checker](https://play.google.com/store/apps/details?id=gr.nikolasspyr.integritycheck)

You should pass all three integrity checks:
- **BASIC ✅**
- **DEVICE ✅**
- **STRONG ✅**

---

## 🏦 Banking Apps & Root-Sensitive Apps

If banking or other sensitive apps still detect root:

### 🔹 Additional Setup:

1. **Install Shamiko module** from the downloads table above
2. **Uninstall** all root-detecting apps (banking apps, etc.)
3. **Reinstall** the apps fresh
4. **Add them to Magisk DenyList:**
   - Open **Magisk > Settings**
   - Enable **Magisk DenyList**
   - Go to **Magisk DenyList** and add the problematic apps
5. **Reboot** your device

✅ Your banking and sensitive apps should now work properly
