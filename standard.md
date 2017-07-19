# Discord Bot Currency Standard
*Drafted by austinhuang#1076.*

Sometimes your users found hard to earn a specific virtual currency on a specific bot that they enjoy. Sometimes your users found easy to earn another currency on another bot but they have nowhere to use it. For these reasons your users will abandon both bots and turn to a bot that allow them to earn and use the currency wisely.

Introducing **Discoin**, a universal currency allowing users to exchange currencies from one bot to another bot.

## Definition of a central currency
**Discoin** is a currency that is __solely used to be exchanged into other bots' currencies.__ It can be traded between users.

Exchange rates with other bot currencies are discussed based on rarity. They're fixed unless methods used to earn currencies has changed significantly.

## Technology
A central *guild* should be created so that each participating bot can send message and receive message to process transactions.

Let's say a user wants to exchange A bot currency to B bot currency.

1. The user requests exchanging on A bot
2. In a central server, A bot sends a message indicates that a transaction has been started and convert the amount from A bot currency to Discoin
3. B bot picks the message up and convert the amount from Discoin to B bot currency and finishes the transaction
4. The user is notified by B bot indicates that the transaction has been finished.

## Obligation on participating developers
Participating developers should not abuse their privilege of manipulating the currency, including but not limited to adding a high amount of currency to themselves and convert them into other currencies. Violators will be banned from this program.