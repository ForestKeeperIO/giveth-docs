---
id: torusonramp
title: Donating with Fiat via the Torus on-ramp
slug: dapps/torusonramp
---
import useBaseUrl from '@docusaurus/useBaseUrl'
import styles from '../../../../src/css/custom.css'

This guide will take you through the steps of donating your fiat currency using Torus. To do so, you'll use a third party payment provider to send your fiat to Torus, which will 'top-up' your Torus wallet with your chosen cryptocurrency. That cryptocurrency that was converted from fiat will then be donated to the project you've selected. There are fees associated with this conversion from Torus as well as the third party provider that you choose. We'll walk you through the steps, but depending on your native currency, the payment provider you use and the crypto you're converting to, things might look a bit different.

Click "Donate" to the project, and choose your Torus wallet.

<img id="contentimg" alt='Donating to the Project' src={useBaseUrl('img/content/projectselect.png')} />

A transaction pop-up window will then say *'Insufficient Funds'*. OK, let's fix that. At the bottom of that same pop-up window click `TOP UP`.
<img alt='Top up Torus Wallet' src={useBaseUrl('img/content/torustopup.png')} />

From there you'll get a list of third party payment providers; look through the fees and currencies they support, and choose the best match for you.

<img id="contentimg" alt='Select Payment Provider' src={useBaseUrl('img/content/selectprovider.png')} />

On the following screen enter the amount of fiat you would like to donate. Note that the estimate of fees will reflect here depending on the payment provider you select.

<img id="contentimg" alt='Enter fiat amount to donate' src={useBaseUrl('img/content/torusramp.png')} />

Next you'll be redirected to the website of your selected payment provider. Follow the prompts, which will be different depending on which provider you choose.

An example from the Ramp Network:
<img id="contentimg" alt='Ramp Network Example' src={useBaseUrl('img/content/paymentmethod.png')} />

 Once you've completed that, you'll be taken back to the Torus top-up window. You should see your funds in there. Take a second to confirm the amount to be donating; if it looks good then hit confirm.

You can follow up to watch the transaction being confirmed on the block explorer by clicking `View transaction details`. From this point your donation should be done! Nice work!
