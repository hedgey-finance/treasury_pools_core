# Hedgey Treasury Pool Contracts

This repository contains the contracts and audits for the HedgeyPools contracts deployed across various EVM networks. 
The HedgeyCalls and HedgeyPuts contracts are the primary pair contracts that create an options market (either calls or puts) for a specific pair. 
A pair is defined as an asset currency and a payment currency. Any asset & payment currency pair is possible. 
The Hedgey Celo Calls / Puts are specific to Celo network, removing the WETH constraints and adding in a method to handle "mTokens" for interest accruals. 

The Factorys are deployed at the below addresses, each with a specific constant AMM factory and WETH address. 
Each time a new pair is created, it is done so via the factory, which deploys a new individual pair (either calls or puts). 



# Active deployments:

**Rinkeby TestNet**
Calls Factory Address: 0xe4231602128EDF7CD100F62c1D70CB246811e170      
WETH Address: 0xc778417E063141139Fce010982780140Aa0cD5Ab              
UniswapV2 Factory: 0x5C69bEe701ef814a2B6a3EDD4B1652CB9cc5aA6f


**xDAI (Gnosis) Network**

Calls Factory Address: 0x24f4BC74C00412422C9D2A7c78033fc8Aea8Da18        
WETH Address (wxDAI): 0xe91D153E0b41518A2Ce8Dd3D7944Fa863463a97d      
HoneySwap AMM Address: 0xA818b4F111Ccac7AA31D0BCc0806d64F2E0737D7
