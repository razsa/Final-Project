# TakeShare

**Step 1: Player 1 Begins game enters bet and odd or even choice**
- ```startGame("1", "0x1700000000000000000000000000000000000000000000000000000000000000") ```
**Step 2: Player 2 enters game and enters gamenumber, bet, odd or even choice**
- ```changeOwner("player 2 address") ```
- ```joinGame("1", "2", "0x2A00000000000000000000000000000000000000000000000000000000000000") ```
**Step 2.1: Player 2 reveals choice
- ```reveal("1", "0x2A00000000000000000000000000000000000000000000000000000000000000") ```
**Step 3: Player 1 enters game and reveals choice
- ```changeOwner("player 1 address")```
- ```reveal("1", "0x1700000000000000000000000000000000000000000000000000000000000000") ```
**Step 4: Claiming reward after results are computed
- ```claimRewardK("1")```


