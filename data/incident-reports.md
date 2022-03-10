---
description: Reports of Incidents affecting DexGuru Data
---

# Incident Reports

## **21st Feb 2022 - Incorrect Token Prices on Polygon Network**&#x20;

Our engineering team identified an issue that impacted all Tokens Prices on the Polygon Network.

_**First Identified:** 21st February 2022 - 21:00 UTC_\
_**Resolved:** 22nd February 2022 - 03:00 UTC_&#x20;

**Issue Description**

The price of the native token of Polygon, $MATIC was being incorrectly calculated due to transactions from an very low liquidity MATIC pool being factored into it's price calculation. This resulted in $MATIC's price being inaccurately skewered and not reflective actual market price during this period of time.&#x20;

As the prices of all tokens in each Network is calculated from it's Native token, this further affected all token prices on the Polygon network and resulted in incorrect prices being displayed as well.

**Resolution**

A short term fix was implemented to fix the incorrect price of $MATIC by removing all the "extreme" price records that incorrectly skewered the calculation of $MATIC's price. This allowed for all the Tokens on Polygon Network to be accurately re-calculated and be reflective of their proper market price.

Moving forward, in preventing this issue from occurring again, we've improved how we calculate Native tokens (such as ETH, MATIC, BNB, AVAX & etc) of networks by excluding illiquid pools from being used to calculate these token prices. This improvement will safeguard and prevent any "extreme" transactions from inaccurately skewering the Native Network Tokens Prices which would further impact the Token Price data in the network.



