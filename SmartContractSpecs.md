# Objective 

* Issue and send tokens that represent a fiat value to the wallet of the user that makes a purchase in a Shelpin affiliated online vendor through Shelpin desktop app. 

# Issuance ratio: 

* Tokens are issued 1:1 to the fiat value of a percentage of the sale that is set by the donor brand and can be different over time. I.e A fashion vendor decides to donate 1 % of purchases made through the Shelpin desktop app,a user makes a 100 € purchase and receives in his wallet 1 token. In Christmas the vendor might decide to increase the donation to 3 % so the client would receive 3  SHELP tokens for the same 100 EUR purchase. 

* This % are managed through a web based donor brand dashboard. For the sake of simplicity we go for a fixed 2.5 % percentage of the purchase for the moment.

# To have in mind: 

* Tokens need to be “labelled” with the brand that issues them, as they represent a payment obligation for them equal to the number of tokens issued by them in exchange of purchases.  

* Those tokens will be then sent by the users to Giveth DAC´s, campaigns or milestones entering the Giveth donation flow, but this is for the moment another beautiful story.

* The less (ideally the null) need for making any implementations by the brand site side the better, purchases can be tracked by them with their analytics as they come from Shelpin (the app is used as browser, based in Brave) and the event of the purchase being finalized, and the amount of the purchase, thus of the amount of tokens to be issued, could be taken from the built in browser that interacts with the smart contract. 

* In real production there should be a mechanism to prevent the user keeping tokens from returned bought goods, either delaying the issuance of the tokens equaling the return period without action of the brand to cancel the issuance because a refund, or by “fiat unbacking” them after the issuance (see below the bigger picture about backing and unbacking Shelp tokens).

# The bigger picture 

In Shelpin launch SHELP tokens will be given away for free, in any amount that the user wants , the first issuance will be symbolically fixed at 482 TRN, estimated amount to have every human being having access to fresh water and a daily nutrition. 

Out of that 482 TRN SHELP tokens users claim the amount they wish ( we recommend asking for the amount that the user thinks he can obtain from their brands to donate using the dapp), but those tokens are worthless… they are not backed by any value, until a vendor backs those tokens with donations obtained by the user that claimed the tokens . We want to movilize token holders/ users to ask their favourite brands to start giving back for his purchases affiliating to Shelpin. 

## And how are they gonna do that??? 

Via a massive campaign of automated calling from users to brands asking them to join Shelpin and donate to a concrete NGO if they want them to be their clients anymore… a web based contact center open sourced for this purpose will be set up to make their ears burn. (asterisk devs welcome ;)) 

# Getting back to the token and contract

The useless tokens are kept in the users wallet and when he makes a purchase, rather than generating a new token, the main smart contract “activates” an equivalent amount of tokens to the donation obtained , that are now backed by fiat and can be sent to charities through the Giveth flow. Those tokens are specifically in the wallet of the user that makes the purchase labeled with the brand that assumed the obligation of donating an equivalent amount of fiat.   

When milestones are validated and the ngo / changemaker receives the SHELP token… they can send them to another contract that will “unback” the tokens by signing a message for the brands to make the fiat transfers to the NGO, the unbacking is completed when a proof of the fiat transfer is uploaded to IPFS and the NGO gives its conformity. 

# Reputational side of the token:

When the tokens are useless they say about its holder “I want to create donations of this XXXX value” but that does not mean anything, nothing has been achieved, only when fiat is transferred upon successful completion of a mileston, there has been a positive impact made to balance our world. So when backed tokens are unbacked because the impact has been made, they are still out there as a proof of:

Brand X: Supported with X amount to create balance
NGO Y: Wisely used X amount to create balance
User Z: Generated X amount to create balance. 

# Conclusion: 

The best step is always the first – just wanted to share part of the bigger picture about the smart contract / tokens.  
For the moment let us just focus on making something that sends tokens in exchange of purchases work. 

# THANKS

 


 
