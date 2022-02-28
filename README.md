# Ethereum Dapp for Tracking Items through Supply Chain
Project for Udacity - Blockchain Developer Nanodegree.
Boilerplate code provided [here](https://github.com/udacity/nd1309-Project-6b-Example-Template)

#### Project general write-up:
Project is build in accordance to plan provided by Udacity - Project Details.
Project has been divided to multiple building parts:
- 1 Plan the project. I added UML diagrams required in specification. 
- 2 Write smart contracts: Based on the boilerplate and specifications, I added the required code for the smart contract.
- 3 Test smart contract code coverage: Based on the boilerplate and specifications, I added the required code for test coverage ensuring all test are passing.
- 4 Deploy smart contracts on Rinkeby: I used the Truffle framework and Infura to deploy my smart contracts onto the Rinkeby test network.

#### Very helpful resources 
1. [Architect a Blockchain Supply Chain Solution Part B Project FAQ — Udacity Blockchain](https://andresaaap.medium.com/architect-a-blockchain-supply-chain-solution-part-b-project-faq-udacity-blockchain-da86496fce55)
2. Error fix: [truffle-contract.js:28 Uncaught TypeError:](https://knowledge.udacity.com/questions/566213)
3. UML diagrams tool [LucidChart](https://www.lucidchart.com/)
4. UML diagrams tool [Draw.io](https://www.draw.io/)
5. Development suite [Infura](https://www.infura.io)
6. Crypto wallet [Metamask](https://www.metamask.io)

#### Contract address deployed on the Ethereum RINKEBY test network
[0x55dc0222616fF09b4C157bFB4E92112D113Ec2aE](https://rinkeby.etherscan.io/address/0x55dc0222616ff09b4c157bfb4e92112d113ec2ae)


#### Version numbers
```
Truffle v4.1.14
Solidity v0.4.24
Node v12.17.0
Web3.js v1.7.0
```

```
"dependencies": {
    "dotenv": "^16.0.0",
    "truffle-contract": "^4.0.31",
    "truffle-hdwallet-provider": "^1.0.17"
  }
```