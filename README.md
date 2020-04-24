## TakeShare

## How to Play
1. Player 1
```startGame("1", "0x1700000000000000000000000000000000000000000000000000000000000000") ```
2. Player 2
```changeOwner("player 2 address") ```
```joinGame("1", "2", "0x2A00000000000000000000000000000000000000000000000000000000000000") ```
3. Player 2 reveals their choice
```reveal("1", "0x2A00000000000000000000000000000000000000000000000000000000000000") ```
4. Player 1 reveals their choice
```changeOwner("player 1 address")```
```reveal("1", "0x1700000000000000000000000000000000000000000000000000000000000000") ```
5. Claiming reward after results are computed
```claimRewardK("1")```