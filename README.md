# ERC20 Smart Contract Library  

A curated collection of ERC20 token smart contracts for various use cases and applications.

## votingEscrow.sol

Contract module which provides a basic access control mechanism, where there is an account (an owner) that can be granted exclusive access to specific functions. By default, the owner account will be the one that deploys the contract. This can later be changed with {transferOwnership}. This module is used through inheritance. It will make available the modifier `onlyOwner`, which can be applied to your functions to restrict their use to the owner.

## erc20plus.sol

ERC20 token with features such as transaction tax, anti-bot measures, & automatic liquidity provision.

## sample-contract.sol

A sample contract for testing and demonstration purposes.

## erc20.sol

ERC20 token standard implementation.

## data-query-contract.sol

Contract module for querying data from the contract.

## lottery.sol

A contract for conducting a lottery.

## multisend.sol

Contract module which provides a basic access control mechanism, where there is an account (an owner) that can be granted exclusive access to specific functions. By default, the owner account will be the one that deploys the contract. This can later be changed with {transferOwnership}. This module is used through inheritance. It will make available the modifier `onlyOwner`, which can be applied to your functions to restrict their use to the owner.

## simpleStaking.sol

A simple staking contract.

## crowdFund.sol

This smart contract allows users to create and participate in crowdfunding campaigns. Users can launch a campaign with a specified goal and duration. They can pledge tokens to a campaign, and the pledged amount is tracked. The creator can claim the pledged tokens if the goal is reached, or users can request a refund if the goal is not reached.

## multiSigWallet.sol

The MultiSigWallet contract is a multi-signature wallet that requires multiple owners to confirm and execute transactions. It allows owners to deposit funds, submit transactions, confirm transactions, revoke confirmations, and execute transactions. The contract keeps track of the number of confirmations required and the status of each transaction.

## erc20shitcoin.sol

This smart contract implements trading functionalities, including creating a trading pair on a decentralized exchange. The contract manages buy and sell taxes, which can be adjusted based on the number of transactions. It supports token swaps for ETH and transfers ETH to a designated wallet. The contract also includes mechanisms to exempt certain addresses from fees and to lock swaps during execution.
