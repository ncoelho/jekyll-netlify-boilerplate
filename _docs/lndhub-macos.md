---
title: LNDHub on Mac OSX
subtitle: Coldcard with Bluewallet - Lightning SD card
tags: [lndhub]
---


In this video you will see the usage of PSBT, watch-only wallets. And how to send transactions offline with your Coldcard and Bluewallet.

Using a [Lightning to SD adaptor](https://www.apple.com/shop/product/MJYT2AM/A/lightning-to-sd-card-camera-reader)

- Start the Coldcard device, go to `Advanced` ➤ `MicroSD Card` ➤ `Export Wallet` ➤ `Electrum Wallet`. Put the SD card into Coldcard. Choose Native Segwit. It should create the wallet skeleton file on SD card.
- Put the SD card into the adaptor, go to the import wallets screen and choose your file.
- Create a transaction from this watch-only wallet, when prompted - export it to a file and save it in your folder.
- Put the SD card into the Coldcard, go to "Ready To Sign" and proceed with signing the transaction.
- Put the SD card into the adaptor. There should be 2 new files: 
	- a file with the transaction hex that is ready to broadcast 
```(*-final.txn)```
	- a signed transaction file 
```(*-signed.psbt)```
	- Choose the signed transaction file 
```('*-signed.psbt)```
- Tap send! You are done :)