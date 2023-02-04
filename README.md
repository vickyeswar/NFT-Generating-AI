# Generate NFTs with AI and mint directly to the IPFS by a simple click.
### Setup .env file:
Before running any scripts, you'll want to create a .env file with the following values (see .env.example):

- **REACT_APP_HUGGING_FACE_API_KEY=""**
- **REACT_APP_NFT_STORAGE_API_KEY=""**

You'll need to create an account on [Hugging Face](https://huggingface.co/), visit your profile settings, and create a read access token. 

You'll also need to create an account on [NFT.Storage](https://nft.storage/), and create a new API key.

### RUN TEST:
## STEP 01 : add hardhat to your metamask wallet

Network name :  Hardhat

New RPC URL : http://127.0.0.1:8545/

Chain ID : 31337

Currency symbol :  ETH


## STEP 02 : run hardhat and nodeJS server

# start hardhat node : 

`$ npx hardhat node`

# Run deployment script :

`$ npx hardhat run ./scripts/deploy.js --network localhost`

# Start frontend :

`$ npm run start`
