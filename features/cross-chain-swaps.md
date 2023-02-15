# Cross-Chain Swaps

Cross-chain swaps on DexGuru are available inside [trading-tools](../general/features/trading-tools/ "mention"). They are implemented using [LiFi](https://li.fi/) bridge aggregation protocol that supports swaps by aggregating [bridges](https://docs.li.fi/list-chains-bridges-dexs#bridges) and connecting them to [DEX aggregators](https://docs.li.fi/list-chains-bridges-dexs#exchanges).

<figure><img src="../.gitbook/assets/Screen Shot 2023-02-14 at 5.09.14 PM.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
If you are facing an issue with cross-chain swap please [contact LiFi directly](https://lifihelp.zendesk.com/hc/en-us/articles/11158438085531-Where-can-I-get-real-time-support-). &#x20;
{% endhint %}

Note that cross-chain transactions take longer than single-chain ones. Sometimes you can receive a stablecoin token on the destination chain instead of the requested token. Unfortunately, we are unable to control this because this type of behavior comes directly from [LiFi](https://li.fi/). \
&#x20;

