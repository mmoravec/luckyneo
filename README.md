# Lucky NEO

## Overview
Lucky NEO lets users send GAS to a smart contract to enter into a two week contest. At the end of the two weeks, one winner will be chosen to receive the winnings of the contest

## Why Lucky NEO?
Token games are a great past time that is fun for all. As your GAS dividends roll in, you can now use them to enter a contest for a chance to win up to 1024 GAS

## How does Lucky NEO work?
Send your GAS to the contract address provided on our website at [www.luckyneo.com](www.luckyneo.com). [Soon] See the page to view your current chance to win and countdown till our random draw. We will draw one winner at the end of the two week period. Winner is chosen at random.

## Features
- Entries capped at 1024 GAS
- You can submit as much GAS as you like up to the cap
- Winner is drawn every two weeks
- GAS is automatically sent to the winning address
- See your chance to win on our website
- 97% Payout at 1024 GAS

## Try it out yourself!
We used the fantastic neo-python library to build and test Lucky NEO.
* clone neo-python to your computer and follow the installation steps
* setup a private chain and claim all NEO https://github.com/CityOfZion/neo-privatenet-docker 
* open your wallet
* move LuckyNeo.py to the neo-python main directory
* build LuckyNeo.py 05 05 True
* import contract LuckyNeo.avm 05 05 True  
* copy the contract hash from the invoke step and wait for the transaction to work its way through the chain
* testinvoke {contract_hash} deploy
* this deploys the contract and sets an empty array
* testinvoke {contract_hash} '' --attach-gas=5
* here we are sending gas to the contract and you'll see your entries printed out
* any address on the test network can send entries 
* at the end of the time period the winner will automatically be sent their winnings 


## Soon to come
We will finish our site at luckyneo.com so that anyone wanting to participate will be able to send their gas to the listed address and track the contest progress on the site. 




