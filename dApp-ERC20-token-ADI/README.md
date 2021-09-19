# ERC20 token - ADI

Here's how to deploy this project

1. Clone the repo

2. Install the dependencies

```sh
npm install

# or

yarn install
```

3. Start the local test node

```sh
npx hardhat node
```

4. Deploy the contract

```sh
npx hardhat run scripts/deploy.js --network localhost
```

5. Update **src/App.js** with the values of your contract address(`tokenAddress`)

6. Run the app

```sh
npm start
```
