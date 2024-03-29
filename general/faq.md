---
description: Most commonly asked questions from the DexGuru community.
cover: ../.gitbook/assets/fag2.jpg
coverY: 0
---

# FAQ

## What is DexGuru?

DexGuru is an on-chain analytics and trading terminal that focuses on providing the best trading experience possible. We strive to bring the following all under one easy-to-use integrated UI:

* Real-time Data across all DEX Markets
* On-Chain Research
* Powerful Data Analytics
* Token Swap Execution Capabilities

Our goal is to make it easy for all traders to leverage on-chain data in a simple, understandable, and timely way and enable them to make the best possible decisions in real time.

To learn more about DexGuru and what we're all about, visit our [Manifesto on our blog](https://blog.dex.guru/manifesto)!

## Is DexGuru free to use? And does trading on DexGuru cost anything extra?

DexGuru's analytics features are currently entirely free to use. All features on DexGuru are available to everyone once they have connected their wallet.&#x20;

Trading tokens on DexGuru includes a 0.5% fee from your order that helps develop our product. Remember that you will still need to pay Network Transaction Fees (Gas Fees) as you would if you were swapping on a DEX/AMM.&#x20;

{% hint style="info" %}
We do have future plans to introduce and add premium subscription plans for more comprehensive and advanced features! Keep on the lookout :eyes:
{% endhint %}

## How **are Token Swap O**rders being routed?

All swaps on DexGuru are routed through one of the suported DEX aggregators. We call this process Meta-aggregtion.&#x20;

For more details about please visit\
[meta-aggregation.md](features/trading-tools/meta-aggregation.md "mention")\
[swapping-tokens.md](../more-info/swapping-tokens.md "mention")

## Do I need to connect my Wallet to use DexGuru?&#x20;

No, you don't have to connect your wallet to use DexGuru if you choose not to, but some features will be limited. We encourage users to connect their wallet as it provides full access to the DexGuru platform, along with allowing you to save tokens to your favorites, buy and sell tokens, setting price alerts & more!&#x20;

## Why am I asked for a Signature Request when connecting my Wallet? And token approvals before swapping?

When you connect your wallet for the first time on a new device, you will be asked for a Signature request to verify you are the owner of the address. There are no blockchain transactions, gas fees or approvals associated with this at all, so feel rest assured that your funds are SAFU!

Additionally, you will be asked for token approvals before swapping a token on DexGuru to allow the smart contract to spend your tokens from your wallet in exchange for the one that you are buying. This type of Token approval is exactly the same as if you were swapping directly on a DEX/AMM and will cost a small Network Transaction fee (gas fee) as it is a transaction on the blockchain.

For more in-depth information about Signature Requests, Token Approvals and using your Wallet on DexGuru, check out the [wallets-security-and-more.md](../more-info/wallets-security-and-more.md "mention") section.

## What is the "Degen Mode🙊" inside the Market Selector aka Unverified Tokens?

<figure><img src="../.gitbook/assets/001 (2) (2).png" alt=""><figcaption><p>Degen Mode in the bottom portion of the DexGuru Market Selector</p></figcaption></figure>

Tokens that fall under the Full Degen Mode in the [market-selector](features/market-selector/ "mention") are tokens that are not on at least one verified Token List. We recommend double-checking and verifying contract addresses for Tokens under Degen Mode to ensure you're interacting with the correct Token.&#x20;

### **What exactly are token lists?**

Token lists are an industry standard created by Uniswap to help users navigate the vast number of tokens in the world of crypto. Since anyone can create tokens, it's become for bad actors to create scams, fakes or duplicate tokens to take advantage of market participants. Token lists are created and approved by reputable parties in the Crypto industry to help users interact with authentic tokens.

Directly from Uniswap's [official blog post on Token Lists](https://uniswap.org/blog/token-lists):

> _As the rate of token issuance accelerates, it has become increasingly difficult for users to filter out high quality, legitimate tokens from scams, fakes, and duplicates. Across the space, projects are managing and maintaining rapidly growing token lists. The end result is a lot of wasted time, slow listing processes and scammed users. In addition, builders should spend their time building, not deciding which tokens are legitimate and which are scams, fakes or duplicates._
>
> \
> _Today, we are excited to announce_ [_Token Lists_](https://tokenlists.org/)_, a new standard for creating lists of ERC20 tokens. This is a community-led initiative to improve discoverability and trust in ERC20 token lists in a manner that is inclusive, transparent, and decentralized._

For more information about Token Lists, check out the full [Uniswap official blog post](https://uniswap.org/blog/token-lists) that covers everything you need to know.

For more information on the exact sources of the token lists that we use, check out [#usage-of-token-lists](../data/off-chain-data-usage.md#usage-of-token-lists "mention").

### How we use Token Lists on DexGuru

We use Token Lists to help provide additional context when browsing Tokens. Keep in mind, **verified status is NOT investment advice, a stamp of approval, or any kind of recommendation**. It is only an indicator that a particular Token is reputable enough to be recognized by a trusted List creator.

Additionally, tokens that are not verified and that fall under Full Degen Mode does not necessarily mean they are fraudulent either - they have just not been vetted and verified by List creators yet.&#x20;

As always, DYOR, double check all Token contract addresses that you're interacting with to ensure they are the right one, especially if they are not on Token Lists.

{% hint style="info" %}
_You may have previously seen the button "Manage Token Lists" when selecting tokens to swap on leading DEXs; the lists that appear there are likely to be the same ones that we use!_
{% endhint %}

### Why are Recently Listed Tokens under Degen Mode?

<figure><img src="../.gitbook/assets/002.png" alt=""><figcaption><p>Recently Listed tab in Market Selector</p></figcaption></figure>

For the vast majority of cases, Tokens shown in the Recently Listed tab will also fall under Degen Mode due to their recency of being created within the past 24 hours. During this time period, it is very unlikely that these tokens have been able to been verified into an existing established Token and as a result will fall under Degen Mode.

## How can I add/update a Token's Logo?&#x20;

Currently, Token logos are being pulled from 3 off-chain data sources, if one source does not contain a Token's Logo, then the next one will be used. They are listed and ranked below in terms of priority:

* [DexGuru Asset Repo](https://github.com/dex-guru/assets)&#x20;
* [Trust Wallet's Asset Repo](https://github.com/trustwallet/assets)&#x20;
* [Coingecko's API](https://www.coingecko.com/en/api/documentation)&#x20;

If you are looking to update a Token's logo, you can do it directly on the [DexGuru Asset Repo](https://github.com/dex-guru/assets). You will need make a PR request with your token logo into the `token// folder` with a `<checsum_address>.svg|png` filename. For full list of requirements and instructions, please visit our [Asset Repo](https://github.com/dex-guru/assets).&#x20;

Alternatively, you may visit Trust Wallet's Asset Repo & CoinGecko to update your Token Assets through their channels.

For more information about how Token data is pulled and displayed on DexGuru, please visit our [Broken link](broken-reference "mention") section.

## What does the :thinking: Emoji mean on Token Logos?

The :thinking: is used a placeholder for Tokens that currently do not have their Logos in one of the sources listed above in [#how-can-i-add-update-a-tokens-logo](faq.md#how-can-i-add-update-a-tokens-logo "mention")

## What is the process for getting a new Token listed on DexGuru

We're a permissionless platform, meaning there is no application process or listing fees. We automatically index all tokens that are on our [supported-chains.md](../data/supported-chains.md "mention"), have liquidity on at least one of our [supported-dexs.md](../data/supported-dexs.md "mention") and has had recent transactions.&#x20;

For more information about how data makes its way onto DexGuru, please check out our [data-faq.md](../data/data-faq.md "mention") which covers many questions you may have!

## What is the process for getting a new integration with your platform?

#### Integrations for Exchanges/AMMs/DEXs

1\. To enable routing via your exchange:

* Integration with one of DEX aggregators that we support, which enables us to route orders via your exchange.  Reach out to their teams. You can find the list of aggregators on [meta-aggregation.md](features/trading-tools/meta-aggregation.md "mention") page.&#x20;

2\. To show price charts and trading info in DexGuru UI:&#x20;

* Integration in DexGuru UI. This could be done via pull request at this repo: [https://github.com/dex-guru/data-sources](https://github.com/dex-guru/data-sources)  &#x20;

#### Integrations for Aggregators&#x20;

You can add your aggregator to our Meta-aggregation API at this repo: [https://github.com/dex-guru/meta-aggregation-api](https://github.com/dex-guru/meta-aggregation-api) &#x20;

#### Integrations for  EVM-compatible blockchains&#x20;

We recently streamlined the process of adding new EVM-compatible networks, it could be done with a simple pull request as described here:: [https://github.com/dex-guru/data-sources](https://github.com/dex-guru/data-sources)  &#x20;

Feel free to reach out team at our discord server if you have further questions.&#x20;

## Ser, Wen Token? Wen Airdrop?

We're focused on building the best trader experience first!

Additionally, we have no plans to do any airdrops and would like to make it clear that you won't receive anything if you are using DexGuru with an expectation of future airdrops :blush:.&#x20;

