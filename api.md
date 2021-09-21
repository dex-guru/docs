# API

To start using DexGuru API, all you need is an API key. Go to [developers.dex.guru](https://developers.dex.guru/), connect your web3 wallet, create a project and copy your API key. 

We currently support requests over HTTP and HTTPS. 

There are two ways to authorize your API request. Instead of YOUR\_API\_KEY, use the key you got at developers.dex.guru.

Query Parameter

ex:

`curl https://api.dev.dex.guru/v1/chain/?api-key=YOUR_API_KEY`

Authorization Header

ex:

`curl https://api.dev.dex.guru/v1/chain/ -H 'api-key: YOUR_API_KEY'`

For the complete list of requests, please [refer to this page](https://api.dev.dex.guru/docs). 

