# 🗝️ Yuri Keybox Manager Guide

<p align="center">
  <img src="https://github.com/yadavnikhil03/Play-integrity-fix-guide/blob/main/assets/yurikey.png" alt="YuriKey" width="350"/>
</p>

## Overview
This guide explains how to use **Yuri Keybox Manager** and related modules to pass all levels of Play Integrity, including strong integrity, on your device. This method also includes bootloader spoofing (your bootloader status will show as locked).

---

## 📦 Prerequisites & Installation

Download and install the following modules:

1. **Zygisk Next**  
   [Download](https://github.com/Dr-TSNG/ZygiskNext/releases)
2. **Play Integrity Fork (Osmosis)**  
   [Download](https://github.com/osm0sis/PlayIntegrityFork/releases)
3. **Tricky Store**  
   [Download](https://github.com/5ec1cff/TrickyStore/releases)
4. **Yuri Keybox Manager**  
   [Download](https://github.com/dpejoh/yurikey/releases/)

> **Note:** If your ROM has a default/inbuilt Play Integrity option, make sure it is **disabled**. If not present, you can skip this step.

5. **Reboot your device** after installing all modules

---

## 🔍 Verification & Strong Integrity Fix

1. After reboot, confirm all modules are installed and active in Magisk
2. Check Play Integrity status (using Play Integrity API Checker or similar app)
   - You may pass **BASIC** and **DEVICE** integrity, but **STRONG** integrity may still fail
3. To fix **STRONG** integrity:
   - Open **Magisk**
   - Tap the **action button** for **Yuri Keybox Manager**
   - Wait for the process to complete
   - Re-check Play Integrity status
   - You should now pass **BASIC**, **DEVICE**, and **STRONG** integrity

---

## 🛡️ Bootloader Spoofing

- This method also spoofs your bootloader status
- Your device will show **bootloader locked** (even if it's actually unlocked)

---

