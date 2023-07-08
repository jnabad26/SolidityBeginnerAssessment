# SolidityBeginnerAssessment
myToken.sol is a basic token contract written in Solidity. It provides functionalities for minting and burning tokens. This contract serves as a starting point for understanding token contracts in Solidity.

## Requirements

1. The contract has public variables that store the details about the coin (Token Name, Token Abbreviation, Total Supply).
2. The contract has a mapping of addresses to balances (`address` => `uint`).
3. The `mint` function increases the total supply and the balance of the given address by the specified value.
4. The `burn` function decreases the total supply and the balance of the given address by the specified value, with appropriate conditionals to ensure the balance is sufficient.

## Usage

1. Clone the repository
2. Open the Solidity contract MyToken.sol in your preferred Solidity IDE.
3. Deploy the contract.
4. Interact with the contract using the provided functions:
* mint(address _address, uint _value): Mints new tokens and assigns them to the specified address.
* burn(address _address, uint _value): Burns existing tokens from the specified address.
   
