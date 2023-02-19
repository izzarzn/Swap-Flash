
# Flash Swap Arbitrage Bot
Smart Contract BOT code, running on Ethereum Blockchain, watching for and executing profitable arbitrage opportunities using flash loans and flash swaps. 

Flash loans are an innovative financial product made possible by the atomic nature of transactions on the Ethereum blockchain. They allow users to borrow large amounts of cryptocurrency from liquidity pools without collateral if the loan is repaid in the same transaction. They are like leverage trades and margin accounts in traditional finance, but without the need to be approved and provide collateral.  
 
Decentralized Exchanges (DEXes) like Uniswap and Sushiswap are cryptocurrency exchanges that use smart contracts to enforce the trading rules, execute trades, and securely handle funds when necessary. They allow us to exchange different cryptocurrencies and stable coins quickly. They may be used as part of flash loan strategies to acquire the needed assets.

Arbitrage is arguably the primary use case for flash loans, which means buying cryptocurrency (or an asset) for a price and selling it for a higher price on a different exchange.

The main challenge with arbitrage is that by the time you sell an asset, its price might have changed, but you don’t have that problem with flash loans. Additionally, you don’t have to have the crypto asset; you can borrow it. Therefore, the earning coming from the price difference (spread) will be proportional to the amount traded.


# How it works
Alfred monitors DEXs for opportunities, and when he finds it, he borrows capital to conclude the arbitrage transaction.

## Decentralized Exchanges
The most popular DEX architectures use the concept of liquidity pools rather than orderbooks and are called Automated Market Makers.

Other DEXes, in particular those using the 0x protocol use a classic orderbook and rely on makers and takers for determining an asset’s price;

## Flash Loan
Flash Alfred can take advantage of flash loans in order to do arbitrage trading using only borrowed funds!

Not only you are not at risk of losing all of your capital if prices are very volatile, but also because as mentioned before, the money isn’t even yours; 

“Flash Loans are special uncollateralised loans that allow the borrowing of an asset, as long as the borrowed amount (and a fee) is returned before the end of the transaction. There is no real-world analogy to Flash Loans”.

## Arbitrage on DeFi
Arbitrage is the purchase and sale of an asset in order to profit from a difference in the asset’s price between marketplaces. 

There is no risk of losing money should a sequence of trades not execute as expected; the transactions will be reverted due to lack of funds, because the smart contract isn’t able to repay a flash loan or before others do.

It does not require any kind of prediction algorithm or stop-loss strategy, but rather it deals with finding profitable opportunities in the present moment before they disappear .


# Features
- Smart contract written in solidity code published in the Ethereum blockchain main network;
- Connected with UniSwap and SushiSwap, two of the principal decentralized exchanges in DeFi;
- API connected with AAVE loan network;



