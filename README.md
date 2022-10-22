# Smart Contract With Truffle

Smart contract development with truffle has four parts as following,
1.	Installing Truffle
2.	Migrations / deployment
3.	Testing – unit testing
4.	Deployment of the smart contract to the Testnet

# Installing Truffle
- In order to install truffle we need to install Nodejs first.  
-'truffle init' command creates all the contract migration and testing related files.
-To create a new contract the following command needs to be entered into the terminal
'truffle create contract <contract name>'
- To compile a contract 'truffle compile' command is used.
- Migration files are created to deploy the contracts so when these contracts are deployed they are deployed to a local dev chain.
- The command for that is 'truffle migrate'.
- Then 'truffle develop' command is used to open the local dev chain test network for the contracts.

# Migration / Deployment
- Used truffle develop command to make the local node started.
- A simple contract Helloworld is created and in it we created a function hello() which returns a message.
- Another method setMessage() is also created where a new user defined message is passed through the user.
  
# Testing
- This is all about testing the contracts and functions written in them.
- The first test case is written to test the setMessage function.
- The second test case is written to check whether the owner’s address is same as the first value in the accounts array. 

# Deployment of the Smart Contact
- As far as here whatever contract is deployed everything is deployed on the local blockchain network, now here we deploy these contracts to the Ethereum testnet
For that I have used sepolia network.
