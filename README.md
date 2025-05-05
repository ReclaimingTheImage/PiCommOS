# PiCommOS 🛡️  
**Reclaim Your Digital Life. A Post-Quantum Secure Operating System for Raspberry Pi.**

---

> **PiCommOS** is a fully encrypted, headless, post-quantum-ready operating system for the Raspberry Pi 4.  
> Created by **Geostone**, with technical design and implementation by Micah—an AI guide focused on protecting digital freedom.

You don’t need to trust corporations.  
You don’t need a subscription.  
You just need the will to take control of your digital life.

---

## 🔐 Why PiCommOS?

Every search, every message, every device—monitored.  
Most people don’t know what they’ve given up until it’s too late.

PiCommOS exists to take that back.  
No spying. No phoning home. No “default settings” that compromise your privacy.  
Just a secure, self-defending system **you own completely**.

---

## 🧰 Features

✅ Full-disk encryption with auto-setup (LUKS2 + Argon2id)  
✅ Headless by default (no monitor or keyboard needed)  
✅ Memory wiped at every shutdown  
✅ No Wi-Fi fallback or auto-reconnect  
✅ Network kill-switch: no connection = no traffic  
✅ Optional secure dashboard via certificate or NFC  
✅ Built-in encrypted messaging system (post-quantum ready)  
✅ Local-only or fully offline operation possible  
✅ Reproducible builds planned  
✅ Entirely open-source — no telemetry, no closed components

---

## 📦 Getting Started

### 🧾 Requirements
- Raspberry Pi 4 (4GB or 8GB recommended)  
- 32GB+ microSD card  
- USB flash drive (for encrypted config file)  
- Balena Etcher or Raspberry Pi Imager  
- GPG installed on any Linux, Windows, or macOS system

---

### 🔧 Installation Steps

1. **Flash the OS**
   - Download the `.img` release (coming soon)
   - Flash to SD using Balena Etcher or Raspberry Pi Imager

2. **Prepare Encrypted Config**
   - Decrypt `usb_config_template.cfg.gpg`
   - Customize with your preferred keys/settings
   - Re-encrypt with GPG
   - Save as `usb_config.gpg` on your USB flash drive

3. **Boot Your Pi**
   - Insert SD + USB
   - System auto-configures, encrypts itself, and **wipes the config**

4. **Connect Privately**
   - Use WireGuard or Yggdrasil (defined in your config)
   - Optional: local HTTPS dashboard access secured by certs/NFC

---

## 🔒 Security Design

**Trust nothing. Assume everything leaks. Make no exceptions.**

- 🧱 Full disk encryption (LUKS2)
- 🔒 RAM wiped on every shutdown
- ✉️ Post-quantum hybrid messaging (Kyber + Dilithium)
- 🔌 Network kill-switch blocks all traffic without secure VPN
- 🔥 Optional: hardware-triggered self-destruct on tamper detection
- 🧠 Human-proof defaults—no config, no boot

Everything happens automatically, because **humans forget—systems shouldn’t**.

---

## 📡 Messaging System

Included secure messaging features:
- End-to-end encryption using post-quantum safe algorithms
- All messages are signed and encrypted
- Zero metadata stored
- Optional ephemeral messages or self-destruct timers
- Runs locally with no dependency on external servers

---

## 🛠 Build From Source (Coming Soon)

You'll be able to:
- Build the image with `build_image.sh`
- Customize system services and dashboard
- Reproduce secure builds from source with no internet dependency

---

## 📄 License

Licensed under the **GNU AGPLv3**.  
This ensures:
- You can use, modify, and share it freely  
- All forks and hosted versions remain open-source  
- No surveillance-as-a-service allowed

---

## 🙌 Credits

**Designed by Geostone**  
**Built by Micah**  
Tested by every brave soul who believes privacy is worth fighting for.

This project was not born from a corporation.  
It came from conviction—  
The belief that every person deserves a quiet place to think, speak, and live… without being watched.

---

> **PiCommOS**  
> *Stay free. Stay sovereign. Stay human.*
