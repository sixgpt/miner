# SixGPT Miner

This is the official SixGPT miner.

First install docker on your machine. (https://docs.docker.com/engine/install/)

Then set the following environment variables:

```
git clone 
cd miner
export VANA_PRIVATE_KEY=<your_private_key>
export VANA_NETWORK=satoshi // satoshi | moksha | mainnet
docker compose up
```

## Notes
- You must have logged into sixgpt.xyz with your wallet before running the miner
- Make sure the wallet associated with your vana private key has enough $VANA balance on the desired network (at least 0.1)
