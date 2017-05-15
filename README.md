# Crypto-Currency-Price
Function to get price of a cryptocurrency into a google drive sheet. Uses the [coinmarketcap api](https://coinmarketcap.com/api/)

To use in google sheets:

1. Open script editor (Under tools)
2. File new "script file", give it a name
3. Copy Code and Save
4. In your sheet, type in =ccprice(cryptocurrency, currency)
   example:   
   =ccprice("ethereum", "USD")  

   
The currency parameter accepts the following currencies:  
"BTC", "USD", "AUD", "BRL", "CAD", "CHF", "CNY", "EUR", "GBP", "HKD", "IDR", "INR", "JPY", "KRW", "MXN", "RUB"

__\*\*\*the currency parameter needs to be uppercase\*\*\*__  
=ccprice("ethereum", "USD") will work  
=ccprice("ethereum", "usd") will not!  
   

also very easy to get any of the following by making  minor edits to the code:

id  
name  
symbol  
rank  
24h_volume_usd  
market_cap_usd  
available_supply  
total_supply  
percent_change_1h  
percent_change_24h  
percent_change_7d  
last_updated  
24h_volume_eur (or w/e your currency is)  
market_cap_eur (or w/e your currency is)

Show some love:  
1N1iZfDJLYjCDNQMNaJosWyeJBAqJF91ub

 
