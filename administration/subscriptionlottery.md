<!-- TITLE: Monthly Lottery Subscriptions -->
<!-- SUBTITLE: A quick summary of Subscriptionlottery -->

# What is a Subscription Lottery?

Pay as You Go Monthly Lottery subscriptions (‘Pay-Go’) enable a player to subscribe to one or more Lottery games and make equal monthly payments, over the year.

The monthly payments per Entry are equal to **(Total Games Per year * Cost Per Entry)/12 **

Example: Weekly Lottery at $1.00 equals (52 x 1)/12 = $4.34 Per month.

Here is the general flow:

Once the player signs up, the platform creates the following: 

**A)	An Account for the player**
**B)	A Pay-Go Subscription which is made up of the following:**

a.	Game Subscription (s) This subscription instructs the system to join the player into each upcoming game, for a specific length of time, with a particular line/selection.
b.	Monthly Invoice (s)  The invoice calculates the total amount due for the next calendar month, based on the Game Subscriptions described above.
c.	A Recurring Payment Subscription. This subscription instructs a payment processor to debit the player's account every month.

# How can customers sign up?
Customers can purchase Subscriptions, digital tickets, or printed one-time tickets.

## Online
Players can create a subscription by visiting the web site and completing the easy to use Subscription Sign up form.
Alternatively you can enable players to purchase one time tickets.

## Retail
Tickets can be sold at retail locations using the Sales Agent application compatible with any smart device.
You can easily sell and print tickets by using your existing PC and thermal printer. 

## Telesales & Canvassers
Canvassers can sign customers up directly from any smart device, including phones and tablets.
The Sales Agent application can be accessed from any smartphone and can help you track your agents activity and sales efforts in real time.

Alternatively you can use an All-in-one POS, perfectly suited for mobile ticket sellers than need to sell, print and scan tickets.


# Can I customize my games?
Yes, you can absolutely customize your games. 

You can choose from any of the games in our games Library, [Traditional Lottery Games](/administration/games/lottery  "Managing your Lottery Games") , [Cash & Prize Draw Raffles (i.e. 50/50 Draw)](/administration/games/raffle "Managing your Raffle Games ") or [LottoRace Raffle Games](/administration/games/lottorace "Managing your Lottery & Raffle Games")


# Accessing Subscriptions

You, the Admin, can view all existing Pay-Go subscription in one of the two following ways:

**From Player Profile**
You can see all Pay-Go Subscriptions belonging to a single player by visiting the Player Detail View as shown below:

 ![Tournament Tiles](/uploads/player-pay-go.png "Players subscriptions")
 
1.	Navigate to Players Detail View
2.	Scroll down to the Pay-Go Subs tab
3.	You can view all Pay-Go subscriptions belonging to the player here
4.	Click on the subscription ID to be taken to the Pay-Go Subscription Detail View


**From Pay-Go Subs**
You can view and search all Pay-Go Subscriptions that have been created by players by viewing Pay-Go Subscription as shown below:

 ![Tournament Tiles](/uploads/pay-go-sub-listing2.png "All Players subscriptions")

1.	Navigate to Games -> Pay-Go Subscriptions
2.	Search for the Pay-Go subscription by any of
a.	URN
b.	Player 
c.	Status, ID, or Date create
3.	Click on “Details” to access the Pay-Go Subscription Detail View



# Pay-Go Subscription Details
The Pay-Go Subscription detail view, shown below, allows you to access all relevant information about a subscription.
 
 ![Tournament Tiles](/uploads/subscription-detail-view.png "Lottery Subscription detail view")
 
The **top header** section includes the following pertinent information:

•	Player Name 
•	Started-On | The sign-up day
•	Monthly Subscription | Total monthly bill for all Game Subscriptions in this Pay-Go Sub
•	Status | Active/Cancelled
•	Games to date |Number of games the player has played due to this Pay-Go Subscription
•	Winnings to Date | Total Amount won by games from this Pay-Go Subscription 

Use the **navigation tabs** to view the critical elements of a Pay-Go Subscription


 ![Tournament Tiles](/uploads/sub-det-tabs.png "Lottery Subscription sections")

•	**Details tab** | Is the default view and displays Game Subscriptions and Activity feed
•	**Payment Info tab**| Displays details of payment and its status with the payment processor
•	**Invoices tab** | Displays Past & Present monthly invoices
•	**Games Instances tab** | Displays all games joined stemming from this Pay-Go Subscription
•	**API Calls tab** | Displays all relevant 3 Party API Calls, i.e., Payment Provider, Insurance Provider

**The functionality of each tab is described below: **

## Details (default)
The details tab is the default tab on the Game Subscription Detail view and includes information about the games the player has subscribed to, along with a trail of recent activity, and the status of the upcoming invoice.
See a description of each section below.

![Subscription Detail View 2](/uploads/subscription-detail-view-2.png "Subscription Detail View 2")

### Game Subscriptions
Each Game Subscription is displayed in the Details section, as shown below. The list includes canceled and modified Game Subscriptions.

 ![Game Subscriptions](/uploads/subscription-game.png "Game subscriptions")

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


### Upcoming Invoice & Credit Dates
Invoice due dates reflect when the invoice amount is billed to the customers' bank account or Credit Card. 

The credit date reflects the date on which the invoice payment is credited to the players’ account and made available to be used for purchasing tickets.  

 ![Credit Invoices](/uploads/invoice-credit-date.png "Invoice Credit")
 
For credit card payments, this credit date is the same as the bill date. For Direct Debit payments, the credit date is at least 11 days from the bill date.

### Activity Feed
The Activity feed contains a chronological feed of all events associated with the Pay-Go subscription.
This feed includes registration, amendments, and any other jobs performed by the system and staff.
 
  ![Activity Feed](/uploads/sub-activity.png "Activity Feed")
 
## Monthly Invoices
Each month, for each Pay-Go Subscription, the system will create a new invoice for all the active Game Subscriptions.

An Invoice has four critical components
A)	**The invoice Amount**
B)	**The Bill Date** – The date on which amounts is debited/authorized from the customers' bank account. This bill date will be the same for all players. 
C)	**The Credit Date** – The date on which the invoice value gets credited to the Players account and will be available to be used by a Game Subscription
a.	For Credit Cards this is instant and as soon as the transaction is authorized
b.	For Direct Debit payments, The credit date is 7 days after the bill date, allowing enough time for payment failures to be communicated back to us
D)	**The Payment Type** can be one of the following
a.	Direct Debit
b.	Credit Cards (Additional Option)
c.	Cash Collection (Additional Option)

**The example below shows the series of monthly invoices for a Pay-Go Subscription:**

![Sub Invoices](/uploads/sub-invoices.png "Sub Invoices")

### Invoice Verification Job
This periodic system batch job will pick up any changes made to the Game Subscriptions by staff and reflect any required changes to the respective invoice and payment processor if needed.
This job can also be run Manually from the Invoice Detail View, as shown below. 
 
If the DDI mandate amount needs updating with the processor, an amendment request is sent to make the change.
This update can also be done manually by pressing the “Update with Processor” button.

## Payment Info (Direct Debit)
The Payment info tab displays details of the Direct Debit Instruction registered with the payment processor. 

This Payment Subscription is responsible for debiting the players’ bank account every month and in turn crediting the players’ lottery account for use by upcoming Game Subscription.
 
 ![Dd Payment Success](/uploads/dd-payment-success.png "Dd Payment Success")
 
The bank details submitted by the player are displayed near the top: 
**Account Holder**
**Account Number**
**Sort Code**

**Payment information recorded by the payment processor is shown in the following section:**

**Mandate Amount:**  The total debited from the players' Bank account by, on each collection date. 
**URN:** Unique Registration Number; The unique ID of this payment subscription, registered with BACS
**DDI Date:** The date the Direct Debit Instruction was set up.
**First Collection Date:** The first date that the customers' account is debited
**Monthly Collection Date:** The recurring monthly collection day
**Next Collection Date:** The upcoming collection date
**Frequency:** Monthly, Daily
**Can Cancel:**  If the processor will allow us to cancel

### Registering DDI flow

The first time a player signs up, the Direct Debit payment information entered by the player will be communicated via API to the Direct Debit processor.
In the first few minutes after a direct debit payment is created, it will be Pending, as shown below. 
The ‘processing’ icon next to each of the critical fields indicate that the DDI is registering with the Direct Debit payment processor.
 
Upon successful confirmation from the payment processor, you will see the green arrows next to each of Account Holder, Number, and Sort Code, as shown below.

![Dd Payment Pending](/uploads/dd-payment-pending.png "Dd Payment Pending")
 

Additionally, the Payment subscription will now receive a CORBACS ID and URN number. 
This URN number is the unique identifier for this payment subscription 
Any amendments made to the Account information or Mandate amount will be communicated to the payment processor and are verifiable in the Remote Activities section shown below.
Remote Activities
The Remote Activities section displays a list of changes made to the DDI as recorded by the Direct Debit processor. This list of amendments by the payment processor should match up with any changes made on the platform, which are displayed in the Activity feed. 
 
 
## Game Results

You can view all the game instances that were joined as part of this subscription here:
Note: Any Free tickets won as a result of subscribed games will not be here. I.e. if your subscription entry wins a free ticket to another game, that game won’t be shown here.
 
## API Calls (Direct Debit)

API calls list all communications made from the Bonobo platform to the payment processor and Vice Versa. 

This list contains any event, including pulling DDI info from the processor (happens each time you view the payment info tab) as well as any change or cancellation requests submitted or received.
   
## Paying Prizes

After each game, winnings are instantly credited to the player’s account on the platform.
Players can manually request payouts or alternatively, payout files can be created automatically after each game for manual processing through your bank. 

**Automated Payout files need to be explicitly enabled by Bonobo and are created in the following manner:**

1.	A withdrawal request is automatically created for any player with a cash prize and existing Direct Debit payment info
a.	This withdrawal request can be found in “Payments” 
b.	Total winnings for the respective game is transferred from the players’ Trust Account to the players’ Pending Withdrawals account until the withdrawal is approved
2.	The Payout File (CSV) is automatically created and contains entries for each of the withdrawal requests described above and contains the following
a.	Players name
b.	Account info
c.	Amount to be credited (Winnings)
d.	Bank Account info
3.	The Payout File can be downloaded and used to process the payout through your bank 
4.	Upon successfully processing through your bank, you must mark the Payout File as paid by clicking on “Mark as Paid” button
a.	This action sets the withdrawal request to Paid
b.	It also reflects the change from Pending Withdrawals to Withdrawals Paid in the players' account

  
# Lottery Subscription FAQ
  

## Viewing a subscription
**How does a staff member search and view existing Monthly Subscriptions?**

You can view all monthly subscriptions by going to the Pay-Go Subscriptions section.

1.	Navigate to Games -> Pay-Go Subs 
2.	You can search for a subscription by Name, URN or sign-up date
3.	Click on “View Details” for the subscription you’d like to see
4.	
To view details of the respective Pay-Go Sub, click on “Details”.
You will be taken to the Pay-Go Sub Detail View
Alternatively, you can see the Pay-Go Subs for a specific player by going to the Player’s Detail View and scrolling down to the Pay-Go Subs tab.

## Editing a subscription
**How does a staff member edit a Game Subscription for a player?**

You can edit a subscription at any time. Depending on how far you are from the next collection date, the change might be reflected in the current or upcoming subscription and invoice. 
To edit a Game Subscription
1.	Navigate to the Pay-Go Sub Detail View for the subscription you wish to edit
2.	Click on “Edit” for the Game Subscription you wish to amend
3.	Use the + / -  keys to increase/decrease the number of lines
4.	You can change the numbers by simply typing in the text field
5.	Click Save to save your changes
 
Note: If you are only changing the numbers on the Lines played, then the changes will be reflected in the next game. If the edits impact the Monthly total, then the Direct Debit Instruction must be amended and therefore, the change will be in effect after the next available payment cycle.

## Amendments
**When a subscription is changed, when and how does it take effect?**

Changes to subscriptions do not take effect immediately unless you are only changing the numbers and not the number of plays.  
For example, the change from 5, 10, 15, 25, 30  to  11, 12, 13, 14, 15 will take effect in the next join. Changing from 1 to 2 plays will take effect in the next calendar month or after that.
After submitting an amendment, the current subscription receives an end date, typically the end of the current month. A new Game Subscription, with the latest details is then created and set to start when the current Game Subscription Ends. 
Due to the delays associated with amending Direct Debit payments, changes to subscriptions using Direct Debits can take as long 7 weeks to come into effect.  The estimated date where the change will come into effect is shown in the update screen and should be communicated to players when making the change.
Note: Changes cannot be made to subscriptions 3 days before the collection date.
 
## Registered Games
**How does a staff member see which games a player has registered from their subscription?**

1.	Navigate to the Pay-Go Subscription Detail View 
2.	Click on “Game Instances” Tab

## Direct Debit setup time
**How long does it take to set up a new Direct Debit?**

The initial time to set up a Direct Debit Instruction is approximately 11 days. 
If the collection day of each month is the 19th, then all subscriptions must be placed before the 8th, or they will be collected in the following month. 
The Game Subscription will begin on the 1st of the calendar month following a successful collection. 

## Direct Debit support
**Which Direct Debit processors do you currently support in the UK?**

Bonobo's platform comes pre-integrated with RapiData, one of UK's premier Direct Debit payment processors.  

All you need to start processing payments, is to obtain your RapiData account, configure it into your install with a few clicks of your mouse, and you’ll be ready!

Bonobo can also integrate any Direct Debit Processor of your choosing for a fee.

## Supported Payment methods
**How can players pay for Monthly Subscriptions?**

Direct Debit and Credit Cards* can be used to pay for the Monthly Invoices generated in respect of the Game Subscriptions.

Depending on the type of payment method used, the credits to the Players’ wallet will be either immediate (credit cards) or delayed in the case of Direct Debit payments.
This delay impacts the speed of registration and amendments, and most importantly, the Start Date of the Game Subscriptions; the first time the player will be in a game. 
In the case of Direct Debits, the delay between sign up and registering into a game can be as long as 7 weeks. 

Other payment methods can be implemented upon request. 

## Player Accounts & self-service 
**Can players log in and manage their own subscriptions?**

Yes, by default players are able to log in and manage their own account.

If you'd prefer to handle all communication and customer account changes through your customer service team, then we can, by request, disable account log in and self-service features.




