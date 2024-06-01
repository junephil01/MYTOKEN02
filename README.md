# MyToken Contract

## Overview

This contract, `MyToken`, is a simple ERC20 token implementation written in Solidity. It provides basic functionality for minting and burning tokens.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Usage

### Token Details

- **Token Name**: ASTRO
- **Token Abbreviation**: AST
- **Initial Total Supply**: 0

### Public Variables

- `tokenName`: A public string variable representing the name of the token.
- `tokenAbbrv`: A public string variable representing the abbreviation of the token.
- `totalSupply`: A public uint variable representing the total supply of the token.

### Mapping Variable

- `balances`: A mapping variable that maps addresses to their respective token balances.

### Mint Function

```solidity
function mint(address _address, uint _value) public
