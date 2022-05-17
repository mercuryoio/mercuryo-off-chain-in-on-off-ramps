# Mercuryo. Off-Chain in On-Off-Ramps

## What we are improving and why

When users buy cryptocurrency with Mercuryo, there is a network fee that increases the cost of transactions. Depending on the network fee the cost might be doubled, hence making higher the exchange rate or fee for the transaction itself. To make transactions cheaper for users Mercuryo implemented a brand new feature that allows completely eliminate the network fee by processing transactions off-chain.

## **How it works**

![Temp drawings - OOR. Off-chain - v.2.jpg](https://github.com/mercuryoio/mercuryo-off-chain-in-on-off-ramps/blob/master/images/img_1.jpg)

To start using the off-chain feature you’ll need to register [Mercuryo wallet](https://my.mercuryo.io/login/email). This allows you to collect all crypto payments and manage them.

###  Mercuryo wallet registration for merchant

Before registering for a wallet, you need to sign an additional agreement.
If during the registration process for on-off-ramps you have already provided Mercuryo with a statement about your company (registration data, information about the founder and director), then you do not need to provide additional documents. It is enough to sign the consent for additional Terms and return it by e-mail. 

You can read these Terms below:

[T&C for Legal Entitites](https://github.com/mercuryoio/mercuryo-off-chain-in-on-off-ramps/blob/master/T%26C%20for%20Legal%20Entitites.md)

**Attention!** The business wallet does not allow customers to sell cryptocurrency.
This wallet is needed to credit the purchased cryptocurrency and for withdrawals of cryptocurrency to external wallets. In the future, it will also be possible to buy and sell cryptocurrency within this wallet, but it will require additional verification

After signing the Terms customer creates a wallet (register here [https://my.mercuryo.io/login/email](https://my.mercuryo.io/login/email)) and inform Mercuryo of the email that was used to register.
This email must not have been used before to register for the Mercuryo service

**Information for accounts:**
When a customer tells Mercuryo the wallet email address, Mercuryo set this up wallet on our side as a business wallet, and then Mercuryo disable the customer's minimum commission parameter.

###  Where to get the address to substitute in the widget.

In the Mercuryo wallet, you can get the Mercuryo address, which you’ll need to substitute in the transaction instead of the end user's address.

###  Information on receiving funds to the Mercuryo Wallet

When the cryptocurrency arrives to your Mercuryo wallet, a callback will be displayed in the admin panel.
You can also view the status using the handle [https://api.mercuryo.io/v1.6/sdk-partner/transactions](https://api.mercuryo.io/v1.6/sdk-partner/transactions)

### 4. Cryptocurrency withdrawal from Mercuryo wallet.

You can log in to the Mercuryo Wallet at any time and withdraw cryptocurrencies  to a third-party wallet.
