---
description: Guidance on how to deal and solve common errors.
cover: ../.gitbook/assets/Troubleshooting Errors.jpg
coverY: 0
---

# Troubleshooting Errors

## "**0x API Estimation Error" when attempting to swap**&#x20;

![0x API Estimation Error when attempting to swap](<../.gitbook/assets/image (28) (1) (1).png>)

### General Cases

If you are trading a normal token and receiving this error, **it's possible that liquidity in the pool is not high enough and your allowed slippage % is too low. We recommend you increase your slippage to 2-5% and attempt to swap again**. Keep in mind, the higher your slippage is, the less tokens you will receive, so increase your slippage wisely and always review the estimated receiving amount.

If you are still receiving this error after increasing your slippage to 2-5%, you may be attempting to trade a token that has in-built transaction fees - _refer to the next section for more details_.

If the token you are swapping does not have in-built transaction fees, then in the unlikely scenario where it is still not working after increasing your slippage, we recommend swapping directly on a leading DEX with high liquidity for the token that you attempting to swap for.

### Trading Tokens with in-built Transaction Fees

For Tokens that have in-built transaction fees into the Token contract which take a % of the amount you are trying to buy or sell, this is a common error you may face.&#x20;

One way to get around this is **to increase your slippage 2-5% above the in-built transaction fee %**. For example, if the Token you are attempting to swap has an in-built transaction fee of 10%, then try increasing your slippage to 12-15%.&#x20;

If you are still receiving this error after increasing your slippage, we recommend you swap directly on leading DEX with high liquidity for the token that you attempting to swap for as the 0x Protocol API we use is not optimized for trading these types of tokens.

For more information about tokens with in-built transaction fees, check out [#i-bought-sold-x-token-but-received-less-than-the-amount-displayed](../more-info/swapping-tokens.md#i-bought-sold-x-token-but-received-less-than-the-amount-displayed "mention")

### Trading on Polygon (Matic) Network

If you are receiving the 0x API Estimation Error when trading on the Polygon (Matic) Network, we recommend using the [Official high-performance RPC Polygon endpoint](https://blog.polygon.technology/polygon-rpc-gateway-will-provide-a-free-high-performance-connection-to-the-polygon-pos-blockchain/) in your wallet. In most cases, this will resolve this issue! Additionally, you can use this endpoint whenever you're on the Polygon network even outside of DexGuru.

## Confirm button is Greyed out when attempting to Swap

This generally occurs when there is temporary issues with the 0x Protocol API estimating the Network Transaction Fee (Gas Fee) for the transaction. We recommend closing the window and trying again, or waiting a couple of minutes as it generally resolves by itself.
