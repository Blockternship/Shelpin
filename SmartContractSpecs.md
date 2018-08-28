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

  
