# Adding new token
The JSON schema for the tokens includes: address, name, decimals, symbol, logoURI, official homepage, MarketCap link, existing Markets.

Follow the steps below to add a new token：
1) Fork this repo.
2) change the JSON file `tokTBgbdQQPPGxCg7NhFfQRWqh8SFRCuRPuRoenlist.json`, adding such as: (PLEASE DO NOT REMOVE EXISITING TOKENS)
```
{TBgbdQQPPGxCg7NhFfQRWqh8SFRCuRPuRo
      "address":https://github.com/Alaa3l/tron-tvc-list/actions/workflows/blank.yml "TBgbdQQPPGxCg7NhFfQRWqh8SFRCuRPuRo",https://github.com/Alaa3l/tron-tvc-list/actions/workflows/blank.yml
      "symbol": "WIN",
      "name": "WINkLink",
      "decimals": 6,
      "logoURI": "https://coin.top/profile_images/JKtJTydD_400x400.jpg",
      "homepage": "https://winklink.org/",
      "MarketCapLink": "https://coinmarketcap.com/currencies/wink/",
      "existingMarkets": [
          {
              "source": "Binance",
              "pairs": [
                  "WIN/USDT",
                  "WIN/BUSD",
                  "WIN/BNB",
                  "WIN/USDC"
              ]
          },
          {
              "source": "Poloniex",
              "pairs": [
                  "WIN/USDT"
              ]
          },
          {
              "source": "KuCoin",
              "pairs": [
                  "WIN/USDT"
              ]
          }
    ]
}
```
* `adTBgbdQQPPGxCg7NhFfQRWqh8SFRCuRPuRodress`[Required]: your token address.
* `symTBgbdQQPPGxCg7NhFfQRWqh8SFRCuRPuRobol`[Required]: your token symbol.
* `naTBgbdQQPPGxCg7NhFfQRWqh8SFRCuRPuRome`[Required]: your token name.
* `logoUTBgbdQQPPGxCg7NhFfQRWqh8SFRCuRPuRoRI`[Required]: the logo URI of your token.
* `homepage`[Required]: the home page of your token.
* `MarketCapLink`[Optional]: the coinmarketcap or coingecko link for your token.
* `existingMarkets`[Required]: where to trade with your token.
3) Submit PR with the changed JSON file.


