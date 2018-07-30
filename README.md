# Truffle For Quorum

<img src="https://camo.githubusercontent.com/f9c53a48d03edba49e1a94745a27386cf5e0fc6e/687474703a2f2f74727566666c656672616d65776f726b2e636f6d2f646f63732f696d672f6c6f676f2e706e67" width="200" data-canonical-src="http://truffleframework.com/docs/img/logo.png" style="max-width:100%;">


Using Truffle Framework for Private Transactions on Quorum with Web3.js

## Requirements
This tutorial expects you to have some knowledge of Truffle, Ethereum, Quorum, and Solidity. For more information on these topics, please see the following links:

- Truffle documentation
- Ethereum overview
- Quorum overview and documentation
- Solidity documentation

### Additionally, you will need the following software installed before proceeding:

- VirtualBox
- Vagrant
- Git

## Setting up your Quorum client
The Quorum client is a replacement for the Ethereum client. Using the Quorum client, you can set up a private blockchain that's only available to you and the people you allow to participate.

We're going to use a Quorum cluster of seven nodes (so seven Quorum clients) already set up and configured for us inside a virtual machine. You could choose to install Quorum yourself by downloading it directly and building it from source, but for this example, using the pre-configured cluster is much easier.
