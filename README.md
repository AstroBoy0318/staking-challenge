# staking-challenge
Deploy contracts using Remix.
1. Deploy RewardToken contract(parm is initial suppply, the deployer will get that amount of token.).
2. Deploy Staking contarct.(params are address of rewardtoken and startblock)
3. Transfer ownership of rewardToken to the masterchef.
4. To deposit, call the function approve with parameter of staking address as "spender" and "0xfffffffffffffffffffffffffffff" as amount.(you can do it on explorer).
5. Call deposit function of staking contract with parameter of amount as you want.
6. You can call withdraw or deposit to claim the rewards.
* The emission rate is one. It means one reward token will be mint per block.

I've test it on ropsten.
RewardToken
https://ropsten.etherscan.io/address/0xE94336775cFE757d1A7868E9ef6B03a6437c302F
Staking
https://ropsten.etherscan.io/address/0x4Dc12aA3964a370A0FceD0fd1DE9404073F5052F
