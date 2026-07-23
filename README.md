# 🔐 Secure Authenticator

A professional, privacy-first browser extension for generating secure **2FA One-Time Passwords (OTP)** using **TOTP** and **HOTP** standards. Secure Authenticator keeps your authentication codes encrypted, organized, and completely under your control.

## ✨ Features

Secure Authenticator supports industry-standard **RFC 6238 (TOTP)** and **RFC 4226 (HOTP)** algorithms, allowing you to securely manage authentication codes for thousands of online services.

### Why Secure Authenticator?

- 🔒 Strong local encryption using **AES-256-GCM** with **PBKDF2** key derivation
- 🔑 Generate both **TOTP** and **HOTP** authentication codes
- 📷 Import accounts directly from QR codes
- 📥 Import from:
  - Google Authenticator exports
  - Aegis
  - 2FAS
  - Bitwarden
  - OTP URI lists
  - CSV
  - Encrypted JSON
- 📤 Export to:
  - Encrypted JSON
  - CSV
  - OTP URI Lists
  - QR Bundles
- ⭐ Organize accounts with Groups and Favorites
- 🔐 Optional Master Password protection
- ⏱️ Countdown timers with automatic code refresh
- 📋 One-click copy with optional clipboard auto-clear
- 🔒 Automatic vault locking after inactivity
- 🔔 Optional OTP expiry notifications
- ⚙️ Advanced OTP configuration:
  - SHA-1
  - SHA-256
  - SHA-512
  - 6–8 digit codes
  - Custom time periods
- 🎨 Light, Dark, and System themes
- 🌍 Multi-language support:
  - English
  - Spanish
  - French
  - German
  - Arabic
  - Japanese

## 🔐 Privacy First

Your security and privacy are our highest priorities.

- ✅ No analytics
- ✅ No advertising
- ✅ No telemetry
- ✅ No tracking
- ✅ No cloud storage
- ✅ No account required
- ✅ No data collection
- ✅ Authentication data remains under your control

All OTP secrets and settings are stored locally on your device. If you enable vault encryption, your data is protected using industry-standard cryptography.

Privacy Policy:
https://algodox.github.io/Secure-Authenticator/privacy-policy

## 🛡 Permissions Used

| Permission | Purpose |
|------------|---------|
| `storage` | Securely stores your encrypted local vault and settings. |
| `clipboardRead` | Imports OTP accounts from clipboard content when requested by the user. |
| `clipboardWrite` | Copies OTP codes and supports optional automatic clipboard clearing. |
| `activeTab` | Reads QR codes from the active webpage only when you initiate QR import. |
| `alarms` | Handles OTP refresh timing, auto-lock, clipboard auto-clear, and reminders. |
| `notifications` | Displays optional local security and OTP expiry notifications. |

## 📜 Standards

Secure Authenticator complies with:

- RFC 6238 (Time-based One-Time Password)
- RFC 4226 (HMAC-based One-Time Password)

These standards are supported by major authentication providers and services worldwide.

## ❤️ Security by Design

Secure Authenticator is built with a privacy-first architecture.

- Local-first operation
- Offline OTP generation
- Encrypted local vault
- No remote code execution
- No hidden trackers
- No background data collection

Your authentication data stays on your device, where it belongs.
