---
description: Discord Bot notifies you about significant on-chain events.
---

# Discord Bot

Install the bot to your Discord server [here](https://discord.com/oauth2/authorize?client\_id=962926828950020186\&scope=bot\&permissions=137439267840).&#x20;



DexGuru bot offers 4 types of alerts, aka _<mark style="color:purple;">`typeOfAlert`</mark>_.&#x20;

<mark style="color:purple;">NewToken</mark> - notifies you when a new token gets a liquid on-chain market.&#x20;

<mark style="color:purple;">LPool</mark> - notifies you of liquidity pools adds/removes.&#x20;

<mark style="color:purple;">Whale</mark> - notifies you of large on-chain swaps.&#x20;

<mark style="color:purple;">Volume</mark> - notifies you of volume spikes that happened over the 10 minutes relative to the last hour of the trading volume.



Eight different _<mark style="color:purple;">`network`</mark>_s are supported_:_ \
Ethereum, BSC, Polygon, Avalanche, Arbitrum, Fantom, CELO, Optimism



There are five commands you can give to the DexGuru bot by typing them in your channel. Make  sure the bot has permission to write in the channel.

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

<mark style="color:purple;">`guru add volume polygon 450`</mark> - sets a volume spike alert for polygon networks with a 450% threshold

<mark style="color:purple;">`guru add whale bsc 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48 150000`</mark> - sets a whale alert for swaps over $150000 for USDC token on BSC network.\
\
<mark style="color:purple;">`guru remove`</mark> - removes all liquidity pool alerts.



