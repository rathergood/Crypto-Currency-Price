# Crypto-Currency-Price
Function to get the price of a cryptocurrency into a google drive sheet. Uses the [coingecko api](https://www.coingecko.com/en/api).

The Function takes in the following parameters:  

The **cryptocurrency** that you want the price of  
The **currency** that you want the price of the cryptocurrency to be returned in (optional- If left blank, defaults to USD)  
The **24 hour change** of the cryptocurrency (optional)  

To use in google sheets:  

1. Open script editor (Under tools)  
2. File new "script file"- give it a name (doesn't matter what)  
3. Paste ccprice code and save  
4. In your sheet, type in =cc(cryptocurrency, currency, 24h_change)  

   example:  
   =cc("ethereum")  will return the current price of ethereum in USD  
   =cc("ethereum", "btc") will return the current price of etherum in BTC  
   =cc("ethereum", "btc", "24h_change") will return the 24 hour percentage change of ethereum in BTC  

   
For the list of supported currencies, see:  
https://api.coingecko.com/api/v3/simple/supported_vs_currencies  


If the cryptocurrency parameter isn't working, then find your cc on coingecko and use the name in the website address. For example:  

https://www.coingecko.com/en/coins/basic-attention-token  
so you would type in =cc("basic-attention-token")  


The function unfortunately does not automatically update. To update, close and reopen the sheet.  

Show some love:  
371XjQ6h5ZNFEPRrRnfdRUutpAuQGzEkZK (BTC)
0x32484F2628CB1D780e75E7b76Ecc05Fa14D88092 (ETH)  
LYAUXKTHjtK2iWEyVKPyQrbwLv9vT2vevs (LTC)

 
