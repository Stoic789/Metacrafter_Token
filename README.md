# MyToken

MyToken is a simple token contract implemented in Solidity. It allows you to create and destroy tokens, as well as keep track of token balances for different addresses.

## Features

- Minting: The `mint` function allows you to create new tokens by increasing the total supply and the balance of a specified address.
- Burning: The `burn` function allows you to destroy tokens by reducing the total supply and the balance of a specified address, with a check to ensure the sender's balance is sufficient.

## Getting Started

### Prerequisites

To interact with the MyToken contract, you need the following:

- A development environment for Solidity smart contracts (e.g. Remix).
- A compatible Ethereum network or a local blockchain for deployment and testing .

### Deployment

1. Deploy the MyToken contract to your chosen Ethereum network or local blockchain using your preferred development environment.
2. Once deployed, you can interact with the contract by calling its functions, such as `mint` and `burn`, using the provided parameters.

## Usage

1. Minting Tokens:
   - Call the `mint` function, passing the recipient's address and the desired token value as parameters.
   - The `TotalSupply` will be increased by the specified value, and the recipient's balance will also be increased.

2. Burning Tokens:
   - Call the `burn` function, passing the sender's address and the token value to be burned as parameters.
   - The function will check if the sender's balance is greater than or equal to the specified value.
   - If the condition is met, the `TotalSupply` will be decreased by the specified value, and the sender's balance will also be decreased.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

