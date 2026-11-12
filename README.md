<div align="center">

<img src="assets/logo.png" alt="Ibis Accounts" width="96">

# Ibis Accounts

A private, encrypted manager for your Steam accounts on Windows 10 / 11 (64-bit).

**[⬇ Download the latest version](../../releases/latest)** &nbsp;·&nbsp; current version: **1.0.0**

</div>

## Install

1. Open the [latest release](../../releases/latest) and download **`IbisAccounts.exe`**.
2. Run it. It's a single file: no installer, nothing else to download.
3. The first time, Windows may show **"Windows protected your PC"** because the app isn't
   code-signed yet. Click **More info → Run anyway**.
   (Or right-click the file → **Properties** → tick **Unblock** → OK.)
4. Create a master password. There is no way to recover it, so keep it safe.

## Get notified about new versions

On this page click **Watch → Custom → Releases → Apply**. GitHub e-mails you whenever a
new version is published. To update, download the new `IbisAccounts.exe` and replace the
old one; your accounts and settings are kept.

## Check your download (optional)

Every release lists the file's SHA-256 checksum. In PowerShell:

```powershell
Get-FileHash .\IbisAccounts.exe -Algorithm SHA256
```

The value must match the one on the release page. If it doesn't, don't run the file.

## Your data

- Accounts are stored encrypted on your PC only (AES-256-GCM).
- **Ibis Cloud** backup is optional and end-to-end encrypted: the server only stores data it
  can't read.
- No telemetry. Confirmations and trades are never accepted automatically.

---

This repository only hosts release downloads. Ibis Accounts is based on MIT-licensed
open-source code; see [LICENSE](LICENSE).
