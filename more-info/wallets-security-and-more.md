---
description: >-
  Everything you need to know when you connect your wallet with DexGuru & tips
  on staying safe on Web 3.0!
cover: ../.gitbook/assets/Wallets, Security & More.jpg
coverY: 0
---

# Wallets, Security & More

## **What smart contracts am I interacting with while using DexGuru?**

DexGuru does not have a smart contract; instead, we use [meta-aggregation](https://docs.dex.guru/general/features/trading-tools/meta-aggregation). We use multiple decentralized exchange aggregators and their smart contracts. When you approve your token spending, you provide access to one of the following smart contracts:

### **M**arket orders:

#### via 0x router ([source](https://docs.0x.org/introduction/0x-cheat-sheet#exchange-proxy-addresses)):&#x20;

Ethereum - [0xdef1c0ded9bec7f1a1670819833240f027b25eff](https://etherscan.io/address/0xdef1c0ded9bec7f1a1670819833240f027b25eff)&#x20;

BSC - [0xdef1c0ded9bec7f1a1670819833240f027b25eff](https://bscscan.com/address/0xdef1c0ded9bec7f1a1670819833240f027b25eff)&#x20;

Polygon - [0xdef1c0ded9bec7f1a1670819833240f027b25eff](https://polygonscan.com/address/0xdef1c0ded9bec7f1a1670819833240f027b25eff)&#x20;

Avalanche - [0xdef1c0ded9bec7f1a1670819833240f027b25eff](https://snowtrace.io/address/0xdef1c0ded9bec7f1a1670819833240f027b25eff)&#x20;

Fantom - [0xdef189deaef76e379df891899eb5a00a94cbc250](https://ftmscan.com/address/0xdef189deaef76e379df891899eb5a00a94cbc250)&#x20;

Arbitrum - [0xdef1c0ded9bec7f1a1670819833240f027b25eff](https://arbiscan.io/address/0xdef1c0ded9bec7f1a1670819833240f027b25eff)&#x20;

Optimism - [0xdef1abe32c034e558cdd535791643c58a13acc10](https://optimistic.etherscan.io/address/0xdef1abe32c034e558cdd535791643c58a13acc10)&#x20;

CELO - [0xdef1c0ded9bec7f1a1670819833240f027b25eff](https://celoscan.io/address/0xdef1c0ded9bec7f1a1670819833240f027b25eff)

#### via 1inch router ([source](https://docs.1inch.io/)):&#x20;

Ethereum - [0x1111111254EEB25477B68fb85Ed929f73A960582 ](https://etherscan.io/address/0x1111111254EEB25477B68fb85Ed929f73A960582#contracts)

BSC - [0x1111111254EEB25477B68fb85Ed929f73A960582](https://bscscan.com/address/0x1111111254EEB25477B68fb85Ed929f73A960582)

Polygon - [0x1111111254EEB25477B68fb85Ed929f73A960582](https://polygonscan.com/address/0x1111111254EEB25477B68fb85Ed929f73A960582#code)

Optimism - [0x1111111254EEB25477B68fb85Ed929f73A960582](https://optimistic.etherscan.io/address/0x1111111254EEB25477B68fb85Ed929f73A960582#code)

Arbitrum - [0x1111111254EEB25477B68fb85Ed929f73A960582](https://arbiscan.io/address/0x1111111254eeb25477b68fb85ed929f73a960582#code)

Gnosis - [0x1111111254EEB25477B68fb85Ed929f73A960582](https://gnosisscan.io/address/0x1111111254eeb25477b68fb85ed929f73a960582#contracts)

Avalanche - [0x1111111254EEB25477B68fb85Ed929f73A960582](https://snowtrace.io/address/0x1111111254eeb25477b68fb85ed929f73a960582)

Fantom - [0x1111111254EEB25477B68fb85Ed929f73A960582](https://ftmscan.com/address/0x1111111254EEB25477B68fb85Ed929f73A960582#contracts)

#### via Paraswap ([source](https://developers.paraswap.network/smart-contracts)):

Ethereum: [0x216b4b4ba9f3e719726886d34a177484278bfcae](https://etherscan.io/address/0x216b4b4ba9f3e719726886d34a177484278bfcae#code)

Polygon: [0x216b4b4ba9f3e719726886d34a177484278bfcae](https://polygonscan.com/address/0x216B4B4Ba9F3e719726886d34a177484278Bfcae#code)

BSC: [0x216b4b4ba9f3e719726886d34a177484278bfcae](https://bscscan.com/address/0x216b4b4ba9f3e719726886d34a177484278bfcae#code)

Avalanche: [0x216b4b4ba9f3e719726886d34a177484278bfcae](https://cchain.explorer.avax.network/address/0x216B4B4Ba9F3e719726886d34a177484278Bfcae/contracts)

Arbitrum: [0x216B4B4Ba9F3e719726886d34a177484278Bfcae](https://arbiscan.io/address/0x216B4B4Ba9F3e719726886d34a177484278Bfcae)

Optimism: [0x216B4B4Ba9F3e719726886d34a177484278Bfcae](https://optimistic.etherscan.io/address/0x216b4b4ba9f3e719726886d34a177484278bfcae)

Fantom: [0x216B4B4Ba9F3e719726886d34a177484278Bfcae](https://etherscan.io/address/0x216b4b4ba9f3e719726886d34a177484278bfcae#code)

#### via KyberSwap ([source](https://github.com/dex-guru/meta-aggregation-api/blob/main/meta\_aggregation\_api/providers/kyberswap\_v1/config.json)):

Ethereum: [0x6131B5fae19EA4f9D964eAc0408E4408b66337b5](https://etherscan.io/address/0x6131B5fae19EA4f9D964eAc0408E4408b66337b5)

Polygon: [0x6131B5fae19EA4f9D964eAc0408E4408b66337b5](https://polygonscan.com/address/0x6131b5fae19ea4f9d964eac0408e4408b66337b5#code)

BSC: [0x6131B5fae19EA4f9D964eAc0408E4408b66337b5](https://bscscan.com/address/0x6131b5fae19ea4f9d964eac0408e4408b66337b5)

Avalanche: [0x6131B5fae19EA4f9D964eAc0408E4408b66337b5](https://snowtrace.io/address/0x6131b5fae19ea4f9d964eac0408e4408b66337b5#code)

Arbitrum: [0x6131B5fae19EA4f9D964eAc0408E4408b66337b5](https://arbiscan.io/address/0x6131b5fae19ea4f9d964eac0408e4408b66337b5#contracts)

Optimism: [0x6131B5fae19EA4f9D964eAc0408E4408b66337b5](https://optimistic.etherscan.io/address/0x6131b5fae19ea4f9d964eac0408e4408b66337b5#code)

Fantom: [0x6131B5fae19EA4f9D964eAc0408E4408b66337b5](https://etherscan.io/address/0x6131B5fae19EA4f9D964eAc0408E4408b66337b5#code)

#### &#x20;

### Limit orders:

#### via 1inch protocol ([source](https://github.com/1inch/limit-order-protocol)):

Ethereum - [0x119c71D3BbAC22029622cbaEc24854d3D32D2828](https://etherscan.io/address/0x119c71D3BbAC22029622cbaEc24854d3D32D2828)

BSC - [0x1e38Eff998DF9d3669E32f4ff400031385Bf6362](https://bscscan.com/address/0x1e38Eff998DF9d3669E32f4ff400031385Bf6362#code)

Polygon - [0x94Bc2a1C732BcAd7343B25af48385Fe76E08734f](https://polygonscan.com/address/0x94Bc2a1C732BcAd7343B25af48385Fe76E08734f#code)

Optimism - [0x11431a89893025D2a48dCA4EddC396f8C8117187](https://optimistic.etherscan.io/address/0x11431a89893025D2a48dCA4EddC396f8C8117187)

Arbitrun - [0x7F069df72b7A39bCE9806e3AfaF579E54D8CF2b9](https://arbiscan.io/address/0x7F069df72b7A39bCE9806e3AfaF579E54D8CF2b9)

Gnosis [0x54431918cEC22932fCF97E54769F4E00f646690F](https://blockscout.com/xdai/mainnet/address/0x54431918cEC22932fCF97E54769F4E00f646690F/transactions)

Avalanche - [0x0F85A912448279111694F4Ba4F85dC641c54b594](https://snowtrace.io/address/0x0F85A912448279111694F4Ba4F85dC641c54b594#code)

Fantom - [0x216B4B4Ba9F3e719726886d34a177484278Bfcae](https://ftmscan.com/address/0x216B4B4Ba9F3e719726886d34a177484278Bfcae#code)

## **What wallets does DexGuru Support?**

The DexGuru platform supports the majority of popular Web3.0 wallets, including the following:

* MetaMask
* WalletConnect _(Including all wallets supported by WalletConnect)_
* TrustWallet
* Ledger (via MetaMask)
* Trezor (via MetaMask)

Visit [connect-wallet.md](../how-to/connect-wallet.md "mention") to learn how to connect your wallet on both Desktop & Mobile.

## **What's the benefits of connecting my wallet to DexGuru?**

Connecting your wallet provides you complete access to the DexGuru platform, enabling you to:

* Add tokens to your own Favorites list
* Sync your Favorites list across all your devices _(via connecting with the same wallet)_
* Buy and Sell tokens directly on DexGuru
* Setup Price Alerts through Push Notifications
* [Trader Profile](../general/features/account-profile.md)
* [Token Profile](../general/features/dyor.md)
* [Multi-Chart](https://docs.dex.guru/general/features/multi-chart)&#x20;
* In-depth Analytics of Volume and Liquidity by DEX
* _And more..._ s_tay tuned, we have some cool features coming soon 😉_

## **How can I change the wallet I'm using on DexGuru**

If you are using MetaMask on desktop, changing your wallet is as simple clicking on the MetaMask icon and changing your wallet there. This will be updated and reflected on DexGuru.

_**Note:** If you are changing your wallet that has not previously connected to DexGuru, then you will be asked to sign a transaction to confirm - for more details read the following section_[#whats-a-signature-request-and-why-do-i-need-to-sign-one-when-connecting-to-dexguru](wallets-security-and-more.md#whats-a-signature-request-and-why-do-i-need-to-sign-one-when-connecting-to-dexguru "mention")

## **Can I remove my wallet from DexGuru?**

Removing your wallet is as simple as clicking on the wallet icon and pressing on **"Disconnect Wallet"**.

## **Is DexGuru safe to connect my wallet to?**

Yes it is! DexGuru is a fully non custodial platform and your assets are always under your control.

Just like when you connect to any DApp on Web 3.0, the platform will only be able to view your wallet token balances and activity which are used show you your previous token trades.

## **What's a Signature Request? And why do I need to sign one when connecting to DexGuru?**

### **For First Time Users**

When connecting to DexGuru for the first time, you will be asked to sign a Signature Request which essentially uses your wallet to Login. Don't worry! This doesn't create any actual transactions, approvals or other interactions with your balances on your wallet, it's simply used to confirm you are the owner of the wallet on the device you are using.

Similar to how in Web 2.0, you are able to create an account or login websites using your socials (Facebook/Google/Twitter Accounts), in Web 3.0, by signing the cryptographic Signature request you are able to login onto apps by using your wallet. You'll most likely have logged in using the exact same way on other popular Web 3.0 apps such as OpenSea.

After you have signed it once, whenever you connect to DexGuru using the same wallet address and from the same device, you won't be prompted to sign again unless you have cleared your browser cache recently.

### **For Returning Users**

If you have already previously signed a Signature request, you may be prompted again to sign another one in the future.&#x20;

You may be asked to sign a Signature Request again with the same wallet address you have previously connected with, if you are:

* Connecting from a new Device
* Connecting from a new/different Browser
* Connecting from a browser you have previously connected with BUT have cleared the Cache/Local Storage
* Connecting from the same Browser but using a different browser profile

## **Why am I asked for Token Approval when trying to make a Swap on DexGuru?**

As with all DEXs/AMMs, the first time you swap a token you will need to complete a token approval to give permission for the smart contract to spend your tokens from your wallet.

Once you have approved the token once on DexGuru, you will be able to complete the swap and you won't need to do it again unless you are attempting to make a swap with a new Token that you have yet to approve.

In addition, since the Token Approval is an on-chain transactions, you will be required to pay a small gas fee (network transaction fee) for the approval.

## **Staying Safe on Web 3.0 & on DexGuru**

As with all new and emerging industries, the flow of new opportunities inevitably also attracts bad players into the space such as hackers and scammers.

Of course, this applies to Web 3.0 as well - and although we can't control the actions of bad players out there, we can always be proactive in being smart & safe when navigating web 3.0 to safeguard our wallets and funds.

:exclamation: **Here are some important things to know and remember specifically for DexGuru to help you stay safe!**

* DexGuru does NOT currently have a Token NOR a Planned Token Sale
* DexGuru is NOT offering any airdrops or rewards for redemption
* DexGuru team members will NEVER DM you first on Discord, Twitter, Telegram or any other channel
* **Always check your URL to make sure you're using the official DexGuru platform and related websites.** Below is a list of all the current official related links we have:
  * Official Website -> [https://dex.guru/](https://dex.guru/)
  * Blog -> [https://blog.dex.guru/](https://blog.dex.guru/)
  * Github -> [https://github.com/dex-guru/](https://github.com/dex-guru/)
  * Help & Support Docs -> [https://docs.dex.guru/](https://docs.dex.guru/)
  * Developer & API Docs -> [https://developers.dex.guru/](https://developers.dex.guru/)
  * Official Twitter -> [https://twitter.com/dexguru/](https://twitter.com/dexguru/)
  * Official Discord Invite -> [https://discord.com/invite/dPW8fzwzz9](https://discord.com/invite/dPW8fzwzz9)
  * Official Telegram Group → [https://t.me/dexguru](https://t.me/dexguru) - @dexguru&#x20;
  * Telegram Notifications Bot -> [@dxgurubot](https://t.me/dxgurubot)
* **Never share your recovery phrase with anyone**
  * DexGuru team members will NEVER ask you for your recovery/seed phrase or private key
  * DexGuru official websites will NEVER prompt you to input and enter your recovery/seed phrase or private key
