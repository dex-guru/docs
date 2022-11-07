---
description: Frequently Asked Questions regarding Data on DexGuru
cover: ../.gitbook/assets/Data FAQ.jpg
coverY: 0
---

# Data FAQ

## Where do you get your Data? How do I know it's accurate?

At DexGuru we're 100% committed to delivering the most accurate and complete data about on-chain markets as fast as possible to our community and users.

{% hint style="success" %}
We have invested heavily in our data infrastructure. For each chain that we support, we run our own blockchain nodes in the network. As a result, we're able to retrieve on-chain transaction data as they occur in real time directly from the blockchain and display it on Dexguru with as minimal latency as possible.
{% endhint %}

All market data displayed on DexGuru is from on-chain transactions. However, we have included the usage of limited amount of supplemental off-chain data sources to help us provide additional information and context for a better user experience. An example of off-chain data in DexGuru UI is the token logos or information about verified tokens.

For more details, visit [Broken link](broken-reference "mention") and [off-chain-data-usage.md](off-chain-data-usage.md "mention") sections_._

## Is there a delay in the data?

Data displayed on DexGuru is relayed from our blockchain nodes as soon as they pick up it and retrieve it directly from the blockchain. Under normal circumstances, you can expect the data to be live and have minimal latency.

_If you need to receive data even faster, you may need to run your own nodes!_

## Do you have an API where I can access the data?

Yes! We have an API for developers. Visit our [Public API documentaion](https://api.dev.dex.guru/docs) for more information on how to get started.&#x20;

## Which Blockchains (L1s & L2s) do you cover?

We currently support Ethereum, BSC, Polygon, FTM, Arbitrum, Optimism, Gnosis, Celo & Avalanche. Our team is always adding and supporting EVM-compatible chains on the DexGuru platform. We're also in the progress of adding some non-EVM chains, so keep on the look out!

\
For the most complete and updated list of chains on DexGuru, please visit [supported-chains.md](supported-chains.md "mention").

## Which DEXs (Decentralized Exchanges/AMMs) do you cover?

We prioritize in covering the most popular DEXs on all the chains that we support. For a complete list of supported DEXs, please visit [supported-dexs-amms.md](supported-dexs-amms.md "mention")

{% hint style="info" %}
We're aiming to connect all major DEXs/AMMs with significant trading volume on EVM compatible chains by the end of 2021.&#x20;
{% endhint %}

## Can you add support for "X" blockchain or "X" DEX

As mentioned above, we're always looking to add the most popular Chains and corresponding DEXs/AMMs in their ecosystems.&#x20;

If there is a particular chain that you would really love to see on DexGuru, hop onto our [discord server](https://discord.com/invite/dPW8fzwzz9) and let us in the #suggestions channel.

## Why are some token prices & different from CoinMarketCap & CoinGecko?

Token prices on DexGuru are derived from the latest real-time on-chain buy/sell transactions from DEXs (Decentralized Exchanges/AMMs) that we cover as explained above. Whilst the prices you see on CoinMarketCap & CoinGecko are calculated using an average of prices from CEXs (Centralized Exchanges), even if they are illiquid.

![](../.gitbook/assets/SafeMoon\_price\_today\_\_chart\_\_market\_cap\_\_\_news\_\_\_CoinGecko.png)

## Why are some token prices different from other sources like other Price tools & Wallets?

As mentioned above, Token prices on DexGuru are derived from the latest real-time on-chain buy/sell transactions from DEXs (Decentralized Exchanges/AMMs) that we cover. There might be slight deviations in the token price if a Token is also being actively traded on a DEX/AMM that we do currently do not support.

In addition, other sites and wallets have their own methodology in which they determine the token price, you'll have to ask them how they arrive at their prices!

## I found token buy/sell and liquidity transactions on Etherscan/Blockchain Explorer that are not showing up on Dexguru.

If these transactions are occurring on a DEX/AMM that is currently not supported on DexGuru then it won't show up. We do our best to cover all the major DEXs/AMMs that have high liquidity and volume.&#x20;

Please check our [supported-dexs-amms.md](supported-dexs-amms.md "mention") to see if the transaction occurred on a DexGuru supported DEX/AMM.&#x20;

If you believe you found an exception to this case, where a transaction on a supported DEX/AMM is not showing or being accounted for, please send a message on [#support-dexguru channel on our discord](https://discord.com/invite/dPW8fzwzz9).

## How does a token get listed on DexGuru?

DexGuru is a fully permission-less. Tokens are automatically listed/indexed onto DexGuru as long as they have liquidity and transactions on one of the DEXs that we support listed above. We don't manually list or blacklist any tokens.

## Why isn't "X" token appearing when I search for it?

If you're trying to search using the Token name, try using the contract address for more accurate results. Sometimes there may be issues with the name in the token contract making it difficult for it be searched and found.&#x20;

Additionally, if the Token has no liquidity or transactions on one of the [supported-dexs-amms.md](supported-dexs-amms.md "mention") above then it won't be indexed on DexGuru.

## I saw "X" token on trending, are you guys promoting it?

Tokens on the trending tab are based on a ranking methodology involving trading activity from Whales (Heavy Trader with $500k+ of trading volume in the last 30 days). This is completely done automatically based on the formula we've implemented.&#x20;

F_or more details regarding the methodology, please visit_ [trending-tab.md](../general/features/market-selector/trending-tab.md "mention")_._

{% hint style="info" %}
We have not, and will not ever promote any tokens on DexGuru. If you find that questionable tokens are appearing in the DexGuru trending tab, please note that some token may developers deploy different wash trading strategies to game trending status across different platforms to achieve visibility. \
\
As always, please DYOR before investing in any tokens.
{% endhint %}

## Does **filtering data by time or dates show me data based on the time-zone I am in?**

Yes, it will. Applying any date filter on DexGuru will display data from transactions that occurred in the selected period for the time-zone you are currently in.

For example, if a user is in London, UK, applied a date filter on trade transactions from "1st Nov 2021 to 4th Nov 2021", then the data displayed will be from transactions that occurred between 1st Nov 2021 00:00 AM and 4th Nov 2021 23:59 London, UK time.

This means two people in different time-zones using the same date filters will most likely see slightly different data.

## I came across an issue with the data on DexGuru! What can I do?

If you believe you've come across an issue with the integrity of the data being displayed, please report the issue in the [#support-dexguru channel on discord](https://discord.com/invite/dPW8fzwzz9). We'll look into it as soon as possible!
