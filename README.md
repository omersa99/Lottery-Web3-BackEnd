# Lottery Smart Contract - WEB3 BackEnd
With this smart contract you can manage any form of lottery games that involves the drawing of numbers at random for a prize and handing out tickets.

the mechanism design based on token economics and insures that no prospective owner-occupant has an unfair advantage in the determination of winner.




## Built With [![Next][Next.js]][Next-url]

## Demo
Here is a working live demo: [Web3-lottery-v1](http://web3-lottery-v1.vercel.app)

Deploy the CONTRACT DIRECTLY here: [BackEnd API](https://thirdweb.com/0x741179Acd84FeDEb7315a8ce4149f5cEF914185c/Lottery)

<!-- GETTING STARTED -->
## Getting Started

This is how you may set up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites
  ```sh
  MetaMask account - cryptocurrency wallet 
  ```
  ##### MetaMask only supports Chrome, Firefox, Edge, and Brave browsers and is not available on Safari
  
  
### Installation

1. Get a free API Key at [thirdweb.com](thirdweb.com)
2. Clone the repo
   ```sh
   git clone github.com/omarsa999/lottery-smart-contract.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
  
5. In your app:

<p align="center">
<img src="https://user-images.githubusercontent.com/72961940/189704641-00fdc1b0-e713-46b1-8db7-2b7ec68a46a0.png" width="250" height="300" />
</p>

## Deploy
using **Thirdweb**'s SDK deploy feature, a Powerful SDK to integrate decentralized and Web3 technologies into the backend [Read More](https://portal.thirdweb.com/)


## Features

### Write to BlockChain:
* BuyTickets
* DrawWinnerTicket
* RefundAll
* WithdrawCommission
* WithdrawWinnings
* restartDraw

### Read from BlockChain
* CurrentWinningReward
* IsWinner
* RemainingTickets
* checkWinningsAmount
* duration
* expiration
* getTickets
* getWinningsForAddress
* lastWinner
* operatorTotalCommission
* and more ..



<!-- CONTACT -->
## Contact

[@OmarSa] - hello@omarsa.tech
Project Link: [https://github.com/omarsa999/web3-lottery](https://github.com/omarsa999/web3-lottery)


> This repository was extended from its original smart contract repo: https://github.com/drord9/Lottery

### Research inspiration
[Web3 Meets Behavioral Economics](https://arxiv.org/abs/2206.03664)

[Next.js]: https://img.shields.io/badge/solidity-000000?style=for-the-badge&logo=solidity&logoColor=white
[Next-url]: https://nextjs.org/
