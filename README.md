# Simple Token Program

## Overview

This Aleo smart contract, named "simpletoken.aleo," provides basic functionality for managing a simple token system on the Aleo blockchain. It allows users to perform token minting and transfers, both publicly and privately.

## Features

### Mint Tokens

- **Mint Publicly:** The `mint_public` function issues a specified amount of tokens to a receiver publicly. It records this transaction on the blockchain.

- **Mint Privately:** The `mint_private` function initializes a new record for the receiver with a specified amount of tokens. This operation remains private.

### Transfer Tokens

- **Transfer Publicly:** The `transfer_public` function enables the public transfer of tokens from the sender to the receiver. This is recorded on the blockchain.

- **Transfer Privately:** The `transfer_private` function allows the private transfer of tokens from the sender to the receiver.

- **Transfer Private to Public:** The `transfer_private_to_public` function converts private tokens into public tokens for a specified receiver. It reveals the receiver and token amount publicly.

- **Transfer Public to Private:** The `transfer_public_to_private` function converts public tokens into private tokens for a specified receiver. It reveals the caller and token amount publicly.

## Usage

This smart contract can be deployed on the Aleo blockchain to create and manage your custom token system. You can perform both public and private token operations based on your specific use case.

## Getting Started

To get started with this smart contract, you can deploy it on the Aleo blockchain, and users can interact with it through Aleo-supported tools and platforms.

## Discord:nilssibl
