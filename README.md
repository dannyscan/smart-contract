## DAN Basic Smart Contract
Public / External Functions
Function	Description
name()	Returns the token name
symbol()	Returns the token symbol
decimals()	Returns token decimals
totalSupply()	Returns total token supply
balanceOf(address)	Returns wallet balance
transfer(address,uint256)	Transfers tokens
allowance(address,address)	Checks allowance
approve(address,uint256)	Approves token allowance
transferFrom(address,address,uint256)	Transfers tokens using allowance
owner()	Returns contract owner
transferOwnership(address)	Transfers ownership
renounceOwnership()	Renounces ownership
rescueBalance(address)	Withdraws native coins from contract
rescueToken(address,address)	Withdraws ERC20 tokens sent to contract

# Internal Functions
Function	Description
_transfer()	Internal transfer logic
_update()	Updates balances and supply
_mint()	Mints tokens
_approve()	Sets allowance
_spendAllowance()	Spends allowance

# Functions Not Included

❌ No additional mint function after deployment
❌ No burn function
❌ No pause function
❌ No blacklist system
❌ No tax mechanism
❌ No hidden backdoor
❌ No wallet freeze function

# Contract Features

✅ Fixed Supply
✅ Ownership System
✅ ERC20 Standard
✅ Rescue Native Coin
✅ Rescue ERC20 Tokens
✅ Compatible with DEXs, Wallets, and Explorers

Initial Supply
100,000,000 Tokens
Minted once during deployment only.

## DAN Burn Contract
