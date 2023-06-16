# Adding new token
The JSON schema for the tokens includes: address, name, decimals, symbol, logoURI, official homepage, MarketCap link, existing Markets.

Follow the steps below to add a new token：
1) Fork this repo.
2) change the JSON file `tokenlist.json`, adding such as: (PLEASE DO NOT REMOVE EXISITING TOKENS)
```
{
      "address": "TUhpeUhusNJayQJCYeqiF1NZs7beFLzVdd",
      "symbol": "899uk.com ",
      "name": "899uk ",
      "decimals": 6,
      "logoURI": "https://static.tronscan.org/production/upload/logo/new/TUhpeUhusNJayQJCYeqiF1NZs7beFLzVdd.png?t=1685608064453",
      "homepage": "https://tronscan.org/#/token20/TUhpeUhusNJayQJCYeqiF1NZs7beFLzVdd",
      "existingMarkets": [
          {
              "source": "TRON",
              "pairs": [
                  "899uk.com/USDT",
                  "899uk.com/BUSD",
                  "899uk.com/BNB",
                  "899uk.com/USDC"
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


