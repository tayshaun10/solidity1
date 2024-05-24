# MyCredits Solidity Contract

## Description
This Solidity contract provides basic functionalities for managing a custom token named "MyCredits" with the symbol "TOK". It allows token minting (creation) and burning (destruction), while keeping track of the total token supply and individual token balances.

## Functionalities
- **Token Basics**:
  - `name`: Stores the name of the token, set to "MyCredits".
  - `symbol`: Stores the symbol or abbreviation of the token, set to "TOK".

- **Token Supply and Balances**:
  - `totalSupply`: Tracks the total number of tokens in existence.
  - `balances`: Maps Ethereum addresses to their token balances.

- **Minting Tokens**:
  - `mint(address recipient, uint256 amount)`: Creates new tokens and assigns them to a recipient address.

- **Burning Tokens**:
  - `burn(address from, uint256 amount)`: Removes existing tokens from a specified address.

## Usage
1. **Deployment**:
   - Deploy the contract to an Ethereum network using a tool like Remix IDE or Truffle.

2. **Interacting**:
   - Mint new tokens by specifying a recipient address and the amount of tokens to create.
   - Burn existing tokens by specifying an address and the amount to remove.

3. **State Changes**:
   - Each mint or burn operation updates the total token supply and individual balances.

4. **Execution**:
   - Transactions are executed on the Ethereum blockchain, requiring gas fees.

5. **Viewing State**:
   - Access the current state of the contract, including the total supply and token balances, through public variables or by querying the `balances` mapping.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
