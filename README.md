[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

# Instant Cryptocurrency Exchange API

[![Join the Gitchat at https://gitter.im/TokenIndustrialAverage/Lobby](https://badges.gitter.im/TokenIndustrialAverage/Lobby.svg)](https://gitter.im/TokenIndustrialAverage/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This document is intended to assist software developers who want to develop applications using Doecoins.com API. It fully documents our application programming interface (API) that allows developers to interact with our system.

## To use the information provided here, you should also be familiar with:

* RESTful web services
* HTTP/1.1
* JSON (JavaScript Object Notation)

Our Application Program Interface will allow you to automate the process of making exchanges, receiving, fetching history of exchanges and transactions within your own software without the need of an special API keys or accounts.

The API is based on REST principles, it's very easy to write and test applications. You can use your browser to access URLs, and you can use pretty much any HTTP client in any programming language to interact with the API.

All responses from Doecoins's API are in JSON format.

Doecoins API supports CORS (Cross-origin Resource sharing) to allow access directly from a browser or client side only application.


## Getting Started: How to Check Exchange Transaction Status for Doecoins.com

### Tx Status
* `new`: We haven't received a payment yet.
* `processing`: Your exchange is in our processing queue.
* `processed`: Your exchange has been successfully processed.
* `denied`: Your exchange has been denied and refunded to your payer account/address.

[https://api.iblockchainbank.eu/exchange/exchangeID/ `<exchangeID>` /]          

**you can add '/' or dismiss it**


> EXAMPLE --> [https://api.iblockchainbank.eu/exchange/exchangeID/780a4728-8ac7-4b46-909f-53c7839c9679/]

--------------------------------------------------------------------------------------------------------------------------------------

### How to Check Exchange Rate for Doecoins.com

[https://api.iblockchainbank.eu/rates/send/ `<coin_id>` /receive/ `<coin_id>` /]

> EXAMPLE -- [https://api.iblockchainbank.eu/rates/send/litecoin_LTC/receive/bitcoin_BTC/]

--------------------------------------------------------------------------------------------------------------------------------------

### How to Check Exchange Limits per Transaction for Doecoins.com

[https://api.iblockchainbank.eu/limits/send/ `<coin_id>` /receive/ `<coin_id>` /]

> EXAMPLE -- [https://api.iblockchainbank.eu/limits/send/litecoin_LTC/receive/bitcoin_BTC/]

--------------------------------------------------------------------------------------------------------------------------------------

### Dogecoin's Exchange Coin Pairs 

Example:
> /send/ => `<coin_id>` = `bitcoin_BTC`  /receive/ => `<coin_id>` = `ethereum_ETH`

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

If you're not already familiar our API, you should spend few minutes and go over the excellent details on
- **[How to Perform an Instant Exchange](https://github.com/Doecoins/InstantExchangeAPI/wiki/How-to-Perform-an-Instant-Exchange)**
