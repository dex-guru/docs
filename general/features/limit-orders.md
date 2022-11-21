---
description: A quick overview of limit orders on DexGuru
---

# Limit Orders

![](<../../.gitbook/assets/image (13) (2).png>)

{% hint style="info" %}
Even if the market price reaches your target price, there is no guarantee that your limit order will be filled.&#x20;
{% endhint %}

**What is a limit order?** \
A limit order has a target price and an expiration date. It is a request to buy or sell a token at a certain price that you can specify. When you place a limit order using DexGuru UI, it is sent to a centralized [1inch database](https://1inch.io/limit-order-protocol/). When you set a limit price and an expiration date, keep in mind that anyone can fetch your limit order using [1inch REST API endpoint ](https://docs.1inch.io/docs/limit-order-protocol/api/)to perform trade. &#x20;

**What kind of assets can I use when submitting a limit order? Why can’t I use native ETH for limit orders?** \
Only ERC-20 tokens are supported when you request a limit order on DexGuru. For the Ethereum network, this implies that you can use [WETH](https://weth.io/) but not ETH when submitting a limit order. Native ETH has to be wrapped before you can use it for limit orders. You can sell ETH for WETH on [DexGuru](https://dex.guru/token/0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2-eth). The same is true for Polygon network. You can't request limit orders using native MATIC, you have to use [WMATIC](https://polygonscan.com/token/0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270).&#x20;

**Why do I need to approve the token in my wallet before submitting my limit order?** \
Before submitting your limit order on DexGuru, you need to approve token spending from your wallet. This is done to protect your wallet from being accessed by any smart contract. This approval is an on-chain transaction, so you will have to pay gas fees. Only one approval is required per token, per wallet. However, since we use two different protocols for market orders vs. limit orders, you need to approve token sending for market and limit orders separately.

**What networks are supported?** \
Currently, you can request limit orders on Ethereum, BSC, Polygon, Optimism, Arbitrum, and Avalanche networks.

**Is there a gas fee for limit orders?** \
No, if your limit order gets filled or automatically expires, you do not pay gas fees. The taker of the order will have to consider gas fees, personal profit margin, and order size before completing your order. However, you pay gas fees when approving new token spending in your wallet or canceling a limit order before it expires.

**What does the percentage in the status column mean?** \
Limit orders can be partially filled. For example, a taker of your order might only fill 50% of your limit order before it expires.&#x20;

**Can I cancel my limit order?** \
Yes, you can manually cancel a limit order before it expires. However, it will require an on-chain transaction, and you will be charged a gas fee.

**Why did my order never get filled?** \
There are several reasons for this. The target price might not have been reached. Secondly, there might be no taker for your order because it is not profitable for them or simply because of a low trading volume. Thirdly, you have insufficient funds in your wallet.



DexGuru routes all limit orders through 1inch Limit Order Protocol.
