---
description: DexGuru Public API
---

# API

To start using DexGuru API, all you need is an API key.  Go to [developers.dex.guru](https://developers.dex.guru), connect your web3 wallet, create a project and copy your API key. This API key is all you need to start receiving reliable on-chain trading data on:

* Ethereum
* BSC
* Polygon
* Avalanche
* Fantom
* Arbitrum
* CELO

Examples of data we provide:

* Token Current Price
* Recent On-Chain Transactions
* Mints and Burns, a.k.a Liquidity Pool Adds and Removes
* Wallet Activity

Full API docs is [here](https://api.dev.dex.guru/docs). We also provide convenient SDKs for [Node](https://www.npmjs.com/package/dexguru-sdk) and [Python](https://pypi.org/project/dexguru-sdk/) developers:

_`npm install dexguru-sdk`_

_`pip install dexguru-sdk`_

While we are in Beta, API is free for personal use. After we are out of Beta, we’ll have a free tier and paid tiers based on API calls usage. Paid tier would require you to stake a certain amount of our upcoming token to get access to real-time data.

### Authorization&#x20;

We currently support requests over HTTP and HTTPS.&#x20;

There are two ways to authorize your API request. Instead of YOUR\_API\_KEY, use the key you got at developers.dex.guru.

Query Parameter

ex:

`curl https://api.dev.dex.guru/v1/chain/?api-key=YOUR_API_KEY`

Authorization Header

ex:

`curl https://api.dev.dex.guru/v1/chain/ -H 'api-key: YOUR_API_KEY'`

For the complete list of requests, please [refer to this page](https://api.dev.dex.guru/docs).&#x20;
