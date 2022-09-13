---
description: and Pools Activity
---

# Token Liquidity

<figure><img src="../../.gitbook/assets/Screen Shot 2022-08-23 at 3.49.41 PM.png" alt=""><figcaption><p><strong>Token Liquidity</strong></p></figcaption></figure>

We measure liquidity $ value for a token, not for a trading pair. **** When determining how liquid a token is, we don’t really care about how much of that token is in liquidity pools, we care about the value of other tokens that it can be swapped for.&#x20;

{% hint style="info" %}
To determine a liquidity value for a given token X, we look across [supported liquidity pools](https://docs.dex.guru/data/supported-dexs-amms) and calculate the amounts of available tokens you can swap with token X. Then, to get the liquidity of token X, we multiply these available tokens by their corresponding USD prices and sum it all up.
{% endhint %}

The simple formula that works for all pool types that we are using is:

_**Liquidity of token X = TVL of all pools containing token X minus the total value of token A in those pools**_

Which can also be written as:

_**Liquidity of token X = total value of all other tokens in pools containing token x**_

This left section of the DexGuru interface shows available on-chain token liquidity and AMM’s pool activity. It shows when and how many tokens are deposited or removed from the liquidity pools for the given token.&#x20;

![](<../../.gitbook/assets/Token Liquidity 01 (1).png>)

To specify the token liquidity pool you want to look at, pick it in the [Market Selector](https://docs.dex.guru/features/market-selector) area.&#x20;

![
](<../../.gitbook/assets/Token Liquidity 01.png>)

### Liquidity Provider Categories:

![](<../../.gitbook/assets/Token Liquidity 3.png>)

🐓 (Rooster) - During the last 30 days, this Liquidity Provider continuously has had $10k-$100k locked inside different liquidity pools across all supported chains.

🐅 (Tiger) - During the last 30 days, this Liquidity Provider continuously has had $100k-$500k locked inside different liquidity pools across all supported chains.

🐘 (Elephant) - During the last 30 days, this Liquidity Provider continuously has had $500k+ locked inside different liquidity pools across all supported chains.
