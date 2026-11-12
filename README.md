<div align="center">

<img src="assets/logo.png" alt="Ibis Accounts" width="96">

# Ibis Accounts

A private, encrypted manager for your Steam accounts, for Windows and Android.

**[⬇ Windows (.exe)](../../releases/latest/download/IbisAccounts.exe)** &nbsp;·&nbsp; **[⬇ Android (.apk)](../../releases/latest/download/IbisAccounts.apk)** &nbsp;·&nbsp; current version: **1.0.0**

</div>

## Install

1. Open the [latest release](../../releases/latest) and download **`IbisAccounts.exe`**.
2. Run it. It's a single file: no installer, nothing else to download.
3. The first time, Windows may show **"Windows protected your PC"** because the app isn't
   code-signed yet. Click **More info → Run anyway**.
   (Or right-click the file → **Properties** → tick **Unblock** → OK.)
4. Create a master password. There is no way to recover it, so keep it safe.

## Android app

The Android app is for **Ibis Cloud** users: it shows the same accounts as your PC, with
live Steam Guard codes, Steam confirmations (accept or deny by hand) and editing that syncs
back to the PC.

1. On the PC, turn on Ibis Cloud: **Settings → Ibis Cloud → Create account**.
2. On the phone, download **[IbisAccounts.apk](../../releases/latest/download/IbisAccounts.apk)**
   and open it. Allow **Install unknown apps** when Android asks. If Play Protect warns,
   tap **Install anyway**.
3. Sign in with the same e-mail and cloud password. The app locks with your fingerprint,
   face or phone PIN.

## Get notified about new versions

On this page click **Watch → Custom → Releases → Apply**. GitHub e-mails you whenever a
new version is published. To update, download the new file and install or replace it
over the old one; your accounts and settings are kept.

## Check your download (optional)

Every release lists each file's SHA-256 checksum. In PowerShell:

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
