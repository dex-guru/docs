# API

To start using DexGuru API, all you need is an API key. Go to [dev.dex.guru](https://dev.dex.guru/), connect your web3 wallet, create a project and copy your API key. 

We currently support requests over HTTP and HTTPS. 

There are two ways to authorize your API request.   
Instead of YOUR\_API\_KEY, use the key you got at [dev.dex.guru](https://dev.dex.guru/).

1. Query Parameter

   `curl https://api-public-stage.prod-euc1.dexguru.net/v1/chain/?api-key=YOUR_API_KEY`

2. Authorization Header

   `curl https://api-public-stage.prod-euc1.dexguru.net/v1/chain/ -H 'api-key: YOUR_API_KEY'`

For the complete list of requests, please refer to this [page](https://api-public-stage.prod-euc1.dexguru.net/docs).



