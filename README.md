<p align="center"><img height="200" height="auto" src="https://github.com/furidngrt/Polymer-ibc-testnet/assets/63885192/618a752b-7041-48f0-b98b-91b79dababb1"></p>


### Polymer IBC enabled Solidity contracts


#### Template : https://github.com/open-ibc/ibc-app-solidity-template/tree/main



#### Installation Package
```
sudo apt-get update
sudo apt-get upgrade
apt install npm
sudo apt install git
```

#### Install Nodejs

```
sudo apt install curl wget gnupg
curl -fsSL https://deb.nodesource.com/gpgkey/nodesource.gpg.key | sudo gpg --dearmor -o /usr/share/keyrings/nodesource.gpg
echo "deb [signed-by=/usr/share/keyrings/nodesource.gpg] https://deb.nodesource.com/node_18.x $(lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/nodesource.list
sudo apt update
sudo apt install nodejs
node --version
npm --version
```

#### Install Foundry

```
curl -L https://foundry.paradigm.xyz | bash
foundryup
```

```
source /home/gitpod/.bashrc
```

#### Install Just

```
wget -qO - 'https://proget.makedeb.org/debian-feeds/prebuilt-mpr.pub' | gpg --dearmor | sudo tee /usr/share/keyrings/prebuilt-mpr-archive-keyring.gpg 1> /dev/null
echo "deb [arch=all,$(dpkg --print-architecture) signed-by=/usr/share/keyrings/prebuilt-mpr-archive-keyring.gpg] https://proget.makedeb.org prebuilt-mpr $(lsb_release -cs)" | sudo tee /etc/apt/sources.list.d/prebuilt-mpr.list
sudo apt update
sudo apt install just
```

#### Create API Explorer

Optimsm : https://optimism-sepolia.blockscout.com/account/api-key
<p>
Base : https://base-sepolia.blockscout.com/account/api-key


#### Create Alchemi API Key for Optimsm and Base

https://www.alchemy.com/

#### Configuration

```
git clone https://github.com/username/repo
```

```
cd your-repo
```

```
cp .env.example .env
```

```
nano .env
```

PRIVATE KEY = 'FILL_YOUR_PRIVATE_KEY'
<p>
OP_ALCHEMY_API_KEY='FILL_YOUR_ALCHEMY_OP_KEY' 
<p>
BASE_ALCHEMY_API_KEY='FILL_YOUR_ALCHEMY_BASE_KEY' 
<p>
OP_BLOCKSCOUT_API_KEY='FILL_YOUR_EXPLORER_OP_API_KEY' 
<p>
BASE_BLOCKSCOUT_API_KEY='FILL_YOUR_EXPLORER_BASE_API_KEY'
<p>
TENDERLY_TOKEN='D0_NOT_FILL'

```
just install
```

####  Run IBC channel

```
just do-it
```

Check your channel IBC on https://sepolia.polymer.zone/packets
