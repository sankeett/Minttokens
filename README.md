# MyToken

MyToken is a Solidity smart contract that implements a basic token with minting and burning functionalities.

## Requirements

1. The contract has public variables that store the details about the coin, including the Token Name, Token Abbreviation, and Total Supply.
2. The contract maintains a mapping of addresses to balances (`address => uint`), which represents the token balance for each address.
3. The `mint` function increases the total supply of the token and adds the specified value to the balance of the sender's address.
4. The `burn` function decreases the total supply of the token and deducts the specified value from the sender's address balance.
5. The `burn` function includes conditionals to ensure that the sender's balance is greater than or equal to the amount to be burned.

## Usage

1. Deploy the `MyToken` contract on the Ethereum network using a compatible Ethereum development framework, such as Remix or Truffle.
2. Interact with the contract by calling the following functions:

   - `mint(address _address, uint _value)`: Mints new tokens by increasing the total supply and adding the specified value to the balance of the given address.
   - `burn(address _address, uint _value)`: Burns existing tokens by reducing the total supply and deducting the specified value from the balance of the given address.

##Contributing
Contributions to this repository are not accepted as it is for personal assignments. However, if you have suggestions or feedback, feel free to open an issue.

##License
This project is licensed under the MIT License. You are free to modify and distribute the code for personal and educational purposes.
