---
description: notifies you about significant on-chain events.
---

# Discord Bot

Install the bot to your Discord server [here](https://discord.com/oauth2/authorize?client\_id=962926828950020186\&scope=bot\&permissions=137439267840).&#x20;



DexGuru bot offers **4 types of alerts**, aka _<mark style="color:purple;">`typeOfAlert`</mark>_.&#x20;

<mark style="color:purple;">NewToken</mark> - notifies you when a new token gets a liquid on-chain market.&#x20;

<mark style="color:purple;">LPool</mark> - notifies you of liquidity pools adds/removes.&#x20;

<mark style="color:purple;">Whale</mark> - notifies you of large on-chain swaps.&#x20;

<mark style="color:purple;">Volume</mark> - notifies you of volume spikes that happened over the 10 minutes relative to the last hour of the trading volume.



**Eight different **_<mark style="color:purple;">**`network`**</mark>_**s** are supported_:_ \
Ethereum, BSC, Polygon, Avalanche, Arbitrum, Fantom, CELO, Optimism



There are **five commands** you can give to the DexGuru bot by typing them in your channel. Make  sure the bot has permission to write in the channel.

* All commands start with the word _guru_&#x20;
* We use italics to indicate a variable in a command.&#x20;
* Square brackets \[...] in the command indicate that the variable is optional.&#x20;
* Commands are case-insensitive.&#x20;
* If you do not specify the threshold, we set it to $100,000 for NewToken, LPool, and Whale alerts -and for a Volume alert, the default value is 100%.

### List of commands&#x20;

**Add** - adds a new type of alert to the channel. \
<mark style="color:purple;">`guru add`</mark><mark style="color:purple;">` `</mark>_<mark style="color:purple;">`typeOfAlert network [tokenAddress] [threshold]`</mark>_

**Remove** - removes alerts in the channel. If you do not specify which exact alert to remove, all alerts that fall under the definition you provided are removed. \
<mark style="color:purple;">`guru remove`</mark><mark style="color:purple;">` `</mark>_<mark style="color:purple;">`[typeOfAlert] [network] [tokenAddress] [threshold]`</mark>_

**Change** - allows you to change a threshold on an alert. \
<mark style="color:purple;">`guru change`</mark><mark style="color:purple;">` `</mark>_<mark style="color:purple;">`typeOfAlert network [tokenAddress] threshold`</mark>_

**List** - lists all the alerts that are currently set up in the channel. \
<mark style="color:purple;">`guru list`</mark>

**Help** - displays instructions. \
<mark style="color:purple;">`guru help`</mark>

_<mark style="color:purple;"></mark>_

### Examples:

**Monitor large transactions to detect influential wallet addresses and potentially token price changes.** &#x20;

For example, we can set up a channel #ape-whales and create an alert for transactions that include APE token and are bigger than $200,000 in value by typing the following command:&#x20;

<mark style="color:purple;">`guru add whale ethereum 0x4d224452801aced8b2f0aebe155379bb5d594381 $200000`</mark>

****\
**Monitor newly released tokens and never miss an opportunity to buy them early. Researching newly listed tokens, can help you in finding undervalued projects.**&#x20;

For example, let's set up an alert for newly listed tokens with liquidity over $50,000. This time we are only interested in the Polygon platform. The command will look like this:&#x20;

<mark style="color:purple;">`guru add newtoken polygon $50000`</mark>

****

**Never miss a hot market with volume alerts.** Volume is an essential tool for swing traders. A trend with a high volume alert is stronger than the one with a small volume. &#x20;

For example, to look for high-volume tokens on the Optimism platform, with the 5000% of its average hourly volume, set up the following command:&#x20;

<mark style="color:purple;"><mark style="color:blue;">`guru add volume optimism 5000%`<mark style="color:blue;"></mark>

<mark style="color:purple;">`guru add whale bsc 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48 150000`</mark> - sets a whale alert for swaps over $150000 for USDC token on BSC network.\
\
<mark style="color:purple;">`guru remove`</mark> - removes all liquidity pool alerts. \


\
\
Feel free to reach out to us on [Discord](https://discord.com/invite/dPW8fzwzz9) for support.&#x20;

