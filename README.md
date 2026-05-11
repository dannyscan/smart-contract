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
The DAN20 contract includes the following main functions.

##Public / External Functions
Function	Description
name()	Returns the token name<br>
symbol()	Returns the token symbol<br>
decimals()	Returns the token decimals<br>
totalSupply()	Returns total token supply<br>
balanceOf(address)	Returns wallet token balance<br>
transfer(address,uint256)	Transfers tokens<br>
approve(address,uint256)	Approves allowance<br>
allowance(address,address)	Returns allowance amount<br>
transferFrom(address,address,uint256)	Transfers using allowance<br>
owner()	Returns contract owner<br>
transferOwnership(address)	Transfers ownership<br>
renounceOwnership()	Renounces ownership<br>
burn(uint256)	Burns own tokens<br>
burnFrom(address,uint256)	Burns tokens using allowance<br>
rescueBalance(address)	Withdraws native coin<br>
rescueToken(address,address)	Withdraws tokens stuck in contract<br>

##Internal Functions
Function	Purpose
_transfer()	Handles transfers<br>
_update()	Updates balances<br>
_mint()	Creates tokens<br>
_burn()	Burns tokens<br>
_approve()	Sets allowance<br>
_spendAllowance()	Reduces allowance<br>
Functions NOT Included<br>

# This contract does NOT include:

❌ Mint after deployment<br>
❌ Pause<br>
❌ Blacklist<br>
❌ Tax system<br>
❌ Anti-bot<br>
❌ Max wallet<br>
❌ Max transaction<br>
❌ Upgradeability<br>

# Token Supply

Initial supply minted during deployment:
100000000×10
18
= 100 million tokens with 18 decimals.
