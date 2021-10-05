# SpongeBobNFTPants

This project creates a smart contract for the blockchain which allows for minting NFTs! It designs the NFTs based on a random combination of words (spongebob related) and when deployed will mint two nfts!

To try this out, you need a crypto wallet (I recommend MetaMask for simplicity, or even importing a wallet into MetaMask) and some fake money ([you can use this faucet](https://app.mycrypto.com/faucet)).

You should also add a .env file with the following parameters filled in:

```
STAGING_ALCHEMY_KEY=ARinkebyAlchemyURL
PRIVATE_KEY=YourCryptoWalletsPrivateKey
```

To compile and run/deploy the contract you can use these commands:

```shell
npx hardhat run scripts/run.js
npx hardhat run scripts/deploy.js --network rinkeby
```

## Learn more

If you're interested in this project, or web3 in general, check out the guys over at [_buildspace](https://buildspace.so/) who created the course where I learnt to do all this!