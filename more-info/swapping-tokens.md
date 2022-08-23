---
description: >-
  Information and more details about buying and selling tokens directly on the
  DexGuru platform
cover: ../.gitbook/assets/Swapping Tokens.jpg
coverY: 0
---

# Swapping Tokens

## **How do swaps on DexGuru work? Did you build your own DEX?**

Although we haven't built our own DEX from scratch, we currently use 0x Protocol API and 1inch API to route all buy & sell (swap) orders on the DexGuru platform. Both 0x Protocol and 1inch protocol are industry-leading liquidity aggregators and are used by many Web3.0 leaders that you may already be familiar with, such as MetaMask, DeFi Saver, Zapper & more.

{% hint style="success" %}
By integrating and using 0x Protocol API and 1inch API to route orders, we're able to offer DexGuru traders optimized token swaps that are fast, gas efficient, and have low slippage, meaning you'll get the best deal and rates on your swaps.
{% endhint %}

For more information about 0x Protocol, visit their [official site](https://0x.org/) and check out their [performance analysis](https://blog.0xproject.com/a-comprehensive-analysis-on-dex-liquidity-aggregators-performance-dfb9654b0723) to see how they come out on top when compared with other DEX liquidity aggregators! Learn more about 1inch API [here](https://docs.1inch.io/docs/aggregation-protocol/introduction).&#x20;

For more information on how swaps are routed and which DEXs are being used, check out [#how-are-swaps-routed-which](swapping-tokens.md#how-are-swaps-routed-which "mention")

## **How do I know my swap orders conducted with my wallet are safe?**

As discussed above, when trading on DexGuru all your token approvals and orders are interacting with the 0x Protocol API through their **"0x: Exchange Proxy"** smart contract at: [_**0xdef1c0ded9bec7f1a1670819833240f027b25eff**_](https://etherscan.io/address/0xdef1c0ded9bec7f1a1670819833240f027b25eff)&#x20;

> _You can verify the smart contract address on the_ [_official 0x Protocol documentation_](https://0x.org/docs/guides/0x-cheat-sheet)_. This smart contract address is the same across all currently supported chains and you can view all the transactions that are interacting with this smart contract publicly on supported block explorers._

When a swap is successfully completed through DexGuru, you should see this in your transaction list on your Block Explorer:

![Transaction List on EtherScan](<../.gitbook/assets/image (29) (1).png>)

Whilst inside the actual transaction details, you should see the full smart contract address you’ve interacted with, as below:\


![Transaction Details on EtherScan](<../.gitbook/assets/image (25) (1) (1).png>)

And as with navigating on Web3.0, you should always double & triple-check every contract interaction before confirming to ensure you know exactly how a contract is going to interact with your wallet _(Even on DexGuru!)_.

{% hint style="success" %}
To date, DexGuru traders have done almost $800 Million USD equivalent in transaction volume with almost \~1 Million transactions completed directly on the DexGuru platform, and we've only just begun! :rocket:

__\
_For more analytics & statistics about token swaps being performed on DexGuru, feel free to view our publicly available_ [_dashboard here_](https://metabase.spaceship.0x.org/public/dashboard/e79bb86a-6777-4655-88fd-6453fdbefe0f?affiliate\_address=0x720c9244473dfc596547c1f7b6261c7112a3dad4)_._
{% endhint %}

## **How are my swaps routed? And which chains are supported for swaps?**&#x20;

All swaps besides the Arbitrum chain are routed through 0x Protocol's extensive liquidity network, which also includes the most popular DEXs and their liquidity pools as well. All Arbitrum orders are routed through [1inch aggregation protocol](https://docs.1inch.io/docs/aggregation-protocol/introduction). You may find that your swap may be routed across more than 1 DEX as both protocols optimize your order to be filled with the lowest slippage possible. :raised\_hands:

Below are the chains we currently support Token Swaps for, along with the network of DEXs/AMMs/Protocols your swap could routed and optimized through:

| Chain                     | Routed DEXs/AMMs & Protocols                                                                                                                                                                                                                                 |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Ethereum                  | 0x, Balancer, Balancer\_V2, Bancor, BancorV3, Component, CREAM, CryptoCom, Curve, Curve\_V2, DODO, DODO\_V2, KyberDMM, Lido, MakerPsm, Mooniswap, mStable, MultiHop, Saddle, Shell, ShibaSwap, SushiSwap, Synapse, Uniswap, Uniswap\_V2, Uniswap\_V3, xSigma |
| Polygon (Matic)           | Aave\_V2, ApeSwap, Balancer\_V2, ComethSwap, Curve, Curve\_V2, Dfyn, DODO, DODO\_V2, FirebirdOneSwap, IronSwap, KyberDMM, MeshSwap, mStable, MultiHop, QuickSwap, SushiSwap, Synapse, Uniswap\_V3, WaultSwap                                                 |
| Binance Smart Chain (BSC) | ACryptoS, ApeSwap, BakerySwap, Belt, BiSwap, CheeseSwap, DODO, DODO\_V2, Ellipsis, FirebirdOneSwap, KnightSwap, KyberDMM, MDex, Mooniswap, MultiHop, Nerve, PancakeSwap, PancakeSwap\_V2, Smoothy, SushiSwap, Synapse, WaultSwap                             |
| Avalanche                 | Aave\_V2, Curve, Curve\_V2, GMX, KyberDMM, MultiHop, Pangolin, Platypus, SushiSwap, Synapse, TraderJoe                                                                                                                                                       |
| Fantom                    | Beethovenx, Curve, Curve\_V2, Geist, MorpheusSwap, MultiHop, SpiritSwap, SpookySwap, SushiSwap, Synapse, Yoshi                                                                                                                                               |
| CELO                      | MobiusMoney, MultiHop, SushiSwap, UbeSwap                                                                                                                                                                                                                    |
| Optimism                  | Curve, Curve\_V2, MultiHop, Synapse, Uniswap\_V3, Velodrome                                                                                                                                                                                                  |

## I **bought/sold** "X" Token but received less than the amount displayed

Under normal circumstances, due to slippage, it is possible to receive fewer tokens than expected. This will always be displayed to you on DexGuru before you confirm the transaction in your wallet.

However, **in the instances that you are receiving a noticeable amount less than displayed**, it is possible that the token you bought or sold has in **built transaction fees that have implemented to act as deflationary measures to reduce sell pressure**_._

There are many popular tokens such as SAFEMOON coin that have these in built transaction fees, where buying or selling the tokens result in receiving get a certain % less. Always DYOR and check the official website of the Token for more information regarding the exact Tokenomics you are trading.

## **Can I place limit orders and stop orders for token buys and sells?**

Due to the nature of DEXs & AMMs we currently do not support them as they're hard to reliably and consistently execute due to technical limitations.&#x20;

However, we are aware of new advancements from certain DEXs that have recently improved limit order capabilities and are keeping up to date to see if we can implement this functionality onto DexGuru in the near future!
