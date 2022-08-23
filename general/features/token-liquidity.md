---
description: and Pool Activity
---

# Token Liquidity

<figure><img src="../../.gitbook/assets/Screen Shot 2022-08-23 at 3.49.41 PM.png" alt=""><figcaption><p><strong>Token Liquidity</strong></p></figcaption></figure>

We measure liquidity $ value for a token, not for a trading pair. ****&#x20;

{% hint style="info" %}
To get the liquidity value for any given token, we add the total token amount across [supported liquidity pools](https://docs.dex.guru/data/supported-dexs-amms) and multiply it by the token's USD price. Only the given token is used in calculations out of multiple tokens inside liquidity pools.
{% endhint %}

This section of the DexGuru interface shows available on-chain token liquidity and AMM’s pool activity. It shows when and how many tokens are deposited or removed from the liquidity pools for the given token.&#x20;

![](<../../.gitbook/assets/Token Liquidity 01 (1).png>)

To specify the token liquidity pool you want to look at, pick it in the [Market Selector](https://docs.dex.guru/features/market-selector) area.&#x20;

![
](<../../.gitbook/assets/Token Liquidity 01.png>)

### Liquidity Provider Categories:

![](<../../.gitbook/assets/Token Liquidity 3.png>)

🐓 (Rooster) - During the last 30 days, this Liquidity Provider continuously has had $10k-$100k locked inside different liquidity pools across all supported chains.

🐅 (Tiger) - During the last 30 days, this Liquidity Provider continuously has had $100k-$500k locked inside different liquidity pools across all supported chains.

🐘 (Elephant) - During the last 30 days, this Liquidity Provider continuously has had $500k+ locked inside different liquidity pools across all supported chains.
