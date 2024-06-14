# Uniswap V3 Market Maker Trading Bot

Blog Post:
https://jamesbachini.com/uniswap-market-maker-bot/


The Uniswap market maker trading bot works by automatically buying and selling tokens in a liquidity pool in order to maintain a target price. The bot is programmed to buy tokens when the price falls below the target price, and to sell tokens when the price rises above the target price. This helps to keep the price of the tokens in the pool stable and balances liquidity on either side of the pool.

The bot is programmed to use a fixed target price, but it can also be adapted to use a dynamic target price. A dynamic target price can be based on a linear price path or something like a simple moving average of past prices.

The bot can be used to trade Speed/Weth on Base.

The following are the steps on how to set up the Uniswap market maker trading bot:

- Clone the repository from GitHub.
- Install the necessary libraries with the Node package manager (npm). `npm install`
- update .env samlple file and add your private key and Alchemy API key. Save filename as `.env`
- Edit the mm.js file to specify the target price.
- Run `node mm.js`

The bot will start trading $Speed and will automatically buy and sell tokens in order to maintain the target price.

Note the code is for demonstration purposes only and is not battle tested in a production environment.
