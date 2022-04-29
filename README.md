# XMRig

XMRig is a high performance, open source, cross platform RandomX, KawPow, CryptoNight, AstroBWT and [GhostRider](https://github.com/xmrig/xmrig/tree/master/src/crypto/ghostrider#readme) unified CPU/GPU miner and [RandomX benchmark](https://xmrig.com/benchmark). Official binaries are available for Windows, Linux, macOS and FreeBSD.

## Ubuntu Build
```bash
sudo apt-get install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev
git clone https://github.com/Ashtacore/xmrig.git
mkdir xmrig/build && cd xmrig/build
cmake ..
make -j$(nproc)
```

## Usage
```bash
sudo ./xmrig -o pool.minexmr.com:4444 -u 845e3hwgkPuNyappFgF119VEDyovd5Y59PDUdmJQj6h2fLU6enJ8jYwNkwssPnbdETLQpbv4XGHt2VUECmNAneRV5FX7PMW --rig-ID=rig1
```

## Donations
* I've disabled donations for my personal use, but if you're going to clone this then you should send a donation to the devs here:
* XMR: `48edfHu7V9Z84YzzMa6fUueoELZ9ZRXq9VetWzYGzKt52XU5xvqgzYnDK9URnRoJMk1j8nLwEVsaSWJ4fhdUyZijBGUicoD`

## Original Developers
* **[xmrig](https://github.com/xmrig)**
* **[sech1](https://github.com/SChernykh)**