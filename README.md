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
Function	Description<br>
_transfer()	Internal transfer logic<br>
_update()	Updates balances and supply<br>
_mint()	Mints tokens<br>
_approve()	Sets allowance<br>
_spendAllowance()	Spends allowance<br>

# Functions Not Included

❌ No additional mint function after deployment<br>
❌ No burn function<br>
❌ No pause function<br>
❌ No blacklist system<br>
❌ No tax mechanism<br>
❌ No hidden backdoor<br>
❌ No wallet freeze function<br>

# Contract Features

✅ Fixed Supply<br>
✅ Ownership System<br>
✅ ERC20 Standard<br>
✅ Rescue Native Coin<br>
✅ Rescue ERC20 Tokens<br>
✅ Compatible with DEXs, Wallets, and Explorers<br>

Initial Supply
100,000,000 Tokens
Minted once during deployment only.

## DAN Burn Contract
