---
description: >-
  Information and more details about buying and selling tokens directly on the
  DexGuru platform
cover: ../.gitbook/assets/Swapping Tokens.jpg
coverY: 0
---

# Swapping Tokens

## **How do swaps on DexGuru work? Did you build your own DEX?**

Although we haven't built our own DEX from scratch, we currently use 0x, 1inch, and Paraswap protocols to route all buy & sell (swap) orders on the DexGuru platform. All the above protocols are industry-leading liquidity aggregators and are used by many Web3.0 leaders that you may already be familiar with, such as MetaMask, DeFi Saver, Zapper & more.

{% hint style="success" %}
By integrating and using 0x, 1inch, and Paraswap protocols to route orders, we're able to offer DexGuru traders optimized token swaps that are fast, gas efficient, and have low slippage, meaning you'll get the best deal and rates on your swaps.
{% endhint %}

For more information about protocols, visit their official websites: [0x](https://www.0x.org/), [1inch](https://1inch.io/), and [Paraswap](https://www.paraswap.io/).&#x20;

For more information on how swaps are routed and which DEXs are being used, check out [#how-are-swaps-routed-which](swapping-tokens.md#how-are-swaps-routed-which "mention")

## **How do I know my swap orders conducted with my wallet are safe?**

As discussed above, when trading on DexGuru all your token approvals and orders interact with the 0x, 1inch, or Paraswap protocols through their proxy smart contracts. Check out the full list of smart contract addresses in the [wallets-security-and-more.md](wallets-security-and-more.md "mention")section.&#x20;

> _You can verify the smart contract address on the official documantations:_ [_0x_](https://docs.0x.org/introduction/0x-cheat-sheet)_,_[ _1inch_](https://docs.1inch.io/)_,_ [_Paraswap_](https://developers.paraswap.network/smart-contracts)_._&#x20;

When a swap is successfully completed through DexGuru, you should see this in your transaction list on your Block Explorer. It can be "0x: Exchange Proxy" or "1inch: Router" or something like "Paraswap v5: Augustus Swapper Mainnet".&#x20;

![Transaction List on EtherScan](<../.gitbook/assets/image (29) (1).png>)

Whilst inside the actual transaction details, you should see the full smart contract address you’ve interacted with, as below:\


![Transaction Details on EtherScan](<../.gitbook/assets/image (25) (1) (1).png>)

And as with navigating on Web3.0, you should always double & triple-check every contract interaction before confirming to ensure you know exactly how a contract is going to interact with your wallet _(Even on DexGuru!)_.

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
| Arbitrum                  | 1inch Aggregation Protocol                                                                                                                                                                                                                                   |
| Gnosis                    | 1inch Aggregation Protocol                                                                                                                                                                                                                                   |

## I **bought/sold** "X" Token but received less than the amount displayed

Under normal circumstances, due to slippage, it is possible to receive fewer tokens than expected. This will always be displayed to you on DexGuru before you confirm the transaction in your wallet.

However, **in the instances that you are receiving a noticeable amount less than displayed**, it is possible that the token you bought or sold has in **built transaction fees that have implemented to act as deflationary measures to reduce sell pressure**_._

There are many popular tokens such as SAFEMOON coin that have these in built transaction fees, where buying or selling the tokens result in receiving get a certain % less. Always DYOR and check the official website of the Token for more information regarding the exact Tokenomics you are trading.

## **Can I place limit orders and stop orders for token buys and sells?**

Due to the nature of DEXs & AMMs we currently do not support them as they're hard to reliably and consistently execute due to technical limitations.&#x20;

However, we are aware of new advancements from certain DEXs that have recently improved limit order capabilities and are keeping up to date to see if we can implement this functionality onto DexGuru in the near future!
