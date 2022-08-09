---
description: A quick overview of limit orders on DexGuru
---

# Limit Orders

**What is a limit order?** \
A limit order has a target price and an expiration date. It is a request to buy or sell a token at a ceratin price that you can specify. A limit order is not filled unless the price reaches your target price during the specified time.

**What kind of assets can I use when submitting a limit order? Why can’t I use native ETH for limit orders?** \
Only ERC-20 tokens are supported when you request a limit order on DexGuru. For the Ethereum network, this implies that you can use WETH but not ETH when submitting a limit order. Native ETH has to be wrapped before you can use it for limit orders.

**Why do I need to approve the token in my wallet before submitting my limit order?** \
Before submitting your limit order on DexGuru, you need to approve token spending from your wallet. This is done to protect your wallet from being accessed by any smart contract. This approval is an on-chain transaction, so you will have to pay gas fees. Only one approval is required per token, per wallet. However, since we use two different protocols for market orders vs. limit orders, you need to approve token sending for market and limit orders separately.

**What networks are supported?** \
Currently, you can request limit orders on Ethereum, BSC, Polygon, Optimism, Arbitrum, and Avalanche networks.

**Is there a gas fee for limit orders?** \
No, if your limit order gets filled, you do not pay for gas. The taker of the order will have to consider and pay gas fees. However, you pay gas fees when approving new token spending in your wallet or canceling a limit order before it expires.

**Can I cancel my limit order?** \
Yes, you can manually cancel a limit order before it expires. However, it will require an on-chain transaction, and you will be charged a gas fee.

**Why did my order never get filled?** \
There are several reasons for this. The target price might not have been reached. Secondly, there might be no taker for your order because it is not profitable for them or simply because of a low trading volume. Thirdly, you have insufficient funds in your wallet.



DexGuru routes all limit orders through 1inch Limit Order Protocol.
