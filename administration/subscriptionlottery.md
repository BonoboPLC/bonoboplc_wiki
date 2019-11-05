<!-- TITLE: Monthly Lottery Subscriptions -->
<!-- SUBTITLE: A quick summary of Subscriptionlottery -->

# Subscription Lottery Overview 

Pay as You Go Monthly Lottery subscriptions (‘Pay-Go’) enable a player to subscribe to one or more Lottery games and make equal monthly payments, over the year.

The monthly payments per Entry are equal to **(Total Games Per year * Cost Per Entry)/12 **

Example: Weekly Lottery at $1.00 equals (52 x 1)/12 = $4.34 Per month.

Here is the general flow:

Once the player signs up, the platform creates the following: 
A)	An Account for the player
B)	A Pay-Go Subscription which is made up of the following
a.	Game Subscription (s) This subscription instructs the system to join the player into each upcoming game, for a specific length of time, with a particular line/selection.
b.	Monthly Invoice (s)  The invoice calculates the total amount due for the next calendar month, based on the Game Subscriptions described above.
c.	A Recurring Payment Subscription. This subscription instructs a payment processor to debit the player's account every month.


# Search & View Subscriptions

You can view all existing Pay-Go subscription in one of the two following ways:

**From Player Profile**
You can see all Pay-Go Subscriptions belonging to a single player by visiting the Player Detail View
1.	Navigate to Players Detail View
2.	Scroll down to the Pay-Go Subs tab
3.	You can view all Pay-Go subscriptions belonging to the player here
4.	Click on the subscription ID to be taken to the Pay-Go Subscription Detail View


**From Pay-Go Subs**
You can view and search all Pay-Go Subscriptions that have been created by players by viewing Pay-Go Subscription as shown below:
1.	Navigate to Games -> Pay-Go Subscriptions
2.	Search for the Pay-Go subscription by any of
a.	URN
b.	Player 
c.	Status, ID, or Date create
3.	Click on “Details” to access the Pay-Go Subscription Detail View



# Pay-Go Subscription Detail View
The Pay-Go Subscription detail view, shown below, allows you to access all relevant information about a subscription.
 
The top header section includes the following pertinent information:

•	Player Name 
•	Started-On | The sign-up day
•	Monthly Subscription | Total monthly bill for all Game Subscriptions in this Pay-Go Sub
•	Status | Active/Cancelled
•	Games to date |Number of games the player has played due to this Pay-Go Subscription
•	Winnings to Date | Total Amount won by games from this Pay-Go Subscription 

Use the navigation tabs to view the critical elements of a Pay-Go Subscription

•	Details tab | Is the default view and displays Game Subscriptions and Activity feed
•	Payment Info tab| Displays details of payment and its status with the payment processor
•	Invoices tab | Displays Past & Present monthly invoices
•	Games Instances tab | Displays all games joined stemming from this Pay-Go Subscription
•	API Calls tab | Displays all relevant 3 Party API Calls, i.e., Payment Provider, Insurance Provider
The functionality of each tab is described below. 


## Details tab

The details tab is the default tab on the Game Subscription Detail view and includes information about the games the player has subscribed to, along with a trail of recent activity, and the status of the upcoming invoice.
See a description of each section below.

### Game Subscriptions

Each Game Subscription is displayed in the Details section, as shown below. The list includes canceled and modified Game Subscriptions.

A player can have one more active Game Subscriptions as part of a single Pay-Go Subscription.  For example, a player can subscribe to a Weekly Lottery and a Monthly Raffle within the same Pay-Go Subscription. 

Each Game Subscription includes the following:

A)	The Name of The Game
B)	The  game instance ID that the player is currently registered in
C)	The status of the subscription (Active/Cancelled) 
D)	The Start & Ending dates of the subscription
E)	Monthly Fee | Averaged Annually for all Plays
F)	Play Count | Total Number of Plays
G)	Monthly Total | Total Fee payable for this subscription per month
H)	The players' selected number(s) 

Periodically (daily/hourly), the platform will execute all active subscriptions and ‘attempt’ to enter players into the respective open games.

If the player has a sufficient balance (which will be credited to the players’ account after each monthly invoice is paid), then the player will be successfully entered into the game, and his account debited. 

If the Player does not have a sufficient balance, the system will not be able to purchase tickets for them. The subscription will, however, attempt to buy tickets for the player periodically, until the player or an admin cancels the Game or Pay-Go Subscription.

i.e. If a payment declines, the players' account will not be credited. The subsequent subscription will not execute, and the player will not be in the game. However, if in the following month, a successful payment is made and the players’ account credited, then the subscription will be successful in its next join attempt and the player will enter the game. 


#### Upcoming Invoice & Credit Dates

Invoice due dates reflect when the invoice amount is billed to the customers' bank account or Credit Card. 
The credit date reflects the date on which the invoice payment is credited to the players’ account and made available to be used for purchasing tickets.  
 
For credit card payments, this credit date is the same as the bill date. For Direct Debit payments, the credit date is at least 11 days from the bill date.

#### Activity Feed
The Activity feed contains a chronological feed of all events associated with the Pay-Go subscription.
This feed includes registration, amendments, and any other jobs performed by the system and staff.
 

### Monthly Invoices tab
Each month, for each Pay-Go Subscription, the system will create a new invoice for all the active Game Subscriptions.
An Invoice has four critical components
A)	The invoice Amount
B)	The Bill Date – The date on which amounts is debited/authorized from the customers' bank account. This bill date will be the same for all players. 
C)	The Credit Date – The date on which the invoice value gets credited to the Players account and will be available to be used by a Game Subscription
a.	For Credit Cards this is instant and as soon as the transaction is authorized
b.	For Direct Debit payments, The credit date is 7 days after the bill date, allowing enough time for payment failures to be communicated back to us
D)	The Payment Type can be one of the following
a.	Direct Debit
b.	Credit Cards (Additional Option)
c.	Cash Collection (Additional Option)
The example below shows the series of monthly invoices for a Pay-Go Subscription. 


