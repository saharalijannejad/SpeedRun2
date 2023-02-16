# SpeedRun2

This challenge will help you build/understand a simple decentralized exchange, with one token-pair (ERC20 BALLOONS ($BAL) and ETH). This repo is an updated version of the original tutorial and challenge repos before it. Please read the intro for a background on what we are building first!

There is a DEXTemplate.sol file for your use if you want (rename it to DEX.sol). As well, this repo has solutions (👮🏻 try not to peak!) in it (in root directory, there's a solutions sub-directory) for now, but the challenge is to write the smart contracts yourself of course!

Balloons.sol is just an example ERC20 contract that mints 1000 $BAL to whatever address deploys it. DEX.sol is what we will build in this challenge and you can see it starts with a SafeMath library to help us prevent overflows and underflows and also tracks a token (ERC20 interface) that we set in the constructor (on deploy).
