# InstantExchangeAPI
Instant Cryptocurrency Exchange API

## How to Check Exchange Transaction Status for Doecoins.com

### Tx Status
* `new`: We haven't received a payment yet.
* `processing`: Your exchange is in our processing queue.
* `processed`: Your exchange has been successfully processed.
* `denied`: Your exchange has been denied and refunded to your payer account/address.

[https://api.iblockchainbank.eu/exchange/exchangeID/*exchangeID*/]          

**you can add '/' or dismiss it**


EXAMPLE --> [https://api.iblockchainbank.eu/exchange/exchangeID/780a4728-8ac7-4b46-909f-53c7839c9679/]



### How to Check Exchange Rate for Doecoins.com

[https://api.iblockchainbank.eu/rates/send/*<coin_id>*/receive/*<coin_id>*/]

-->EXAMPLE -- [https://api.iblockchainbank.eu/rates/send/litecoin_LTC/receive/bitcoin_BTC/]

--------------------------------------------------------------------------------------------------------------------------------------

### How to Check Exchange Limits per Transaction for Doecoins.com

[https://api.iblockchainbank.eu/limits/send/*<coin_id>*/receive/*<coin_id>*/]

-->EXAMPLE -- [https://api.iblockchainbank.eu/limits/send/litecoin_LTC/receive/bitcoin_BTC/]

### Dogecoin's Exchange Coin Pairs **<coin_id>**

* pm_USD
* pmvoucher_USD
* payeer_USD
* advcash_USD
* ![bitcoin_BTC] (data:image/png;base64,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)
* ethereum_ETH
* bitcoincash_BCH
* dogecoin_DOGE
* dash_DASH
* monero_XMR
* zcash_ZEC
* litecoin_LTC
* ethereumclassic_ETC
* augur_REP
* golem_GNT
* gnosis_GNO
* liskLSK
* peercoin_PPC
