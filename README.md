# Smart Contract Lottery

This repository contains a smart contract lottery built using Python, Brownie, Infura, Goerli, and Solidity. The smart contract utilizes a random number generator to ensure that the lottery results are unpredictable and unbiased. The contract is designed to be simple to understand and implement, while still providing a secure and reliable system for conducting lotteries.

1. Users can enter lottery with ETH based on a USD fee.
2. An admin will choose when the lottery is over.
3. The lottery will select a random winner.

## Technologies Used

-   Python
-   Brownie
-   Infura
-   Goerli
-   Solidity

## Getting Started

To get started with this project, you'll need to have Python, Brownie, Infura, and Goerli installed on your machine. Once you have these dependencies installed, you can clone this repository and deploy the smart contract to the Goerli testnet using Brownie.

bash

`git clone https://github.com/ibra-zeno/smart-contract-lottery.git		`
`cd smart-contract-lottery	`
`brownie run deploy --network goerli` 

## Features

-   Random number generator to ensure unpredictability and unbiased results
-   Simple implementation and understanding of the contract
-   Secure and reliable system for conducting lotteries

## Usage

To use the smart contract, you can interact with it using a web3 provider such as Infura. You can use the `Lottery` contract ABI and contract address to interact with the contract functions.


`from web3 import Web3`
`w3 = Web3(Web3.HTTPProvider(INFURA_ENDPOINT))`
`lottery = w3.eth.contract(address=CONTRACT_ADDRESS, abi=CONTRACT_ABI)`


## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.
