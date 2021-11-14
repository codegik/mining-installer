# Mining RIG setup

Customizing the ubuntu to mining crypto currencies ETC, ETH, XMR or ZEC.

## Setup

Added permission to execute the scripts.
```
chmod +x install-dependencies install-miner install-nvidia install-radeon set-hostname
```

Add your wallet addresses to receive the mining profit.
```
echo "<my etc wallet address>" > etc-wallet
echo "<my eth wallet address>" > eth-wallet
echo "<my xmr wallet address>" > xmr-wallet
echo "<my zec wallet address>" > zec-wallet
```

## Running

Usage:
```
./install-miner <nvidia|radeon> <etc|eth|xmr|zec>
```

Sample to install the miner for ETC with nvidia driver:
```
./install-miner nvidia etc
```

The mining script will start on the system boot.