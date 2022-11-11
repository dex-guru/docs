---
description: >-
  Information and more details about buying and selling tokens directly on the
  DexGuru platform
cover: ../.gitbook/assets/Swapping Tokens.jpg
coverY: 0
---

# Swapping Tokens

## **How do swaps on DexGuru work? Did you build your own DEX?**

We did not build our own DEX from scratch, we currently use 0x, 1inch, and Paraswap protocols to route all buy & sell (swap) orders on the DexGuru platform. All the above protocols are industry-leading liquidity aggregators and are used by many Web3.0 leaders that you may already be familiar with, such as MetaMask, DeFi Saver, Zapper & more.

{% hint style="success" %}
By integrating and using 0x, 1inch, and Paraswap protocols to route orders, we're able to offer DexGuru traders optimized token swaps that are fast, gas efficient, and have low slippage, meaning you'll get the best deal and rates on your swaps.
{% endhint %}

For more information about protocols, visit their official websites: [0x](https://www.0x.org/), [1inch](https://1inch.io/), and [Paraswap](https://www.paraswap.io/).&#x20;

## **How do I know my swap orders conducted with my wallet are safe?**

As discussed above, when trading on DexGuru all your token approvals and orders interact with the 0x, 1inch, or Paraswap protocols through their proxy smart contracts. Check out the full list of smart contract addresses in the [wallets-security-and-more.md](wallets-security-and-more.md "mention")section.&#x20;

> _You can verify the smart contract address on the official documantations:_ [_0x_](https://docs.0x.org/introduction/0x-cheat-sheet)_,_[ _1inch_](https://docs.1inch.io/)_,_ [_Paraswap_](https://developers.paraswap.network/smart-contracts)_._&#x20;

When a swap is successfully completed through DexGuru, you should see this in your transaction list on a Block Explorer. It can be "0x: Exchange Proxy" or "1inch: Router" or something like "Paraswap v5: Augustus Swapper Mainnet".&#x20;

![Transaction List on EtherScan](<../.gitbook/assets/image (29) (1).png>)

Whilst inside the actual transaction details, you should see the full smart contract address you’ve interacted with, as below:\


![Transaction Details on EtherScan](<../.gitbook/assets/image (25) (1) (1).png>)

And as with navigating on Web3.0, you should always double & triple-check every contract interaction before confirming to ensure you know exactly how a contract is going to interact with your wallet _(Even on DexGuru!)_.

## **How are my swaps routed? And which chains are supported for swaps?**&#x20;

The following protocols define the markets that are used to route your order:  [0x](https://www.0x.org/), [1inch](https://1inch.io/), [Paraswap](https://www.paraswap.io/). You may find that your swap may be routed across more than 1 DEX as both protocols optimize your order to be filled with the lowest slippage possible. :raised\_hands:

## I **bought/sold** "X" Token but received less than the amount displayed

Under normal circumstances, due to slippage, it is possible to receive fewer tokens than expected. This will always be displayed to you on DexGuru before you confirm the transaction in your wallet.

However, **in the instances that you are receiving a noticeable amount less than displayed**, it is possible that the token you bought or sold has **in-built transaction fees that have been implemented to act as deflationary measures to reduce sell pressure**_._

There are many popular tokens such as SAFEMOON coin that have these in-built transaction fees, where buying or selling the tokens results in receiving get a certain % less. Always DYOR and check the official website of the Token for more information regarding the exact Tokenomics you are trading.

## **Can I place limit orders and stop orders for token buys and sells?**

Yes, limit orders are supported by DexGuru. Learn more about [limit-orders.md](../general/features/limit-orders.md "mention")
