## Consentest Token(CTT)

### OVERVIEW
CTT is a simple ERC20 based token which can be used for various purposes.
Deployed to BSC and Ethereum.
It is having a cross-chain feature so can be transferred bsc->eth and eth->bsc.
Having timelock and taxification feature.

### WHAT DOES CTT DO?

1. Can be transferred in BSC and ethereum.
2. Can be transferred from BSC to ethereum and vice-versa.
3. Can be swaped with eth or bbn in PCS and UNISWAP
4. Can incentivize token holders by taking taxes from transactions.(transactions from PCS or Uniswap)
5. Can be timelocked from UNISWAP or PCS.

### Project directory structure
The project contains 3 main directories.
 * token-contract : This is the main project for token contracts. Developed by using hardhat.
   - contracts : Having smart contracts.(token contracts, bridge contracts, and interfaces)
   - test : Unit tests
   - deployment : scripts to deploy token/bridge contracts into bsc and ethereum networks
 * backend : Backend code having the logic should be executed with admin address. Having 4 endpoints.
   - bridge/bsctoeth : The endpoint to be used to send CTT from BSC to ETH
   - bridge/ethtobsc : The endpoint to be used to send CTT from ETH to BSC
   - bridge/getfreecreditfrometh : Can get 10000 CTT in the ethereum
   - bridge/getfreecreditfrombsc : Can get 10000 CTT in the BSC  * frontend : Frontend code.   

### Smart Contract Addresses
 * BSC CTT Contract Address : 0x96CAC1fE6132eEF92BD979D2dEA2650D9cE899E2
 * ethereum CTT Contract Address : 0x05E5451Cd9c042980CEbe3897743A9948E61e2BF
 
### Public address for certification
0xFe169E439506Cfc7edBca083A0785ee1FE52B9F4
