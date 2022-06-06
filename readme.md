JOINT ACCOUNTS IN WEB3.0

Smart contract -> https://github.com/dikshantrajput/multisig-wallet-contract

Intro:
joint account -> more than one member is the owner of that account and can send transactions to another person or do something with the money they together saved or collected.

NOTE:There will be separate accounts but all the tx will be happening when a proposal gets a certain number of votes.

### Flow:
* Submitting a proposal
* Getting approved by majority
* Executing the tx 

There will be a one day lapse between the proposal and execution. This is done to keep the system fair and anyone can revoke their approval anytime before the execution.


In case of withdrawal (pass data in proposal as withdrawal), it will also happen with the help of proposals and every holder will get equal amount specified.


### Improvements:
* UI
* Implementation of backend for storing events and every other data for optimizations


### Steps to run the project:
Prerequisite -> You will need some fake ethers in any testnet and metamask wallet installed on your browser
* Clone the repo
* Run the index.html file
* Create a joint account by providing a bunch of addresses
* Provide count for minimum approvals required for a tx to go through
* Sign the transaction using metamask
* You will get an address of your deployed contract.
* Paste it into the load account field.
* Now you can create as many proposals and anyone whom you specified while creating joint account can approve and as soon as it gets minimum no of approvals, he/she can then execute the tx 
