# Adding new token
The JSON schema for the tokens includes: address, name, decimals, symbol, logoURI, official homepage, MarketCap link, existing Markets.

Follow the steps below to add a new token：
1) Fork this repo.
2) change the JSON file `tokenlist.json`, adding such as: (PLEASE DO NOT REMOVE EXISITING TOKENS)
```
{
      "address": "TKKt9vhwV961ZR92FPF3MJ3xzWeBmt9qUX",
      "symbol": "USDT",
      "name": "USDT/TRX",
      "decimals": 6,
      "logoURI": "https://github.com/TRX-USDT-TRON/TRX20-TRON-/blob/main/5r8_zDRco8RuYLn6H-Blx1DsT46QMBPv9w.png",
      "homepage": "https://github.com/TRX-USDT-TRON/TRX20-TRON-",
      "MarketCapLink": "https://coinmarketcap.com/currencies/wink/",
      "existingMarkets": [
  {
    "source": "Binance",
    "pairs": [
      "USDT/WIN",
      "USDT/PEPE",
      "USDT/TRX",
      "USDT/BNB",
      "USDT/ETH",
      "USDT/BTC"
    ]
  },
  {
    "source": "KuCoin",
    "pairs": [
      "USDT/WIN",
      "USDT/PEPE",
      "USDT/TRX"
    ]
  },
  {
    "source": "Poloniex",
    "pairs": [
      "USDT/WIN",
      "USDT/TRX"
    ]
  },
  {
    "source": "OKX",
    "pairs": [
      "USDT/PEPE",
      "USDT/TRX",
      "USDT/ETH"
    ]
  },
  {
    "source": "Bybit",
    "pairs": [
      "USDT/PEPE",
      "USDT/BNB",
      "USDT/BTC"
    ]
  }
]

}
```
* `address`[Required]: your token address.
* `symbol`[Required]: your token symbol.
* `name`[Required]: your token name.
* `logoURI`[Required]: the logo URI of your token.
* `homepage`[Required]: the home page of your token.
* `MarketCapLink`[Optional]: the coinmarketcap or coingecko link for your token.
* `existingMarkets`[Required]: where to trade with your token.
3) Submit PR with the changed JSON file.


