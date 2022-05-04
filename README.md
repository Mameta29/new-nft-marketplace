# Local setup
To run this project locally, follow these steps.

1. Clone the project locally, change into the directory, and install the dependencies:

```
git clone https://github.com/Mameta29/new-nft-marketplace.git

cd new-nft-marketplace

# install using NPM or Yarn
npm install

# or

yarn
```

2. Start the local Hardhat node

```
npx hardhat node
```

3. With the network running, deploy the contracts to the local network in a separate terminal window
```
npx hardhat run scripts/deploy.js --network localhost
```

4. Start the app
```
npm run dev
```

5. Open any browser with "localhost:3000"
