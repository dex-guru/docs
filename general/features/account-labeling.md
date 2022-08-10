---
description: using on-chain data
---

# Account Labeling

We currently recognize three different account types based on on-chain information:

* ![](<../../.gitbook/assets/wallet 01.svg>) EOA (Externally Owned Account)
* ![](<../../.gitbook/assets/smart contract.svg>) Smart Contract&#x20;
* ![](<../../.gitbook/assets/ice cream.svg>) Liquidity Pool&#x20;

DexGuru labels an account as **EOA** when anyone with private keys controls it. This kind of account can be thought of as a wallet address.&#x20;

We label an account as **Smart Contract** when it is a program/code that runs on-chain. Some contracts will have their name listed and some won't. This is because we can only get names of smart contracts that have a name method in their ABI (Application Binary Interface). \
\
The last label is **Liquidity Pool** implies that an account is a smart contract and specifically represents a liquidity pool address. All liquidity pools are smart contracts, but not all smart contracts are liquidity pools.&#x20;



Currently, the account labeling feature can be found inside 🍄[Token Profile ](dyor.md)

![](<../../.gitbook/assets/Twitter\_Token Profile (1).png>)

You can also check account type inside [Account Profile](trader-profile.md) (aka Token Profile[🐳](trader-profile.md))&#x20;

![](<../../.gitbook/assets/Twitter\_Trader Profile (1).png>)
