---
description: >-
  Market Screener shows a difference between buying and selling volumes of
  different types of traders over the last 24h.
---

# Market Screener

When there are more buyers than sellers, the Market Screener chart is green. When there are more sellers, the chart is red.&#x20;

![](https://lh4.googleusercontent.com/XFZLdfj59ElGZMwGT0XllMz8aG2IpUWcqB81znCDzHbq-MIYcrIJdbBejySozOLBss-YK0KI6rb1-BXWFZIM9pYYWWo4hWSoaTdwAtY9W0MULrPfFS1TMDAd44AsOV2db9x8G9Ir)

Turtle and shark sellers vastly outnumber buyers in the example above, while more whales buy than sell. \
\
Types of traders:&#x20;

🐢 - **Turtle** a.k.a. Casual Trader with $10k-$100k of a trading volume in the last 30 days‌

🦈 - **Shark** a.k.a. Active Trader with $100k-$500k of a trading volume in the last 30 days‌

🐳 - **Whale** a.k.a. Heavy Trader with $500k+ of a trading volume in the last 30 days



We determine the length of the bar by using our custom metric _m_. The formula below shows how we calculate the _m_ value for each day. The _m_ value is calculated over the last 24 hours.&#x20;

![](<../../../.gitbook/assets/image (23).png>)

The _m_ value is similar to the [Speculative Sentiment Index](https://www.fxcm.com/markets/insights/speculative-sentiment-index-ssi/). The ratio inside the formula determines if the _m_ value is positive or negative. If _m_ is positive, more tokens have been bought than sold and vice versa. We multiply the ratio by the number of traders to filter tokens with a high probability of manipulation. For example, when one trader buys most of the token’s supply to drive the price up. \
\
