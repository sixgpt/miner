# SixGPT Miner
This is the official SixGPT miner.


## Prerequisites
(1) install docker on your machine. (https://docs.docker.com/engine/install/)
(2) Fund your wallet with $VANA and log onto sixgpt.xyz with it.


## Run the miner
Clone the repository:
```
git clone git@github.com:sixgpt/miner.git
cd miner
```

Set the following environment variables:
```
export VANA_PRIVATE_KEY=<your_private_key>
export VANA_NETWORK=satoshi // satoshi | moksha | mainnet


Run the miner:
```
docker compose up
```

## Notes
- You must have logged into sixgpt.xyz with your wallet before running the miner
- Make sure the wallet associated with your vana private key has enough $VANA balance on the desired network (at least 0.1)
