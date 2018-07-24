# Truffle For Quorum

Using Truffle Framework for Private Transactions on Quorum

## Requirements
This tutorial expects you to have some knowledge of Truffle, Ethereum, Quorum, and Solidity. For more information on these topics, please see the following links:

- Truffle documentation
- Ethereum overview
- Quorum overview and documentation
- Solidity documentation
- You will primarily be using the command line for this tutorial. Please ensure you have basic familiarity with opening and using the command line provided by your operating system.

## Additionally, you will need the following software installed before proceeding:

- VirtualBox
- Vagrant
- Git

## Setting up your Quorum client
The Quorum client is a replacement for the Ethereum client. Using the Quorum client, you can set up a private blockchain that's only available to you and the people you allow to participate.

We're going to use a Quorum cluster of seven nodes (so seven Quorum clients) already set up and configured for us inside a virtual machine. You could choose to install Quorum yourself by downloading it directly and building it from source, but for this example, using the pre-configured cluster is much easier.
