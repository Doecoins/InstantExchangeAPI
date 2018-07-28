# InstantExchangeAPI
Instant Cryptocurrency Exchange API

## How to Check Exchange Transaction Status for Doecoins.com

### Tx Status
* `new`: We haven't received a payment yet.
* `processing`: Your exchange is in our processing queue.
* `processed`: Your exchange has been successfully processed.
* `denied`: Your exchange has been denied and refunded to your payer account/address.

[https://api.iblockchainbank.eu/exchange/exchangeID/ `<exchangeID>` /]          

**you can add '/' or dismiss it**


EXAMPLE --> [https://api.iblockchainbank.eu/exchange/exchangeID/780a4728-8ac7-4b46-909f-53c7839c9679/]



### How to Check Exchange Rate for Doecoins.com

[https://api.iblockchainbank.eu/rates/send/ `<coin_id>` /receive/ `<coin_id>` /]

-->EXAMPLE -- [https://api.iblockchainbank.eu/rates/send/litecoin_LTC/receive/bitcoin_BTC/]

--------------------------------------------------------------------------------------------------------------------------------------

### How to Check Exchange Limits per Transaction for Doecoins.com

[https://api.iblockchainbank.eu/limits/send/ `<coin_id>` /receive/ `<coin_id>` /]

-->EXAMPLE -- [https://api.iblockchainbank.eu/limits/send/litecoin_LTC/receive/bitcoin_BTC/]

### Dogecoin's Exchange Coin Pairs 

Example:
            Send => `<coin_id>` = `bitcoin_BTC`
            Receive => `<coin_id>` = `ethereum_ETH`

* `pm_USD`
* `pmvoucher_USD`
* `payeer_USD`
* `advcash_USD`
* `bitcoin_BTC`
* `ethereum_ETH`
* `bitcoincash_BCH`
* `dogecoin_DOGE`
* `dash_DASH`
* `monero_XMR`
* `zcash_ZEC`
* `litecoin_LTC`
* `ethereumclassic_ETC`
* `augur_REP`
* `golem_GNT`
* `gnosis_GNO`
* `liskLSK`
* `peercoin_PPC`
