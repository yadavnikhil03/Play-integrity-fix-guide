# 🔑 Keybox.xml Method (Non-Root)

<p align="center">
  <img src="https://raw.githubusercontent.com/yadavnikhil03/Play-integrity-fix-guide/main/assets/keybox_banner.png" width="200"/>
</p>

## 📋 Prerequisites

- A **non-rooted device** (this method works without root access)
- A **custom ROM** that supports **Keybox import functionality**

---

## ⚠️ Important Notes

This method only works if your **custom ROM includes an "Import Keybox" option** in the **Miscellaneous** settings.  
If your ROM does not have this feature, you’ll need to use one of the root-based methods instead.

> 🚨 **CRITICAL:** Before using this method, make sure to **disable all spoofing options** related to Play Integrity Fix.  
> Any active spoofing (device props, fingerprints, etc.) will **interfere with the keybox import and cause integrity checks to fail**.

---

## 🛠️ Setup Instructions

### Step 1: Check ROM Compatibility

1. Open **Settings** on your device  
2. Navigate to **Miscellaneous** (location may vary depending on ROM)  
3. Look for the option **"Import Keybox"** or **"Device Integrity"**  
4. If you do not see this option, your ROM does not support this method

---

### Step 2: Download the Required Keybox File

1. Visit 👉 [https://tryigit.dev/keybox/](https://tryigit.dev/keybox/)  
2. Download the latest working `keybox.xml` file  
3. These files are regularly updated to pass all levels of Play Integrity

---

### Step 3: Disable Spoofing (if any)

1. Turn **OFF all spoofing-related options**, such as:
   - Device model spoofing
   - `build.prop` spoofing
   - Play Integrity Fix-related toggles (LSPosed/Shamiko)
2. **Restart** your device after disabling them

> ✅ This step is crucial — spoofing will break the keybox import process.

---

### Step 4: Import Keybox

1. Copy the downloaded `keybox.xml` file to your device’s internal storage  
2. Go to **Settings > Miscellaneous**  
3. Tap on **"Import Keybox"**  
4. Select the `keybox.xml` file  
5. Confirm the import if prompted

---

### Step 5: Verify Play Integrity Status

1. Install **Play Integrity API Checker** from the Play Store  
2. Open the app and verify:
   - ✅ **BASIC**
   - ✅ **DEVICE**
   - ✅ **STRONG**

---

<p align="center">
  <strong>🎉 Success! You should now be passing all Play Integrity checks.</strong>
</p>

---

<p align="center">
  <a href="../README.md">🏠 Back to Main Guide</a> | 
  <a href="new_guide.md">🔧 Root Guide</a> | 
</p>
