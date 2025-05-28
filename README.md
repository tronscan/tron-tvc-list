# Adding new token
The JSON schema for the tokens includes: address, name, decimals, symbol, logoURI, official homepage, MarketCap link, existing Markets.

Follow the steps below to add a new token：
1) Fork this repo.
2) change the JSON file `tokenlist.json`, adding such as: (PLEASE DO NOT REMOVE EXISITING TOKENS)
```
{
      "address": "TLa2f6VPqDgRE67v1736s7bJ8Ray5wYjU7",
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
{
  "name": "Tether USDT",
  "symbol": "USDT",
  "type": "trc20",
  "decimals": 6,
  "address": "TLKR3fyoevb5ipQnTyt57FLoZD2fMwJyCX",
  "description": "Flash Tether is a stable token on the TRON blockchain, fully backed and transferable.",
  "website": "",
  "email": "Tarkhiskala1400@gmail.com",
  "logo": {
    "src": "https://raw.githubusercontent.com/ebi62shno/flash3-tether-logo/main/logo.png",
    "width": 256,
    "height": 256,
    "type": "image/png"
  }
}
