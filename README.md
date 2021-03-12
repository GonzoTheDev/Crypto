![Logo](https://raw.githubusercontent.com/GonzoTheDev/cryptocoin-gui/master/images/appicons/256x256.png)

# CryptoCoin

Copyright (c) 2021 The CryptoCoin Project.   
Crypto is based on [Monero](README_original.md) and is forked from [Swap](https://github.com/swap-dev/swap).

![Build-Linux](https://github.com/swap-dev/swap/workflows/Build-Linux/badge.svg)

## Production & Development

Active Branches:
- Stable: master(latest/release)
- Unstable: crypto-dev(latest)
- Testing: N/A

To contribute to the Crypto Project, please make all pull requests to the _crypto-dev_ branch.<br/>
For production, please use the _latest or tagged release_ of the _master_ branch.

## Resources
<<<<<<< Updated upstream
- Webpage: [crypt-o-coin.cash](https://crypt-o-coin.cash)
- Explorer: [explorer.crypt-o-coin.cash](https://explorer.crypt-o-coin.cash)
- Pool List: [miningpoolstats.stream/cryptocoin](https://miningpoolstats.stream/cryptocoin)
- GitHub: [https://github.com/GonzoTheDev/crypto](https://github.com/GonzoTheDev/crypto)
=======
- It is HIGHLY recommended that you join the #monero-dev IRC channel if you are developing software that uses Monero. Due to the nature of this open source software project, joining this channel and idling is the best way to stay updated on best practices and new developments in the Monero ecosystem. All you need to do is join the IRC channel and idle to stay updated with the latest in Monero development. If you do not, you risk wasting resources on developing integrations that are not compatible with the Monero network. The Monero core team and community continuously make efforts to communicate updates, developments, and documentation via other platforms � but for the best information, you need to talk to other Monero developers, and they are on IRC. #monero-dev is about Monero development, not getting help about using Monero, or help about development of other software, including yours, unless it also pertains to Monero code itself. For these cases, checkout #monero. 

- Webpage: [xwp.one](https://xwp.one)
- Explorer: [explorer.xwp.one](https://explorer.xwp.one)
- Pool List: [miningpoolstats.stream/swap](https://miningpoolstats.stream/swap)
- GitHub: [github.com/swap-dev/swap](https://github.com/swap-dev/swap)
>>>>>>> Stashed changes

## Social/Contact

- Bitcointalk [https://bitcointalk.org/index.php?topic=5320548](https://bitcointalk.org/index.php?topic=5320548)
- Discord: [https://discord.gg/upPCtgcMJu](https://discord.gg/upPCtgcMJu)
- Reddit: [r/CryptoCoinProject/](https://www.reddit.com/r/CryptoCoinProject/)
- Twitter: [@CryptocoinDev](https://twitter.com/CryptocoinDev)
- Email: therealcryptocoin@gmail.com

## Specifications & Emission

- Coin ticker: CRYPTO
- Total supply: 18,400,000 coins before tail emission
- Tail emission: ~158,000 coins each year (starting at year 8)
- Decimal places: 12
- PoW hash algorithm: Cuckaroo29s
- Block time: 15 seconds
- Difficulty Adjustment Algorithm: Monero DAA
- Genesis block: 2021-03-01 (March 01, 2021) at 00:00:00 (UTC)
- Premine: No
- Developer fee: No
- Founders reward: No
- Mainnet default P2P port: 11111
- Mainnet default RPC port: 22222

## Donation Address
cashdj5d7FM9fh1ezdLg6ibJcwy3bkyXjEw6LuVWJTDceECuW4Ypa6aY3mqNEwPorLedHpLzSGrDef6n7CmHVeHb8w3XEVsM6R

## Build on linux

install deps:

`sudo apt-get install build-essential cmake pkg-config libboost-all-dev libssl-dev libzmq3-dev libunbound-dev libsodium-dev libreadline6-dev libpgm-dev libnorm-dev libhidapi-libusb0`

clone repo:

`git clone --recursive https://github.com/GonzoTheDev/crypto`

build daemon and wallet:

`cd crypto && mkdir build && cd build && cmake .. && make daemon simplewallet`

or build everything:

`cd crypto && mkdir build && cd build && cmake .. && make`

## Build on Windows (using MinGW)

install deps:

`pacman -S mingw-w64-x86_64-toolchain make mingw-w64-x86_64-cmake mingw-w64-x86_64-boost mingw-w64-x86_64-openssl mingw-w64-x86_64-zeromq mingw-w64-x86_64-libsodium mingw-w64-x86_64-hidapi`

clone repo:

`git clone --recursive https://github.com/GonzoTheDev/crypto`

build daemon and wallet:

`cd crypto && make release-static-win64`

