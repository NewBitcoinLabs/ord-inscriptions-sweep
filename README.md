## Ordinals inscriptions sweep with PSBT

This repository provides helpful functions for trading (sweep, buy and sell) Ordinals inscriptions:
* `createPSBTToSell` creates the partially signed bitcoin transaction to sell the inscription
* `createPSBTToBuy` creates the partially signed bitcoin transaction to buy the inscription.
* `createPSBTToBuyMultiInscriptions` creates the partially signed bitcoin transaction to buy multiple inscriptions.
* `reqListForSaleInscription` is used at client side to prepare for an inscription sale transaction.
* `reqBuyInscription` is used at client side to prepare for an inscription purchase transaction.
* `reqBuyMultiInscriptions` is used at client side to prepare for an inscription sweep transaction.
