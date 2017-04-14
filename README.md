# Crypto-Currency-Price
Function to get price of a cryptocurrency into a google drive sheet. Uses coinmarketcap api

To use in google sheets:

1. Open script editor (Under tools)
2. File new "script file", give it a name
3. Copy Code and Save
4. In your sheet, type in =ccprice(cryptocurrency, usd)
   example: 
   =ccprice("ethereum", "usd")
   
   you can also type "btc" instead of usd if you want to return the price in bitcoin

also very easy to get any of the following by making  minor edits to the code:

id
name
symbol 
rank
price_btc 
24h_volume_usd
market_cap_usd
available_supply
total_supply
percent_change_1h
percent_change_24h 
percent_change_7d
last_updated
    
 simply add in another if statement before the line that states "return price"
 example:
 
   if (currency == "24h_volume_usd") {  
      var price = data[0].24h_volume_usd;
      } 
 
