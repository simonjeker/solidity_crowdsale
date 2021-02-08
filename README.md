# solidity_crowdsale

## Project Overview
The goal was to deploy a crowdsale, which offered PupperCoin tokens (PUP) in exchange for ether (ETH). 
To complete this project the following OpenZeppelin libraries were utilized: 
ERC20, ERC20Detailed, ERC20Mintable, Crowdsale, MintedCrowdsale, CappedCrowdsale, TimedCrowdsale, and RefundablePostDeliveryCrowdsale. 
All libraries were used together to deploy the crowdsale and define parameters of the sale. 
A total of three contracts were built to accomplish all tasks. The PupperCoin contract was used to generate tokens, 
the PupperCoinSale contract defines the parameters of the crowdsale, and the PupperCoinSaleDeployer contract brings all contracts 
together and deploys the sale. 
