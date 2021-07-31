# Unit 21: You sure can attract a crowd!

We are going to crowdsale PupperCoin token in order fund the network development.

This network will be used to track the dog breeding activity across the globe in a decentralized way, and allow humans to track the genetic trail of their pets. 

We are only allowed to raise a maximum of 300 Ether. The crowdsale will run for 24 weeks.

We are crearting ERC20 token that will be minted through a Crowdsale contract that you can leverage from the OpenZeppelin Solidity library.

Fist create the PupperCoin.sol where we can import all libraries for ERC20
and use a standard ERC20Mintable and ERC20Detailed contract, hardcoding 18 as the decimals parameter, and leaving the initial_supply parameter alone.

![Deploy](/Images/PupperCoin.png)

Once is ready we have to go and compile the contract:


![Deploy](/Images/Compile_coin.png)

Because all looks good, we can go to Deploy and Run Transactions

Make sure you have connected your MetaMask wallet, with balance in your account, look the following image: 

![Deploy](/Images/Deploy_Coin.png) 

Before deploy we have to type name, symbol and initial supply

We type name "Beagle", symbol "BE"and amount 10000, then push transact button

![Deploy](/Images/transact_Coin.png)

No we are start creating the Crowsales.sol and we need to need to bootstrap the contract by inheriting the following OpenZeppelin contracts:

- Crowdsale
- MintedCrowdsale
- CappedCrowdsale
- TimedCrowdsale
- RefundablePostDeliveryCrowdsale

we will need the parameters for all of the features in our crowdsale, such as the `name`, `symbol`, `wallet` for fundraising, `goal`.

Now we are creating a new contract with Ropsten Network

Contract # 0xb2Cd47a7FECac2fa041FfEd55BC6f1F830DCb70d

![Deploy](/Images/newcontract.png)

Details of transaction via Etherscan portal

![Deploy](/Images/tx_details.png)

Buying Tokens

![Deploy](/Images/buying_tokens.png)

After deployed we can see the rate as 1000000000000000000 and the two adress for the token and the wallet

![Deploy](/Images/transact_rate.png)

We can start buying Tokens including the address beneficiary 

![Deploy](/Images/new_contract.png)

![Deploy](/Images/token_address.png)

![Deploy](/Images/crowdsale_contract_select.png)

Deploying the contract with Ropsten Testnet 
![Deploy](/Images/Contract_Ropsten.png)

Buy tocken via Ropsten Testnet


![Deploy](/Images/buyToken.png)

