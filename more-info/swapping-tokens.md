---
description: >-
  Information and more details about buying and selling tokens directly on the
  DexGuru platform
---

# Swapping Tokens

## **How do swaps on DexGuru work? Did you build your own DEX?**

Although we haven't built our own DEX from scratch, we currently use 0x Protocol API to route all buy & sell (swap) orders on the DexGuru platform. 0x Protocol is an industry leading liquidity aggregator and is used by many Web3.0 leaders that you may already be familiar with such as MetaMask, DeFi Saver, Zappier & more.

{% hint style="success" %}
By integrating and using 0x Protocol API to route orders, we're able to offer DexGuru traders optimized token swaps that are fast, gas efficient and have low slippage meaning you'll get the best deal and rates on your swaps.
{% endhint %}

For more information about 0x Protocol, visit their [official site](https://0x.org) and check out their [performance analysis](https://blog.0xproject.com/a-comprehensive-analysis-on-dex-liquidity-aggregators-performance-dfb9654b0723) to see how they come out on top when compared with other DEX liquidity aggregators!

## **How do I know my swap orders conducted with my wallet are safe?**

As discussed above, when trading on DexGuru all your token approvals and orders are interacting with the 0x Protocol API through their **"0x: Exchange Proxy"** smart contract at: [_**0xdef1c0ded9bec7f1a1670819833240f027b25eff**_](https://etherscan.io/address/0xdef1c0ded9bec7f1a1670819833240f027b25eff)&#x20;

> _You can verify the smart contract address on the_ [_official 0x Protocol documentation_](https://0x.org/docs/guides/0x-cheat-sheet)_. This smart contract address is the same across all currently supported chains and you can view all the transactions that are interacting with this smart contract publicly on supported block explorers._

When a swap is successfully completed through DexGuru, you should see this in your transaction list on your Block Explorer:

![Transaction List on EtherScan](<../.gitbook/assets/image (29).png>)

Whilst inside the actual transaction details, you should see the full smart contract address you’ve interacted with, as below:\


![Transaction Details on EtherScan](<../.gitbook/assets/image (25).png>)

And as with navigating on Web3.0, you should always double & triple check every contract interaction before confirming to ensure you know exactly how a contract is going to interact with your wallet _(Even on DexGuru!)_.

{% hint style="success" %}
To date, DexGuru traders have done almost $800 Million USD equivalent in transaction volume with almost \~1 Million transactions directly on the DexGuru platform and we've only just begun. Feel rest assured you’re amongst great company when swapping on DexGuru!

__\
_For more analytics & statistics about token swaps being performed on DexGuru, feel free to view our publicly available_ [_dashboard here_](https://metabase.spaceship.0x.org/public/dashboard/e79bb86a-6777-4655-88fd-6453fdbefe0f?affiliate\_address=0x720c9244473dfc596547c1f7b6261c7112a3dad4)_._
{% endhint %}

## **What chains are supported for swaps?**

As we use 0x Protocol API to route our orders, as a result you will only be able to support on Chains that are supported and added by 0x Protocol.

The following chains are currently supported:&#x20;

* Ethereum
* Polygon (Matic)
* Binance Smart Chain (BSC)
* Avalanche
* Fantom
* CELO

## I **bought/sold** "X" Token but received less than the amount displayed

Under normal circumstances, due to slippage it is possible to receive less tokens than expected. This will always be displayed to you on DexGuru before you confirm the transaction in your wallet.

However, **in the instances that you are receiving a noticeable amount less than displayed**, it is possible that the token you bought or sold has in **built transaction fees that have implemented to act as deflationary measures to reduce sell pressure**_._

There are many popular tokens such as SAFEMOON coin that have these in built transaction fees, where buying or selling the tokens result in receiving get a certain % less. Always DYOR and check the official website of the Token for more information regarding the exact Tokenomics you are trading.

## **Can I place limit orders and stop orders for token buys and sells?**

Due to the nature of DEXs & AMMs we currently do not support them as they're hard to reliably and consistently execute due to technical limitations.&#x20;

However, we are aware of new advancements from certain DEXs that have recently improved limit order capabilities and are keeping up to date to see if we can implement this functionality onto DexGuru in the near future!
