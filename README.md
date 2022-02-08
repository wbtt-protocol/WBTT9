# WBTT9

This is the wBTT contract of BTTC blockchain. The contract code is forked from wETH9. [MainNet deployment](https://bttcscan.com/address/0x23181f21dea5936e24163ffaba4ea3b316b57f3c#contracts) of commit (618ea8b) 


# Total Supply
The supply of WETH10 is capped at btt.totalSupply, which is [932,497,500,000,000 BTT](https://tronscan.org/#/token20/TAFjULxiVgT4qWk6UZwjqwZXTSaGaqnVp4) 


# Usage

Send BTT to this contract or call ```deposit()``` of this contract to receive equal amount of Wrapped BTT (WBTT), which implements the BRC20 standard. WBTT is interchangeable with BTT in a 1:1 basis.

```withdraw(uint)``` BTT from this contract by unwrapping WBTT from your wallet.  WBTT will be burned, an equal amount of BTT will be sent to your address.

Other functions are based on BRC20 protocol, such as ```totalSupply()```, ```approve(address, uint)```,```transfer(address, uint)```, and ```transferFrom(address, address, uint)```.

# More details

[Our website: wbtt.io](https://wbtt.io/)

[Our token: 0x23181f21dea5936e24163ffaba4ea3b316b57f3c](https://bttcscan.com/address/0x23181f21dea5936e24163ffaba4ea3b316b57f3c#contracts)



