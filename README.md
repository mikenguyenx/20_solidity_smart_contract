# Blockchain Smart Contracts

A fintech startup company has recently hired you. This company is disrupting the finance industry with its own cross-border, Ethereum-compatible blockchain that connects financial institutions. Currently, the team is building smart contracts to automate many of the institutions’ financial processes and features, such as hosting joint savings accounts.

To automate the creation of joint savings accounts, you’ll create a Solidity smart contract that accepts two user addresses. These addresses will be able to control a joint savings account. Your smart contract will use ether management functions to implement a financial institution’s requirements for providing the features of the joint savings account. These features will consist of the ability to deposit and withdraw funds from the account.

## Technologies

Programming Languages: Solidity
Version: Pragma Solidity ^0.5.0


## Instructions

The steps for this Challenge are divided into the following sections:

1. Create a Joint Savings Account Contract in Solidity

2. Compile and Deploy Your Contract in the JavaScript VM

3. Interact with Your Deployed Smart Contract

## Installation

1. Clone the repository: git clone "https://github.com/mikenguyenx/20_solidity_smart_contract.git" using git or download the ZIP file and extract it to a local directory.

2. Open the Solidity file named joint_savings.sol in the Remix IDE.

3. Compile and Deploy contract in the Javascript VM using Remix IDE (https://remix.ethereum.org/).

4. Interact with the deployed smart contract to transfer and withdraw funds.

5. Sample execution results can be found in the [Execution_Results](https://github.com/mikenguyenx/20_solidity_smart_contract/tree/main/Execution_Results) folder.

## Smart Contract Features

- Deposit feature that allows users to deposit Ether into the contract. The contract balance is updated with each deposit.

- Withdraw feature that allows account holders to withdraw Ether. 

- Safeguard to ensure only the account holders can perform withdrawals (“You don't own this account!”) 

- Safeguard to ensure that the requested withdrawal amount does not exceed the contract balance (“Insufficient funds!”).  

- SetAccounts feature that allows updates to the details of account holders Ethereum addresses.

- Fallback feature that allows the contract to accept and store Ether sent outside the deposit function.


## Contributors

Mike Nguyen

## License

GNU General Public License v3.0