---
id: gas-fees
title: Changing Gas Fees
description: Build your next blockchain app on Polygon.
keywords:
  - docs
  - matic
image: https://matic.network/banners/matic-network-16x9.png 
---
import useBaseUrl from '@docusaurus/useBaseUrl';

For any transaction to be completed, for example, deploying a contract on Polygon testnet, Metamask requires some ETH to cover Gas fees. However, not everyone will have ETH in their accounts even if it's a testnet like Ropsten or Polygon testnet.

To overcome this you can bring down the gas fee to zero so that your transactions can be processed.

Consider the example mentioned earlier, "Deploying a contract on Polygon testnet"

When you deploy a contract on Polygon Testnet, you will receive a pop-up alert from metamask to confirm the transaction, but it will show you an error that you do not have sufficient funds to complete the transaction.

<img src={useBaseUrl("img/metamask/insufficient-funds.png")} />

Click on the Edit button in the pop-up and then chnage the Gas Price to Zero. You can then save this and then you’ll be navigated back to the original pop-up. 

<img src={useBaseUrl("img/metamask/customize-gas.png")} />

Now you won’t be seeing the alert anymore for, “Insufficient funds”. You can now click on Confirm to complete the transaction.

<img src={useBaseUrl("img/metamask/edited-gas.png")} />

