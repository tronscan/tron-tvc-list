# Adding new token
The JSON schema for the tokens includes: address, name, decimals, symbol, logoURI, official homepage, MarketCap link, existing Markets.

Follow the steps below to add a new token：
1) Fork this repo.
2) change the JSON file `tokenlist.json`, adding such as: (PLEASE DO NOT REMOVE EXISITING TOKENS)
```
{
      "address": "TJjwnzrBQFtjyumQr5mwRSRsp9hTHUfzLs",
      "symbol": "RGA",
      "name": "RGAToken",
      "decimals": 9,
      "logoURI": "https://ibb.co/m6rSwMF",
      "homepage": "https://gotechims.wixsite.com/rgatoken",
      "MarketCapLink": " ",
      "existingMarkets": [
          {
              "source": "SunSwap",
              "pairs": [
                  "RGA/TRX",
                   
              ]
           
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


