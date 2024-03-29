---
description: >-
  (aka Trader Profile) Discover and deep dive into Trader's wallets to see their
  activity
---

# Account Profile 🐋

For further information regarding a Trader's Wallet token balances and recent activity, you can visit their Trader Profile. This page allows you to dive deep into a Trader's wallet to see precisely what they've been up to recently and view their historical transactions.

<figure><img src="../../.gitbook/assets/Screen Shot 2023-03-23 at 1.00.25 PM.png" alt=""><figcaption></figcaption></figure>

This feature is currently accessible by clicking on any transaction on the main page, your wallet in the top right corner, and the wallet icon in the left navbar.&#x20;

<figure><img src="../../.gitbook/assets/Screen Shot 2023-03-23 at 12.51.26 PM (1).png" alt=""><figcaption></figcaption></figure>

## Trader Overview&#x20;

<figure><img src="../../.gitbook/assets/Screen Shot 2023-03-23 at 1.03.41 PM.png" alt=""><figcaption></figcaption></figure>

At the top of the Trader Profile, you will be able to see a quick overview with information such as:

**Account type**

Learn more at the [account-labeling.md](account-labeling.md "mention") page.&#x20;

**Asset Value**

The total dollar value of _Tokens_\* that the trader is currently holding.&#x20;

**30 Day Trading Volume**

The total dollar value of tokens traded from this Trader in the past 30 days.&#x20;

**Inflow/Outflow, 30d**

The dollar value of tokens that have been transferred to and from the account. Only verified tokens that are listed at least in one [token list](https://docs.dex.guru/data/off-chain-data-usage#usage-of-token-lists) are used for calculations.&#x20;

{% hint style="info" %}
**\*Token Display Criteria:** Currently, for tokens to be calculated in Asset Value, they must fit the criteria of:

* Token has had their balance (# number of Tokens) change in the last 7 days&#x20;
* Greater than >$10 in total market value
* Token is actively traded and has had more than 1 transaction in the last 7 days
{% endhint %}

## Trader Token Balances

As with Asset value in the Trader Overview section, only Tokens that fit the same _**Token Display Criteria**_**\*** mentioned above will be displayed here.

![Trader Token Balances that fit Token Display Criteria\*](<../../.gitbook/assets/image (30).png>)

In the Trader's Token Balances you will also see the following information:

* **Current Balance -** The # of Tokens owned by the Trader along with the dollar value equivalent
* **7 Day Change -** The change in the wallet's Token Balance during the last 7 days for this specific token
* **Average Acquisition Price\*** **-** The average acquisition price of the Token by the wallet
* **In/Out/At Money Status -** Displays whether the wallet is current in/out/at the money based on their Average Acquisition Price compared to the Token's Current Price.

{% hint style="info" %}
_**\*Note:** Transactions that involve a transfer of the Token from one wallet to another are also included in the Acquisition Price. For these transactions, the Token Price at the time of transfer will be taken to be included in the calculation of the Average Acquisition Price._
{% endhint %}

Additionally, by clicking on the Token Balances, you will be able to see how the user's Token Balance for that specific token has changed over time. This graph is also charted alongside the Token price.

## **Full Transaction List**

<figure><img src="../../.gitbook/assets/Screen Shot 2023-03-23 at 12.57.53 PM.png" alt=""><figcaption></figcaption></figure>

In the Trader Profile, you will also be able to view and download to CSV the full transaction history of the Trader's Address including:

* Swaps
* Transfers
* Liquidity Pool Adds/Removals

Don't forget, you'll be able to filter the Trader's transaction list by time, trade size, token and pool address - this'll allow you dig deeper and uncover further insights into their historical activity!

![Filters available for Trader's Transaction List](<../../.gitbook/assets/image (28).png>)
