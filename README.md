# ETH-AVAX-module-4
GameToken is an ERC20 token contract that allows for the creation and transfer of in-game tokens. It is built using OpenZeppelin's ERC20 implementation.

## Features

- Minting of tokens by the contract owner
- Transfer of tokens between addresses
- Redeeming of tokens for in-game items
- Burning of tokens by token holders

## Usage

To use the GameToken contract, simply deploy it to your desired network and interact with it using your preferred wallet or dApp.

### Minting Tokens

Only the contract owner can mint new tokens. To mint tokens, call the mint function with the address to mint to and the amount to mint.

### Transferring Tokens

Tokens can be transferred between addresses using the standard ERC20 transfer function.

### Redeeming Tokens

Tokens can be redeemed for in-game items using the redeem function. The specifics of how this works are up to the game developer.

### Burning Tokens

Token holders can burn their own tokens using the burn function.

## License

This contract is licensed under the MIT License. See LICENSE for more information.
