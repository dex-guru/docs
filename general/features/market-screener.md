---
description: >-
  Market Screener reveals when traders' 24h volume is near its selling or buying
  maximum over the last 30 days.
---

# Market Screener

![](<../../.gitbook/assets/Market Screener\_01.png>)

Types of traders:&#x20;

🐢 - **Turtles** a.k.a. Casual Traders with $10k-$100k of a trading volume in the last 30 days‌

🦈 - **Sharks** a.k.a. Active Traders with $100k-$500k of a trading volume in the last 30 days‌

🐳 - **Whales** a.k.a. Heavy Traders with $500k+ of a trading volume in the last 30 days



## How is the Market Screener bar calculated?&#x20;

Market Screener is an indicator based on a [stochastic oscillato](https://en.wikipedia.org/wiki/Stochastic\_oscillator)r and our custom metrics _**m**_ and _**s**_. Market Screener reveals when traders' 24h volume is near its selling or buying maximum over the last 30 days.

1.  We calculate the custom metric m for every 24h. \


    <figure><img src="../../.gitbook/assets/002 (2).png" alt=""><figcaption></figcaption></figure>
2.  We determine the length of the market screener bar by comparing the current metric _**m**_ with previous _**m\_min**_ and _**m\_max**_ values over the last 30 days. \


    <figure><img src="../../.gitbook/assets/003.png" alt=""><figcaption></figcaption></figure>
3.  If _**s** _ < 0.5, the bar is red and the 24h trading volume is closer to its minimum over the last 30 days. If _**s**_ > 0.5 then the bar is green and the 24h trading volume is closer to its maximum over the last 30 days.\


    <figure><img src="../../.gitbook/assets/004.png" alt=""><figcaption></figcaption></figure>



\
\
