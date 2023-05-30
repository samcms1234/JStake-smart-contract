# JStake: The control is with YOU!

This is a simple web application that interacts with a Staking Contract on the Ethereum blockchain. The application allows users to stake tokens, unstake tokens, claim rewards, and transfer tokens to other accounts.

## Features

- Stake tokens: Users can stake their tokens into the staking contract and earn rewards.
- Unstake tokens: Users can unstake their tokens from the staking contract.
- Claim rewards: Users can claim their earned rewards from the staking contract.
- Transfer tokens: Users can transfer tokens from their account to another account.

## Technologies Used

- React: JavaScript library for building the user interface.
- ethers.js: Library for interacting with the Ethereum blockchain.
- Web3: Library for interacting with the Ethereum provider (e.g., MetaMask).
- Hardhat: Development environment for Ethereum smart contracts.
- Solidity: Programming language for writing smart contracts.
- React Toastify: Library for displaying notifications in the web application.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Solidity
- Javascript
- Node.js
- Hardhat
- Git

### Installing

1. Clone the repository to your local machine

```shell
git clone https://github.com/samcms1234/JStake-smart-contract.git
```

2. Install the dependencies

```shell
cd JStake-smart-contract
```
```shell
npm install
```

3. Compile and deploy the contracts

```shell
npx hardhat node
```

```shell
npx hardhat run scripts/deploy.js --network localhost
```

4. Run the tests

```shell
npx hardhat test
```


Contract address:
 ```shell
 0x56A24924c3B6A2B2d6DA28039fB0Da609D9d6851
 ```
### Built With

- Ethereum - Blockchain platform
- Solidity - Smart contract language
- Hardhat - Development framework for Ethereum

### Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any bugs, feature requests, or suggestions.

### License

This project is licensed under the MIT License.