# Solidity Program

Decentralized Applications, or Dapps, are programs developed on the open-source Blockchain's peer-to-peer network. To create Dapps both frontend and smart contract are used. So in Ethereum Solidity is the programing language which is used to write the code.Solidity programming language was created by Ethereum, the second-largest cryptocurrency market in terms of capitalization.

## Description
In this program using solidity language. I created simple program in which I created smart contract which is used to store the details of the coin and some other function which are used to mint and burn the coin.

## Getting Started

Follow the steps below to get started with the `MyToken` smart contract:

1. Clone this repository to your local machine.
2. Open the project in your preferred Ethereum development environment for example-Remix.
3. Compile the smart contract using the Solidity compiler.
4. Deploy the contract to your preferred Ethereum network.
5. Interact with the contract using the provided functions.

### Functions

#### `mint()`
This function is used to take two argument (adddress,value) where address is used to take the address at which we want to store the token and value take the no. of token that we want to store at the specified address.

#### `burn()`
This function is used to burn/Delete the Token which are stored at a specific address and this function is also used to take two argument (address,value). In this function an if condition is also added which is used to prevent the condition where the present token in an address is lower than the no. of token that we want to delete.

## Usage

To use the `MyToken` smart contract, follow these steps:

1. Compile the program.
2. Deploy the contract. 
3. After deploying check the curent balance usng 'tottalsupply'.
4. Token Name and Token Abbrv can be cheacked
above the 'tottalsupply'. After that using min() and burn() function you can add and remove the token.

## License

This project is licensed under the MIT License.

## Credits

This project is a solution to the project task provided by MetaCrafters.
