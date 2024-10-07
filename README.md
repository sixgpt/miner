# SixGPT Miner
This is the official SixGPT miner.

# About

SixGPT is a decentralized synthetic data generation platform built on the Vana network. We empower users by giving them ownership of their data and enabling them to earn from it.

The SixGPT Miner is a software package which allows users to contribute data they generate for wikipedia question-answer based tasks to the network for rewards.
In the future, we will support other tasks such as chatbot conversations, image captioning, etc.

## Prerequisites
(1) install docker on your machine. (https://docs.docker.com/engine/install/)

(2) Fund your wallet with $VANA and log onto sixgpt.xyz with it.

(3) Login with this wallet on sixgpt.xyz


## Run the miner
Clone the repository:
```
git clone git@github.com:sixgpt/miner.git
cd miner
```

Set the following environment variables:
```
export VANA_PRIVATE_KEY=<your_private_key>
export VANA_NETWORK=satori
```

Run the miner:
```
docker compose up
```

## Notes
- You must have logged into sixgpt.xyz with your wallet before running the miner
- Make sure the wallet associated with your vana private key has enough $VANA balance on the desired network (at least 0.1)
