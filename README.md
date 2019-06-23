# Swap

Swap (previously known as Freehaven) is based on [Monero](README_original.md)  

## Resources

- Webpage: [swap.fyi](https://swap.fyi/)
- Explorer: [swap.coinscope.cc](https://swap.coinscope.cc/)
- Pool List: [miningpoolstats.stream/swap](https://miningpoolstats.stream/swap)
- GitHub: [github.com/swap-dev/swap](https://github.com/swap-dev/swap)

## Social/Contact

- Bitcointalk [bitcointalk.org/index.php?topic=5083455](https://bitcointalk.org/index.php?topic=5083455)
- Discord: [discord.gg/SmcFCPu](https://discord.gg/SmcFCPu)
- Reddit: [r/SwapProject/](https://www.reddit.com/r/SwapProject/)
- Twitter: [@_realSwap](https://twitter.com/_realSwap)
- Email: xwpdev@gmail.com

## Specifications & Emission

- Coin ticker: XWP
- Total supply: 18,400,000 coins before tail emission
- Tail emission: ~158,000 coins each year (starting at year 8)
- Decimal places: 12
- PoW hash algorithm: Cuckaroo29s
- Block time: 15 seconds
- Difficulty Adjustment Algorithm: Monero DAA
- Genesis block: 2018-11-16 (November 16, 2018) at 09:06:03 (UTC)
- Premine: No
- Developer fee: No
- Founders reward: No
- Mainnet default P2P port: 19949
- Mainnet default RPC port: 19950

## Donation Address
fh2jc6PbQYd4a5PY3ooPMZiPVniMy4MGcjSRBnoBVc1xLmdCHJ6hc98Ess2hpN2mDgPnCAXtDUUbmjWYutRvdoSr2Nps2o5wc

## Build on linux

install deps:

`sudo apt-get install build-essential cmake pkg-config libboost-all-dev libssl-dev libzmq3-dev libunbound-dev libsodium-dev libreadline6-dev libpgm-dev`

clone repo:

`git clone --recursive https://github.com/swap-dev/swap`

build daemon and wallet:

`cd swap && mkdir build && cd build && cmake .. && make -j4 daemon simplewallet`

