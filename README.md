![Screenshot (12)](https://user-images.githubusercontent.com/121276285/216772781-41d1f9c9-4884-4a0c-810d-8c928a5b92cd.png)
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

![Screenshot (10)](https://user-images.githubusercontent.com/121276285/216772796-d7077beb-ef98-4752-af4e-66f06e11c2ed.png)

![Screenshot (11)](https://user-images.githubusercontent.com/121276285/216772814-4a224acf-cf8b-47ee-ab1b-79cea3b4ea6e.png)

![Screenshot (9)](https://user-images.githubusercontent.com/121276285/216772827-0c80f7d9-24f0-4f25-9afe-74aa101757b8.png)

