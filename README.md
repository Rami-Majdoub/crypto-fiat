installation

	npm install -g crypto-fiat

token symbol (above the price)

[![token symbol postion](https://user-images.githubusercontent.com/37843591/185834401-7730e94b-a158-44fb-8053-c57e93844f59.png)](https://coinmarketcap.com/currencies/bitcoin/)

get 1 token price in usd

	crypto-fiat --tokens="ETH" --apikey="key here"
	# 1 ETH        = 1602.59773918858 USD

get multiple token prices in usd

	crypto-fiat --tokens="ETH, MATIC, BAT, BCT" --apikey="key here"
	# 1 ETH        = 1602.59773918858 USD
	# 1 MATIC      = 0.8104231677387381 USD
	# 1 BCT        = 1.8929650368687083 USD
	# 1 BAT        = 0.3658860492317096 USD

1 BTC = ? ETH

	crypto-fiat --tokens="BTC:ETH" --apikey="key here"
	# 1 BTC        = 13.386323076847496 ETH

1 ETH = ? TND

	crypto-fiat --tokens="ETH:TND" --apikey="key here"
	# 1 ETH        = 5074.115124903678 TND

[List of fiat currencies](https://coinmarketcap.com/api/documentation/v1/#section/Standards-and-Conventions)
