# Secure-Authenticator
Secure Authenticator for 2FA OTP codes. TOTP & HOTP, encrypted vault, QR import. Private and fast.

## Detailed description

Secure Authenticator keeps your two-factor codes encrypted and under your control.

Generate time-based (TOTP) and counter-based (HOTP) codes using RFC 6238 and RFC 4226. Import accounts from QR codes or common authenticator export formats, organize them with groups and favorites, and protect the vault with an optional master password.

### Why Secure Authenticator

- Professional 2FA authenticator for TOTP and HOTP
- Encrypted vault: AES-256-GCM with PBKDF2 key derivation
- Flexible OTP settings: SHA-1 / SHA-256 / SHA-512, 6–8 digits, custom periods
- Fast popup UI with countdown rings and click-to-copy codes
- Auto-lock and clipboard auto-clear
- Import from Google Authenticator exports, Aegis, 2FAS, Bitwarden, URI lists, CSV, and encrypted JSON
- Export to encrypted JSON, CSV, URI list, or QR bundle
- Light, dark, and system themes
- English, Spanish, French, German, Arabic, and Japanese

### Privacy

No analytics. No ads. No telemetry for OTP generation.

### Permissions

storage, clipboardRead, clipboardWrite, activeTab, alarms, notifications — used for the local vault, copy/clear, and optional expiry alerts.
