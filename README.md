# MyToken Smart Contract

This Solidity smart contract creates a custom ERC20 token called MyToken. The contract owner has the ability to mint tokens to any provided address, while any user can burn and transfer tokens.

## Prerequisites

- [Node.js](https://nodejs.org/) installed
- [Truffle](https://www.trufflesuite.com/truffle) installed
- [OpenZeppelin Contracts](https://github.com/OpenZeppelin/openzeppelin-contracts) installed

## Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/your/repository.git
   

2. Navigate to the project directory:

   
   cd my-token
   

3. Compile the smart contracts:

   
   truffle compile
   

4. Deploy the smart contract to a network of your choice:

   
   truffle migrate --network <network_name>
   

## Usage

- *Mint Tokens:* The owner can mint tokens to any provided address using the mint function.
- *Burn Tokens:* Users can burn their own tokens using the burn function.
- *Transfer Tokens:* Users can transfer tokens to other addresses using the transfer function.

## Smart Contract Details

- *Owner:* The owner of the contract has the ability to mint tokens.
- *Modifiers:*
  - onlyOwner: Restricts certain functions to be called only by the contract owner.
- *Functions:*
  - mint: Mints tokens to a provided address.
  - burn: Burns a specified amount of tokens.
  - transfer: Transfers tokens to another address.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
