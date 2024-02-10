# GamingToken Contract 

The GamingToken contract is a Solidity smart contract deployed on the Ethereum blockchain. It implements an ERC20 token with additional functionalities for gaming rewards.

## Features

- **Minting Tokens**: The contract owner can mint new tokens and assign them to specific addresses.
- **Burning Tokens**: Token holders can burn (destroy) their tokens, reducing the total token supply.
- **Transferring Tokens**: Token holders can transfer their tokens to other addresses.
- **Redeeming Rewards**: Token holders can redeem gaming rewards by burning a specific amount of tokens based on the reward type.

## Setup

1. **Deploying the Contract**:
   - Deploy the contract onto the Ethereum blockchain. The constructor initializes the contract with the name "GAMETOKEN" and the symbol "GMT".

2. **Minting Tokens**:
   - The contract owner can mint additional tokens and assign them to specific addresses using the `mint` function.

3. **Burning Tokens**:
   - Token holders can burn their tokens using the `_burn` function. This reduces the total token supply.

4. **Transferring Tokens**:
   - Token holders can transfer their tokens to other addresses using the `transferTokens` function.

5. **Redeeming Rewards**:
   - Token holders can redeem gaming rewards by calling the `redeemReward` function with a specified reward type. The amount of tokens required to redeem each reward type is predefined in the contract.

## Events

- `Redeemed`: Triggered when a token holder redeems a gaming reward. Includes the address of the gamer and the type of reward redeemed.

## Usage

1. Deploy the contract onto the Ethereum blockchain.
2. Use the provided functions to mint, burn, transfer tokens, and redeem gaming rewards.
3. Monitor events emitted by the contract for activity and updates.

## Author

srk5116@gmail.com
