## TakeShare

## Getting Started
cd Final-Project && cd migrations && touch 2_deploy_contracts.js\

paste ```var TakeShareContract = artifacts.require("./TakeShareContract.sol");                                      module.exports = function(deployer) {
         deployer.deploy(TakeShareContract);
    };``` into '2_deploy_contracts.js'\
    
truffle migrate\

truffle console

## How to Play
```startGame("1", "0x1700000000000000000000000000000000000000000000000000000000000000") // Player 1 Starts ```

```changeOwner("address") //Change to Player 2 account ```

```joinGame("1", "2", "0x2A00000000000000000000000000000000000000000000000000000000000000") // Player 2 Joins ```

```reveal("1", "0x2A00000000000000000000000000000000000000000000000000000000000000") // Player 2 Reveals choice ```

```changeOwner("player 1 address") // Change to Player 1 account ```

```reveal("1", "0x1700000000000000000000000000000000000000000000000000000000000000") // Player 1 Reveals choice ```

```claimRewardK("1") // Rewards claimed ```
